# Sinkronisasi SEO BisaBikinWeb

Source SEO: https://github.com/mejaviskinc/bisabikinweb/tree/main

Referensi perubahan SEO: commit `188daa5bd0011c1732ae6a37ea627b1805f1b55a`.

Menampilkan katalog dan checkout untuk pengujian, tetapi tetap noindex selama integrasi pembayaran dan migrasi URL belum diselesaikan.

Build/redeploy otomatis menggunakan `.github/workflows/deploy-pages.yml` dan mengambil source `main` pada saat workflow dijalankan. Panduan arsitektur: https://github.com/mejaviskinc/bisabikinweb/blob/main/SEO-ARCHITECTURE.md

Pembaruan foto produk: unggah foto melalui admin Merch dan sinkronisasi foto di halaman detail saat katalog dimuat. Source commit: `47ad0fc4b65e6782ac83603c23735ac7637f99d2`.
