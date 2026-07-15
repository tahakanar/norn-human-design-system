---
document_name: Design System
brand: Norn Human
version: 2.0
status: Foundation Specification — Component Production Required
language: tr-TR
last_updated: 2026-07-16
prepared_by: SedInsight — Stratejik Proje Liderliği & İş Geliştirme
primary_use:
  - Brand website and landing pages
  - Social media template system
  - Digital education platform
  - Mobile application
  - Instructor and admin portals
  - Campaign and event materials
  - Figma system setup
  - Claude Design and AI-assisted design production
related_documents:
  - ../01_Strategy/Brand Strategy.md
  - ../01_Strategy/Voice & Messaging.md
  - ../02_Identity/Typography.md
  - ../02_Identity/Color System.md
  - Design Tokens.json
  - Component Library.fig
---

# Norn Human Design System

## 0. Belgenin Rolü

Bu belge, Norn Human'ın bütün dijital ve görsel temas noktalarında kullanılacak tasarım sisteminin çalışma kurallarını tanımlar.

Bu dosya tek tek ekranların veya sosyal medya postlarının nasıl görünmesi gerektiğini tarif eden bir kreatif brief değildir. Farklı ekiplerin ve yapay zekâ araçlarının aynı görsel karar sisteminden üretim yapabilmesi için ortak altyapıyı kurar.

Bu sistem **Norn Human** için hazırlanmıştır. **Norn** ana marka ve kurucu yaklaşımı; **Norn Human** ise dijital eğitim platformunu, kullanıcı deneyimini, üyeliği ve ilgili pazarlama temaslarını ifade eder. Tasarım sistemi Norn ana markasının değerlerini taşır; ancak ürün bileşenleri ve dijital kullanım kuralları Norn Human'a özgüdür.



Design System şu sorulara cevap verir:

- Tasarımlar hangi temel ilkelerle üretilir?
- Marka sitesi, sosyal medya ve ürün arayüzü aynı kimliği nasıl korur?
- Grid, spacing, radius, border ve elevation nasıl kullanılır?
- Responsive tasarımlar hangi kırılma noktalarıyla çalışır?
- Bileşenler hangi anatomi ve durum kurallarına uyar?
- Fotoğraf, ikon, illüstrasyon ve pattern dili nasıl yönetilir?
- Motion ne zaman kullanılır, ne zaman kullanılmaz?
- Erişilebilirlik hangi tasarım kararlarının zorunlu parçasıdır?
- Figma dosyası nasıl organize edilir?
- Claude Design tasarım üretirken hangi kuralları ihlal edemez?

> **Ana sistem ilkesi:** Norn Human tasarımı yalnızca estetik tutarlılık değil; güven, açıklık, öğrenme kolaylığı ve ölçeklenebilir operasyon üretmelidir.

---

# 1. Sistem Kapsamı

## 1.1 Marka ve Pazarlama

- Kurumsal web sitesi
- Landing page
- Eğitim ve eğitmen sayfaları
- Blog ve kavram rehberleri
- Instagram carousel
- Reels cover
- Story
- Etkinlik ve seminer duyuruları
- E-posta ve bülten
- Sunum ve basılı materyal

## 1.2 Dijital Ürün

- Üye web deneyimi
- Mobil uygulama
- Eğitim kütüphanesi
- Video izleme
- İlerleme takibi
- Profil
- Canlı ders ve rezervasyon
- Soru-cevap
- Üyelik ve ödeme
- Eğitmen portalı
- Admin paneli
- Raporlama ve CRM ekranları

## 1.3 Bu Dosyanın Kapsamadığı Alanlar

Aşağıdaki alanlar ayrı dosya veya çalışma paketlerinde detaylandırılır:

- Nihai logo ve wordmark çizimi
- Logo kullanım kılavuzu
- Tam ikon kütüphanesi
- Bütün component varyantlarını içeren Component Library
- Nihai Design Tokens JSON
- Sayfa bazlı high-fidelity UI tasarımları
- Kod kütüphanesi
- Baskıya özel üretim spesifikasyonları

---

# 2. Design North Star

## 2.1 Tek Cümlelik Yön

**Norn Human; Norn yaklaşımının derinliğini ağırlaştırmadan, insaniliğini romantikleştirmeden ve dijital ürün yapısını soğutmadan aynı deneyimde birleştirmelidir.**

## 2.2 Vermesi Gereken His

- Güvenilir
- Sakin
- Güçlü
- Seçici
- Açık
- Düşünsel
- Yaşayan
- İnsani
- Modern
- Kökleri olan
- Uygulanabilir
- Düzenli

## 2.3 Vermemesi Gereken His

- Jenerik spiritüel marka
- Karanlık ezoterik dünya
- Siyah–altın lüks marka
- Wellness stüdyosu
- Üniversite kadar ağır yapı
- Steril teknoloji girişimi
- Renkli kurs pazaryeri
- Amatör kişisel gelişim hesabı
- Rastgele AI görsel koleksiyonu

---

# 3. Ana Tasarım İlkeleri

## 3.1 Önce Açıklık

Tasarım kullanıcının şu sorularına hızlı cevap vermelidir:

- Neredeyim?
- Bu içerik ne hakkında?
- Bana uygun mu?
- Ne yapabilirim?
- Sonraki adım nedir?
- Bu bilgiye neden güvenebilirim?

Görsel atmosfer, bilgi hiyerarşisinin önüne geçmez.

