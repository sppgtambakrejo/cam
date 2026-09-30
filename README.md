# Kamera Timestamp (PWA)

Kamera web dengan stempel waktu, lokasi, kecerahan, dan watermark logo. Bisa dipasang seperti aplikasi dan jalan offline.

## Deploy ke GitHub Pages
1. Buat repo baru di GitHub, lalu unggah semua isi folder ini (index.html, sw.js, manifest.webmanifest, folder icons).
2. Buka **Settings → Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu Save.
3. Tunggu 1–2 menit. Alamatnya: `https://USERNAME.github.io/NAMA-REPO/`

## Pasang sebagai aplikasi
- Android (Chrome): menu ⋮ → **Instal aplikasi** / **Tambahkan ke layar utama**.
- iPhone (Safari): tombol Bagikan → **Tambah ke Layar Utama**.

## Catatan
- Kamera butuh HTTPS. GitHub Pages sudah HTTPS.
- Setelah mengubah file, naikkan `CACHE` di `sw.js` (mis. `kamera-ts-v2`) agar pembaruan sampai ke pengguna.
