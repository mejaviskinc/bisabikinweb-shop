# BisaBikinWeb — SHOP

Repo khusus GitHub Pages untuk `shop.bisabikinweb.site` (Merchandise, katalog, akun pembeli, serta checkout).

Source aplikasi: https://github.com/mejaviskinc/bisabikinweb

Workflow deploy di `.github/workflows/deploy-pages.yml` akan checkout source utama dan membuat `pages-shop`. Jangan mengedit file build manual, karena perubahan sebaiknya dilakukan pada repo utama.

Untuk aktivasi: Settings → Pages → Source = GitHub Actions; Custom domain = `shop.bisabikinweb.site`.

DNS: `CNAME shop → mejaviskinc.github.io` (hanya record host tersebut, jangan mengganti record domain utama atau email).

SEO masih noindex selama perpindahan; canonical di domain utama tidak berubah sampai migrasi URL disetujui. Login/customer dan checkout perlu pengujian CORS Supabase, Midtrans, dan callback sebelum produksi.