## 3.2 Derinlik Boşlukla Kurulur

Derinlik;

- aşırı karanlık arka plan,
- ağır metafor,
- çok katmanlı efekt,
- sembol kalabalığı

ile değil;

- ölçülü tipografi,
- boşluk,
- editoryal ritim,
- bağlam,
- gerçek içerik,
- kontrollü detay

ile oluşturulur.

## 3.3 Bir Tasarım, Bir Ana Mesaj

Her ekran, post veya slayt tek bir ana görevi taşımalıdır.

Bir tasarımda:

- bir ana mesaj,
- en fazla iki destekleyici bilgi,
- tek bir primary action

öne çıkarılır.

## 3.4 İnsan Görünür Olmalıdır

Norn Human yalnızca soyut şekillerden oluşmaz. Sistem gerçek eğitmen, katılımcı, mekân, hareket, öğrenme anı ve topluluğa yer açmalıdır.

## 3.5 Marka ve Ürün Aynı Aileden Gelmeli

Pazarlama sayfaları daha editoryal, ürün ekranları daha işlevsel olabilir. Ancak ikisi aynı:

- renk ailesi,
- tipografi,
- spacing mantığı,
- radius karakteri,
- ikon dili,
- içerik yaklaşımı

üzerinden ilerlemelidir.

## 3.6 Erişilebilirlik Son Kontrol Değildir

Erişilebilirlik renk, komponent boyutu, motion, içerik hiyerarşisi, form ve responsive davranışta en baştan ele alınır.

---

# 4. Sistem Mimarisi

Norn Human Design System dört katmandan oluşur.

## 4.1 Foundations

- Color
- Typography
- Spacing
- Sizing
- Grid
- Radius
- Border
- Elevation
- Opacity
- Iconography
- Imagery
- Motion
- Accessibility

## 4.2 Primitives

Tek başına anlam taşımayan yapı taşları:

- color scales,
- spacing values,
- font sizes,
- radius values,
- shadow values,
- stroke widths,
- duration ve easing.

## 4.3 Semantic Tokens

Kullanım amacını belirten değerler:

```text
text.primary
bg.canvas
action.primary.default
border.focus
space.section.desktop
radius.card
motion.feedback.fast
```

## 4.4 Components and Patterns

- Button
- Input
- Card
- Tag
- Tabs
- Navigation
- Modal
- Education Card
- Instructor Card
- Event Card
- Player
- Progress
- Empty State
- Filter Pattern
- Form Pattern
- Checkout Pattern
- Social Templates

Component detayları `Component Library.fig` içinde üretilir.

---

# 5. Figma Dosya Yapısı

## 5.1 Ana Sayfalar

```text
00 — Cover & Status
01 — Foundations
02 — Brand Elements
03 — Components
04 — Patterns
05 — Web Templates
06 — Product Templates
07 — Social Templates
08 — Prototypes
09 — Documentation
90 — Exploration
99 — Archive
```

## 5.2 Sayfa Rolleri

### 00 — Cover & Status

- Sistem adı
- Sürüm
- Son güncelleme
- Sahiplik
- Status
- Changelog

### 01 — Foundations

- Color variables
- Typography styles
- Spacing
- Grid
- Radius
- Elevation
- Motion
- Accessibility

### 02 — Brand Elements

- Logo varyantları
- Wordmark
- Pattern
- Fotoğraf dili
- Kategori görsel sistemi

### 03 — Components

- Base components
- Variants
- States
- Responsive properties
- Accessibility annotations

### 04 — Patterns

- Form
- Filter
- Navigation
- Empty state
- Error recovery
- Content discovery
- Learning progression

### 05–07 — Templates

Onaylı component ve foundations kullanılarak oluşturulmuş web, ürün ve sosyal medya sayfa örnekleri.

### 90 — Exploration

Henüz onaylanmamış alternatiflerdir. Production için kullanılmaz.

### 99 — Archive

Eski sürümler ve deprecated components.

## 5.3 Component İsimlendirme

```text
Button
Input
Card/Education
Card/Instructor
Navigation/Header
Navigation/Sidebar
Feedback/Alert
Overlay/Modal
```

Variant properties:

```text
Type=Primary
Size=Medium
State=Default
Icon=Leading
Theme=Light
```

Kaçınılacak isimler:

```text
Button New
Final Final
Card 2
Blue Button
Copy of Input
```

---

# 6. Layout Grid

## 6.1 Breakpoints

| Token | Viewport |
|---|---:|
| `xs` | 0–479px |
| `sm` | 480–767px |
| `md` | 768–1023px |
| `lg` | 1024–1279px |
| `xl` | 1280–1535px |
| `2xl` | 1536px ve üzeri |

Breakpoint'ler cihaz modeline değil, içeriğin bozulduğu noktalara göre uygulanır.

## 6.2 Web Container

| Breakpoint | Max container | Side padding |
|---|---:|---:|
| xs | Fluid | 20px |
| sm | Fluid | 24px |
| md | 720px | 32px |
| lg | 960px | 40px |
| xl | 1200px | 48px |
| 2xl | 1320px | 64px |

Uzun okuma alanı:

```text
Max width: 68ch
```

Form alanı:

```text
Max width: 480–560px
```

Dashboard:

```text
Max width: 1440px
```

## 6.3 Column Grid

### Mobile

