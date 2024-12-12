# poliklinik

1. Download dan Instal XAMPP di Komputer
Download:
Kunjungi situs resmi XAMPP di https://www.apachefriends.org.
Pilih versi XAMPP sesuai sistem operasi Anda (Windows, Mac, atau Linux) dan download file instalasinya.
Instalasi:
Setelah file selesai diunduh, buka file instalasi.
Ikuti langkah-langkah instalasi hingga selesai. Biasanya, XAMPP akan diinstal di direktori C:\xampp (default untuk Windows).

2. Ekstrak File Menggunakan WinRAR
Klik kanan file tersebut.
Pilih Extract Here atau ekstrak file ke direktori tertentu menggunakan aplikasi WinRAR.

3. Copy Folder "poliklinik" ke Folder "htdocs"
Folder htdocs adalah tempat menyimpan file aplikasi web agar bisa diakses melalui server lokal.
Langkah-langkah:
Copy folder poliklinik yang telah diekstrak.
Paste ke direktori C:\xampp\htdocs.
Struktur direktori menjadi:
C:\xampp\htdocs\poliklinik

4. Aktifkan Apache dan MySQL di XAMPP
Buka XAMPP Control Panel (bisa diakses dari desktop atau menu Start).
Klik tombol Start pada modul Apache dan MySQL.
Jika berhasil, status akan berubah menjadi Running.
Apache berfungsi sebagai server web lokal, sedangkan MySQL digunakan sebagai database.

5. Buat Database Baru di phpMyAdmin
Akses phpMyAdmin:
Buka browser, lalu ketik alamat localhost/phpmyadmin dan tekan Enter.
phpMyAdmin akan terbuka. Ini adalah alat untuk mengelola database MySQL.
Buat Database Baru:
Klik tab Databases di phpMyAdmin.
Di kolom Create Database, ketik nama database poliklinik.
Klik tombol Create untuk membuat database baru.

6. Import Database ke "poliklinik"
Import File Database:
Pilih database poliklinik yang telah dibuat.
Klik tab Import di bagian atas.
Klik tombol Choose File dan pilih file database (biasanya berekstensi .sql) yang terdapat dalam folder aplikasi.
Klik Go untuk memulai proses import.
Jika berhasil, tabel-tabel database akan muncul di dalam database poliklinik.

7. Jalankan Aplikasi
Akses Aplikasi di Browser:
Buka browser dan ketik alamat localhost/poliklinik, lalu tekan Enter.
Halaman utama aplikasi akan muncul.


Login ke Aplikasi:

Login Admin
->Masuk ke "Login Sebagai Dokter"
    username : Admin
    password : admin

Login Dokter
username = password
contoh :
    username : Anita
    password : Anita

Login Pasien
    username : sesuai saat registrasi
    password : sesuai saat registrasi

Klik Login untuk masuk ke dalam aplikasi.
