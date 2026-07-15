---
document_name: Claude Design Instructions
brand_architecture:
  master_brand: Norn
  digital_platform: Norn Human
version: 1.0
status: Approved Operating Instructions
language: tr-TR
last_updated: 2026-07-16
prepared_by: SedInsight — Stratejik Proje Liderliği & İş Geliştirme
primary_use:
  - Claude Design project setup
  - Brand and UI design generation
  - Figma-ready design planning
  - Social, web and product templates
  - Design review and system compliance
related_documents:
  - AI Prompt Rules.md
  - ../01_Strategy/Brand Strategy.md
  - ../01_Strategy/Voice & Messaging.md
  - ../02_Identity/Typography.md
  - ../02_Identity/Color System.md
  - ../03_Design_System/Design System.md
  - ../03_Design_System/Design Tokens.json
---

# Norn / Norn Human Claude Design Instructions

## 0. Belgenin Rolü

Bu belge, Claude Design’ın Norn ve Norn Human için tasarım üretirken izlemesi gereken çalışma sırasını, karar hiyerarşisini, teslim standardını ve yasakları tanımlar.

Bu talimat:

- logo,
- web,
- sosyal medya,
- dijital ürün,
- mobil uygulama,
- sunum,
- component,
- template

çalışmalarında ortak çalışma protokolüdür.

Göreve özel brief varsa bu dosya ile birlikte kullanılır. Göreve özel brief bu ana sistemle çelişirse çelişki açıkça raporlanır; sessizce yeni kural üretilmez.

---

# 1. Çalışma Başlatma Protokolü

## 1.1 Dosyaları Okuma Sırası

Her yeni tasarım görevinde şu sıra izlenmelidir:

1. `Brand Strategy.md`
2. `Voice & Messaging.md`
3. `Typography.md`
4. `Color System.md`
5. `Design System.md`
6. `Design Tokens.json`
7. `AI Prompt Rules.md`
8. Göreve özel brief
9. Referans manifesti
10. Referans görseller
11. Mevcut tasarım veya component dosyası

Görev yalnızca küçük bir revizyon olsa bile ilgili foundation dosyaları kontrol edilmelidir.

## 1.2 Görsel Üretimden Önce

Claude Design ilk yanıtında şu özeti vermelidir:

```text
1. Görevi nasıl anladım?
2. Tasarım türü nedir?
3. Kullanıcının ana görevi nedir?
4. Kullanılacak mesaj ve CTA nedir?
5. Hangi Brand OS kuralları kritik?
6. Hangi bilgiler eksik veya kesinleşmemiş?
7. Hangi varsayımları yapıyorum?
8. Üreteceğim varyantlar nelerdir?
```

Eksik bilgi tasarımın çekirdeğini engellemiyorsa placeholder ile ilerlenir. Placeholder açıkça işaretlenir.

## 1.3 Tasarım Statüsü

Her çalışma şu statülerden biriyle başlatılır:

- `EXPLORATION`
- `DRAFT`
- `REVIEW REQUIRED`
- `READY FOR DEVELOPMENT`

Claude Design kendi başına `APPROVED` veya `FINAL` statüsü veremez.

---

# 2. Tasarım Türünü Belirleme

Her görev önce aşağıdaki türlerden biri veya birkaçı olarak sınıflandırılır:

## 2.1 Brand / Identity

- logo,
- wordmark,
- pattern,
- icon family,
- brand application.

## 2.2 Marketing

- landing page,
- campaign page,
- event page,
- social campaign,
- e-mail visual.

## 2.3 Editorial

- article,
- guide,
- manifesto,
- report,
- concept page.

## 2.4 Social

- carousel,
- reels cover,
- story,
- announcement,
- instructor profile.

## 2.5 Product

- member experience,
- education library,
- player,
- profile,
- membership,
- reservation.

## 2.6 Admin / Portal

- instructor portal,
- admin panel,
- reporting,
- content management.

## 2.7 Presentation

- strategy deck,
- project review,
- partner presentation,
- training deck.

Tasarım türü; typography mode, density, component seti ve görsel yoğunluğu belirler.

---

# 3. Marka Mimarisi Kuralı

