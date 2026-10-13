# Undangan Baptisan Kudus — Jesslyn Imanuella Faith Lintong

Website undangan digital memiliki 2 mode:

- `index.html` — **Tamu** (tanpa tombol edit, hanya melihat dan mengonfirmasi lewat WhatsApp).
- `editor.html` — **Editor** (edit isi undangan, foto, lokasi, galeri, dan publikasi perubahan).
- `data.json` — Data publik bersama yang dibaca kedua mode.

## Mengaktifkan situs GitHub Pages

Karena GitHub Pages adalah pengaturan repositori, pemilik repo perlu mengaktifkannya **satu kali**:

1. Masuk ke GitHub repo: https://github.com/jeforoh03-cell/undjesselyn
2. Buka **Settings > Pages**.
3. Pada **Build and deployment**, set **Source** menjadi **Deploy from a branch**.
4. Pilih **Branch: main** dan **Folder: /(root)**, lalu **Save**.
5. Setelah GitHub selesai memublikasikan situs:
   - **Tamu:** https://jeforoh03-cell.github.io/undjesselyn/
   - **Editor:** https://jeforoh03-cell.github.io/undjesselyn/editor.html

## Memakai mode editor

1. Buka halaman `editor.html`, lalu klik **✎ Edit Undangan**.
2. Perbarui nama, tanggal, lokasi, foto, galeri, atau bagian lainnya.
3. Buat [fine-grained Personal Access Token](https://github.com/settings/personal-access-tokens/new) di GitHub dengan akses **Contents: Read and write** hanya untuk repository `jeforoh03-cell/undjesselyn`.
4. Tempel token pada panel. Klik **Publikasikan ke GitHub**. Halaman akan mengupdate `data.json`.
5. Buka / refresh halaman tamu untuk melihat hasil terbaru. GitHub Pages mungkin perlu sedikit waktu memuat perubahan.

**Keamanan:** Halaman editor sendiri dapat dikunjungi melalui URL, tetapi menyimpan perubahan membutuhkan akses GitHub. Jangan taruh token dalam HTML, jangan membagikannya, dan jangan simpan token pada browser milik orang lain. Jika lupa token, buat yang baru dari GitHub.

## Pengiriman undangan pribadi

Gunakan: `https://jeforoh03-cell.github.io/undjesselyn/?to=Keluarga%20Budi`

Ganti **nomor WhatsApp contoh** di panel Editor sebelum undangan dibagikan. Data RSVP lewat WhatsApp; pesan ucapan lokal tidak menjadi basis data yang tersinkron ke semua tamu.

## Pengunduhan cadangan

Dari mode Editor Anda tetap dapat mengunduh HTML lengkap dan HTML versi Tamu untuk arsip atau berbagi offline.
