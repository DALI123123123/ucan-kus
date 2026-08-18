# Uçan Kuş 🐦

Tarayıcıda çalışan, tek dosyalık Flappy Bird benzeri bir oyun. Kurulum yok, bağımlılık yok,
internet gerekmiyor — sadece `index.html`.

**▶️ Oyna: https://dali123123123.github.io/ucan-kus/**

## Günlük meydan okuma

Her gün herkese **aynı borular** çıkar. Boru dizilimi o günün tarihinden türeyen bir tohumla
üretilir ve zorluk oyuncunun skoruna değil boru sırasına bağlıdır — yani iki kişi aynı gün
oynadığında birebir aynı diziyi görür. Skorunu paylaş, arkadaşın tam olarak senin borularını
denesin.

Sonsuz mod da var: orada her koşu rastgeledir.

## Kontroller

| Tuş | Ne yapar |
|---|---|
| `Boşluk` / `↑` / `W` / dokunma / tıklama | Kanat çırp |
| `R` | Yeniden başla |
| `M` | Sesi kapat / aç |

## Özellikler

- **Kıl payı & kombo** — boruyu sıyırarak geçmek `1 + 2×kombo` puan, kısa bir yavaşlatma efekti
  ve ekran yazısı verir; arka arkaya sıyırdıkça çarpan büyür
- **Hayalet yarış** — rekor koşunun yarı saydam kopyası aynı anda uçar, onu geçmeye çalışırsın
- **Kilit açılan karakterler** — Sarı (0), Ateş (10), Gök (20), Papağan (30), Gece (45), Altın (60)
- **Paylaşılabilir skor kartı** — oyun sonunda 640×640 PNG kart üretilir; Web Share API varsa
  görselle paylaşılır, yoksa metin panoya kopyalanır ve kart ekranda gösterilir
- **Günlük seri** — üst üste kaç gün günlük meydan okumayı oynadığın sayılır
- **Madalyalar** — 5 / 12 / 25 / 40 skorda bronz, gümüş, altın, platin
- **Sabit 60 Hz fizik adımı** — ekran tazeleme hızı 144 Hz olsa da oyun hep aynı hızda akar
- **Artan zorluk** — boru arası boşluk 178 px'den 132 px'e daralır, hız 2.6'dan 4.4'e çıkar
- **Ses** — Web Audio ile anlık üretilir, harici ses dosyası yok
- **Efektler** — çarpışmada ekran sarsıntısı, beyaz flaş, tüy parçacıkları ve düşüş animasyonu

Rekorlar, açılan karakterler, hayalet kaydı ve seri `localStorage` içinde tutulur.
Tamamı HTML5 Canvas + saf JavaScript; hiçbir kütüphane kullanılmıyor.

## Yerelde çalıştırma

`index.html` dosyasını indirip herhangi bir tarayıcıda aç. Hepsi bu.

## Kardeş projeler

- Su altı versiyonu: [kirmizi-balik](https://github.com/DALI123123123/kirmizi-balik)
- Aynı oyunun native Android sürümü (Kotlin + Jetpack Compose) da var; günlük meydan okumada
  tarayıcı sürümüyle **birebir aynı** boruları üretir.
