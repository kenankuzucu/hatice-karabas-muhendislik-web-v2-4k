# Hatice Karabaş Mühendislik — Web Sitesi (V7 · Kurumsal Studio)

<div align="center">

**Mimari · Mühendislik · Konut · Ticari Yapı** — tek dosyalık profesyonel kurumsal tanıtım sitesi.

![durum](https://img.shields.io/badge/durum-yay%C4%B1nda-2ea043?style=for-the-badge)
![sürüm](https://img.shields.io/badge/s%C3%BCr%C3%BCm-V7%20%C2%B7%20Kurumsal%20Studio-c7a66a?style=for-the-badge)
![dosya](https://img.shields.io/badge/tek%20dosya-index.html-1f6feb?style=for-the-badge)
![lisans](https://img.shields.io/badge/t%C3%BCm%20haklar%C4%B1-sakl%C4%B1d%C4%B1r-b60205?style=for-the-badge)

**[Canlı site →](https://kenankuzucu.github.io/hatice-karabas-muhendislik-web-v2-4k/)**

</div>

---

## Nedir?

Hatice Karabaş Mühendislik için hazırlanmış **tek sayfalık (single-page) kurumsal tanıtım sitesi**. Sunucu tarafı
yok, veritabanı yok, kurulum yok: `index.html` + bir profil görseli. Koyu tema + altın (`#c7a66a`) vurgu,
yüksek çözünürlüklü mimari görseller, 3B derinlik efektleri, proje önizleme penceresi (modal), görsel galeri +
tam ekran büyütme (lightbox) ve interaktif mimari stüdyo içerir.

## Sayfada ne var?

| Bölüm | İçerik |
|---|---|
| Kapak (hero) | “Geleceğin Yapılarını Bugünden Tasarlıyoruz.” + çağrı düğmeleri |
| Hakkımızda | “Mühendislikte Güven, Mimariyle Gelecek.” + HATİCE KARABAŞ tanıtımı + istatistikler + profil görseli |
| Proje Galerisi (kart) | “Projeleri Keşfedin.” → Modern Yaşam Rezidansı · Prestij Villa · Çağdaş Dubleks · Cephe Tasarım Serisi · Yapısal Çözüm Projesi · Modern İş Merkezi · Yaşam Kompleksi · 3D Mimari Sunum (tıklayınca önizleme penceresi açılır) |
| Hizmetler | “Tek Çatı Altında Proje Çözümleri.” → Mimari Projeler · Mühendislik · Konut · Villa & Dubleks · Ticari Yapılar · Kentsel Projeler · 3D & Animasyon · Danışmanlık |
| Süreç | Fikir → Mimari → Mühendislik → 3D Modelleme → İnşaat → Teslim |
| **Görsel Galeri** | “Mimariyi detaylarıyla görün.” → 4 kare (Dış cephe · İç mekân · Villa · Detay) + tam ekran lightbox (ok tuşlarıyla gezinme) |
| İnteraktif Mimari Stüdyo | “Projeyi ekranda keşfedin.” → döndürülebilir 3B kütle, cephe/kat/proje bilgileri |
| Süreç şeridi | Keşif & ihtiyaç analizi · Konsept & mimari tasarım · Teknik proje & mühendislik · Sunum & proje takibi |
| İletişim | “Hayalinizdeki Yapıyı Birlikte Tasarlayalım.” + proje talep formu |

## Dosyalar

| Dosya | Boyut | Açıklama |
|---|---|---|
| `index.html` | 41.047 bayt | Sitenin tamamı (HTML + CSS + JS gömülü) |
| `assets/hatice-karabas-profile.jpg` | 68.138 bayt | Hakkımızda bölümündeki profil görseli |
| `README.md` | — | Bu dosya |
| `.nojekyll` | — | GitHub Pages'in dosyaları olduğu gibi sunması için |

## Sürüm geçmişi

| Sürüm | Tarih | Not |
|---|---|---|
| **V7 · Kurumsal Studio** | 24.09.2026 | **Yayındaki sürüm.** Görsel galeri + lightbox, interaktif mimari stüdyo, süreç şeridi |
| V6 · 3D Profesyonel | 24.09.2026 | Proje kartları + 8 hizmet başlığı + modal önizleme |
| V4 · Tam Proje Platformu | 24.09.2026 | Bölüm sayısı artırılmış platform sürümü |
| V3 · Cinematic | 24.09.2026 | Sinematik kapak düzeni |
| v2 · 4K | 24.09.2026 | İlk yayınlanan sürüm |

Tüm eski sürümler depo geçmişinde durur: `git log --oneline`.

## Canlı adres

Site GitHub Pages üzerinde yayında:
`https://kenankuzucu.github.io/hatice-karabas-muhendislik-web-v2-4k/`

> Depo adının sonunda hâlâ `v2-4k` yazıyor; adres paylaşıldığı için linki bozmamak adına değiştirilmedi.

## Telefona kurmak (Ana ekrana ekle)

1. Canlı adresi telefonda tarayıcıyla aç.
2. iPhone: **Paylaş → Ana Ekrana Ekle** · Android: **⋮ → Ana ekrana ekle**.
3. Simge ana ekranda görünür; sayfa tek dosya olduğu için önbellekten hızlı açılır.

## Teknik notlar

- Bağımlılık yok: çerçeve (framework) veya derleme adımı kullanılmaz; dosyayı çift tıklayınca da çalışır.
- Mimari görseller Unsplash CDN'inden gelir (internet gerekir); tamamen çevrimdışı istenirse görseller
  `assets/` klasörüne indirilip yolları yerelleştirilmelidir.
- Tüm yollar göreli (`assets/...`) — site alt klasörde de sorunsuz açılır.
- Türkçe karakterler UTF-8 olarak tam desteklenir.

## Güncelleme

```bash
git clone https://github.com/kenankuzucu/hatice-karabas-muhendislik-web-v2-4k.git
# index.html üzerinde değişiklik yap, sonra:
git add -A && git commit -m "guncelleme" && git push
```

GitHub Pages yayını 1-2 dakika içinde kendini yeniler.

---

## Yasal uyarı

Bu depo ve içeriğindeki tüm metin, tasarım, kod ve görseller **Hatice Karabaş Mühendislik** projesine aittir.
**Tüm hakları saklıdır.** İzinsiz kopyalanamaz, çoğaltılamaz, başka bir projede kullanılamaz veya ticari
amaçla dağıtılamaz. Sitedeki bazı görseller üçüncü taraf (Unsplash) kaynaklıdır ve ilgili lisanslarına tabidir.

<div align="center">
<sub>Hazırlayan: <b>ÜSTAD KENAN KUZUCU</b></sub>
</div>
