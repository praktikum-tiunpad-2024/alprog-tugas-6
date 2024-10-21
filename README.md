[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-aI7sY65)
# Tugas 6 Praktikum Algoritma dan Pemrograman 2024: STRUCT

**PENTING: Harap untuk membaca instruksi di [wiki](https://github.com/praktikum-tiunpad-angkatan-2022/modul-algoritma-dan-pemrograman/wiki) terlebih dahulu sampai dipahami sebelum mengerjakan soal!**

**Penting Juga: Biasakan menambah format berikut pada bagian paling atas setiap file kode!**

```cpp
/*
Nama Program :
Nama         :
NPM          :
Tanggal Buat :
Deskripsi    :
*/
```

## Daftar Isi
- [Latihan 1](#latihan-1)
- [Latihan 2](#latihan-2)
- [Penjualan Mobil](#nilai-mutu-terbaru)
- [Sistem Manajemen Nilai Mahasiswa](#manhattan-distance)
- [Sistem Manajemen Kontak](#rumus-abc)

## Latihan 1
> file: `latihan_1.cpp`

### Deskripsi
Buatlah program yang dapat menyimpan data film menggunakan struct. Setiap film memiliki data berikut:

- Judul Film (string)
- Sutradara (string)
- Tahun Rilis (integer)
- Rating (float)

### Format Input
Data Film

### Contoh
  
* Sample Input 1
  
  ```
  Inception
  Christopher Nolan
  2010
  8.8
  ```

* Sample Output 1
  
  ```
  Judul: Inception
  Sutradara: Christopher Nolan
  Tahun Rilis: 2010
  Rating: 8.8
  ```
    
* Sample Input 2
  
  ```
  The Shawshank Redemption
  Frank Darabont
  1994
  9.3
  ```

* Sample Output 2
  
  ```
  Judul: The Shawshank Redemption
  Sutradara: Frank   Darabont
  Tahun Rilis: 1994
  Rating: 9.3
  ```

## Latihan 2
> file: `latihan_2.cpp`

### Deskripsi
Buatlah sebuah struct yang dapat menampilkan produk dengan jumlah terbanyak. Data yang disimpan meliputi:
- n jumlah produk
- Nama Produk (string)
- Kode Produk (integer)
- Harga Produk (float)
- stok barang (int)
### Contoh
  
* Sample Input 1
  
  ```
  2
  Laptop
  1001
  5000000
  50
  Smartphone
  1002
  3000000
  40
  ```

* Sample Output 1
  
  ```
  Produk dengan Stok terbanyak :
  Nama Produk: Laptop 
  Kode Produk: 1001
  Harga: 5000000
  dengan 50 stok
  ```
  
* Sample Input 2
  
  ```
  3
  Laptop
  1001
  5000000
  50
  Smartphone
  1002
  3000000
  40
  Power Bank
  1003
  100000
  80
  ```

* Sample Output 2
  
  ```
  Produk dengan Stok terbanyak :
  Nama Produk: Power Bank
  Kode Produk: 1003
  Harga: 100000
  dengan 80 stok
  ```

## Penjualan Mobil
> file: `tugas_1.cpp`

### Deskripsi
Buatlah sebuah program untuk mengelola penjualan mobil di sebuah dealer mobil. Program ini harus dapat menyimpan informasi tentang mobil yang tersedia dan mencatat mobil yang sudah terjual. Setiap mobil memiliki data berikut:

- Nama Mobil (string)
- Kode Mobil (integer)
- Harga (float)
- Status (boolean: true untuk terjual, false untuk belum terjual)
- Deskripsi Program:

Program menerima input dari pengguna dalam satu kali proses.
Pengguna harus memasukkan beberapa mobil sekaligus, diakhiri dengan sebuah tanda tertentu (misalnya, kata "selesai").
Setelah pengguna selesai memasukkan data, program akan menampilkan:
Daftar semua mobil dengan status masing-masing.
- Daftar mobil yang sudah terjual.
- Daftar mobil yang belum terjual.
### Format Input
- n jumlah mobil
- nama mobil
- cc
- status penjualan
### Contoh
  
* Sample Input 1
  
  ```
  2
  Avanza 2019
  1300
  terjual
  Nissan GT-R Nismo 2020
  3800
  belum terjual
  ```

* Sample Output 1
  
  ```
  Terjual : Avanza 2019
  Belum Terjual : Nissan GT-R Nismo 2020 
  ```
  * Sample Input 2
  
  ```
  3
  Avanza 2019
  1300
  terjual
  Nissan GT-R Nismo 2020
  3800
  belum terjual
  MV3 Garuda Limousine
  2157
  belum terjual
  ```

* Sample Output 2
  
  ```
  Terjual : Avanza 2019
  Belum Terjual : Nissan GT-R Nismo 2020 , MV3 Garuda Limousine
  ```

## Sistem Manajemen Nilai Mahasiswa
> file: `tugas_2.cpp`

### Deskripsi
Buatlah sebuah program untuk mengelola data mahasiswa dan nilai ujian mereka. Setiap mahasiswa harus disimpan dalam struct dengan informasi sebagai berikut:

- Nama Mahasiswa (string)
- NIM (integer)
- Nilai Ujian (float)

Deskripsi Program:

Program harus dapat menerima input dari pengguna untuk beberapa mahasiswa dalam satu proses.
Setelah memasukkan data mahasiswa, program harus dapat menghitung:
Rata-rata nilai ujian dari semua mahasiswa.
Jumlah mahasiswa yang lulus dan tidak lulus.
Menampilkan daftar semua mahasiswa dengan status lulus atau tidak.  

### Format Input
- n jumlah mahasiswa
- Nama mahasiswa
- NPM mahasiswa
- Nilai Mahasiswa

### Format Output
- Daftar Nama mahasiswa beserta lulus atau tidaknya 
- Rata-rata Nilai mahasiswa

nilai kelulusan >= 75
### Catatan

### Contoh
  
* Sample Input 1
  
  ```
  2
  Rizki
  140808
  80
  Farel
  140881
  70
  ```

* Sample Output 1
  
  ```
  Lulus : 140808
  Tidak Lulus : 140881
  Rata-rata : 75
  ```
    
* Sample Input 2
  
  ```
  3
  Rizki
  140808
  80
  Farel
  140881
  70
  Panji
  140882
  90
  ```

* Sample Output 2
  
  ```
  Lulus : 140808 , 140882
  Tidak Lulus : 140881
  Rata-rata : 80
  ```

## Sistem Manajemen Kontak
> file: `freeform.cpp`

### Deskripsi
Buatlah sebuah program untuk mengelola kontak dalam sebuah buku alamat. Setiap kontak harus disimpan dalam struct dengan informasi sebagai berikut:

- Nama (string)
- Nomor Telepon (string)
- Alamat (string)
- Email (string)
- Deskripsi Program:

Program harus dapat menerima input dari pengguna untuk beberapa kontak dalam satu proses.
Setelah memasukkan data kontak, program harus dapat melakukan hal-hal berikut:
Menampilkan semua kontak yang telah dimasukkan.
Mencari dan menampilkan kontak berdasarkan nama.
Menghapus kontak berdasarkan nama.

### Contoh
  
* Sample Input 1
  
  ```
    Nama: Andi
    Nomor Telepon: 08123456789
    Alamat: Jalan Mawar No. 10
    Email: andi@example.com
  ```

* Sample Output 1
  
  ```
  Daftar Kontak:
  1. Nama: Andi, Nomor Telepon: 08123456789, Alamat:  Jalan Mawar No. 10, Email: andi@example.com

  ```
  
* Sample Input 2
  
  ```
    Nama: Budi
    Nomor Telepon: 08234567890
    Alamat: Jalan Melati No. 20
    Email: budi@example.com
  ```

* Sample Output 2
  
  ```
  Daftar Kontak:
  1. Nama: Andi, Nomor Telepon: 08123456789, Alamat: Jalan Mawar No. 10, Email: andi@example.com
  2. Nama: Budi, Nomor Telepon: 08234567890, Alamat: Jalan Melati No. 20, Email: budi@example.com
  ```

