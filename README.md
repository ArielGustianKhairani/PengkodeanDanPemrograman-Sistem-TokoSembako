# PengkodeanDanPemrograman-Sistem-TokoSembako
Source Code Aplikasi Penjualan Barang sederhana berbasis Website dengan PHP & MYSQL.

# Tugas Pengkodean dan Pemrograman
Nama : Ariel Gustian Khairani
NIM : 12030122120016
#Web Toko Clone dari (https://github.com/bagussatoto/Point-Of-Sale-Lara-8.git)

# SETTING KONEKSI PHP
setting koneksi di config.php dan ganti username, password

# PENGGUNAAN LOG IN
Username : admin@gmail.com
Password : 123

# PROGRAM ASLI

# PROGRAM YANG TELAH DIMODIFIKASI

1.	Halaman Log In Sistem Informasi Toko Sembako
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/3588ddc6-95cf-472c-80e4-d6db057f9c0b)

3.	Halaman Utama Sistem Informasi Toko Sembako
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/ed7c58c9-ab84-4252-a967-2cb34ac3921d)

5.	Halaman Form Kategori
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/9cab9908-56ef-4b98-a580-8e8d911a20a2)

7.	Halaman Form Produk
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/9258cafc-80dc-4ab7-98af-11b163eade51)

9.	Halaman Form Member
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/8de4e5b7-2d1d-47fc-b7b2-7126b7373390)

11.	Halaman Form Supplier
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/c136e35e-62d7-4ab2-8262-e832683ae1da)

13.	Halaman Form Pengeluaran
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/7215b4cf-c7a6-4f9f-a483-2c5ddf284476)

15.	Halaman Pembelian
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/33bbeaa4-73e5-46f9-afb8-fe3cea9149b4)

17.	Halaman Form Penjualan
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/1792865f-3048-4002-a037-bed9cc6022ee)

19.	Halaman Form Transaksi Aktif
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/920f348e-f9a6-484e-a657-18748917d509)

21.	Halaman Transaksi Baru
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/0990f08b-fac9-4427-bc54-00515aec57d6)

23.	Halaman Laporan
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/8cc88fc4-95be-41f9-b969-6b6ee6f0bda7)

25.	Halaman Data User
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/267da156-e090-4519-8526-39f6ba33dbb2)

27.	Halaman Profile
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/3e54565f-0d52-48bb-a206-531a0f81903d)

29.	Halaman Pengaturan
![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/d4f3c26a-a0c7-450e-b155-34c167273684)

# BENTUK ERD

![image](https://github.com/ArielGustianKhairani/PengkodeanDanPemrograman-Sistem-TokoSembako/assets/167192109/086aad83-8760-4c45-ad22-fa4fc338a08a)

<p align="center">
    <a href="https://github.com/sandinur157" target="_blank"><img src="https://raw.githubusercontent.com/sandinur157/tuturial-membuat-aplikasi-point-of-sales/main/public/img/logo.png" width="120"></a>
</p>

## Tentang Aplikasi

Aplikasi POS atau point of sales adalah aplikasi yang digunakan untuk mengelola transaksi pada sebuah toko atau oleh kasir. Aplikasi ini dibuat menggunakan Laravel v8.* dan minimal PHP v7.4 jadi apabila pada saat proses instalasi atau penggunaan terdapat error atau bug kemungkinan karena versi dari PHP yang tidak support.

## Beberapa Fitur yang tersedia:
- Manajemen Kategori Produk
- Manajemen Produk
  - Multiple Delete
  - Cetak Barcode
- Manajemen Member atau Anggota
  - Cetak Kartu Member
- Manajemen Supplier
- Transaksi Pengeluaran
- Transaksi Pembelian
- Transaksi Penjualan
- Laporan Pendapatan atau Laba & Rugi
  - Bulanan
  - Harian
  - Custom Tanggal
- Custom Tipe Nota
  - Nota Besar
  - Nota Kecil / Thermal Nota
- Manajemen User dan Profil
- Pengaturan Toko
  - Identitas
  - Upload Desain Kartu Member
  - Setting Diskon Member
- User (Administrator, Kasir)
- Grafik ChartJS pada Dashboard


## Setup Aplikasi
Jalankan perintah 
```bash
composer update
```
atau:
```bash
composer install
```
Copy file .env dari .env.example
```bash
cp .env.example .env
```
Konfigurasi file .env
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example_app
DB_USERNAME=root
DB_PASSWORD=
```
Opsional
```bash
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:QGRW4K7UVzS2M5HE2ZCLlUuiCtOIzRSfb38iWApkphE=
APP_DEBUG=true
APP_URL=http://example-app.test
```
Generate key
```bash
php artisan key:generate
```
Migrate database
```bash
php artisan migrate
```
Seeder table User, Pengaturan
```bash
php artisan db:seed
```
Menjalankan aplikasi
```bash
php artisan serve
```

## License

[MIT license](https://opensource.org/licenses/MIT)
