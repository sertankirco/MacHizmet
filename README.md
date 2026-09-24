# MacHizmet

Apple Silicon (M1/M2/M3/M4) Mac'ler için Windows 11 ARM64 kurulum ve entegrasyon hizmetinin SEO odaklı, tek dosyalık landing page'i.

## İçerik

- `index.html` — Tüm sayfa (CSS + JS dahil, build adımı gerektirmez). SEO meta etiketleri, Open Graph/Twitter kartları ve `Service` + `FAQPage` JSON-LD şeması içerir.
- `robots.txt`, `sitemap.xml`, `site.webmanifest` — Arama motoru ve PWA meta dosyaları.

## Yayına Alma

Statik bir dosya seti olduğu için Vercel, Netlify, GitHub Pages veya herhangi bir statik hosting üzerinde doğrudan çalışır. Ek yapılandırma gerekmez.

## Yapılacaklar (Deploy Öncesi)

`index.html` içindeki aşağıdaki placeholder değerleri gerçek bilgilerinizle güncelleyin:

- `info@machizmet.com` → gerçek e-posta adresiniz
- `+90 500 000 00 00` / `wa.me/905000000000` → gerçek WhatsApp numaranız
- `https://machizmet.com` → gerçek domain adresiniz (canonical, Open Graph, sitemap, robots dahil)
- `og-image.jpg` → 1200x630 boyutunda paylaşım görseli ekleyin

## Yerel Önizleme

```bash
python3 -m http.server 8000
# http://localhost:8000
```
