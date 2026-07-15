---
document_name: Claude Design Icon Prompt
project: Norn / Norn Human Icon System
version: 1.0
status: Ready to Use
language: tr-TR
last_updated: 2026-07-16
---

# Claude Design Icon System Prompt

Bu klasördeki dosyaları `00_START_HERE.md` içinde belirtilen sırayla oku.

## Görev

Norn Human için Lucide tabanlı hibrit icon sistemi kur.

Sistem iki katmandan oluşmalıdır:

1. Base UI Icons → Lucide
2. Brand Custom Icons → Norn Human'a özgü sekiz özel ikon

## İlk Aşama

Önce:

- Base UI icon setini kontrol et,
- semantic alias map'i incele,
- eksik veya çakışan anlamları raporla,
- özel icon brieflerini özetle.

Görsel üretmeden önce şu formatta yanıt ver:

```text
1. System Understanding
2. Base UI Coverage
3. Semantic Conflicts
4. Custom Icon Concepts
5. Risks
6. Planned Outputs
```

## Teknik Kurallar

```text
Canvas: 24×24
ViewBox: 0 0 24 24
Stroke: 2px
Linecap: round
Linejoin: round
Stroke alignment: centered
Fill: none
Color: currentColor
Safe area: minimum 1px
Element spacing: minimum 2px
```

## Özel İkonlar

Şu ikonları üret:

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

Her ikon için üç alternatif geliştir.

## Kaçınılacaklar

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
- beyin,
- kitap,
- ampul,
- kalp,
- çark,
- node network,
- teknoloji devresi.

## Zorunlu Test

Her alternatif:

- 16 px,
- 20 px,
- 24 px,
- 32 px,
- siyah,
- beyaz,
- Navy,
- açık zemin,
- koyu zemin

olarak test edilmelidir.

## Değerlendirme

Her ikon için:

- kavramsal uyum,
- ayırt edicilik,
- Lucide uyumu,
- küçük boyut performansı,
- yanlış kategori riski,
- optik hacim

değerlendirmesi yap.

## Çıktı Statüsü

İlk çıktı:

```text
EXPLORATION
```

olarak etiketlenmelidir.

İnsan onayı olmadan final SVG kabul etme.

Finale seçilen ikonlar için temiz SVG code önerisi üret ve dosya adlarını `nh-[concept].svg` biçiminde kullan.