```text
Columns: 4
Gutter: 16px
Margin: 20–24px
```

### Tablet

```text
Columns: 8
Gutter: 20–24px
Margin: 32px
```

### Desktop

```text
Columns: 12
Gutter: 24px
Margin: 40–64px
```

## 6.4 Social Media Grid

1080px tasarımlar için:

```text
Safe outer margin: 72–96px
Columns: 6 veya 12
Gutter: 20–28px
Baseline increment: 8px
```

Story ve reels tasarımlarında platform UI güvenli alanları ayrıca kontrol edilir.

---

# 7. Spacing System

## 7.1 Temel Birim

Spacing sistemi **4px temel birime** dayanır. Ana ritim çoğunlukla 8px katlarıyla kurulur.

## 7.2 Primitive Scale

| Token | Value |
|---|---:|
| `space.0` | 0 |
| `space.1` | 4px |
| `space.2` | 8px |
| `space.3` | 12px |
| `space.4` | 16px |
| `space.5` | 20px |
| `space.6` | 24px |
| `space.8` | 32px |
| `space.10` | 40px |
| `space.12` | 48px |
| `space.16` | 64px |
| `space.20` | 80px |
| `space.24` | 96px |
| `space.32` | 128px |
| `space.40` | 160px |

## 7.3 Semantic Spacing

| Token | Mobile | Desktop |
|---|---:|---:|
| `space.page.inline` | 20px | 48–64px |
| `space.section.compact` | 48px | 64px |
| `space.section.default` | 64px | 96px |
| `space.section.spacious` | 80px | 128px |
| `space.card.padding.sm` | 16px | 16px |
| `space.card.padding.md` | 20px | 24px |
| `space.card.padding.lg` | 24px | 32px |
| `space.stack.sm` | 8px | 8px |
| `space.stack.md` | 16px | 16px |
| `space.stack.lg` | 24px | 24px |

## 7.4 Kullanım Kuralı

- Bileşen içinde küçük değerler
- Bileşenler arasında orta değerler
- Bölümler arasında büyük değerler
- Hiyerarşi arttıkça boşluk artar
- Metin sığdırmak için spacing rastgele azaltılmaz

---

# 8. Sizing and Density

## 8.1 Control Heights

| Size | Height | Kullanım |
|---|---:|---|
| Small | 36px | Yoğun desktop alanı |
| Medium | 44px | Varsayılan web ve ürün |
| Large | 52px | Landing page ve güçlü CTA |
| XL | 60px | Sınırlı kampanya alanı |

Mobil primary action için varsayılan minimum:

```text
48px
```

## 8.2 Icon Button

| Size | Target |
|---|---:|
| Small | 36×36px |
| Medium | 44×44px |
| Large | 52×52px |

## 8.3 Touch Target Standard

```text
Tercih edilen minimum: 44×44 CSS px
Teknik alt sınır: WCAG 2.2 AA koşullarına uygun 24×24 CSS px veya yeterli spacing
```

24px teknik minimum, önerilen varsayılan component boyutu değildir.

## 8.4 Density Modes

### Comfortable

- Öğrenci ve pazarlama deneyimi
- Daha büyük touch targets
- Daha fazla spacing
- Varsayılan mode

### Compact

- Admin ve eğitmen panellerindeki yoğun tablolar
- Yalnızca desktop
- Erişilebilir kontrol boyutları korunur

---

# 9. Border Radius

## 9.1 Radius Karakteri

Norn Human tamamen keskin veya aşırı yuvarlak bir sistem kullanmaz. Köşeler yumuşak fakat kontrollüdür.

## 9.2 Radius Scale

| Token | Value | Kullanım |
|---|---:|---|
| `radius.none` | 0 | Full bleed |
| `radius.xs` | 4px | Küçük badge |
| `radius.sm` | 8px | Input, tag |
| `radius.md` | 12px | Button, compact card |
| `radius.lg` | 16px | Default card, modal |
| `radius.xl` | 24px | Hero card, large media |
| `radius.full` | 999px | Avatar, pill |

Semantic kullanım:

```text
radius.button = 12px
radius.input = 10–12px
radius.card = 16px
radius.modal = 20px
radius.media = 16–24px
```

Aynı sayfada rastgele radius değerleri kullanılmaz.

---

# 10. Borders and Dividers

## 10.1 Stroke Scale

| Token | Value |
|---|---:|
| `stroke.hairline` | 1px |
| `stroke.default` | 1px |
| `stroke.strong` | 2px |
| `stroke.focus` | 2px |
| `stroke.emphasis` | 3px |

## 10.2 Öncelik Sırası

Alan ayrımı için öncelik:

1. Boşluk
2. Zemin farkı
3. Border
4. Shadow

Divider, spacing ile çözülebilen her alanda kullanılmaz.

---

# 11. Elevation and Shadows

Shadow dekorasyon için değil, katman ve etkileşim ayrımı için kullanılır.

```text
elevation.0
No shadow

elevation.1
0 1px 2px rgba(31, 36, 40, 0.06)

elevation.2
0 4px 12px rgba(31, 36, 40, 0.08)

elevation.3
0 10px 28px rgba(31, 36, 40, 0.12)

elevation.4
0 20px 48px rgba(31, 36, 40, 0.16)
```

| Elevation | Kullanım |
|---|---|
| 0 | Normal page section |
| 1 | Hover card, sticky bar |
| 2 | Dropdown, floating card |
| 3 | Modal, popover |
| 4 | Kritik overlay; sınırlı |

