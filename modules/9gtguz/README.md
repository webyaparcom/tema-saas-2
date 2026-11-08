# Slider Ken Burns — `9gtguz` (tema-saas-2)

## Amaç
Sıfır bağımlılıklı tam genişlik slider (Swiper yok): görsel yavaş yakınlaşma/kayma (CSS keyframes 10 sn, reduced-motion'da kapalı), her slaytta eyebrow + h2 + metin + CTA ve metin giriş animasyonu; nokta + ok navigasyon, klavye ←/→, dokunma kaydırma, otomatik oynatma durdur/başlat düğmesi (hover/odakta duraklar, reduced-motion'da kapalı). data[] = [{img, alt{}, eyebrow{}, title{}, text{}, cta{}, url}]. desing.stil: tam | kart (içerik yarı saydam kartta) | bolunmus (görsel bitiş tarafında, metin düz zeminde). Yükseklik desing.yukseklik (vh, min 420px). Üç dil + RTL.

## Meta
- version: `1.0.0`
- category: `slider`
- tags: slider, kenburns, ken-burns, karusel, hero, sifir-bagimlilik, ar
- icon: `slideshow`

## Dosyalar
- `back.js` — sunucu tarafı çizim
- `index.html` — şablon
- `index.jpeg` — önizleme görseli
- `index.json` — tanım
- `README.md` — bu belge

## Not
Bu klasör siteye özel kurulum örneğidir; kurulum kaynağı `projeler/webyapar/data/tema/tema-set/icerik/saas-2/spec.js` → `tema-set/araclar/demo-kur.js` (webmaker uçları). Burası elle değiştirilmez; değişiklik spec'te yapılıp yeniden kurulur.
