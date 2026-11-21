# Haftalık CSS Uygulamaları

Nov 21, 2026 · @Birnaz

Her hafta sitenin bir bölümüne yeni CSS özellikleri eklenir; üç grubun görevleri aynı konuyu kendi sitesi üzerinden işler.

## Hafta 1: Üst bölüm

Yeni özellikler: `text-align` yazıyı hizalar (left, center, right), `font-size` yazı boyutunu px ile belirler. Öğretmen önce gösterir, öğrenci kendi sitesinin üst bölümünü değiştirir.

Ad Soyad: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  Sınıf: \_\_\_\_\_\_  Grup: \_\_\_\_\_\_

### HTMLHaber

Üst bölümdeki yazıları ortala, ana başlığı 48px, h4 başlığı 18px yap.

```
<div style="background-color: darkorange; height: 120px; width: 100%; ________: center;">
    <h1 style="color: white; ________: 48px;">HTMLHaber</h1>
    <h4 style="color: white; font-size: ____px;">Web'in temel dilinden son haberler</h4>
</div>
```

**Zor:** Aynı bölümün yazılarını sağa yasla ve h1 başlığını 36px yap. Kodu kendin yaz.

### JSGündem

Üst bölümdeki yazıları sağa yasla, ana başlığı 40px, h5 başlığı 14px yap.

```
<div style="background-color: gold; height: 100px; width: 100%; ________: right;">
    <h1 style="color: black; ________: 40px;">JSGündem</h1>
    <h5 style="color: black; font-size: ____px;">JavaScript dünyasından günlük gelişmeler</h5>
</div>
```

**Zor:** Aynı bölümün yazılarını ortala ve h1 başlığını 56px yap. Kodu kendin yaz.

### BootstrapGazetesi

Üst bölümdeki yazıları ortala, ana başlığı 44px, h3 başlığı 22px yap.

```
<div style="background-color: purple; height: 130px; width: 100%; ________: center;">
    <h1 style="color: white; ________: 44px;">BootstrapGazetesi</h1>
    <h3 style="color: plum; font-size: ____px;">Hazır tasarımın en güncel haberleri</h3>
</div>
```

**Zor:** Aynı bölümün yazılarını sola yasla ve h1 başlığını 32px yap. Kodu kendin yaz.

## Hafta 2: Menü

Yeni özellikler: `padding` kutunun içinde kenarlardan boşluk bırakır, `text-decoration: none` bağlantıdaki alt çizgiyi kaldırır. Padding kutuyu büyütür: toplam yükseklik = height + üstteki padding + alttaki padding.

Ad Soyad: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  Sınıf: \_\_\_\_\_\_  Grup: \_\_\_\_\_\_

### HTMLHaber

Menü kutusuna 10px padding ver. Toplam yükseklik 40px kalsın, height kaç olmalı? Bağlantıların alt çizgisini kaldır.

```
<div style="background-color: black; height: ____px; width: 100%; ________: 10px;">
    <a href="#" style="color: white; ________________: none;">Ana Sayfa</a> |
    <a href="#" style="color: white; text-decoration: none;">Etiketler</a>
</div>
```

**Zor:** Menünün arka planını darkred, padding'ini 5px yap. Toplam yükseklik yine 40px kalsın. Kodu kendin yaz.

### JSGündem

Menü kutusuna 8px padding ver. Toplam yükseklik 35px kalsın, height kaç olmalı? Bağlantıların alt çizgisini kaldır.

```
<div style="background-color: darkgray; height: ____px; width: 100%; ________: 8px;">
    <a href="#" style="color: black; ________________: none;"><b>Ana Sayfa</b></a> -
    <a href="#" style="color: black; text-decoration: none;"><b>Dil Haberleri</b></a>
</div>
```

**Zor:** Menünün arka planını lightgray, padding'ini 5px yap. Toplam yükseklik yine 35px kalsın. Kodu kendin yaz.

### BootstrapGazetesi

Menü kutusuna 10px padding ver. Toplam yükseklik 40px kalsın, height kaç olmalı? Bağlantıların alt çizgisini kaldır.

```
<div style="background-color: indigo; height: ____px; width: 100%; ________: 10px;">
    <a href="#" style="color: white; ________________: none;">Gündem</a> &nbsp;
    <a href="#" style="color: white; text-decoration: none;">Sürümler</a>
</div>
```

**Zor:** Menünün arka planını darkviolet, padding'ini 4px yap. Toplam yükseklik yine 40px kalsın. Kodu kendin yaz.

## Hafta 3: Manşet haber

Yeni özellikler: `font-family` yazı tipini seçer (Arial, Verdana, Tahoma, Georgia), `line-height` satırlar arasını açar (1.5 gibi bir çarpan yazılır). Bir kutuya yazılan `font-family`, içindeki tüm yazılara geçer.

