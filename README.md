# Aplikasi Ganjil Genap

Aplikasi Ganjil Genap adalah aplikasi berbasis Java yang membantu pengguna menentukan apakah suatu angka adalah ganjil atau genap dan memeriksa apakah angka tersebut merupakan bilangan prima. Aplikasi ini memiliki antarmuka pengguna yang sederhana dan intuitif serta dilengkapi dengan validasi input angka.

## Keunggulan Aplikasi

- **Validasi Input Angka**: Memastikan bahwa hanya angka yang dapat dimasukkan oleh pengguna.
- **Penentuan Ganjil atau Genap**: Menentukan apakah angka yang dimasukkan adalah ganjil atau genap.
- **Pemeriksaan Bilangan Prima**: Memeriksa apakah angka tersebut termasuk bilangan prima.
- **Antarmuka Pengguna yang Sederhana**: Menggunakan Java Swing untuk antarmuka yang mudah dipahami.

## Pembuat Aplikasi

Salsa Alya Istiqamah - 2210010089 - Tugas 1

## Fitur

Aplikasi Ganjil Genap menawarkan fitur-fitur berikut:

1. **Validasi Input**  
   Hanya menerima input berupa angka. Jika pengguna mencoba memasukkan karakter non-angka, aplikasi akan menampilkan pesan error.

2. **Cek Ganjil atau Genap**  
   Menampilkan informasi apakah angka yang dimasukkan adalah ganjil atau genap setelah menekan tombol "Cek".

3. **Pemeriksaan Bilangan Prima**  
   Selain mengecek ganjil/genap, aplikasi juga memeriksa apakah angka tersebut merupakan bilangan prima.

4. **Konfirmasi Keluar**  
   Tombol "Keluar" dilengkapi dengan dialog konfirmasi untuk memastikan pengguna sebelum menutup aplikasi.

5. **Antarmuka yang Mudah Digunakan**  
   Dibangun dengan Java Swing, aplikasi ini memiliki antarmuka yang ramah dan mudah digunakan.

## Cara Menjalankan

1. Clone repositori ini ke komputer Anda atau unduh sebagai file ZIP.
2. Buka proyek di IDE pilihan Anda (misalnya, NetBeans, IntelliJ, atau Eclipse).
3. Pastikan JDK sudah terkonfigurasi dengan benar di IDE Anda.
4. Jalankan `Tugas1` untuk memulai aplikasi.

## Struktur Kode

- **Tugas1**: Kelas utama yang berisi antarmuka pengguna serta metode untuk menangani input dan tombol.
- **initComponents**: Metode untuk menginisialisasi komponen GUI, termasuk pengaturan tombol dan label.
- **keyTyped pada jTextField1**: Menerapkan validasi input agar hanya angka yang bisa dimasukkan.
- **ActionListener pada Tombol**:
  - **Cek**: Mengambil input dari kolom, menampilkan apakah angka ganjil atau genap, dan apakah bilangan tersebut prima.
  - **Keluar**: Mengonfirmasi sebelum menutup aplikasi.
- **isPrima**: Metode untuk memeriksa apakah angka yang dimasukkan adalah bilangan prima.

## Demo


note : Aplikasi ini dirancang untuk memudahkan pengguna dalam mengecek apakah suatu angka adalah ganjil/genap dan bilangan prima dengan cepat dan sederhana.

