
# PAW-JURNAL3-PAULUS-102042500087

## CeLOE LMS (Learning Management System)

Project ini merupakan hasil pengerjaan Praktikum Pengembangan Aplikasi Website (PAW) Jurnal 3. Aplikasi CeLOE LMS dikembangkan menggunakan framework Laravel sebagai sistem pembelajaran berbasis web.

## Teknologi yang Digunakan

- PHP
- Laravel
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap

## Fitur Aplikasi

- Login dan autentikasi pengguna.
- Dashboard Dosen dan Mahasiswa.
- Pengelolaan mata kuliah.
- Pengelolaan materi pembelajaran.
- Pengelolaan tugas dan pengumpulan tugas.
- Pembagian hak akses berdasarkan peran pengguna.

## Cara Menjalankan Project

1. Clone repository:

   ```bash
   git clone https://github.com/paulus180/PAW-JURNAL3-PAULUS-102042500087.git
   ```

2. Masuk ke folder project:

   ```bash
   cd PAW-JURNAL3-PAULUS-102042500087
   ```

3. Install dependency:

   ```bash
   composer install
   ```

4. Salin file konfigurasi:

   ```bash
   copy .env.example .env
   ```

5. Generate application key:

   ```bash
   php artisan key:generate
   ```

6. Atur konfigurasi database MySQL pada file `.env`.

7. Jalankan migration dan seeder:

   ```bash
   php artisan migrate --seed
   ```

8. Jalankan server Laravel:

   ```bash
   php artisan serve
   ```

9. Buka aplikasi melalui browser:

   ```text
   http://127.0.0.1:8000
   ```

## Identitas

- Nama: Paulus Berutu
- NIM: 102042500087
- Mata Kuliah: Pengembangan Aplikasi Website
- Praktikum: Jurnal 3