Ad Soyad: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  Sınıf: \_\_\_\_\_\_  Grup: \_\_\_\_\_\_

### HTMLHaber

Manşet kutusunun yazı tipini Arial, paragrafın satır aralığını 1.6 yap.

```
<div style="background-color: white; width: 700px; ________: Arial;">
    <h2 style="color: darkorange;">HTML Hâlâ Web'in Temeli</h2>
    <p style="________: 1.6;">HTML, <b>HyperText Markup Language</b> sözcüklerinin kısaltmasıdır.</p>
</div>
```

**Zor:** Kutunun yazı tipini Georgia yap. Paragrafın yazı boyutunu 18px, satır aralığını 2 yap. Kodu kendin yaz.

### JSGündem

Manşet kutusunun yazı tipini Verdana, paragrafın satır aralığını 1.8 yap.

```
<div style="background-color: darkslategray; width: 800px; ________: Verdana;">
    <h2 style="color: gold;">JavaScript 10 Günde Doğdu</h2>
    <p style="color: white; ________: 1.8;">JavaScript, <b>1995</b> yılında Brendan Eich tarafından geliştirildi.</p>
</div>
```

**Zor:** Kutunun yazı tipini Georgia yap. Paragrafın yazı boyutunu 16px, satır aralığını 2 yap. Kodu kendin yaz.

### BootstrapGazetesi

Manşet kutusunun yazı tipini Tahoma, paragrafın satır aralığını 1.5 yap.

```
<div style="background-color: white; width: 750px; ________: Tahoma;">
    <h2 style="color: purple;">Bootstrap 6 İlk Alfa Sürümüyle Geldi</h2>
    <p style="________: 1.5;">Bootstrap, 6. sürümünün ilk alfa sürümünü yayımladı.</p>
</div>
```

**Zor:** Kutunun yazı tipini Verdana yap. Tarih satırını (h5) 12px, paragrafın satır aralığını 2 yap. Kodu kendin yaz.

## Hafta 4: Liste kutuları

Yeni özellikler: `border` kenarlık çizer (kalınlık, çizgi türü, renk sırasıyla: `3px solid black`), `list-style-type` liste işaretini değiştirir (disc, circle, square, none; sıralı listede decimal, lower-alpha, upper-roman).

Ad Soyad: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  Sınıf: \_\_\_\_\_\_  Grup: \_\_\_\_\_\_

### HTMLHaber

İlk kutuya 3px düz siyah kenarlık ver, listeyi kare işaretli yap. İkinci listeyi Roma rakamlı (upper-roman) yap.

```
<div style="background-color: orange; width: 700px; ________: 3px solid black;">
    <ul style="list-style-type: ________;">
        <li>div: sayfayı bölümlere ayırır</li>
    </ul>
</div>
<div style="background-color: lightblue; width: 700px; border: 3px dashed darkblue;">
    <ol style="list-style-type: ________;">
        <li>Sayfa iskeleti</li>
    </ol>
</div>
```

**Zor:** İlk kutunun kenarlığını 5px çift çizgili (double) koyu kırmızı (darkred) yap, listeyi daire işaretli (circle) yap. Kodu kendin yaz.

### JSGündem

İlk kutuya 2px kesik çizgili (dashed) koyu mavi kenarlık ver, listeyi daire işaretli yap. İkinci listeyi küçük harfli (lower-alpha) yap.

```
<div style="background-color: white; width: 390px; height: 200px; ________: 2px dashed darkblue;">
    <ul style="list-style-type: ________;">
        <li>Hesaplama yapar</li>
    </ul>
</div>
<div style="background-color: lightyellow; width: 390px; height: 200px; border: 2px dotted darkred;">
    <ol style="list-style-type: ________;">
        <li>Değişkenler</li>
    </ol>
</div>
```

**Zor:** İkinci kutunun kenarlığını 6px çift çizgili (double) altın (gold) yap, listeyi küçük Roma rakamlı (lower-roman) yap. Kodu kendin yaz.

### BootstrapGazetesi

İlk kutuya 4px çift çizgili (double) çivit (indigo) kenarlık ver, listeyi kare işaretli yap. İkinci listeyi büyük harfli (upper-alpha) yap.

```
<div style="background-color: plum; width: 750px; ________: 4px double indigo;">
    <ul style="list-style-type: ________;">
        <li>Hazır düğme sunar</li>
    </ul>
</div>
<div style="background-color: lightcyan; width: 750px; border: 4px solid darkcyan;">
    <ol style="list-style-type: ________;">
        <li>HTML sayfasını hazırla</li>
    </ol>
</div>
```

