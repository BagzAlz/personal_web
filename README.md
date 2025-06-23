# Personal Web
**Deskripsi**

Studi kasus ini bertujuan untuk membangun sebuah aplikasi web personal yang bersifat dinamis, di mana pemilik web dapat mengelola konten secara mandiri melalui halaman admin. Aplikasi dikembangkan menggunakan PHP dan menyimpan data menggunakan database MySQL. Tampilan antarmuka dirancang menggunakan Tailwind CSS agar responsif, modern, dan mudah dikustomisasi. 

Website ini memiliki dua bagian utama: 
1. Halaman Publik, yang dapat diakses oleh semua pengunjung.
2. Halaman Admin, yang hanya dapat diakses setelah login, digunakan untuk
mengelola konten.

**Fitur-fitur**

A. Login & Logout

• Halaman login admin dengan validasi.

• Sistem sesi untuk melindungi halaman admin.

• Logout untuk mengakhiri sesi dengan aman.

B. Manajemen Artikel 

• Tambah artikel (judul + isi). 

• Edit artikel yang sudah ada. 

• Hapus artikel. 

• Tampilkan daftar artikel di halaman utama. 

• Sidebar "Daftar Artikel" yang terupdate otomatis.

C. Manajemen Gallery 

• Upload gambar beserta judul. 

• Ganti gambar dan judul yang sudah ada. 

• Hapus gambar. 

• Tampilkan gambar di halaman galeri publik dalam grid responsif.

D. Manajemen About (Tentang Saya) 

• Tambah deskripsi tentang diri. 

• Edit dan hapus bagian “About”. 

• Tampilkan deskripsi di halaman publik about.php.

E. Dashboard Statistik Admin 

• Menampilkan ringkasan jumlah: 

  o Artikel 

  o Gambar di gallery 
 
F. Halaman Publik yang Rapi & Dinamis 

• Artikel terbaru ditampilkan otomatis. 

• Galeri responsif dan ringan. 

• Tentang Saya tampil dengan struktur informatif. 

**Teknologi yang Digunakan**

• Bahasa Pemrograman : PHP

• Database : MySQL

• Frontend : Tailwind CSS, HTML

• Server Side : Apache / XAMPP

**Struktur Folder**

personal_web/

├── index.php

├── gallery.php
├── about.php
├── koneksi.php
├── admin/
│   ├── login.php
│   ├── cek_login.php
│   ├── logout.php
│   ├── about.php
│   ├── add_about.php
│   ├── add_artikel.php
│   ├── add_gallery.php
│   ├── beranda_admin.php
│   ├── data_artikel.php
│   ├── data_gallery.php
│   ├── delete_about.php
│   ├── delete_artikel.php
│   ├── delete_gallery.php
│   ├── edit_artikel.php
│   ├── edit_gallery.php
│   ├── edit_about.php
│   ├── proses_add_about.php
│   ├── proses_add_artikel.php
│   ├── proses_add_gallery.php
│   ├── proses_edit_about.php
│   ├── proses_edit_artikel.php
│   ├── proses_edit_gallery.php
├── images/
├── tailwind.config.js (opsional)


