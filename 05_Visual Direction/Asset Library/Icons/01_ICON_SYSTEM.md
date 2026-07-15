---
document_name: Icon System
brand_architecture:
  master_brand: Norn
  digital_platform: Norn Human
version: 1.0
status: Approved Foundation
language: tr-TR
last_updated: 2026-07-16
prepared_by: SedInsight — Stratejik Proje Liderliği & İş Geliştirme
---

# Norn / Norn Human Icon System

## 0. Sistem Kararı

Norn Human icon sistemi iki katmandan oluşur:

```text
Base UI Icons
→ Lucide tabanlı işlevsel ikonlar

Brand Custom Icons
→ Norn Human'a özgü kategori ve marka ikonları
```

Bu yaklaşım:

- web,
- mobil uygulama,
- Figma,
- sosyal medya,
- sunum,
- admin paneli,
- eğitmen portalı

arasında tutarlı ve yönetilebilir bir sistem oluşturur.

---

# 1. Teknik Standart

```text
Canvas: 24 × 24 px
ViewBox: 0 0 24 24
Default Stroke: 2 px
Small Stroke: 1.75 px only when required
Stroke Linecap: round
Stroke Linejoin: round
Stroke Alignment: centered
Fill: none
Color: currentColor
Minimum Safe Area: 1 px
Minimum Element Spacing: 2 px
```

## 1.1 Boyutlar

```text
16 px → dense metadata
20 px → small UI
24 px → default UI
32 px → feature / card
40 px → large feature
48 px → illustrative feature
```

## 1.2 Varsayılan Kullanım

- UI ikonlarının varsayılan ölçüsü 24 px'tir.
- 16 px kullanımda gerekirse stroke 1.75 px'e indirilebilir.
- 20–48 px arasında varsayılan stroke 2 px korunur.
- Optik hacim ikonlar arasında dengelenir.
- Matematiksel merkez yerine görsel merkez esas alınır.

---

# 2. Stil

## 2.1 Ana Stil

```text
Outline
Rounded
Calm
Functional
Low-detail
```

## 2.2 Filled Kullanım

Filled ikon ana sistem değildir.

Yalnızca açık state farkı gerektiğinde kullanılabilir:

```text
bookmark outline → kaydedilmedi
bookmark filled  → kaydedildi

heart outline → favori değil
heart filled  → favori

bell outline → normal
bell filled  → aktif
```

Filled varyant:

- aynı base geometry üzerinden geliştirilir,
- ayrı bir icon kütüphanesi gibi kullanılmaz,
- yalnızca selected / active state için kullanılır.

---

# 3. Renk Sistemi

İkonların varsayılan rengi `currentColor` olmalıdır.

## 3.1 Semantic Kullanım

```text
Primary icon   → text.primary / Norn Charcoal
Secondary icon → text.secondary
Muted icon     → text.muted
Brand icon     → Deep Norn Navy
Inverse icon   → White
Disabled icon  → text.disabled
```

## 3.2 Kategori

```text
Meaning → Navy
Body    → Olive
Life    → Earth
```

Kategori anlamı yalnızca renkle verilmez. İkonun formu veya yanında yer alan metin de anlamı taşımalıdır.

## 3.3 Bronze

Bronze:

- ana UI icon rengi değildir,
- sınırlı editoryal vurgu için kullanılabilir,
- düşük kontrast üretiyorsa kullanılmaz.

---

# 4. Base UI Icon Kuralları

- Base UI ikonları `02_LUCIDE_BASE_SET.json` içinden seçilir.
- Aynı eylem için tek icon standardı kullanılır.
- Yeni icon gerekirse önce mevcut Lucide kütüphanesi kontrol edilir.
- Lucide'da uygun icon yoksa özel çizim talebi oluşturulur.
- Aynı projede Lucide, Material ve Font Awesome karıştırılmaz.
- Kod tarafında mümkünse ikonlar doğrudan paket üzerinden import edilir.
- Bütün icon kütüphanesini topluca import etmek yerine yalnızca kullanılan ikonlar import edilir.

---

# 5. Brand Custom Icon Kuralları

