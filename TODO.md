# Fizyo — Yapılacaklar (TODO)

_Eklendi: 11 Temmuz 2026_

## Profil
- [x] Kişisel bilgiler bölümüne **yaş** alanı eklensin; kullanıcı yaşını değiştirebilsin (`birth_year` üzerinden kaydedilir).
- [x] Kişisel bilgiler düzenleme ekranı accordion yerine **bottom sheet** olarak alttan açılsın. (`src/components/bottom-sheet.tsx`)

## Ön Değerlendirme (Anamnez) Formu
- [x] "Hangi bölgede?" sorusundaki bölge seçeneklerine **ikon** eklensin — ilgili bölgelerin küçük vektörel görselleri. (`src/components/region-icons.tsx` — mini vücut haritası: figür + bölge noktası)
- [x] "Nasıl başladı?" sorusuna 3 seçeneğin yanına bir **serbest metin input** eklensin — kullanıcı seçenekler uymuyorsa kendisi yazabilsin.
- [x] Ağrı şiddeti (0–10) 10 buton yerine **slider** olsun — kullanıcı kaydırarak seçsin. (`@react-native-community/slider` eklendi)
- [x] Üstteki **ilerleme çubuğu daha belirgin** olsun: ilerlenen kısım yeşil, ilerlenmemiş kısım farklı (ayırt edilebilir) renkte. (6px; dolu: `success`, boş: `tintSoft`)

## Yerleşim / Spacing
- [x] Değerlendirme formundaki **"Devam et" butonu** ve Mesajlar'daki **mesaj yazma alanı** tab bar'dan fazla yukarıda kalıyor — tab bar'a biraz daha yaklaştırılsın. (iki yerde de 16px yaklaştırıldı — cihazda kontrol edilecek)

## Öneriler — Kod Denetimi (11 Temmuz 2026, commit 0af8648)

_Tüm kod okunarak çıkarıldı; öncelik sırasına göre. Her madde bağımsız yapılabilir._
_Ayrıntılı uygulama planları: `plans/` dizini (yürütme sırası ve bağımlılıklar `plans/README.md`'de)._

### Düzeltilmesi önerilenler (kullanıcıya dokunan hatalar)

- [x] **Mesaj gönderimi hatayı yutuyor** — `send()` artık `error` kontrol ediyor; hata durumunda taslak geri konuyor + uyarı gösteriliyor. (Plan 003)
- [x] **"Yaptım" işaretleme hataları yutuluyor** — iki `toggleDone` da hata kontrolü + geri alma yapıyor; `'pending'` id'si üzerinden silme artık imkânsız. (Plan 004)
- [x] **Ağ hatası "program yok" gibi görünüyor + offline önbellek eksik** — program `src/lib/program-cache.ts` ile AsyncStorage'a yazılıyor; sorgu hatasında önbellekten gösteriliyor + çevrimdışı bandı; önbellek yoksa "Bağlantı kurulamadı / Tekrar dene" ekranı. Anamnez sekmesi hata durumunda doldurulabilir formu göstermiyor. (Plan 007 — cihazda uçak moduyla gözle doğrulanmalı)
- [x] **Uyum (compliance) formülü `frequency_per_week`'i yok sayıyor** — `computeCompliance` `src/lib/stats.ts`'e eklendi; payda atanan haftalık sıklığa göre, pay yalnız güncel programın tamamlamaları. (Plan 005 — birim testleri test altyapısı [002] kurulunca eklenecek)
- [x] **Serbest metin "nasıl başladı" travma kırmızı bayrağını atlıyor** — serbest metin onset artık `baslangic_serbest_metin` bayrağı üretiyor; admin panelde etiket eşlemesi varsa oraya da eklenmeli (ayrı repo). (Plan 006 — birim testleri 002 sonrası)

### Altyapı / kod sağlığı

- [ ] **Hiç test yok, CI yok** — repo'da tek doğrulama `tsc` + lint. `src/lib/` saf fonksiyonları (`computeStreak`, `computeRedFlags`, `dateString`) jest-expo ile yarım günde test altına alınır; kırmızı bayrak mantığı klinik açıdan test edilmeye en çok değen kod. Sonra GitHub Actions'a `tsc + lint + test` eklenir. (Orta iş)
- [ ] **Lint 14 hatayla kırmızı** — gerçek regresyonlar gürültüde kayboluyor ve `reactCompiler: true` olduğundan işaretli bileşenlerde compiler devre dışı kalıyor. Başlıcaları: `ui.tsx:60` (Skeleton, render'da ref), `profil.tsx` (`SettingsRow` render içinde bileşen tanımı — her render'da remount), `use-color-scheme.web.ts:11`, kaçışsız `'` karakterleri. Sıfıra indirip lint'i gerçek bir kapı yap. (Küçük iş)
- [ ] **`eas.json` yok** — Store build maddesi için önkoşul; `eas build:configure` ile production profili oluşturulmalı. (Küçük iş)
- [ ] **Kopya `ExerciseVideo` bileşeni** — `egzersiz/[id].tsx` ve `egzersizler/[id].tsx` birebir aynı bileşeni tanımlıyor; `src/components/`'a taşınabilir. (Küçük iş, düşük öncelik)

### Yön fikirleri (karar senin)

- **Push bildirimi: "Programın hazır" + yeni mesaj** — CLAUDE.md'de Faz 1.5 olarak zaten planlı; `expo-notifications` kurulu ve izin akışı hatırlatıcılarda mevcut. Store lansmanında hastayı geri getiren en kritik an "program atandı" bildirimi. (Expo Push token + DB webhook + Edge Function; orta iş)
- **Anonim hesabı kalıcı hesaba yükseltme** — şu an telefon değişince/app silinince hastanın tüm verisi kaybolur; store'daki gerçek hastalar için risk. Supabase anonim hesabı e-posta/telefonla kalıcılaştırmayı destekliyor (CLAUDE.md'de not edilmişti). Program atanan hastaya "hesabını güvenceye al" akışı. (Orta iş)
- **RevenueCat + server-side mesaj limiti** — karar verilmiş, stub'lar hazır (`premium.ts`, `paywall.tsx`); store build'iyle aynı pakette ele alınabilir. Mesaj limiti RLS/trigger ile DB'de uygulanmalı (CLAUDE.md notu), client kapısı yetmez.

### Değerlendirilip yapılmamasına karar verilenler

- `uuid` moderate güvenlik uyarısı (pnpm audit): yalnız build-time zincirinde (`expo > @expo/config-plugins > xcode`), runtime'a ulaşmıyor — Expo güncellemesiyle kendiliğinden çözülür.
- `delete_own_account` SECURITY DEFINER: bilinçli ve migration yorumunda belgeli, korumaları yerinde.
- Mesaj haftalık limiti şu an yok: premium kapısı kapalıyken kasıtlı — RevenueCat kurulumuna ertelendi (CLAUDE.md kararı).

## Store Hazırlığı
- [ ] Build alınıp **App Store'a yüklenecek** — MANUEL ADIM: EAS build + App Store Connect kaydı (aşağıdaki nota bak). App adı Fizyoline yapıldı (app.json `name`), `ios.bundleIdentifier` / `android.package` = `com.tahakanar.fizyoline` eklendi (build öncesi istenirse değiştirilebilir); splash/icon asset'leri mevcut.
- [x] App içinde **"Fzt. Taha Kanar"** geçen tüm yerler **"Uzm. Fzt. Taha Kanar"** olarak değiştirilecek (`src/lib/therapist.ts` tek kaynak yapıldı; mesajlar, anamnez, profil, program ekranları oradan okuyor).