- Norn ana markadır.
- Norn Human dijital eğitim ve bütüncül gelişim platformudur.
- Kullanıcı platform, eğitim, üyelik veya uygulamayla etkileşiyorsa ana isim Norn Human’dır.
- Ana marka yaklaşımı veya geniş ekosistem anlatılıyorsa Norn kullanılabilir.
- Eski Norn Akademi, Norn Enstitü ve Nornetik adları aktif tasarım metninde kullanılmaz.
- Nihai logo henüz onaylanmamışsa geçici metinsel `Norn Human` kullanılır.
- Geçici yazım Manrope Semibold, normal boşluk ve tek renk ile gösterilir.
- Geçici wordmark final logo gibi sunulmaz.

---

# 4. Design Tokens Kullanım Kuralı

## 4.1 Token Önceliği

Claude Design şu sırayı izlemelidir:

```text
Component token
→ Semantic token
→ Primitive token
→ Yeni değer talebi
```

Doğrudan hex veya rastgele px değeri yalnızca:

- token bulunmadığında,
- kullanım tekil ve gerekçeli olduğunda,
- yeni token önerisi açıkça raporlandığında

kullanılabilir.

## 4.2 Token Referans Örnekleri

Doğru:

```text
text.primary
bg.canvas
border.focus
space.section.default
radius.card
button.primary.backgroundDefault
```

Yanlış:

```text
#0E2A47 çünkü güzel duruyor
18px rastgele gap
22px özel radius
Yeni mor vurgu
```

## 4.3 Yeni Token Talebi

Yeni token önerirken:

- problem,
- mevcut tokenın neden yetmediği,
- tekrar sıklığı,
- önerilen isim,
- primitive referansı,
- etkilenen componentler

belirtilmelidir.

---

# 5. Tipografi Talimatları

## 5.1 Font Rolleri

### Source Serif 4

- marka ve manifesto,
- editoryal başlık,
- büyük hero mesajı,
- alıntı,
- düşünsel içerik.

### Manrope

- gövde metni,
- UI,
- buton,
- form,
- metadata,
- navigasyon,
- sosyal medya operasyonel bilgi,
- admin ve portal.

## 5.2 Yasaklar

- Üçüncü font ekleme
- Serif buton
- Serif input
- Serif tab veya tablo
- Çok ince Manrope
- Tamamı büyük harf ve aşırı tracking ile teknoloji estetiği
- Her başlığı Source Serif 4 yapma
- Logo için fontları doğrudan yazıp final kabul etme
- Logo harf müdahalesini normal metinlere taşıma

## 5.3 Responsive Type

Tasarım:

- desktop ve mobile text style kullanmalı,
- uzun Türkçe başlıklarla test edilmeli,
- metni sığdırmak için minimum okunabilirliğin altına düşmemeli,
- iki satır CTA üretmemelidir.

---

# 6. Renk Talimatları

## 6.1 Ana Sistem

- Canvas: Norn Ivory
- Primary text: Norn Charcoal
- Primary action: Deep Norn Navy
- Editorial accent: Norn Bronze
- Body / movement: Olive
- Life / relationship / production: Earth

## 6.2 Kullanım

- Aynı tasarımda tek ana vurgu rengi
- Bronze sınırlı
- Olive ve Earth kategori / içerik desteği
- Status renkleri kategori renkleriyle karıştırılmaz
- Kategori yalnızca renkle gösterilmez
- Link gövde içinde underline veya ek gösterge taşır
- Fotoğraf üstü kontrast gerçek görselle test edilir

## 6.3 Yasaklar

- Neon
- Mor aura
- Gökkuşağı
- Holografik efekt
- Siyah–parlak altın lüks sistem
- Turkuaz–lime teknoloji gradient’i
- Her kartı ayrı renge boyama
- Düşük kontrastlı pastel metin
- Dark mode’u talep olmadan oluşturma

---

# 7. Layout ve Spacing Talimatları

## 7.1 Grid

- Mobile: 4 kolon
- Tablet: 8 kolon
- Desktop: 12 kolon

## 7.2 Temel Ritim

- 4px temel birim
- Ana ritim 8px katları
- Bölümler arası büyük boşluk
- Bileşen içinde küçük boşluk
- Hiyerarşi arttıkça boşluk artar

## 7.3 Container

