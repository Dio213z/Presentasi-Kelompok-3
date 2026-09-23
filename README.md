# Presentasi Kelompok 3
Website presentasi statis, HTML + CSS + JavaScript. Tidak membutuhkan npm, backend, atau API key. Semua gambar sudah disertakan; dapat dibuka langsung lewat index.html dan berjalan offline.

## Isi
Pembuka — Gilang Angga Putra (TIDAK MASUK) dan I Shava Yogi Flachintya.
1. Pembuatan WordPress, menggunakan foto kedua.
2. Kalkulator Flowgorithm dengan metode if / else, menggunakan foto ketiga.
3. Google Colab dan Python, menggunakan foto keempat.
Penutup dan sesi pertanyaan.

Foto pertama hanya digunakan untuk mengecek ejaan nama, bukan ditampilkan sebagai slide. Cuplikan Python di slide adalah contoh sederhana, bukan salinan penuh kode foto.

## GitHub → Vercel
1. Ekstrak ZIP ini.
2. Buat repository baru di akun GitHub Anda, misalnya `presentasi-kelompok-3`.
3. Unggah seluruh isi folder proyek ke root repository. Pastikan index.html berada di root, bukan di dalam ZIP atau folder tambahan. Pertahankan folder assets beserta tiga fotonya.
4. Di Vercel, tambahkan proyek dan impor repository tersebut.
5. Gunakan Framework Preset: Other. Root Directory: root repository. Build Command: kosong / override tanpa perintah. Output Directory: `.`. Tidak perlu Install Command atau environment variables.
6. Deploy. Perubahan berikutnya yang di-push ke repository akan memicu deployment sesuai pengaturan integrasi GitHub Anda.

Arsip ini berisi source siap unggah, bukan repository GitHub yang telah dibuat atau situs yang telah diterbitkan. GitHub dan Vercel memerlukan akun Anda.
Referensi: https://vercel.com/docs/deployments/configure-a-build

## Kontrol
- Tombol panah di bawah, titik navigasi, atau keyboard ← → / Page Up / Page Down.
- Home untuk pembuka; End untuk penutup.
- Geser horizontal pada HP; scroll vertikal untuk konten slide yang panjang.
- Klik foto untuk memperbesar. Esc atau × untuk menutup.
- Tombol layar penuh tersedia pada browser yang mendukung.
- Animasi mengikuti pengaturan reduced motion perangkat.

## Mengedit
index.html: teks, nama, urutan materi.
style.css: warna, layout, dan animasi.
script.js: navigasi, swipe, foto, dan fullscreen.
assets/: foto dokumentasi asli.
vercel.json: konfigurasi Vercel.
