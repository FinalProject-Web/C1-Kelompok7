# C1-Kelompok7
![erd riska](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/6ee9cb48-ce7f-49cc-8b3e-6ffc63376966)

Penjelasan ERD :
1. Terdapat 6 table dalam database Takofee yaitu
   - Role : berisi role login website (admin, kasir, user)
   - User : berisi data akun dari pengguna website
   - Stok : berisi data stok penjualan 
   - Menu : berisi data menu penjualan
   - Pesan : berisi data pesanan pelanggan
   - Order : berisi data pembayaran/transaksi pelanggan
2. Role memiliki relasi 1 to N dengan User karena 1 Role dapat dimiliki oleh 1 atau lebih dari satu User (pengguna).
3. User memiliki relasi 1 to N dengan Pesan karena 1 pengguna dapat memmesan 1 atau lebih dari 1 pesanan.
4. Stok memiliki relasi 1 to N dengan Pesan karena 1 Stok dijual oleh 1 atau lebih dari satu pesanan, begitu pula dengan tabel Menu karena Stok dapat ditambahkan ke 1 atau lebih dari 1 menu.
5. Pesan memiliki relasi N to N dengan Menu karena 1 pesanan dapat memilih 1 atau lebih dari 1 menu, sebaliknya.
6. Pesan memiliki relasi 1 to 1 dengan Order karena 1 pesanan hanya dapat dibayar oleh 1 Order (transaksi).

![use case fixxx](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/e26b26f3-c933-42d4-8279-0b1a13ec62bc)

Penjelasan Use Case:
1. Terdapat 3 role login website Takofee (admin, kasir, user)
2. Admin memiliki beberapa hak akses yaitu a) lihat laporan, b) lihat data pengguna, c) tambah menu
3. Kasir memiliki hak akses yaitu a) menerima pembayaran, dan b) lihat laporan
4. User memiliki hak akses yaitu a) daftar akun, dan b) beli produk

## Tutorial penggunaan website Takofee berdasarkan role
### A. User
1. Tampilan awal website yaitu menampilkan form login dengan memasukan username dan password pengguna. Apabila pengguna belum memiliki akun, pengguna dapat mendafarkan akun baru yang terdapat dibawah form login.
![Masuk __ Takofee - Google Chrome 10_05_2023 22_44_50](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/d3c2e1e7-25da-442a-8de0-3e4098031cdd)

2. Apabila pengguna ingin mendaftarkan akun baru, maka tampilan websitenya akan seperti gambar dibawah ini. Pengguna dapat mengisi form pendaftaran akun sesuai dengan ketentuan.

3.  
4. 
5. 
