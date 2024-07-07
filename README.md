# Aplikasi Manajemen Pemesanan Mobil

Ini adalah aplikasi manajemen pemesanan  rental mobil yang dibangun menggunakan Laravel 11. Aplikasi ini memungkinkan pengguna untuk melihat, menambah, mengedit, dan menghapus pemesanan rental mobil.

## Persyaratan Sistem

- PHP >= 8.0
- Composer
- MySQL
- Web server seperti Apache atau Nginx

## Instalasi

## import database yang di file rental_mobil.sql


### 1. Clone Repository

Clone repository ini ke komputer Anda.

```bash
git clone https://github.com/username/repository-name.git

cd Rental_Mobil_Syariah

composer install

cp .env.example .env

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=rental_mobil
DB_USERNAME=root
DB_PASSWORD=

php artisan key:generate

php artisan migrate

php artisan serve
