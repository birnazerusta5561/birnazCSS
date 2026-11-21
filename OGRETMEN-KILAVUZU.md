# CSS Ders Paketi - Öğretmen Kılavuzu

Bu paket, HTML'yi bilen ama seviyesi karışık (çoğunluğu zayıf) meslek lisesi öğrencilerine CSS'i **bol uygulamayla** öğretmek için hazırlandı.

## 1. Pakette ne var?

```
css-ders-paketi/
├── OGRETMEN-KILAVUZU.md        <- bu dosya
├── haber-sitesi/               <- sizin gösteri sitesi (TeknoHaber)
│   ├── resimler/               <- robot.svg, islemci.svg, kilit.svg
│   ├── hafta-0-css-yok/        <- öğrencilerin başlangıç dosyası (sadece HTML)
│   ├── hafta-1-etiket-secici/  <- her klasör bir öncekinin üstüne yeni konu ekler
│   ├── hafta-2-yazi/
│   ├── hafta-3-class/
│   ├── hafta-4-kutu-modeli/
│   ├── hafta-5-resim-tablo/
│   ├── hafta-6-menu/
│   ├── hafta-7-form/
│   └── hafta-8-son-hali/       <- CSS ayrı style.css dosyasında
└── alistirma-sitesi/
    ├── index.html              <- oyunlaştırılmış alıştırma sitesi (Kod Macerası)
    └── robot.svg
```

## 2. Nasıl kullanılır?

