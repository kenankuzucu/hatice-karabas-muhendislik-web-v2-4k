# Hatice Karabaş Mühendislik — Web Sitesi (v2 · 4K)

<div align="center">

**Mimari · Mühendislik · Konut Projeleri** — tek dosyalık, hızlı açılan tanıtım sitesi.

![durum](https://img.shields.io/badge/durum-yay%C4%B1nda-2ea043?style=for-the-badge)
![sürüm](https://img.shields.io/badge/s%C3%BCr%C3%BCm-v2%20%C2%B7%204K-c7a66a?style=for-the-badge)
![dosya](https://img.shields.io/badge/tek%20dosya-index.html-1f6feb?style=for-the-badge)
![lisans](https://img.shields.io/badge/t%C3%BCm%20haklar%C4%B1-sakl%C4%B1d%C4%B1r-b60205?style=for-the-badge)

</div>

---

## Nedir?

Hatice Karabaş Mühendislik için hazırlanmış **tek sayfalık (single-page) tanıtım sitesi**. Sunucu tarafı yok:
`index.html` + bir profil görseli. 4K ekranlarda net görünen yüksek çözünürlüklü arka planlar ve altın
(`#c7a66a`) vurgulu koyu tema kullanır.

## Sayfada ne var?

| Bölüm | İçerik |
|---|---|
| Kapak (hero) | “Geleceğin Yapılarını Bugünden Tasarlıyoruz.” + çağrı düğmeleri |
| Hakkımızda | “Mühendislikte Güven, Mimariyle Gelecek.” + istatistik kutuları + profil görseli |
| Projeler | Modern Apartman · Lüks Villa · Dubleks Konut kartları |
| Hizmetler | Mimari Proje Tasarımı · Mühendislik Hizmetleri · Konut Projeleri · Villa ve Dubleks · 3D Mimari Görselleştirme · Proje ve Yapı Danışmanlığı |
| Süreç | Fikir → Mimari → Mühendislik → 3D Modelleme → İnşaat → Teslim |
| İletişim | “Hayalinizdeki Yapıyı Birlikte Tasarlayalım.” |

## Dosyalar

| Dosya | Boyut | Açıklama |
|---|---|---|
| `index.html` | ~13 KB | Sitenin tamamı (HTML + CSS + JS gömülü) |
| `assets/hatice-karabas-profile.jpg` | ~67 KB | Hakkımızda bölümündeki profil görseli |
| `README.md` | — | Bu dosya |
| `.nojekyll` | — | GitHub Pages'in dosyaları olduğu gibi sunması için |

## Canlı adres

Site GitHub Pages üzerinde yayında:
`https://kenankuzucu.github.io/hatice-karabas-muhendislik-web-v2-4k/`

## Telefona kurmak (Ana ekrana ekle)

1. Canlı adresi telefonda tarayıcıyla aç.
2. iPhone: **Paylaş → Ana Ekrana Ekle** · Android: **⋮ → Ana ekrana ekle**.
3. Simge ana ekranda görünür, internet olmadan da açılır (sayfa tek dosya olduğu için önbellekten gelir).

## Teknik notlar

- Bağımlılık yok: çerçeve (framework) veya derleme adımı kullanılmaz, dosyayı çift tıklayınca da çalışır.
- Arka plan görselleri Unsplash CDN'inden gelir (internet gerekir); kalıcılık istenirse görseller
  `assets/` klasörüne indirilip yolları yerelleştirilmelidir.
- Tüm yollar göreli (`assets/...`) — site alt klasörde de sorunsuz açılır.
- Türkçe karakterler UTF-8 olarak tam desteklenir.

## Yeniden yayınlama

```bash
git clone https://github.com/kenankuzucu/hatice-karabas-muhendislik-web-v2-4k.git
# index.html üzerinde değişiklik yap, sonra:
git add -A && git commit -m "guncelleme" && git push
```

Pages yayını 1-2 dakika içinde kendini yeniler.

---

## Yasal uyarı

Bu depo ve içeriğindeki tüm metin, tasarım, kod ve görseller **Hatice Karabaş Mühendislik** projesine aittir.
**Tüm hakları saklıdır.** İzinsiz kopyalanamaz, çoğaltılamaz, başka bir projede kullanılamaz veya ticari
amaçla dağıtılamaz. Sitedeki bazı görseller üçüncü taraf (Unsplash) kaynaklıdır ve ilgili lisanslarına tabidir.

<div align="center">
<sub>Hazırlayan: <b>ÜSTAD KENAN KUZUCU</b></sub>
</div>