**Zor:** İlk listenin işaretlerini tamamen kaldır (none), kutunun kenarlığını 1px düz (solid) siyah yap. Kodu kendin yaz.

## Hafta 5: Alt haber kutuları

Yeni özellikler: `margin` kutunun dışında boşluk bırakır (padding içeride, margin dışarıda), `border-radius` köşeleri yuvarlar. Margin ile kutular arası boşluk verilebildiği için aradaki `<br>` etiketleri silinir.

Ad Soyad: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  Sınıf: \_\_\_\_\_\_  Grup: \_\_\_\_\_\_

### HTMLHaber

İki kutunun köşelerini 15px yuvarla, dışlarına 10px boşluk ver. Aradaki `<br>` etiketini sil.

```
<div style="background-color: lightgreen; width: 330px; height: 150px; ________: 15px; ________: 10px;">
    <h4 style="color: darkgreen;">Etiketler Büyüyor mu?</h4>
</div>
<div style="background-color: pink; width: 330px; height: 150px; border-radius: 15px; margin: 10px;">
    <h4 style="color: darkred;">Öğrenciler Sayfa Yapıyor</h4>
</div>
```

**Zor:** Kutulara 10px padding ver. Toplam genişlik 330px, toplam yükseklik 150px kalsın. width ve height kaç olmalı? Kodu kendin yaz.

### JSGündem

Üç kutunun köşelerini 10px yuvarla, her kutunun altına 10px boşluk ver (`margin-bottom`). Aradaki `<br>` etiketlerini sil.

```
<div style="background-color: crimson; width: 800px; height: 80px; ________: 10px; ________: 10px;">
    <h4 style="color: white;">Her yıl yeni özellikler geliyor</h4>
</div>
<div style="background-color: teal; width: 800px; height: 80px; border-radius: 10px; margin-bottom: 10px;">
    <h4 style="color: white;">Tarayıcıda deneyin</h4>
</div>
```

**Zor:** Kutulara 10px padding ver. Toplam genişlik 800px, toplam yükseklik 80px kalsın. width ve height kaç olmalı? Kodu kendin yaz.

### BootstrapGazetesi

Üç kutunun köşelerini 20px yuvarla, dışlarına 12px boşluk ver. Aradaki `<br>` etiketlerini sil.

```
<div style="background-color: orange; width: 360px; height: 130px; ________: 20px; ________: 12px;">
    <h4 style="color: black;">5 mi, 6 mı?</h4>
</div>
<div style="background-color: seagreen; width: 360px; height: 130px; border-radius: 20px; margin: 12px;">
    <h4 style="color: white;">Eski Tarayıcılara Veda</h4>
</div>
```

**Zor:** Kutulara 15px padding ver. Toplam genişlik 360px, toplam yükseklik 130px kalsın. width ve height kaç olmalı? Kodu kendin yaz.

## Hafta 6: style bloğu, etiket seçici ve sınıf (class)

Yeni konu: tekrar eden stilleri her etiketin içine yazmak yerine `<style>` bloğunda toplamak. Etiket seçici bütün aynı etiketlere uygulanır (`body { ... }`). Sınıf seçici nokta ile başlar (`.kutu { ... }`) ve etikette `class="kutu"` yazılan yerlere uygulanır. Bir etikete birden fazla sınıf verilebilir: `class="kutu yesil"`.

Ad Soyad: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  Sınıf: \_\_\_\_\_\_  Grup: \_\_\_\_\_\_

### HTMLHaber

Sayfa arka planı için etiket seçici yaz. Ortak kutu stiline `haber-kutusu` adını ver ve ikinci kutuya da bu sınıfı yaz.

```
<head>
    <style>
        ________ {
            background-color: lightyellow;
        }
        .________ {
            width: 330px;
            height: 150px;
            border-radius: 15px;
            margin: 10px;
        }
        .yesil { background-color: lightgreen; }
        .pembe { background-color: pink; }
    </style>
</head>
<body>
    <div class="haber-kutusu yesil">Etiketler Büyüyor mu?</div>
    <div class="________ pembe">Öğrenciler Sayfa Yapıyor</div>
</body>
```

**Zor:** Menüdeki bağlantılar için `.menu-link` sınıfı yaz (yazı rengi beyaz, alt çizgi yok). Dört bağlantıya da bu sınıfı ver. Kodu kendin yaz.

### JSGündem

Sayfa arka planı için etiket seçici yaz. Ortak kutu stiline `kisa-haber` adını ver ve ikinci kutuya da bu sınıfı yaz.

```
<head>
    <style>
        ________ {
            background-color: black;
        }
        .________ {
            width: 800px;
            height: 80px;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .kirmizi { background-color: crimson; }
        .mavi { background-color: teal; }
    </style>
</head>
<body>
    <div class="kisa-haber kirmizi">Her yıl yeni özellikler geliyor</div>
    <div class="________ mavi">Tarayıcıda deneyin</div>
</body>
```

