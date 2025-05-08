# 🛍️ Toko Online WP

![Laravel](https://img.shields.io/badge/Framework-Laravel-red)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

**Toko Online WP** adalah sebuah aplikasi web toko online sederhana yang dibangun menggunakan Laravel. Proyek ini cocok untuk belajar dan memahami konsep dasar e-commerce, termasuk pengelolaan produk, kategori, keranjang, dan transaksi.

---

## 🚀 Fitur Utama

✨ Antarmuka pengguna yang responsif
🛒 Sistem keranjang belanja
📦 Manajemen produk & kategori
🧾 Riwayat transaksi
🔐 Otentikasi pengguna
💾 Integrasi database MySQL

---

## 🧰 Teknologi yang Digunakan

* [Laravel](https://laravel.com/)
* [MySQL](https://www.mysql.com/)
* [Blade Template](https://laravel.com/docs/10.x/blade)
* [Tailwind CSS](https://tailwindcss.com/)

---

## 📦 Instalasi

Ikuti langkah-langkah berikut untuk menjalankan proyek ini secara lokal:

```bash
1. Clone repositori ini
git clone https://github.com/riosaputraduha/toko-online-wp.git
cd toko-online-wp

2. Install dependensi
composer install

3. Copy file .env
cp .env.example .env

4. Atur konfigurasi database di file .env

5. Generate application key
php artisan key:generate

6. Import database
Buka phpMyAdmin atau gunakan MySQL CLI untuk mengimpor file:
database/db_tokoonline_wp.sql

7. Jalankan server lokal
php artisan serve
```

---

## 🗂️ Struktur Direktori

```
├── app/
├── database/
├── public/
├── resources/
│   └── views/
├── routes/
│   └── web.php
├── .env.example
└── composer.json
```

---

## 👨‍💻 Kontribusi

Kontribusi sangat terbuka!
Silakan **fork**, buat branch baru, dan kirimkan **pull request**.

---

## 📄 Lisensi

Proyek ini berada di bawah lisensi **MIT**. Silakan baca [LICENSE](LICENSE) untuk informasi lebih lanjut.

---
