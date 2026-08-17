# Cemil Gündüz — Academic Website

Bu, Cemil Gündüz'ün akademik kişisel web sitesidir. GitHub Pages üzerinde statik olarak barındırılır.

## Klasör Yapısı

- `index.html` — Ana sayfa
- `research/`, `publications/`, `books/`, `projects/`, `international-experience/`, `collaboration/`, `cv/`, `contact/` — Alt sayfalar
- `assets/css/style.css` — Tüm sayfalarda kullanılan ortak stil dosyası
- `data/*.yaml` — Yayın, kitap, proje ve araştırma teması verileri (sitenin "tek doğruluk kaynağı")
- `sitemap.xml`, `robots.txt` — SEO dosyaları

## Yeni İçerik Ekleme

Yeni bir yayın, kitap veya proje eklemek için ilgili `.yaml` dosyasına bir kayıt eklenir ve karşılık gelen HTML sayfası (bkz. Claude ile yapılan geliştirme süreci) yeniden üretilir. Bu işlem normalde Claude ile sohbet üzerinden yapılır.
