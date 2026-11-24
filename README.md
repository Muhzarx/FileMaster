# FileMaster Mobile

**FileMaster Mobile** adalah toolkit pengelolaan file berbasis web dengan tampilan mobile-first. Dirancang agar nyaman digunakan melalui browser Android maupun desktop.

## Live Demo

https://muhzarx.github.io/FileMaster/

> Jika halaman belum terbuka, aktifkan GitHub Pages melalui **Settings → Pages → Deploy from a branch → `main` → `/ (root)`**.

## Fitur

- Memilih beberapa file dari perangkat dan melihat daftar file dalam sesi.
- Mencari dan menghapus file dari daftar.
- Kompres gambar menggunakan Canvas.
- Konversi gambar ke JPG, PNG, atau WebP.
- Membuat ZIP dari file yang dipilih dan mengekstrak file ZIP.
- Alat teks: penghitung karakter, kata, baris, uppercase, lowercase, rapikan spasi, dan salin teks.
- Informasi ukuran, tipe, dan tanggal file.
- Tema gelap dan terang.
- PWA: dapat dipasang ke layar utama Android.
- Pemrosesan file dilakukan di browser/perangkat pengguna.

## Cara menjalankan

Jalankan melalui localhost atau unggah seluruh isi repository ke GitHub Pages. Service worker dan instalasi PWA membutuhkan HTTPS atau localhost.

## Instalasi Android

1. Buka Live Demo melalui Chrome Android.
2. Buka menu titik tiga.
3. Pilih **Install app** atau **Tambahkan ke layar utama**.

## Privasi dan batasan

FileMaster tidak mengunggah file ke server. Pengguna memilih file secara manual melalui file picker browser. Browser tidak memberikan akses bebas ke seluruh penyimpanan Android, sehingga aplikasi ini bukan pengganti file manager native. Fitur ZIP memakai JSZip dari CDN dan memerlukan koneksi internet ketika library belum tersimpan di cache.

## Teknologi

HTML, CSS, JavaScript, Canvas API, Service Worker, Web App Manifest, dan JSZip.

## Hak Cipta

© 2026 Muhammad Hafizd Anshari  
All Rights Reserved.  
Designed & Developed by Muhammad Hafizd Anshari.

Seluruh hak cipta atas desain, identitas, dan kode orisinal proyek ini dimiliki oleh **Muhammad Hafizd Anshari**, kecuali komponen pihak ketiga yang tunduk pada lisensinya masing-masing.
