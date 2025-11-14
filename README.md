# Fitur User

## Login
- Pengguna masuk menggunakan username/email dan password.  
- Sistem melakukan autentikasi.  
- Sistem menyimpan sesi selama aplikasi digunakan.  
- Sistem mengatur hak akses berdasarkan role (user atau admin).

## Registrasi
- Pengguna baru membuat akun dengan mengisi nama, username, email, nomor telepon, dan password.  
- Sistem memvalidasi data agar tidak duplikat dan sesuai format.  
- Setelah registrasi berhasil, pengguna bisa langsung login.

---

# Fitur Pelanggan

## Booking Layanan
- Pelanggan memilih layanan, kapster, dan waktu.  
- Sistem mengecek ketersediaan jadwal dan membuat reservasi otomatis.  
- Sistem menghitung durasi dan total harga.  
- Sistem menyimpan status booking (pending, confirmed, done, cancelled).  
- Sistem mengirim notifikasi konfirmasi atau pengingat.

## List Kapster
- Sistem menampilkan daftar kapster beserta nama, spesialisasi, pengalaman, rating, dan status.  
- Pelanggan bisa melihat profil kapster sebelum booking.  
- Admin dapat menambah, mengubah, dan memperbarui status kapster.

## Menu/Katalog
- Pelanggan membuka menu untuk melihat layanan.  
- Sistem menampilkan daftar layanan, termasuk deskripsi, durasi, harga, dan kapster yang mendukung.  
- Pelanggan bisa membuka detail layanan dan lanjut ke booking.

## List Produk
- Sistem menampilkan daftar produk yang dijual atau digunakan salon (nama, harga, stok).  
- Pelanggan bisa melihat produk dari menu produk.

## Pembayaran
- Pelanggan memilih booking dari history untuk dibayar.  
- Sistem menampilkan detail booking dan total harga.  
- Pelanggan memilih metode pembayaran.  
- Pelanggan dapat memasukkan kode promo.  
- Sistem menghitung total akhir.  
- Pelanggan mengonfirmasi pembayaran.  
- Sistem memverifikasi dan mengubah status booking menjadi "confirmed".  
- Sistem mengirim notifikasi.

## History
- Sistem menampilkan seluruh riwayat booking dan pembelian.  
- Sistem menyediakan filter periode atau status.  
- Pelanggan bisa repeat booking dari riwayat.  
- Sistem menyediakan detail harga dan status pembayaran.

## Feedback
- Pelanggan memberikan rating (1–5) dan ulasan setelah layanan selesai (status "done").  
- Rating untuk kapster dan layanan bisa terpisah.  
- Sistem menghitung rata-rata rating untuk ditampilkan di List Kapster dan Menu/Katalog.  
- Admin dapat meninjau semua feedback.  
- Ulasan relevan bisa ditampilkan sebagai referensi publik.

---

# Fitur Admin

## Kelola Promo
- Admin membuka menu promo.  
- Sistem menampilkan daftar promo.  
- Admin bisa menambah, mengedit, atau menonaktifkan promo.  
- Sistem melakukan validasi sebelum menyimpan.

## Tambah Stok Barang
- Admin memilih produk yang ingin ditambah stoknya.  
- Admin memasukkan jumlah stok tambahan.  
- Sistem memvalidasi dan memperbarui stok.  
- Sistem menampilkan notifikasi berhasil.

## View Reports
- Admin membuka halaman laporan.  
- Sistem menampilkan jenis laporan seperti penjualan produk, layanan, kinerja kapster, stok, dan pendapatan.  
- Admin menerapkan filter seperti periode atau kapster tertentu.  
- Sistem menyajikan data dalam bentuk visual.

---

# Fitur Bersama

## Profile Management
- Pengguna membuka halaman profil setelah login.  
- Sistem menampilkan data profil saat ini.  
- Pengguna dapat mengubah email, nomor telepon, atau kata sandi.  
- Untuk ubah password, pengguna memasukkan password lama dan baru.  
- Sistem memvalidasi perubahan dan memperbarui data.  
- Sistem menampilkan notifikasi bahwa perubahan berhasil.
