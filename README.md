# Uçan Kuş 🐦

Tarayıcıda çalışan, tek dosyalık Flappy Bird benzeri bir oyun. Kurulum yok, bağımlılık yok,
internet gerekmiyor — sadece `index.html`.

**▶️ Oyna: https://dali123123123.github.io/ucan-kus/**

## Kontroller

| Tuş | Ne yapar |
|---|---|
| `Boşluk` / `↑` / `W` / fare tıklaması | Kanat çırp |
| `R` | Yeniden başla |
| `M` (veya sağ üstteki hoparlör) | Sesi kapat / aç |

## Özellikler

- **Sabit 60 Hz fizik adımı** — ekran tazeleme hızı 144 Hz olsa da oyun hep aynı hızda akar
- **Artan zorluk** — skor yükseldikçe boru arası boşluk 178 px'den 132 px'e daralır, hız 2.6'dan 4.4'e çıkar
- **Rekor kaydı** — `localStorage` ile tarayıcıda saklanır
- **Madalyalar** — 5 / 12 / 25 / 40 skorda bronz, gümüş, altın, platin
- **Ses** — Web Audio ile anlık üretilir, harici ses dosyası yok
- **Efektler** — çarpışmada ekran sarsıntısı, beyaz flaş, tüy parçacıkları ve düşüş animasyonu
- **Parallax arka plan** — bulutlar, tepeler ve zemin farklı hızlarda kayar

Tamamı HTML5 Canvas + saf JavaScript. Hiçbir kütüphane kullanılmıyor.

## Yerelde çalıştırma

`index.html` dosyasını indirip herhangi bir tarayıcıda aç. Hepsi bu.