**Zor:** Bölüm başlıkları için `.baslik` sınıfı yaz (yazı rengi gold, yazı boyutu 28px). Sayfadaki h2 başlıklarına bu sınıfı ver. Kodu kendin yaz.

### BootstrapGazetesi

Sayfa arka planı için etiket seçici yaz. Ortak kutu stiline `okuma-kutusu` adını ver ve ikinci kutuya da bu sınıfı yaz.

```
<head>
    <style>
        ________ {
            background-color: lavender;
        }
        .________ {
            width: 360px;
            height: 130px;
            border-radius: 20px;
            margin: 12px;
        }
        .turuncu { background-color: orange; }
        .yesil { background-color: seagreen; }
    </style>
</head>
<body>
    <div class="okuma-kutusu turuncu">5 mi, 6 mı?</div>
    <div class="________ yesil">Eski Tarayıcılara Veda</div>
</body>
```

**Zor:** Kutulardaki başlıklar için `.baslik-beyaz` sınıfı yaz (yazı rengi beyaz). Üç kutudaki h4 başlıklarına bu sınıfı ver. Kodu kendin yaz.

## Öğretmen Cevap Anahtarı (öğrencilere dağıtmayın)

Boşluklar kodda göründüğü sırayla numaralandı. Zor sorularda farklı ama doğru yazımlar kabul edilebilir.

### Hafta 1: Üst bölüm

| Boşluk | HTMLHaber | JSGündem | BootstrapGazetesi |
| --- | --- | --- | --- |
| 1 | text-align | text-align | text-align |
| 2 | font-size | font-size | font-size |
| 3 | 18 | 14 | 22 |
| Zor | `text-align: right;` ve h1 `font-size: 36px;` | `text-align: center;` ve h1 `font-size: 56px;` | `text-align: left;` ve h1 `font-size: 32px;` |

### Hafta 2: Menü

| Boşluk | HTMLHaber | JSGündem | BootstrapGazetesi |
| --- | --- | --- | --- |
| 1 | 20 | 19 | 20 |
| 2 | padding | padding | padding |
| 3 | text-decoration | text-decoration | text-decoration |
| Zor | `background-color: darkred; padding: 5px; height: 30px;` | `background-color: lightgray; padding: 5px; height: 25px;` | `background-color: darkviolet; padding: 4px; height: 32px;` |

### Hafta 3: Manşet haber

| Boşluk | HTMLHaber | JSGündem | BootstrapGazetesi |
| --- | --- | --- | --- |
| 1 | font-family | font-family | font-family |
| 2 | line-height | line-height | line-height |
| Zor | kutuda `font-family: Georgia;`, p'de `font-size: 18px; line-height: 2;` | kutuda `font-family: Georgia;`, p'de `font-size: 16px; line-height: 2;` | kutuda `font-family: Verdana;`, h5'te `font-size: 12px;`, p'de `line-height: 2;` |

### Hafta 4: Liste kutuları

| Boşluk | HTMLHaber | JSGündem | BootstrapGazetesi |
| --- | --- | --- | --- |
| 1 | border | border | border |
| 2 | square | circle | square |
| 3 | upper-roman | lower-alpha | upper-alpha |
| Zor | `border: 5px double darkred;` ve ul'de `list-style-type: circle;` | ikinci kutuda `border: 6px double gold;` ve ol'de `list-style-type: lower-roman;` | ul'de `list-style-type: none;` ve kutuda `border: 1px solid black;` |

### Hafta 5: Alt haber kutuları

| Boşluk | HTMLHaber | JSGündem | BootstrapGazetesi |
| --- | --- | --- | --- |
| 1 | border-radius | border-radius | border-radius |
| 2 | margin | margin-bottom | margin |
| Zor | `padding: 10px; width: 310px; height: 130px;` | `padding: 10px; width: 780px; height: 60px;` | `padding: 15px; width: 330px; height: 100px;` |

Her grupta aradaki `<br>` etiketlerinin silinmesi de beklenir.

### Hafta 6: style bloğu, etiket seçici ve sınıf

| Boşluk | HTMLHaber | JSGündem | BootstrapGazetesi |
| --- | --- | --- | --- |
| 1 | body | body | body |
| 2 | haber-kutusu | kisa-haber | okuma-kutusu |
| 3 | haber-kutusu | kisa-haber | okuma-kutusu |
| Zor | `.menu-link { color: white; text-decoration: none; }` ve `<a href="#" class="menu-link">` | `.baslik { color: gold; font-size: 28px; }` ve `<h2 class="baslik">` | `.baslik-beyaz { color: white; }` ve `<h4 class="baslik-beyaz">` |