Kartların çoğu surface, border ve spacing ile ayrılır.

---

# 12. Opacity

| Token | Value |
|---|---:|
| `opacity.disabled` | 0.48 |
| `opacity.muted` | 0.64 |
| `opacity.overlay.light` | 0.84 |
| `opacity.overlay.dark` | 0.76 |
| `opacity.scrim` | 0.56 |

Kurallar:

- Metin kontrastı opacity ile rastgele düşürülmez
- Disabled yalnızca opacity ile anlatılmaz
- Fotoğraf overlay değeri gerçek görselde test edilir
- Primary text üzerinde opacity kullanılmaz

---

# 13. Typography and Color Integration

Tipografi ayrıntıları `Typography.md`, renk ayrıntıları `Color System.md` içindedir.

## 13.1 Tipografi Özeti

```text
Source Serif 4: Marka, editoryal, büyük başlık, alıntı
Manrope: Gövde, UI, sosyal medya, form, buton, veri
```

- Serif buton, input, tab ve tablo metni olmaz
- Text color typography style içine gömülmez
- Bir component içinde iki font yalnızca açık hiyerarşi gerekçesiyle kullanılır

## 13.2 Renk Özeti

```text
Canvas: Ivory
Primary text: Charcoal
Primary action: Navy
Editorial accent: Bronze
Body / practice: Olive
Life / relationship: Earth
```

- Primitive renk doğrudan component içine yazılmaz
- Semantic token kullanılır
- Kategori rengi action rengi yerine geçmez
- Status renkleri kategori renkleriyle karıştırılmaz
- Renk hiçbir bilgiyi tek başına taşımaz

---

# 14. Iconography

## 14.1 İkon Karakteri

- Sade
- Çizgisel
- Çok geometrik olmayan
- Çok organik olmayan
- Küçük ölçekte açık
- Ürün arayüzüne uygun

## 14.2 Base Style

```text
Grid: 24×24
Stroke: 1.75–2px
Line cap: Round
Line join: Round
Default fill: None
Default color: CurrentColor
```

## 14.3 Sizes

| Size | Kullanım |
|---|---|
| 16px | Metadata |
| 20px | Form, button |
| 24px | Varsayılan UI |
| 32px | Empty state |
| 40–48px | Marketing feature |

## 14.4 Kategori İkonları

Kavramlar:

- Merkez
- Yol
- Katman
- Bağlantı
- Hareket
- Denge
- İlişki
- Üretim

Kategori ikonları:

- metin etiketiyle birlikte kullanılır,
- mandala, göz, lotus, aura ve rune klişelerine yaslanmaz,
- aynı stroke ve optik ağırlığı korur.

## 14.5 Yasaklar

- Farklı ikon kütüphanelerini karıştırmak
- Filled ve outline ikonları rastgele kullanmak
- İkon içine metin koymak
- Yalnızca ikona dayalı belirsiz navigation

---

# 15. Imagery

## 15.1 Fotoğrafın Rolü

Fotoğraf Norn Human'ın yaşayan tarafını kanıtlar.

Göstermesi gerekenler:

- Eğitmen ve katılımcı ilişkisi
- Öğrenme anı
- Uygulama
- Hareket
- Mekân
- Kamp
- Üretim
- Topluluk

## 15.2 Seçim Kriterleri

- Doğal ışık
- Gerçek ortam
- Doğal beden dili
- Çeşitlilik
- Aşırı prodüksiyonlu olmayan görünüm
- Konuyla gerçek bağ
- Stok klişesinden uzaklık
- Negatif alan
- Mobil crop'a uygunluk

## 15.3 Kaçınılacak Görseller

- Meditasyon yapan siluet
- Kristal, tütsü ve mum kompozisyonu
- Eller havada enerji görseli
- Soyut galaksi
- Kusursuz yoga pozu
- Sahte uzman stok fotoğrafı
- Dramatik önce–sonra dönüşümü

## 15.4 Aspect Ratios

| Ratio | Kullanım |
|---|---|
| 16:9 | Hero, video |
| 4:3 | Atölye, mekân |
| 3:2 | Galeri |
| 4:5 | Instagram post |
| 9:16 | Reels / story |
| 1:1 | Avatar, compact card |
| 3:4 | Eğitmen portresi |

---

# 16. Illustration and Graphic Language

## 16.1 Kavramlar

- İplik
- Çizgi
- Örgü
- Yol
- Merkez
- Katman
- Denge
- Akış
- Bağlantı
- Zaman

## 16.2 Ana Yaklaşım

Grafik dil:

- tek veya birkaç çizgiden oluşan,
- ritmik,
- sakin,
- kontrollü asimetrik,
- organik ve geometrik arasında,
- boşlukla çalışan

bir sistem olmalıdır.

## 16.3 Pattern Kullanımı

Pattern:

- düşük yoğunlukta,
- bölüm geçişinde,
- sosyal medya seri işareti olarak,
- baskı detayında

kullanılabilir.

Pattern metin okunabilirliğini düşürmez, bütün arka planı doldurmaz ve logo yerine kullanılmaz.

---

# 17. Content Density

## 17.1 Marketing

- Daha fazla boşluk
- Daha büyük tipografi
- Daha az component
- Her bölümde tek anlatı
- Güven kanıtlarının görünürlüğü

## 17.2 Editorial