- Editorial text: max 68ch
- Form: 480–560px
- Dashboard: max 1440px
- Desktop marketing: max 1200–1320px

## 7.4 Yasaklar

- Metni sığdırmak için rastgele spacing azaltma
- Her sayfada yeni grid
- Elementleri yalnızca görsel denge için sistem dışı hizalama
- Mobil tasarımı desktop ekranın küçültülmüş hali olarak üretme
- Desktop’taki görsel sırasını mobile otomatik taşıma

---

# 8. Radius, Border ve Elevation

## 8.1 Radius

- Button: 12px
- Input: 12px
- Card: 16px
- Modal: 20px
- Large media: 24px
- Avatar / pill: full

## 8.2 Ayrım Önceliği

1. Spacing
2. Surface
3. Border
4. Shadow

## 8.3 Shadow

Shadow:

- dekorasyon için değil,
- katman ve etkileşim için,
- düşük yoğunlukta

kullanılır.

## 8.4 Yasaklar

- Her kartta büyük shadow
- Border + güçlü shadow + renk farkını aynı anda kullanma
- Rastgele 14px, 18px, 26px radius
- Cam efekti veya yoğun blur’u varsayılan stil yapma

---

# 9. Component Talimatları

Her component dokümantasyonu şunları içermelidir:

1. Amaç
2. Kullanım alanı
3. Kullanılmaması gereken durum
4. Anatomy
5. Variants
6. Sizes
7. States
8. Content rules
9. Responsive behavior
10. Accessibility
11. Token references
12. Developer notes
13. Do / Don’t

## 9.1 Zorunlu States

```text
Default
Hover
Focus
Active / Pressed
Selected
Disabled
Loading
Error
Success
```

İlgisiz state’ler çıkarılabilir; ancak eksik state sessizce atlanmaz.

## 9.2 Variant Kuralı

Yeni variant yalnızca:

- farklı semantik rol,
- farklı interaction,
- farklı responsive davranış,
- tekrar eden gerçek kullanım

varsa oluşturulur.

Görsel çeşitlilik için variant üretilmez.

## 9.3 Component İsimleri

Doğru:

```text
Button
Card/Education
Navigation/Header
Feedback/Alert
Overlay/Modal
```

Yanlış:

```text
Button New
Card 2
Blue Button
Final Final
```

---

# 10. Responsive Talimatları

## 10.1 Mobile First

Önce şu sorular mobilde çözülür:

- Kullanıcının ana görevi ne?
- İlk bilgi ne?
- Primary CTA nerede?
- İçerik sırası nasıl?
- Touch target yeterli mi?
- Metin okunuyor mu?

## 10.2 Reflow

- 12 → 8 → 4 kolon
- Kartlar gerektiğinde alt alta
- Sidebar → drawer
- Tablo → card/list veya yatay scroll, bağlama göre
- İkincil aksiyon → overflow
- Primary CTA görünür kalır

## 10.3 Zorunlu Teslim

Her web veya ürün tasarımında en az:

- desktop,
- mobile

varyantı bulunmalıdır.

Kritik tablet davranışı varsa tablet de eklenir.

---

# 11. Erişilebilirlik Talimatları

Hedef:

```text
WCAG 2.2 AA
```

## 11.1 Zorunlu Kontroller

- Normal metin: en az 4.5:1
- Büyük metin: en az 3:1
- UI ve grafik: en az 3:1
- Tercih edilen target: 44×44px
- Visible focus
- Keyboard akışı
- Renk dışı durum göstergesi
- Heading sırası
- Form label
- Error suggestion
- Reduced motion
- Text resize
- Responsive reflow

## 11.2 Focus

Varsayılan:

- 2px görünür indicator
- 2px offset
- yüksek kontrast
- keyboard kullanımında kesintisiz görünürlük

## 11.3 Error

Error:

- kullanıcıyı suçlamaz,
- problemi açıklar,
- çözümü gösterir,
- girilen veriyi silmez,
- yalnızca kırmızı renge dayanmaz.

---

# 12. Motion Talimatları

## 12.1 Karakter

- kısa,
- sakin,
- anlamlı,
- yön gösteren.

## 12.2 Tokenlar