**Haber sitesi (sizin ders anlatımınız için):**
- VS Code'da `css-ders-paketi` klasörünü açın. Her haftanın `index.html` dosyasını tarayıcıda açın (sağ tık, "Open with Live Server" ya da dosyaya çift tıklama).
- Öğrencilere **hafta-0** klasörünü verin. Onlar bu dosyaya `<style>` ekleyerek sizinle birlikte ilerler.
- Hafta sonunda sizin hafta-N klasörünüz "doğru çözüm" olarak elinizde hazır durur.
- Not: `class` özellikleri hafta-3'ten itibaren HTML'de hazır yazılıdır. İsterseniz hafta-3 dersinde bunları öğrencilere tek tek eklettirin (hafta-0'da class yok).

**Alıştırma sitesi (öğrenci uygulaması):**
- `alistirma-sitesi/index.html` dosyasına çift tıklayın, **Chrome veya Edge** ile açın. İnternet gerekmez.
- Öğrenci takma ad girer, soldan seviye seçer, kodu yazar, sağda canlı sonucu görür, **Kontrol Et**'e basar. Bütün maddeler yeşilse XP kazanır.
- İlerleme, o bilgisayarın tarayıcısında saklanır. Öğrenci başka bilgisayara geçerse sıfırdan başlar. **Karnım** düğmesi ekran görüntüsü almaya uygundur.
- Bütün klasörü USB ile ya da okul ağından öğrencilere dağıtabilirsiniz. `robot.svg` dosyası `index.html` ile aynı klasörde kalmalıdır.

## 3. 8 haftalık ders akışı

Her ders için önerilen süre dağılımı (40-45 dk):
- **10 dk** gösterim: önceki hafta klasörü ile yeni hafta klasörünü yan yana açın, "önce / sonra" farkını gösterin.
- **10 dk** birlikte yapma: aynı değişikliği sizinle öğrenciler hafta-0 dosyasında yapar.
- **20 dk** alıştırma sitesinde seviyeler.
- **5 dk** karne: kim hangi rozeti aldı.

| Hafta | Yeni konu | Haber sitesi | Alıştırma sitesi seviyeleri |
|---|---|---|---|
| 1 | `<style>` etiketi, etiket seçici, `color`, `background-color` | hafta-1 | Mavi Paragraflar, Ortala ve Boya, Sayfanın Arka Planı |
| 2 | `font-size`, `text-align`, `font-family` | hafta-2 | Büyük Yazı, Hata Avcısı 1 |
| 3 | `class` (nokta ile seçici) | hafta-3 | Sınıf Etiketi |
| 4 | `border`, `padding`, `margin`, `width` | hafta-4 | Kutu Modeli, Dış Boşluk ve Genişlik |
| 5 | Resim ve tablo güzelleştirme | hafta-5 | Yuvarlak Resim, Tablo Güzelleştir |
| 6 | Menü, bağlantı, `:hover` | hafta-6 | Fare Üstüne Gelince, Menü Yapımı |
| 7 | Form ve düğme tasarımı | hafta-7 | Düğme Tasarla, Hata Avcısı 2 |
| 8 | Hepsi bir arada, CSS'i ayrı dosyaya taşıma | hafta-8 | BOSS: Teknoloji Haber Kartı + kendi sayfaları |

**HTML dünyası** (8 seviye) bir tekrar/ısınma bölümüdür. İlk iki haftada derse başlarken 5-10 dakika HTML seviyelerinden birini yaptırabilirsiniz. Boss seviyesi (Haber Kartı) HTML bilgisini ölçer.

Bu hafta bir konuyu öğrencilerin çoğu anlamadıysa bir sonraki haftaya geçmeyin. Alıştırma sitesinde aynı seviyeyi tekrar çözdürmek (Baştan başla düğmesi) yeterlidir.

## 4. Seviye farkını yönetme (3 grup)

Alıştırma sitesindeki ⭐ işaretleri bunun içindir. Öğrencilere "grup" demeyin, "hangi yıldızda başlıyorsun?" deyin.

| Grup | Hedef | Ne yapsın? |
|---|---|---|
| **⭐ Temel** (çoğunluk) | Boşluk doldurarak CSS yazma alışkanlığı | Sadece ⭐ seviyeleri. İpucu almak serbest (XP yarıya düşer ama ceza gibi sunmayın). Sizinle birlikte hafta klasöründeki kodu yazsın. |
| **⭐⭐ Orta** | Kodu kendi yazması | ⭐⭐ seviyeleri. İpucunu en sona saklasın. |
| **⭐⭐⭐ Usta** (birkaç öğrenci) | Anlatımı beklemeden ilerleme, başkasına öğretme | ⭐⭐⭐ ve BOSS seviyeleri. Haftanın konusunu siz anlatmadan hafta klasöründeki sayfayı tek başına yapmayı denesin. Takılan arkadaşına yardım eden "mentor" olsun (ona rozet / not artısı verin). |

Sizin "etiket şunu yapar, öznitelikleri şunlardır" demenizin yettiği öğrenciler bu gruptadır. Onlara tek cümlelik bir yönerge verin: "Bu haftanın konusu şu, hafta-N klasöründeki sayfayı kendin yap, bitirince Boss'a geç."

## 5. Oyunlaştırma önerileri

Alıştırma sitesinde hazır olanlar: **XP, 6 rütbe, 6 rozet, ipucu sistemi, boss seviyeleri, konfeti, karne**.

Sınıfta ek olarak:
- **Takım XP'si:** 4-5 kişilik takımlar. Hafta sonunda karnelerdeki XP toplanır. Tahtaya takım tablosu çizin.
- **En çok gelişen ödülü:** "En çok XP" yerine "bu hafta en çok ilerleyen" öğrenciyi ödüllendirin. Yoksa zayıf öğrenciler yarıştan hemen kopar.
- **Hata Avcısı Günü:** Siz bilerek hatalı kod yazın, öğrenciler bulsun. Sitedeki iki "Hata Avcısı" seviyesi bu mantıkla çalışır.
- **Boss Günü:** 8. hafta, boss seviyesini bütün sınıf aynı anda açar.
- **Rozet töreni:** Her ders sonunda yeni rozeti kapan öğrencinin adını okuyun.

## 6. Sık yapılan hatalar (tahtaya yazın)

| Hata | Örnek | Doğrusu |
|---|---|---|
| `;` unutmak | `color: red` | `color: red;` |
| `:` yerine `=` | `color = red;` | `color: red;` |
| `{ }` açık kalması | `p { color: red;` | `p { color: red; }` |
| Birimi unutmak | `font-size: 20;` | `font-size: 20px;` |
| İngilizce yazım | `colour`, `centre` | `color`, `center` |
| Class'ta nokta | `spor { }` | `.spor { }` |
| Yanlış yer | `<style>` body içinde | `<head>` içinde |

## 7. Küçük notlar

- **Hile:** İlerleme tarayıcıda saklandığı için isteyen öğrenci F12 ile değiştirebilir. Bu bir oyun/motivasyon aracıdır, resmi not için kullanmayın.
- **Yeni seviye eklemek:** `alistirma-sitesi/index.html` içinde `LEVELS` listesine mevcut seviyelerin biçiminde bir kayıt ekleyin (başlık, görev, başlangıç kodu, ipucu, kontroller).
- **Rütbe eşikleri:** `RANKS` listesindedir. Toplam XP: 550.
- **Tarayıcı:** Chrome ve Edge ile denendi. Çok eski tarayıcılarda çalışmayabilir.