- 68ch okuma alanı
- Net heading sistemi
- İçindekiler
- Sınırlı pull quote
- Kaynak ve metadata

## 17.3 Product

- Görev odaklı
- Daha az dekor
- Net states
- Tutarlı form ve navigation

## 17.4 Admin

- Daha yüksek bilgi yoğunluğu
- Compact mode
- Tablo ve filtre
- Veri öncelikli
- Marka dekoru minimum
- İşlem güvenliği maksimum

---

# 18. Responsive Behavior

## 18.1 Mobile First

Tasarım önce mobilde:

- içerik sırası,
- ana görev,
- CTA,
- touch target,
- metin uzunluğu

açısından çözülür.

Desktop, mobil tasarımın yalnızca genişletilmiş hali değildir.

## 18.2 Reflow

- 12 kolon → 8 kolon → 4 kolon
- Kartlar alt alta geçer
- Sidebar drawer veya accordion olabilir
- Tablo list/card görünümüne dönüşebilir
- İkincil aksiyonlar overflow içinde gruplanabilir
- Ana CTA görünürlüğünü korur

## 18.3 Mobil İçerik Sırası

1. Sayfa amacı
2. Ana içerik
3. Primary action
4. Güven ve detay
5. İkincil içerik

Görsel desktop'ta solda olduğu için mobilde otomatik ilk sıraya alınmaz.

## 18.4 Navigation

### Marketing

- Desktop header
- Mobile drawer
- Tek primary CTA
- Gereksiz mega menu yok

### Product

- Desktop sidebar veya top navigation
- Mobile bottom navigation yalnızca ana 3–5 işlev için
- Back ve breadcrumb
- Aktif konum görünür

---

# 19. Motion System

## 19.1 Karakter

Motion:

- sakin,
- kısa,
- anlamlı,
- yön gösteren,
- dikkat dağıtmayan

olmalıdır.

## 19.2 Amaçları

- Durum değişikliğini açıklamak
- Giriş–çıkış ilişkisini göstermek
- Aksiyona geri bildirim vermek
- Yön duygusu sağlamak
- Yüklenmeyi görünür kılmak

## 19.3 Duration Tokens

| Token | Duration | Kullanım |
|---|---:|---|
| `motion.instant` | 0ms | Reduced motion |
| `motion.fast` | 120ms | Hover, press |
| `motion.base` | 180ms | Küçük feedback |
| `motion.medium` | 240ms | Dropdown, accordion |
| `motion.slow` | 320ms | Modal, drawer |
| `motion.editorial` | 480ms | Sınırlı marketing reveal |

## 19.4 Easing

```text
Standard: cubic-bezier(0.2, 0, 0, 1)
Enter:    cubic-bezier(0, 0, 0, 1)
Exit:     cubic-bezier(0.3, 0, 1, 1)
```

## 19.5 Reduced Motion

Reduced motion tercihinde:

- Parallax kapatılır
- Büyük slide ve zoom kaldırılır
- Page flip kullanılmaz
- Opacity veya anlık state değişimi tercih edilir
- Fonksiyon kaybolmaz

## 19.6 Yasak Motion

- Sürekli dönen sembol
- Parlayan aura
- Uzun parallax
- Scroll hijacking
- Zorunlu autoplay motion
- Dikkat için titreşim
- Aşırı konfeti

---

# 20. Interaction States

Her interaktif component en az şu durumları düşünmelidir:

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

## 20.1 Focus

Varsayılan focus:

```text
2px solid indicator
2px offset
Yüksek kontrastlı semantic focus color
```

Focus yalnızca çok hafif gölgeyle anlatılmaz.

## 20.2 Hover

Hover renk, border, elevation veya küçük transform ile gösterilebilir. Touch cihazlarda hover'a bağlı kritik bilgi olmaz.

## 20.3 Loading

- Button label mümkünse korunur
- Layout zıplamaz
- Uzun işlemde durum mesajı verilir
- Tekrarlanan işlem engellenir

## 20.4 Disabled

Disabled durumda gerektiğinde neden kullanılamadığı açıklanır. Yalnızca düşük opacity yeterli değildir.

## 20.5 Error

Error:

- alanı gösterir,
- problemi açıklar,
- çözüm önerir,
- girilen veriyi gereksiz yere silmez,
- yalnızca kırmızı renge dayanmaz.

---

# 21. Accessibility Requirements

## 21.1 Hedef

```text
WCAG 2.2 Level AA
```

## 21.2 Zorunlu Kontroller

- Metin kontrastı
- Non-text contrast
- Renk dışı durum göstergeleri
- Keyboard navigation
- Visible focus
- Focus not obscured
- Heading order
- Form label ve instruction
- Error identification ve suggestion
- Reflow
- Text resize
- Reduced motion
- Touch target
- Caption ve transcript
- Alt text planı
- Dil ve okuma açıklığı

## 21.3 Target Size

Sistem varsayılanı:

```text
44×44px veya daha büyük interaktif alan
```

Yoğun arayüzde daha küçük hedef kullanılacaksa WCAG 2.2 minimum target size ve spacing koşulları ayrıca doğrulanır.

## 21.4 Focus Appearance

Focus indicator:

- en az 2px görünür alan,
- component ve çevresiyle yeterli kontrast,
- keyboard interaction'da kesintisiz görünürlük

sağlamalıdır.

## 21.5 Semantic Annotation

