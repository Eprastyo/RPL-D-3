
<html>
<body>
<div align="center"><h1>Software Design Document</h1></div>

<p align="center"><b>Version 1.2 </b><br>
<p align="center">15 April 2018</b>
<p align="center">
<img src="https://2.bp.blogspot.com/-dxdRgMQGbLk/WpA-Tp2rNGI/AAAAAAAAAh8/3_jBWFb7Cf48033QvB34D2WCwoN2sxZLgCLcBGAs/s1000/index.png"/>
</p>

<br><p align="center"><b> SSAL APPS </b><br>
<p align="center"><b>Aplikasi Pemesanan Lapangan Futsal
</b>
<p align="center">Kelompok 3 <br>
 Eko Prastyo 		(1603096)<br>
Syahrul Gunawan 	(1603113)<br>
Tuti Nurafni Amalia (1603116)<br>
Wulandiani 			(1603118) <br> <br> <br>
 
<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
</p>
<hr>
</body>
</html>

# BAB 1 PENDAHULUAN

### 1.1 Tujuan    

<p align="justify">Tujuan pembuatan SDD(Software Design Description) ini adalah untuk menjelaskan langkah-langkah design dan proses-proses dalam pembuatan sistem aplikasi "Pemesanan Lapangangan Futsal " yang disebut dengan nama S'SAL, dan juga memberikan definisi untuk sistem , spesifikasi kebutuhan fungsional. Fungsi utama dari S'SAL ini adalah pemesanan lapangan futsal secara online berbasis android untuk pengguna dan pemilik, serta berbasis web untuk admin dan juga dapat mengetahui informasi lapangan kosong, serta transaksi pemesanan lapangan futsal.</p>
<p align="justify">Aplikasi ini digunakan untuk kalangan kaum umum untuk pemesanan dan penjadwalan penggunaan lapangan futsal, serta dapat memberikan informasi pemesanan lapangan dan penjadwalan futsal. dan mempermudah pelangganuntuk pemesanan lapangan futsal.</p>  
  
### 1.2 Lingkup Masalah  
  
<p align="justify">Aplikasi SSAL Pemesanan Lapangan Futsal ini adalah aplikasi berbasis android yang mempermudah dalam pemesanan lapangan futsal, Pengguna aplikasi ini dapat melakukan pendaftaran, login, melihat jadwal lapangan yang sudah di pesan, memesan lapangan futsal, dan melakukan pembayaran. Sistem ini dikelola oleh seorang admin yang bertugas mengelola data lapangan, mengelola data pelanggan, mengelola data pemesanan dan transakasi juga laporan.</p>
  
### 1.3 Definsi,akronim,singkatan
  
| Istilah | Arti |  
| ------- | ------------------------------------------------ |  
| SDD | *Software Design Document* |  
| S'SAL | Satria Shintia futsal |  
| IEEE | Institute of Electrical and Electronics Engineer |  
| CI | Code Igniter |   
  
### 1.4 Referensi
  
[1]IEEE Software Engineering Standards Committee, IEEE Std 830-1998, IEEERecommended  

[2]https://en.wikipedia.org/wiki/SDD

[3]https://yohanesgunawan.files.wordpress.com/2007/10/sdd-aeromodeling-store_final.pdf  
    
### 1.5 Ikhtisar Dokumen
  
Penulisan dokumen ini dibagi menjadi beberapa bab sbb :  
  
<ul>  
<li> Bab 1, adalah pendahuluan yang menjelaskan mengenai tujuan perangkat lunak, ruang lingkup, definisi, referensi serta ikhtiar dokumen </li>  
<li> Bab 2, adalah Deskripsi perancangan global, yang bersisi tengtang rancangan lingkungan iplementasi, deskripsi data dan deskripsi modul.</li>  
<li> Bab 3, adalah Deskripsi perancangan rinci, yang berisi tentang Diagram konteks, Deskripsi rinci tabel, Deskripsi rinci modul, dan matriks kerunutan.</li>  
</ul>  
   
# BAB 2 Deskripsi Perancangan Global 
  
### 2.1 Rancangan Lingkungan Implementasi
<p align="justify">pada proses pembuatan aplikasi ini , hal-hal yang mendukung dalam pemrosesan pembuatan aplikasi seperti sistem operasi yang digunakan untuk membuat aplikasi SSAL ini adalah :  </p>

##### a. Sistem Operasi
Sistem Operasi yang digunakan adalah :
 - Microsoft Windows 7
 - Microsoft Windows 10

##### b. DBMS 
 - DBMS yang digunakan adalah Mysql dan Firebase

##### c. Development Tools
 - Android Studio
 - Sublime text 3

##### d. Bahasa Pemrograman
 - Pada Admin (Web)  menggunakan bahasa pemrograman PHP, HTML, Framework model code igninteer (CI), Bootstrap dan CSS.
 - Pada Dosen dan Mahasiswa (Mobile) dalam pembuatannya menggunakan bahasa pemrograman android (java).

### 2.2 Deskripsi Data

**Tabel Pembayaran**

| Data Item     | Type    | Volume | laju        | Primary key | Constrain Integrity | Deskripsi                 |
|---------------|---------|--------|-------------|-------------|---------------------|---------------------------|
| id_pembayaran | integer | 5      | Primary Key | Iya         | Auto Increment      | Nomor id pembayaran       |
| id_pemesanan  | integer | 11     | Tidak       | Tidak       | -                   | nomor id pemesanan        |
| ke_rekening   | varchar | 20     | Tidak       | Tidak       | -                   | keterangan                |
| no_rekening   | varchar | 20     | Tidak       | Tidak       | -                   | nomer rekening pembayaran |
| total_bayar   | integer | 20     | Tidak       | Tidak       | -                   | jumlah bayar              |

