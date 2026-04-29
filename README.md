# Sistem Manajemen Pedagang Universitas Pancasila

## Kelompok 7
### Anggota Kelompok:
1. 4521210009 - Muhammad Adyatma Widyadhana
2. 4521210088 - Muhammad Yusuf Hadinata
3. 4522210062 - Sakahayu Pribadi
4. 4522210110 - Libryan Isra Gunawan
5. 4522210118 - Mochamad Zaidan Al Rasyid

##
## Topik
### Alasan memilih topik
Topik ini dipilih karena usaha kantin kampus masih menggunakan sistem manual dalam proses pemesanan dan pembayaran. Hal ini menyebabkan beberapa kendala, terutama saat kondisi ramai pembeli, seperti antrean panjang, kesalahan pencatatan pesanan, dan keterlambatan pelayanan.

Selain itu, berdasarkan hasil wawancara, pemilik usaha mengalami kesulitan dalam mengelola pesanan sendirian. Oleh karena itu, dibutuhkan sebuah sistem yang dapat membantu mengotomatisasi proses pemesanan dan pembayaran agar lebih efisien, terstruktur, dan real-time.

Topik ini juga relevan dengan perkembangan teknologi digital, khususnya penerapan QR Code untuk meningkatkan kualitas layanan usaha kecil.

### Tujuan Wawancara
1. Mengidentifikasi proses bisnis yang sedang berjalan pada usaha kantin.
2. Mengetahui kendala atau permasalahan yang dihadapi oleh pemilik usaha.
3. Menggali kebutuhan sistem yang dapat membantu meningkatkan efisiensi operasional.
4. Menjadi dasar dalam merancang solusi sistem informasi yang sesuai dengan kondisi nyata di lapangan.

### Destinasi Wawancara
- Nama Usaha: Kanrek (Kantin Rektorat)
- Narasumber: Mba Yuni
- Lokasi: Lingkungan Kampus (Kantin Rektorat)

##
## Pertanyaan Wawancara
### Alur Wawancara
### Bagian A (Profiling)
1. sudah berapa lama usaha ini berjalan? dan apa saja layanan utama yang diberikan?
### Bagian B (Analisis Proses Bisnis)
2. bisa di ceritain bagaimana proses layanan, misal pemesanan makanan dari awal sampai selesai?
3. siapa saja yang terlibat dalam proses ini?
### Bagian C (Identifikasi Masalah)
4. kendala apa saja yang sering muncul dalam menjalankan proses tersebut? (seperti saat catat pesanan atau stok habis atau kendala lain)
5. bagaimana cara menangani masalah tersebut sekarang secara manual?
### Bagian D (Solusi/Kebutuhan Sistem)
6. jika kita membuat sistem kira kira fitur apa yang paling membantu buat masalah tersebut?
7. siapa saja nanti yang di izinkan untuk mengakses sistem tersebut?

##
## Alur Bisnis
### Gambaran Alur Sistem Kerja Awal Cafe
Sistem yang ada di kantin mba Yuni sekarang masih bersifat konvensional/manual dengan proses sebagai berikut:
1. Pelanggan datang ke kantin.
2. Melihat menu secara langsung (display atau bertanya ke penjual).
3. Untuk menu Nasi Rames pelanggan bisa mengambil sendiri atau prasmanan.
4. Untuk menu lain seperti indomie, minuman dingin, makanan ringan bisa langsung ke penjual.
5. Penjual mencatat pesanan atau hanya mengingat pesanan yang sudah dipesan.
6. Penjual menyiapkan pesanan satu per satu.
7. Setelah selesai, pelanggan melakukan pembayaran langsung bisa cash bisa melalui QRIS.
8. Penjual menghitung total secara manual.

### Penjelasan Permasalahan Cafe
Berdasarkan observasi dan wawancara dengan narasumber (Mba Yuni), ditemukan beberapa permasalahan utama:
1. Overload saat kondisi ramai.
2. Penjual mengelola semua proses sendirian (order, masak, bayar) Menyebabkan kewalahan dan penurunan kualitas pelayanan.
3. Antrean Tidak Teratur, tidak ada sistem antrian digital, pelanggan bisa saling mendahului atau bingung urutan. 
4. Kesalahan pencatatat pesanan mengandalkan ingatan/ manual menyebabkan rawan salah
5. Keterlambatan pelayanan karena proses dilakukan satu per satu dan juga tidak ada sistem otomatisasi.
6. Tidak ada monitoring transaksi pemilik jadi tidak bisa melihat jumlah pesanan dan total penjualan secara real-time

### Solusi Yang Ditawarkan
Dari permaslahan yang kami dengar dari narasumber solusi yang kami berikan yaitu digitalisasi sistem pemesanan dan pembayaran menggunakan QR Code
### Fitur Utama:
1. QR Code di setiap meja (pelanggan scan menggunakan device HP nya masing masing, setelah itu langsung masuk ke menu digital).
2. Menu digital interaktif (tersedia berbagai macam kategori makanan berat, minuman, snack dan juga pelanggan bisa memilih jumlah dan varian).
3. Sistem pemesanan otomatis (pesanan masuk ke sistem dashboard penjual dan akan melakukan urutan otomatis menggunakan sistem FIFO).
4. Pembayaran digital (bisa menggunakan e-wallet, QRIS, atau bayar di kasir tapi sudah tercatat).
5. Dashboard Penjual (menampilkan daftar pesanan, status pesanan, total transaksi, stok barang).

### Gambaran Rancangan Sistem Kerja Baru
Setelah mendengarkan permasalahan dari narasumber dan kita memberi solusi terhadap permasalahan kantin tersebut, sekarang kita akan memberi alur sistem digital untuk kantin sebagai berikut:
1. Pelanggan datang dan duduk.
2. Scan QR Code di meja.
3. Sistem menampilkan menu digital.
4. Pelanggan memilih makan dan minum.
5. Pelanggan melakukan pemesanan.
6. Sistem akan otomatis menyimpan pesanan dan memberi nomor antrian.
7. Pesanan masuk ke dashboard penjual.
8. Penjual menyiapkan pesanan sesuai urutan.
9. Pelanggan melakukan pembayaran langsung menggunakan e-wallet atau QRIS atau cash dengan datang ke kasir.
10. Pesanan selesai pelanggan bisa mengambil atau diantar pesanannya.
