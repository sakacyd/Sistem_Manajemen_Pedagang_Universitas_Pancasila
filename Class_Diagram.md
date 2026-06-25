#
## Class Diagram

Berdasarkan Class Diagram yang telah dirancang untuk Sistem Manajemen Pedagang Kantin, terdapat 5 entitas (class) utama pembentuk sistem. Berikut adalah rincian fungsionalitas, atribut (data yang disimpan), dan operasi (fungsi/tindakan) dari masing-masing class:

1. Class Pelanggan

Fungsi: Menyimpan data pengguna (pembeli) yang menggunakan sistem QR Code untuk memesan makanan atau minuman.

Atribut: id_pelanggan (identitas unik pembeli), nama (nama pembeli).

Operasi: buatPesanan() (proses pelanggan memulai transaksi atau pemesanan baru).

2. Class Penjual

Fungsi: Mewakili pemilik usaha kantin (narasumber) yang bertugas mengelola pesanan masuk melalui layar dashboard.

Atribut: id_penjual (identitas unik penjual), nama_warung (nama stan/warung di kantin).

Operasi: terimaPesanan() (mengonfirmasi pesanan yang masuk), updateStatusPesanan() (mengubah status pesanan dari 'sedang disiapkan' menjadi 'selesai').

3. Class Menu

Fungsi: Menyimpan seluruh katalog produk makanan dan minuman yang ditawarkan di kantin.

Atribut: id_menu, nama_menu, kategori (makanan berat, camilan, atau minuman), harga (harga satuan), dan stok (jumlah porsi yang tersedia).

Operasi: updateStok() (sistem otomatis mengurangi stok saat ada pesanan atau penjual menambah stok saat bahan baku baru datang).

4. Class Pesanan

Fungsi: Entitas inti yang merekam seluruh riwayat pemesanan dari pelanggan sejak menekan tombol pesan hingga selesai.

Atribut: id_pesanan, waktu_pesan, nomor_antrean (dihasilkan otomatis oleh sistem), total_harga, dan status (dalam antrean, disiapkan, menunggu pembayaran, atau selesai).

Operasi: tambahMenu() (pelanggan memasukkan menu ke keranjang), hitungTotalHarga() (sistem mengkalkulasi harga seluruh menu yang dipesan).

5. Class Pembayaran

- Fungsi: Mengelola pencatatan transaksi keuangan dari setiap pesanan yang telah dikonfirmasi.

- Atribut: id_pembayaran, metode_pembayaran (QRIS, e-Wallet, atau Cash), jumlah_bayar, dan status_pembayaran (lunas atau belum lunas).

- Operasi: prosesPembayaran() (menjalankan dan memvalidasi transaksi).

Relasi Antar Class (Kardinalitas)

- Pelanggan ke Pesanan (1 to Many):
1 orang pelanggan dapat membuat banyak (*) pesanan (misalnya pesan di pagi hari dan pesan lagi di siang hari). 
Namun, 1 pesanan spesifik hanya dimiliki oleh 1 pelanggan.

- Penjual ke Pesanan (1 to Many):
1 penjual dapat mengelola dan memproses banyak (*) pesanan sekaligus dari berbagai pelanggan.

- Pesanan ke Menu (1 to Many): 
Di dalam 1 pesanan, pelanggan dapat memilih dan memasukkan banyak (*) jenis menu sekaligus ke dalam satu nomor antrean.

- Pesanan ke Pembayaran (1 to 1):
1 transaksi pesanan hanya memiliki tepat 1 proses pembayaran (menghasilkan satu struk atau satu resi digital).

<img width="457" height="616" alt="Class_Diagram_APBO" src="https://github.com/user-attachments/assets/7844fd46-e3c0-47d3-a707-abbc620fc659" />
