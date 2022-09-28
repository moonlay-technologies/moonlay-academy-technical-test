
## Moonlay Academy - Senior Frontend Technical Test

Selamat datang di **Moonlay Academy - Senior Frontend Technical Test.**
Berikut adalah langkah - langkah tugas yang harus diikuti dan dikerjakan untuk menyelesaikan Technical Test **Senior Frontend Developer Moonlay Technologies**
##### Sebelum Memulai
- siapkan 1 public repo di github
- gunakan repo tersebut untuk men-submit hasil task yang Anda kerjakan nanti
------------
#### 1. UI Implementation
Pada tahap ini Anda diharapkan mampu menerapkan ui React JS
##### Tugas
- Buatlah sebuah aplikasi `Warehouse Management System` yang didalamnya terdapat modul
    - Login
    - Master Barang
    - Master Gudang
    - Master User
    - Pencatatan Keluar Masuk Barang
- Buat tampilan ui menggunakan Tailwind CSS (from scratch)
- Komponen design (posisi, warna, ukuran, bentuk dll) tidak diatur
- Mengimplementasi CSS Animation
- Memperhatikan UI/UX yang baik
- Menggunakan plugin di bawah ini:
    - `react-router`
    - `mobx-state-tree`
    - `react-hook-form`
    - `yup`
    - `sweetalert`
    - `jest` or `react-testing-library`
- Commit project ke dalam repo
------------
#### 2. Backend Implementation
Pada tahap ini Anda diharapkan mampu membuat Backend REST menggunakan NodeJS
##### Tugas
- Buatlah REST terhadap modul modul yang telah dibuat diatas menggunakan NodeJS dan MongoDB
- Gunakan JWT untuk Authentification
- Bisnis Logic
    - User dapat melalukan login dan logout
    - Buat hak akses berbeda (Input Master Data dan Pencatat Keluar Masuk Barang)
    - Di Master Barang terdapat picture
    - Barang yang sudah ada tidak bisa didaftarkan kembali
    - Barang yang belum pernah keluar gudang, tidak boleh dimasukan ke gudang lain
- Terdapat Unit Test
- Commit project ke dalam repo
------------
#### 3. REST Integration
Pada tahap ini Anda diharapkan mampu melakukan konsumsi data REST
##### Tugas
- Pada UI yang telah Anda buat sebelumnya, lakukan implementasi konsumsi data REST ke Backend yang sudah dibuat
- Bisnis Logic
    - Autentifikasi menggunakan token
    - Ada mekanisme refresh token
    - token expired tidak bisa digunakan
- Menggunakan plugin di bawah ini:
    - `axios`
- Commit project ke dalam repo

------------
##### Langkah akhir
- kirim link repo Anda beserta panduan untuk menjalankan project tersebut dalam Readme.md file

------------
#### Bonus
Task ini bersifat tidak wajib tapi akan mempengaruhi poin penilaian jika dikerjakan
##### Tugas
- Buat Sebuah Aplikasi Kalkulator (simple)
- Publish Aplikasi tersebut ke NPM dalam bentuk plugin
- Install Plugin tersebut ke dalam aplikasi yang telah anda buat
------------
**SELAMAT MENGERJAKAN**
