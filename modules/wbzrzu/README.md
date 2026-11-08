# Menü 9 — Ortalı logo — `wbzrzu` (tema-saas-2)

## Amaç
Üstte ince bilgi bandı (telefon, e-posta, çalışma saati, sosyal, dil seçici — desing.bilgi_bandi ile açılır/kapanır), altında ortada logo; menü öğeleri logonun iki yanına bölünür (tek sayıda ise fazlası sağa). Mobilde hamburger + tam ekran panel. desing.sticky: kaydırınca küçülen sabit çubuk (300 ms). Ek bağlantılar data[] = [{name{tr,en,ar}, url}]. desing.stil: ince | cizgili | kutulu. Renkler yalnız desing anahtarı + var(--mx-site-*) — koyu mod otomatik. Üç dil + RTL.

## Meta
- version: `1.0.0`
- category: `menu`
- tags: menu, ortali-logo, centered, bilgi-bandi, sticky, ar
- icon: `align_horizontal_center`

## Dosyalar
- `back.js` — sunucu tarafı çizim
- `index.html` — şablon
- `index.jpeg` — önizleme görseli
- `index.json` — tanım
- `README.md` — bu belge

## Not
Bu klasör siteye özel kurulum örneğidir; kurulum kaynağı `projeler/webyapar/data/tema/tema-set/icerik/saas-2/spec.js` → `tema-set/araclar/demo-kur.js` (webmaker uçları). Burası elle değiştirilmez; değişiklik spec'te yapılıp yeniden kurulur.
