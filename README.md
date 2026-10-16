# TMI Bireuen

Website statis DPD Tani Merdeka Indonesia Kabupaten Bireuen.

## Struktur

- `index.html`: halaman utama dan navigasi seluruh bagian.
- `assets/css/styles.css`: gaya responsif.
- `assets/js/data.js`: data berita, edukasi, pengurus, dan kecamatan.
- `assets/js/config.js`: konfigurasi endpoint formulir.
- `assets/js/app.js`: pencarian, filter, modal artikel, menu mobile, dan validasi formulir.
- `privacy.html`, `404.html`, `robots.txt`, `sitemap.xml`: kebutuhan dasar publikasi.
- `docs/google-form-aspirasi.md`: template pertanyaan Google Form aspirasi.

## Menjalankan lokal

Buka `index.html` langsung di browser. Untuk pengujian yang lebih mirip GitHub Pages, gunakan server statis sederhana seperti Live Server di VS Code.

## Mengubah konten

Edit `assets/js/data.js`. Jangan menghapus penanda “menunggu data resmi” sebelum nama, tanggal, foto, dan sumber sudah disetujui pengelola.

## Formulir aspirasi

GitHub Pages tidak menyimpan kiriman formulir. Buat Google Form, hubungkan ke Google Sheets, lalu integrasikan melalui endpoint yang sesuai dan isi `aspirationFormEndpoint` di `assets/js/config.js`. Jangan menaruh password, token, atau kunci rahasia di repository publik.

## Publikasi

Unggah isi folder ini ke branch `main` repository GitHub. Aktifkan Settings → Pages → Deploy from a branch → `main` / root. Karena repository memakai subdirektori, seluruh tautan menggunakan path relatif.