- Hover / press: 120ms
- Küçük feedback: 180ms
- Dropdown / accordion: 240ms
- Modal / drawer: 320ms
- Sınırlı editorial reveal: 480ms

## 12.3 Yasaklar

- Sürekli dönen sembol
- Parlayan aura
- Uzun parallax
- Scroll hijacking
- Zorunlu autoplay
- Dikkat için titreşim
- Aşırı konfeti
- Kullanıcıyı acele ettiren animasyon

Reduced-motion tercihinde işlev korunmalıdır.

---

# 13. Görsel ve Fotoğraf Talimatları

## 13.1 Tercih Edilen Fotoğraf

- gerçek eğitmen,
- gerçek katılımcı,
- gerçek öğrenme anı,
- doğal ışık,
- doğal hareket,
- gerçek mekân,
- aşırı yapay olmayan prodüksiyon,
- mobil crop için negatif alan.

## 13.2 Kaçınılacak Görsel

- meditasyon silueti,
- kristal / tütsü / mum kompozisyonu,
- aura ve galaksi,
- yapay kusursuz yoga pozu,
- beyaz önlüklü sahte uzman,
- stok ekip,
- dramatik dönüşüm,
- önce–sonra sağlık iddiası.

## 13.3 Grafik Dil

- iplik,
- çizgi,
- örgü,
- yol,
- katman,
- merkez,
- bağlantı.

Grafik:

- düşük yoğunlukta,
- içerikle yarışmadan,
- sade,
- kontrollü asimetrik

olmalıdır.

---

# 14. Kanal Bazlı Uygulama

## 14.1 Marketing Page

- Daha geniş boşluk
- Source Serif 4 görünür
- Güven kanıtı
- Bir ana CTA
- Bir bölümde tek anlatı
- Mobil çözüm

## 14.2 Editorial Page

- 68ch
- İçindekiler
- Heading düzeni
- Kaynak ve metadata
- Pull quote sınırlı

## 14.3 Product

- Manrope ana font
- Görev odaklı
- Dekor minimum
- Clear states
- Empty/error/loading
- Navigation açık

## 14.4 Admin

- Compact mode olabilir
- Veri öncelikli
- Tablo ve filtre
- Marka dekoru minimum
- İşlem güvenliği maksimum

## 14.5 Social Media

- 72–96px safe margin
- Bir ana mesaj
- En fazla iki font weight
- Bir ana accent
- Cover mobilde okunur
- Seri etiketi
- Gerçek CTA
- Feed crop kontrolü

## 14.6 Presentation

- Bir slaytta bir karar
- Grafik veya veri destekli anlatım
- Uzun paragraf yok
- Tipografi ve whitespace ile hiyerarşi
- Ana marka atmosferi içerikten baskın değil

---

# 15. İçerik ve Mikro Metin Talimatları

Claude Design tasarım içindeki metni de marka kurallarına göre ele almalıdır.

## 15.1 Ton

- Açık
- Sakin
- Rehber
- Kullanıcıyı suçlamayan
- Kesinlik satmayan

## 15.2 UI Copy

Doğru:

```text
Kaldığın yerden devam et
Bilgilerini kontrol et
Bu alan zorunludur
Tekrar deneyebilirsin
```

Yanlış:

```text
Hata yaptın
Başarısız oldun
Hemen şimdi hayatını değiştir
Son şans
```

## 15.3 Placeholder

Kesin bilgi yoksa:

```text
[Eğitim adı]
[Eğitmen adı — doğrulanacak]
[Tarih — açık karar]
[Fiyat — açık karar]
```

kullanılır.

Uydurma gerçekçi veri final metne yazılmaz.

---

# 16. Göreve Özel Akışlar

## 16.1 Logo

Logo görevi için:

- `Logo Brief.md`
- `Reference Manifest`
- logo route yapısı

esas alınır.

İlk tur:

- monochrome,
- dört farklı route,
- Norn + Norn Human lockup,
- 32px test,
- app icon test.

## 16.2 Web Sayfası

Teslim:

- bilgi mimarisi,
- section listesi,
- desktop wireframe,
- mobile wireframe,
- high-fidelity,
- states,
- component listesi,
- token listesi.

## 16.3 Product Screen

Teslim:

- user goal,
- screen anatomy,
- primary flow,
- desktop/mobile,
- states,
- edge cases,
- accessibility,
- token references.

## 16.4 Social Template

Teslim:

- template amacı,
- content limits,
- safe area,
- cover,
- content slide,
- CTA slide,
- photo and text variants,
- editable zones.

## 16.5 Component

Teslim:

- anatomy,
- properties,
- variants,
- states,
- responsive,
- accessibility,
- token mapping.

---

# 17. Çıktı Formatı

Claude Design her teslimde şu yapıyı kullanmalıdır:

```text
STATUS:
DESIGN TYPE:
PRIMARY USER GOAL:
MAIN MESSAGE:
PRIMARY CTA:

FILES READ:
ASSUMPTIONS:
OPEN DECISIONS:
RISKS:

DESIGN RATIONALE:
LAYOUT:
TYPOGRAPHY:
COLOR:
COMPONENTS:
RESPONSIVE:
STATES:
ACCESSIBILITY:
TOKEN REFERENCES:

OUTPUTS:
NEXT REVIEW DECISION:
```

Bu format sunum metnine aynen yazılmak zorunda değildir; çalışma notunda bulunmalıdır.

---

# 18. Review Checklist

## Strateji

- Norn / Norn Human ayrımı doğru mu?
- Marka yalnızca yoga veya spiritüel yapı gibi mi?
- Kullanıcı değeri açık mı?
- Tek ana mesaj var mı?

## Sistem

- Semantic token kullanıldı mı?
- Font rolleri doğru mu?
- 4px spacing var mı?
- Radius ve shadow sistemde mi?
- Component tekrar kullanılabilir mi?

## Responsive

- Mobile var mı?
- İçerik sırası doğru mu?
- Uzun Türkçe metin test edildi mi?
- Navigation davranışı belli mi?

## Interaction

- Hover
- Focus
- Active
- Disabled
- Loading
- Error
- Success

## Accessibility

- Contrast
- Target size
- Keyboard
- Focus
- Reduced motion
- Label ve error
- Color-independent meaning

## İçerik

- İddialar doğrulanmış mı?
- Placeholder açık mı?
- Eğitmen rolleri doğru mu?
- Sahte aciliyet var mı?
- CTA gerçek mi?

---

# 19. Yasaklar

Claude Design:

- Brand OS okumadan tasarıma başlamamalı,
- eski marka adını kullanmamalı,
- Deniz Lökçüler’i kurucu göstermemeli,
- üçüncü font eklememeli,
- palet dışı ana renk oluşturmamalı,
- dark mode’u kendiliğinden üretmemeli,
- her ekran için yeni component oluşturmamalı,
- loading/error/empty state’i atlamamalı,
- mobile tasarımı desktop’tan küçültmemeli,
- kritik bilgiyi hover’a saklamamalı,
- renk tek başına anlam taşıyacak şekilde kullanmamalı,
- uydurma eğitmen, fiyat, tarih veya kullanıcı yorumu üretmemeli,
- sağlık ve psikoloji sonucu vaat etmemeli,
- görsel referansı kopyalamamalı,
- exploration çıktısını final olarak adlandırmamalıdır.

---

# 20. Kısa Başlangıç Prompt’u

```text
Bu projede Norn / Norn Human Claude Design Instructions, AI Prompt Rules ve Design Tokens dosyalarına bağlı çalış.

Önce ilgili Brand OS dosyalarını oku. Görsel üretmeden önce görevi nasıl anladığını, kullanıcı hedefini, açık kararları, varsayımları ve üreteceğin varyantları özetle.

Norn ana marka; Norn Human dijital eğitim ve bütüncül gelişim platformudur. Eski marka adlarını aktif tasarımda kullanma. Deniz Lökçüler kurucu değildir.

Component → semantic → primitive token sırasını kullan. Source Serif 4 yalnızca editoryal ve marka alanlarında; Manrope UI ve gövde alanlarında kullanılmalı. Mobile-first tasarla, gerçek Türkçe içerikle test et, state ve erişilebilirlik gereksinimlerini göster.

İlk çıktıyı EXPLORATION veya DRAFT olarak etiketle. İnsan onayı olmadan final kabul etme.
```

---

**Dosya sonu**