Figma annotation içinde:

- heading level,
- button name,
- link purpose,
- image alt intent,
- form label,
- status message,
- reading order

belirtilmelidir.

## 21.6 Video ve Eğitim İçeriği

- Caption
- Transcript
- Keyboard control
- Playback speed
- Pause
- Volume
- Yalnızca sesle verilen bilgiye alternatif

ürün gereksinimlerine eklenmelidir.

---

# 22. Component Architecture

## 22.1 Base Components

- Button
- Icon Button
- Link
- Input
- Textarea
- Select
- Checkbox
- Radio
- Switch
- Tag
- Badge
- Avatar
- Tooltip
- Divider
- Progress
- Skeleton
- Spinner

## 22.2 Navigation

- Header
- Mobile Navigation
- Sidebar
- Bottom Navigation
- Breadcrumb
- Tabs
- Pagination
- Stepper

## 22.3 Content

- Education Card
- Instructor Card
- Event Card
- Article Card
- Program Schedule
- Accordion
- Quote
- Media Block
- Player Shell
- Learning Progress
- Resource List

## 22.4 Feedback

- Alert
- Toast
- Inline Message
- Empty State
- Error State
- Confirmation
- Modal
- Drawer
- Popover

## 22.5 Commerce and Membership

- Pricing Card
- Membership Summary
- Checkout Summary
- Coupon Field
- Payment Status
- Access State
- Upgrade Prompt

## 22.6 Social Templates

- Manifesto Cover
- Concept Carousel
- Education Announcement
- Instructor Profile
- Event Announcement
- Reels Cover
- Quote Card
- Community / Camp Template

---

# 23. Component Anatomy Rules

Her component dokümantasyonunda bulunmalıdır:

1. Amaç
2. Ne zaman kullanılır?
3. Ne zaman kullanılmaz?
4. Anatomy
5. Variants
6. Sizes
7. States
8. Content rules
9. Responsive behavior
10. Accessibility notes
11. Design tokens
12. Developer notes
13. Do / Don't examples

## 23.1 Variant Limiti

Yeni variant yalnızca:

- farklı semantik rol,
- farklı interaction,
- farklı responsive davranış,
- tekrar eden doğrulanmış kullanım

varsa eklenir.

Sadece görsel çeşitlilik için variant oluşturulmaz.

## 23.2 Gerçek İçerikle Test

Component şu içeriklerle test edilir:

- Uzun eğitim adı
- Uzun eğitmen adı
- Tarih ve saat
- Fiyat
- Hata mesajı
- İki satır buton riski
- Boş ve dolu durum

---

# 24. Core Pattern Rules

## 24.1 Form

- Label input üstünde
- Placeholder label yerine kullanılmaz
- Required açık
- Helper text görünür
- Error alanla ilişkili
- Kullanıcı verisi hata sonrası korunur
- Tek kolon varsayılan

## 24.2 Card

Kart:

- içerik türünü,
- ana başlığı,
- gerekli metadata'yı,
- CTA'yı

taşır.

Kart içinde birden fazla primary CTA bulunmaz.

## 24.3 Filter

- Aktif filtreler görünür
- Tümünü temizle
- Sonuç sayısı
- Mobile drawer
- Desktop inline veya sidebar
- Sonuç feedback'i

## 24.4 Empty State

- Ne olduğunu açıklar
- Gerektiğinde nedenini söyler
- Gerçek sonraki adımı gösterir
- Kullanıcıyı suçlamaz
- Dekorasyon mesajın önüne geçmez

## 24.5 Destructive Action

- Açık fiil
- Etki açıklaması
- Confirmation
- Geri alınabilirlik
- Renk + metin + ikon
- “Evet / Hayır” yerine işlem adı

---

# 25. Marketing Page Structure

Norn Human marketing sayfaları genellikle şu sırayı takip eder:

1. Hero
2. Problem veya bağlam
3. Norn Human yaklaşımı
4. Ana değer önerileri
5. Eğitim alanları veya program
6. Eğitmen ve güven
7. Dijital + fiziksel deneyim
8. Sosyal proof veya kanıt
9. CTA
10. SSS
11. Footer

Her sayfa bütün bölümleri kullanmak zorunda değildir. Amaç, kullanıcı yolculuğuna göre gereksiz bölümleri kaldırmaktır.

---

# 26. Product Page Structure

## 26.1 Education Library

- Search
- Category
- Level
- Instructor
- Continue learning
- Recommended
- Empty ve no-result states

## 26.2 Education Detail

- Eğitim adı
- Değer açıklaması
- Eğitmen
- Format / seviye / süre
- Curriculum
- Learning outcomes
- Uygunluk ve sınırlar
- Access state
- CTA
- Related content

## 26.3 Player

- Video
- Chapter navigation
- Progress
- Transcript / caption
- Resources
- Next lesson
- Exit and continue
- Error recovery

## 26.4 Dashboard

- Continue learning
- Upcoming live events
- Progress
- Saved items
- Relevant next step
- Account and access alerts

Dashboard bütün modüllerin reklam alanı değildir. Kullanıcının sonraki en anlamlı adımını göstermelidir.

---

# 27. Social Media Template System

## 27.1 Ortak Kurallar

- 72–96px safe margin
- Bir ana mesaj
- En fazla iki font weight
- Bir ana vurgu rengi
- Seri etiketi
- Mobilde okunabilir başlık
- Gerçek CTA
- Logo küçük ve tutarlı