**Tabel Jam**

| Data Item | Type    | Volume | laju        | Primary key | Constrain Integrity | Deskripsi                |
|-----------|---------|--------|-------------|-------------|---------------------|--------------------------|
| id_jam    | integer | 11     | Primari Key | Iya         | Auto Increment      | jam pemesanan            |
| mulai     | time    | -      | Tidak       | Tidak       | -                   | keterangan waktu         |
| selesai   | time    | -      | Tidak       | Tidak       | -                   | keterangan waktu selesai |

**Tabel Member**

| Data Item | Type    | Volume | laju        | Primary key | Constrain Integrity | Deskripsi              |
|-----------|---------|--------|-------------|-------------|---------------------|------------------------|
| id_member | integer | 11     | Primary Key | Iya         | Auto Increment      | nomor id anggota       |
| user name | varchar | 255    | Tidak       | Tidak       | -                   | username pengguna      |
| password  | varchar | 255    | Tidak       | Tidak       | -                   | password pengguna      |
| level     | varchar | 20     | Tidak       | Tidak       | -                   | admin                  |
| alamat    | varchar | 13     | Tidak       | Tidak       | -                   | alamat pengguna        |
| telepon   | varchar | 10     | Tidak       | Tidak       | -                   | nomor telepon pengguna |

**Tabel Lapangan**

| Data Item   | Type     | Volume | laju        | Primary key | Constrain Integrity | Deskripsi           |
|-------------|----------|--------|-------------|-------------|---------------------|---------------------|
| id_lapangan | integer  | 11     | Primary key | Iya         | AUTO INCREMENT      | nomor id lapangan   |
| nama        | varchar  | 11     | Tidak       | Tidak       | -                   | nama                |
| harga sewa  | integer  | 20     | Tidak       | Tidak       | -                   | harga sewa lapangan |
| keterangan  | varchar  | 100    | Tidak       | Tidak       | -                   | keterangan          |
| gambar      | longblob | -      | Tidak       | Tidak       | -                   | gambar lapangan     |

**Tabel Pemesanan**

| Data Item        | Type    | Volume | laju        | Primary key | Constrain Integrity | Deskripsi               |
|------------------|---------|--------|-------------|-------------|---------------------|-------------------------|
| id_pemesanan     | integer | 11     | Primary Key | Iya         | Auto Increment      | nomor id pemesanan      |
| id_member        | integer | 11     | Tidak       | Tidak       | -                   | nomor id pelanggan      |
| id_lapangan      | integer | 20     | Tidak       | Tidak       | -                   | nomor id lapangan       |
| durasi           | integer | 11     | Tidak       | Tidak       | -                   | lamanya waktu pemesanan |
| tanggal          | integer | 11     | Tidak       | Tidak       | -                   | tangga pemesanan        |
| status           | varchar | 10     | Tidak       | Tidak       | -                   | status pembayaran       |
| bukti_pembayaran | blob    |        | Tidak       | Tidak       | -                   | gambar bukti pembayaran |

**Tabel Transaksi**
  
| Data Item     | Type | Volume | laju        | Primary key | Constrain Integrity | Deskripsi           |
|---------------|------|--------|-------------|-------------|---------------------|---------------------|
| id_transaksi  | int  | 11     | Primary Key | Iya         | Auto Incremen       | nomor id transaksi  |
| id_pembayaran | int  | 20     | Tidak       | Tidak       | -                   | nomor id pembayaran |  
  
# BAB 3 DESKRIPSI RANCANGAN RINCI

### 3.1 Dekomposisi model

#### 3.1.1 Diagram Konteks

<p align="justify">Diagram konteks adalah diagram yang terdiri dari suatu proses dan menggambarkan ruang lingkup suatu sistem. Diagram konteks merupakan level tertinggi dari DFD yang menggambarkan seluruh input ke dalam sistem atau output dari sistem yang memberi gambaran tentang keseluruhan sistem. Sistem dibatasi oleh boundary (Digambarkan dengan garis putus - putus). Dalam diagram konteks hanya ada satu proses, tidak boleh ada store dalam diagram konteks. Berikut ini adalah gambar diagram konteks dari sistem Aplikasi SSAL</p>
![enter image description here](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/DFD%20CONTEX.PNG)  
  
#### 3.1.2 DFD level 0

Data Flow Diagram merupakan cara untuk memodelkan proses dalam analisis dan perancangan perangkat lunak, dan merupakan penjelasan dari context diagram.
![enter image description here](https://github.com/Eprastyo/RPL-D-3/raw/master/Gambar/DFD%20LEVEL%200.PNG)  

### Dekomposisi proses konkuren 

#### 3.1.1.1 DFD level 1 Proses Mengelola Data Pemesanan
![DFD](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/DFD%20LEVEL%201%20PEMESANAN.PNG)  
  
#### 3.1.1.2 DFD Level 1 Proses Mengelola Data Pelanggan
![DFD](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/DFD%20LEVEL%201%20MEMBER.PNG)

#### 3.1.1.3 DFD Level 1 Proses Mengelola Data Pembayaran
![DFD](https://github.com/Eprastyo/RPL-D-3/blob/master/Gambar/DFD%20LEVEL%201%20PEMBAYARAN.PNG?raw=true)  
  
### 3.1.1.4 DFD level 1 Mengelola data lapangan
![DFD](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/DFD%20LEVEL%201%20LAPANGAN.PNG)  
  