Özel ikonlar şu alanlarla sınırlıdır:

```text
nh-meaning
nh-body
nh-life
nh-path
nh-progress
nh-connection
nh-practice
nh-gathering
```

Gerektiğinde:

```text
nh-perspective
```

eklenebilir.

## 5.1 Zorunlu Testler

Her özel ikon:

- 16 px
- 20 px
- 24 px
- 32 px
- siyah
- beyaz
- Navy
- açık ve koyu zemin

testlerinden geçirilir.

## 5.2 Kaçınılacaklar

- lotus,
- göz,
- mandala,
- insan silueti,
- yoga pozu,
- sonsuzluk,
- rune,
- Viking,
- kristal,
- aura,
- galaksi,
- kitap,
- ampul,
- doğrudan beyin,
- kalp,
- çark,
- aşırı karmaşık monogram.

---

# 6. Semantic Mapping

UI içinde icon isimleri doğrudan component adı üzerinden değil, mümkünse semantic alias üzerinden çağrılmalıdır.

Örnek:

```text
navigation.back → arrow-left
navigation.close → x
content.play → play
education.library → library
feedback.warning → triangle-alert
```

Semantic map `03_SEMANTIC_ICON_MAP.json` içinde tanımlıdır.

---

# 7. Accessibility

## 7.1 Dekoratif Icon

Dekoratif icon:

- ekran okuyucudan gizlenir,
- ek bilgi taşımaz,
- yanında veya yakınında görünen metin bulunur.

## 7.2 İşlevsel Icon

Icon-only button:

- erişilebilir isim taşır,
- tooltip veya görünür label ile desteklenir,
- minimum touch target 44×44 px tercih edilir,
- focus state görünürdür.

## 7.3 Kritik Bilgi

Kritik işlem yalnızca soyut icon ile sunulmamalıdır.

Özellikle:

- silme,
- ödeme,
- üyelik iptali,
- sertifika,
- yayınlama,
- erişim kaldırma

işlemlerinde metin label veya confirmation gerekir.

---

# 8. Naming Convention

## 8.1 Lucide

Lucide icon adları lower kebab-case tutulur:

```text
arrow-left
circle-check
calendar-days
```

## 8.2 Norn Human Custom

```text
nh-[concept]
```

Örnek:

```text
nh-meaning
nh-body
nh-connection
```

## 8.3 Dosya

```text
nh-meaning.svg
nh-meaning_24.png
nh-meaning_48.png
```

## 8.4 Yasak İsimler

```text
icon1.svg
final-icon.svg
new-icon.svg
meaning-final-final.svg
```

---

# 9. SVG Standardı

Özel SVG çıktıları:

```xml
<svg
  xmlns="http://www.w3.org/2000/svg"
  width="24"
  height="24"
  viewBox="0 0 24 24"
  fill="none"
  stroke="currentColor"
  stroke-width="2"
  stroke-linecap="round"
  stroke-linejoin="round"
>
  <!-- path / line / circle / rect -->
</svg>
```

Kullanılmamalı:

- embedded color,
- gradient,
- filter,
- mask gerekmedikçe,
- transform karmaşası,
- raster image,
- text element,
- inline style,
- gereksiz group.

---

# 10. Review Checklist

## Sistem

- Lucide mı custom mı?
- Aynı anlam için mevcut icon var mı?
- Semantic map güncellendi mi?
- Manifest kaydı var mı?

## Görsel

- 24×24 grid?
- 1 px safe area?
- 2 px stroke?
- Round cap / join?
- Optik hacim dengeli?
- Görsel merkez doğru?
- Detay yoğunluğu uygun?
- 16 px testinden geçti mi?

## Marka

- Wellness klişesi var mı?
- Rune / Viking çağrışımı var mı?
- Norn Human'ın sakin ve modern karakteri korunuyor mu?
- Kategori yalnızca renkle mi anlatılıyor?

## Teknik

- currentColor?
- fill none?
- viewBox doğru?
- path optimize?
- dosya adı doğru?
- accessible label ihtiyacı tanımlı mı?

---

**Dosya sonu**