## 27.2 Carousel

- Cover
- Context
- Main insight
- Supporting explanation
- Example veya application
- Summary
- CTA

Slide sayısı içeriğe göre belirlenir.

## 27.3 Reels Cover

- Konu ilk okunur
- Eğitmen ikinci seviye
- Seri etiketi üçüncü seviye
- 2–4 satır
- Safe crop
- Feed preview kontrolü

## 27.4 Announcement

- Program adı
- Eğitmen
- Tarih ve saat
- Format
- Yer veya online
- CTA

Dekoratif kavram metni operasyonel bilginin önüne geçmez.

---

# 28. Design Tokens Architecture

## 28.1 Katmanlar

```text
Global / Primitive
Alias / Semantic
Component
```

### Global

```text
color.navy.800
space.6
radius.lg
font.size.16
```

### Alias

```text
text.primary
bg.canvas
space.card.padding
radius.card
```

### Component

```text
button.primary.bg.default
button.primary.text.default
input.border.focus
card.education.padding
```

## 28.2 Token Kuralı

Component token doğrudan raw hex veya px yerine semantic veya primitive token'a referans verir.

## 28.3 Naming

- İngilizce
- Küçük harf
- Nokta ayrımı
- Görünüm yerine işlev
- `blue` yerine `brand`
- `big` yerine `lg`
- State açık adıyla

Kaçınılacak isimler:

```text
niceBlue
goldText
cardShadowNew
paddingBig
buttonGreen
homepageTitle
```

---

# 29. Documentation and Handoff

## 29.1 Her Component Tesliminde

- Figma component link
- Status
- Version
- Anatomy
- Variants
- Responsive
- Tokens
- Accessibility
- Content notes
- Developer behavior
- Test cases

## 29.2 Status Modeli

```text
Exploration
Draft
Review
Ready for Development
In Development
Released
Deprecated
```

## 29.3 Definition of Ready

Bir component geliştirmeye hazır sayılmadan önce:

- kullanım amacı net,
- bütün state'ler tanımlı,
- responsive davranış belli,
- accessibility acceptance criteria yazılı,
- gerçek içerik test edilmiş,
- token referansları tamam,
- design review tamam

olmalıdır.

## 29.4 Definition of Done

- Geliştirme tasarımla uyumlu
- Keyboard test
- Screen reader smoke test
- Contrast kontrolü
- Responsive kontrol
- Loading/error/empty state
- Visual regression
- Documentation güncel
- Changelog yazılmış

---

# 30. Governance

## 30.1 Roller

### Design System Owner

- Sistem bütünlüğü
- Component review
- Token ve naming
- Figma yönetimi

### Brand Owner

- Marka stratejisi
- Görsel kimlik
- Kampanya ve sosyal şablonlar

### Product / UX Owner

- Kullanım ihtiyacı
- Interaction
- User journey
- Priority

### Engineering Owner

- Kod mimarisi
- Accessibility implementation
- Performance
- Release

### Content Owner

- UI copy
- Eğitim metadata
- Hata ve empty state
- Türkçe içerik testi

## 30.2 Yeni Component Talebi

- Problem
- Kullanıcı ve kullanım alanı
- Mevcut component neden yetmiyor?
- Tekrar sıklığı
- State gereksinimleri
- Responsive ihtiyaç
- Accessibility riski
- İş önceliği

## 30.3 Değişiklik Yönetimi

Token veya temel component değişikliği:

- etki analizi,
- bağımlı ekranlar,
- migration plan,
- version,
- changelog,
- release note

olmadan yapılmaz.

---

# 31. Implementation Roadmap

## 31.1 İş Paketleri

### WP1 — Foundations

- Typography styles
- Color variables
- Grid
- Spacing
- Radius
- Elevation
- Motion
- Accessibility

**Çıktı:** Onaylı foundation page

### WP2 — Base Components

- Button
- Input
- Form controls
- Tag
- Badge
- Card base
- Feedback
- Overlay

**Çıktı:** UI temel component seti

### WP3 — Brand Components

- Header
- Footer
- Editorial blocks
- Education card
- Instructor card
- Event card
- CTA section
- Social templates

**Çıktı:** Marka ve pazarlama component seti

### WP4 — Product Components

- Navigation
- Library
- Player shell
- Progress
- Filter
- Table
- Modal
- Empty/error/loading
- Dashboard widgets

**Çıktı:** MVP product component seti

### WP5 — Templates and QA

- Web templates
- Product templates
- Social templates
- Responsive
- Accessibility
- Documentation

**Çıktı:** Kullanıma hazır sistem

## 31.2 Bağımlılıklar

```text
Typography + Color
        ↓
Spacing + Grid + Tokens
        ↓
Base Components
        ↓
Brand / Product Components
        ↓
Patterns
        ↓
Templates
        ↓
QA + Documentation
```

Logo ve icon system brand component üretimini etkiler; base UI component üretimini tamamen durdurmamalıdır.

## 31.3 Kritik Yol

1. Foundations onayı
2. Token yapısı
3. Base components
4. Education ve navigation components
5. MVP templates
6. Accessibility QA
7. Development handoff

## 31.4 Paralel Çalışabilecek İşler

- Logo çalışması + base UI components
- Fotoğraf asset araştırması + token kurulumu
- Social template exploration + product form components
- Content model + education card design
- Icon set + web layout templates

