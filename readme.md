
# PACLIB - E-library Database Design 
SQL Database Design E-library PACLIB


## Overview

Database ini dirancang untuk mendukung sistem e-library PACLIB yang mengelola banyak perpustakaan di berbagai daerah. Pengguna dapat  mengakses koleksi buku , mengetahui ketersedian, meminjam dan melakukan pemesanan jika buku tidak tersedia dari berbagai perpustakaan.
## Business Rules

- Batas Peminjaman : Maksimal 2 buku aktif per pengguna 
- Batas Pemesanan : Maksimal 2 pemesanan aktif per pengguna
- Durasi Peminjaman : 2 minggu, otomatis dikembalikan jika melewati    jatuh tempo 
- Masa Berlaku Hold(Peminjaman): 1 minggu setelah buku tersedia 
- Update ketersedian : Quantity di kurangi saat buku dipinjam, dan di tambahkan saat buku di kembalikan 



## ERD

![App Screenshot](./image/ERD%20PACLIB%201.pgerd.png)

