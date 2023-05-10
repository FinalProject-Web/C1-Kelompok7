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
![Daftar - Google Chrome 10_05_2023 22_48_51](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/bed62c33-b3fb-4c32-8d1b-186b81fb1f1d)

3. Apabila pengguna sudah memiliki akun, pengguna dapat melakukan login dengan memasukkan username dan password, kemudian jika berhasil login akan tampil halaman seperti gambar dibawah ini.

4. Untuk halaman entri order berisi tempat untuk memesan produk dari Takofee.
![Entri Order - Google Chrome 10_05_2023 22_55_10](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/31012fc8-c2df-4804-874e-4369df93f53f)

5. Pengguna dapat memesan produk Takofee dengan mengklik tombol pesan, kemudian mengisi jumlah pesanan dan nomor meja yang ada disebelah kanan website kemudian pesanan akan segera diproses.

### B. Kasir
1. Pada role kasir sama halnya dengan pengguna biasa yaitu melakukan login terlebih dahulu dengan memasukkan username dan password.
2. Jika berhasil login, akan tampil halaman website seperti gambar dibawah ini.
3. Tugas utama kasir yaitu membantu pelanggan melakukan pembayaran dengan memasukkan uang pembayaran pelanggan, dan memberikan uang kembalian jika ada.
![Entri Transaksi - Google Chrome 10_05_2023 23_12_31](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/a98b6f0b-4ef6-4934-87a6-0338386ef4c8)

4. Selain itu, kasir dapat melihat rekap pendapatan perhari dari Takofee.
![Entri Transaksi - Google Chrome 10_05_2023 23_14_15](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/d02490c9-a90a-4761-8c34-8f25ab1a7b86)
![Transaksi - Google Chrome 10_05_2023 23_23_20](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/8c7d7f91-2e70-4f60-a7c0-fb59c1c2c995)


### C. Admin
1. Sama dengan role lainnya, role admin juga perlu melakukan login terlebih dahulu sebelum mengakses website.
2. Tampilan awal pada role admin yaitu menampilkan data pengguna website Takofee seperti gambar dibawah ini.
![Beranda - Google Chrome 10_05_2023 23_06_56](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/bdbdf00c-b76f-43ab-8006-de3609cd7de6)

3. Kemudian admin dapat melakukan penambahan data, pada kasus ini admin dapat menambah data menu pada halamann Entri Referensi.
- Tampilan entri referensi
![Entri Referensi - Google Chrome 10_05_2023 23_09_00](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/1e07c0c0-8dcf-46e1-9ab6-e9dd64e5b418)

- Tambah menu
![Entri Referensi - Google Chrome 10_05_2023 23_09_30](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/2c8b3d04-178b-421f-9806-e2ba682a1086)

- Berhasil tambah menu
![Entri Referensi - Google Chrome 10_05_2023 23_09_43](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/92e2c9c8-ce17-42d1-880f-5272191b117c)

4. Selanjutnya sama seperti role kasir, admin juga dapat melihat data penjualan harian (rekap) pada halaman Generate Laporan 
![Entri Transaksi - Google Chrome 10_05_2023 23_12_15](https://github.com/FinalProject-Web/C1-Kelompok7/assets/120191981/f2c2bff2-1c58-41cf-b455-493bd604b28e)