## 31.5 Darboğazlar

- Logo kararının gecikmesi
- Eğitim metadata'sının net olmaması
- Üyelik modelinin değişmesi
- Yıldız sisteminin belirsizliği
- Gerçek fotoğraf asset eksikliği
- Türkçe uzun içerikle test yapılmaması
- Component yerine ekran bazlı tasarım üretilmesi
- Design token olmadan paralel ekip üretimi

---

# 32. Claude Design Rules

## 32.1 Önce Tasarım Türünü Belirle

- Brand / marketing
- Editorial
- Social
- Product
- Admin
- Event
- Presentation

## 32.2 Sonra İçerik Amacını Belirle

- Tanıtma
- Açıklama
- Güven kurma
- Eğitim keşfi
- Kayıt
- İzleme
- İlerleme
- Yönetim

## 32.3 Zorunlu Kurallar

Claude Design:

- yalnızca tanımlı fontları kullanmalı,
- tanımlı palette kalmalı,
- 4px spacing sistemini korumalı,
- semantic color kullanmalı,
- bir tasarımda bir ana mesaj taşımalı,
- gerçek Türkçe içerikle test etmeli,
- mobil varyant üretmeli,
- loading/error/empty state düşünmeli,
- focus ve target size belirtmeli,
- fotoğrafı gerçek deneyim kanıtı olarak kullanmalı,
- yeni component üretmeden önce mevcut sistemi kontrol etmelidir.

## 32.4 Yasaklar

Claude Design:

- üçüncü font eklememeli,
- neon veya mor aura kullanmamalı,
- siyah–altın lüks sistem kurmamalı,
- bütün kartları farklı renge boyamamalı,
- çok küçük metin kullanmamalı,
- serif UI button üretmemeli,
- mobile ekranı desktop'tan otomatik küçültmemeli,
- hover'a kritik bilgi koymamalı,
- erişilemez pastel metin kullanmamalı,
- rastgele radius ve shadow üretmemeli,
- dark mode'u talep olmadan üretmemeli,
- sosyal medya şablonunu ürün arayüzüne taşımamalıdır.

---

# 33. Design Review Checklist

## Strateji

- Norn Human doğru kategoride görünüyor mu?
- Fazla spiritüel veya teknolojik mi?
- Kullanıcı değeri görünür mü?
- Güven unsuru var mı?

## Hiyerarşi

- Ana görev açık mı?
- Birden fazla primary action var mı?
- Operasyonel bilgi dekorun arkasında mı?

## Foundations

- Doğru font?
- Doğru semantic color?
- Spacing scale?
- Radius?
- Grid?
- Shadow?

## Responsive

- Mobil çözüm var mı?
- İçerik sırası doğru mu?
- Long content taşması var mı?
- Table ve navigation davranışı belli mi?

## Interaction

- Hover?
- Focus?
- Active?
- Disabled?
- Loading?
- Error?
- Success?

## Accessibility

- Contrast?
- Target size?
- Keyboard?
- Focus visible?
- Color-independent meaning?
- Reduced motion?
- Heading order?
- Form label ve error?

## Production

- Auto layout?
- Variables?
- Components?
- Naming?
- Annotation?
- Changelog?

---

# 34. System Summary

## Visual Character

```text
Sıcak nötrler
Derin lacivert
Sınırlı bronz
Zeytin ve toprak destekleri
Source Serif 4 + Manrope
Kontrollü radius
Düşük elevation
Sistemli boşluk
Gerçek insan ve mekân
İnce çizgisel grafikler
```

## Layout

```text
4px base
8px main rhythm
4 / 8 / 12 column grid
Mobile first
68ch editorial width
44px default controls
```

## Interaction

```text
Visible focus
Clear states
Short motion
Reduced-motion support
No hover-only critical content
No color-only meaning
```

## Sistem İlkesi

> **Norn Human Design System; markanın derinlik ve insanilik duygusunu, dijital ürünün açıklık ve operasyon ihtiyacıyla aynı sistem içinde birleştirir.**

---

# 35. Teknik Referans Çerçevesi

Bu sistem aşağıdaki teknik yaklaşımı esas alır:

- WCAG 2.2 Level AA erişilebilirlik hedefi
- Semantic design token mimarisi
- Mobile-first responsive tasarım
- Keyboard ve focus görünürlüğü
- Reduced motion desteği
- En az 24×24px teknik target size koşulu; Norn Human varsayılanında daha büyük hedefler
- Component ve token temelli handoff
- Gerçek içerikle responsive ve accessibility testi

---

# 36. Kaynak Girdileri

Bu tasarım sistemi aşağıdaki proje kararlarının birlikte değerlendirilmesiyle hazırlanmıştır:

- Norn Human Brand Strategy
- Norn Human Voice & Messaging
- Norn Human Typography
- Norn Human Color System
- Norn Designer Brief
- Norn Human dijital deneyiminin Norn ekosistemindeki canlı ve fiziksel çalışmalarla ilişkilendirilmesi
- Sosyal medya sisteminin gelecekte ürün arayüzüne taşınabilir olması gereksinimi
- Eğitim platformu MVP modülleri
- Üye, eğitmen ve admin deneyimi ihtiyaçları
- W3C WCAG 2.2 erişilebilirlik kriterleri
- Modern bilgelik, bütünlük, yol, akış ve bağlantı kavramları

---

**Dosya sonu**
