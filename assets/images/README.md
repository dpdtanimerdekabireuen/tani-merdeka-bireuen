# Panduan foto kegiatan

Folder ini dipakai untuk foto pengurus dan galeri kegiatan.

## Cara menambahkan foto setelah website online

1. Unggah foto ke folder ini melalui GitHub.
2. Gunakan nama file tanpa spasi, misalnya `rapat-dpd-2026.webp`.
3. Pastikan ukuran foto idealnya di bawah 1–2 MB.
4. Buka `assets/js/data.js` dan isi array `gallery`:

```js
gallery:[
  {
    file:"rapat-dpd-2026.webp",
    title:"Rapat DPD TMI Bireuen",
    category:"Kegiatan DPD",
    date:"16 Oktober 2026",
    caption:"Rapat koordinasi pengurus DPD TMI Bireuen.",
    credit:"Dokumentasi TMI Bireuen",
    alt:"Pengurus DPD TMI Bireuen dalam rapat koordinasi"
  }
]
```

5. Simpan perubahan (`Commit changes`). GitHub Pages akan menerbitkan pembaruan otomatis.

Pastikan semua foto memiliki izin penggunaan dan sudah disetujui untuk dipublikasikan.
