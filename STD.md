<html>
<body>
<div align="center"><h2>Software Testing Document</h2></div>

<p align="center"><b>Version 1.0 </b><br>
<p align="center">09 Mei 2018</b>
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
</body>
</html>

### BAB 1. PENDAHULUAN

**1.1 Tujuan Pembuatan Dokumen**

Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap perangkat lunak Pemesanan Lapangan Futsal SSAL APPS. Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditujukan untuk menguji perangkat lunak Pemesanan Lapangan Futsal SSAL APPS yang merupakan bagian dari tugas mata kuliah Rekayasa Perangkat Lunak.

**1.2 Deskripsi Umum Sistem**

Perangkat lunak yang akan diuji adalah “Pemesanan Lapangan Futsal SSAL APPS”. Perangkat lunak ini adalah perangkat lunak yang digunakan untuk melakukan transaksi pemesanan lapangan futsal di Satria Shintia Futsal. Sistem ini diimplementasikan melalui komunikasi di media antara sesama pengguna dengan sistem.

**1.3 Deskripsi Dokumen (Ikhtisar)**

Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil.

**1.4 Definisi dan Singkatan**

- SKPL adalah Spesifikasi Kebutuhan Perangkat Lunak, atau dalam bahasa Inggris-nya sering juga disebut sebagai Software Requirements Spesification (SRS), dan merupakan spesifikasi dari perangkat lunak yang akan dikembangkan
- SKPL-SK.K-xxxx adalah kode yang digunakan untuk merepresentasikan kebutuhan (requirement) pada SK, dengan SK merupakan kode perangkat lunak, SK.K adalah kode fase, dan xxxx adalah digit/nomor kebutuhan (requirement).
- DFD adalah Data Flow Diagram, diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak.
- ERD adalah Entity Relationship Diagram, diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak.
- DPPL-Akkses.K-xxxx adalah kode yang digunakan untuk mengimplementasikan perancangan pada Akkses, dengan Akkses merupakan kode perangkat lunak, Akkses.Kadalah kode fase, dan xxxx adalahdigit/nomor perancangan.

**1.5 Dokumen Referensi**
- Ernita H. GL03. Dokumen Uji Perangkat Lunak (DUPL) SDS. Bogor. 
- Sistem Pentiketan Elektronik Konser.2013. Spesifikasi Kebutuhan Perangkat Lunak (SKPL)SPEK. Bogor.
- Sistem Pentiketan Elektronik Konser.2013. Dokumen Perancangan Perangkat Lunak (DPPL)SPEK. Bogor.

###  BAB 2 Lingkungan Pengujian Perangkat Lunak

**2.1 Perangkat Lunak Pengujian**

Perangkat lunak ini (SPEK) diujikan dengan beberapa perangkat lunak lain, yaitu:
- Sistem operasi: Windows 8
- Bahasa pemrograman: PHP
- Data base: XAMPP

**2.2 Perangkat Keras Pengujian**

Perangkat keras yang diperlukan untuk menguji aplikasi SPEK ini adalah satu set komputer dengan minimal spesifikasi:
- Processor: Intel® Pentium Dual Core
- Memory: 2 GB DDR3
- Harddisk 100 GB

**2.3 Material Pengujian**

Pada program “Pemesanan Lapangan Futsal SSAL APPS” ini seorang calon pemesan dapat melakukan pendaftaran dan pemesanan lapangan tanpa melalui admin. Admin sendiri dapat memanipulasi data pembayaran. Pelanggan dapat langsung memesan lapangan futsal dengan masuk ke menu pemesanan lapangan yang ada di menu utama. Pelanggan melakukan pembayaran setelah memesan lapangan. Setelah pelanggan melakukan pembayaran maka si admin akan mengkonfirmasi pembayaran tersebut setelah si admin mengkonfirmasi pembayaran maka si pelanggan bisa melakukan mencetak bukti pembayaran dan menyerahkan ke petugas futsal.

**2.4 Sumber Daya Manusia**

Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian perangkat lunak ini adalah :
- Memahami konsep pemrograman berorientasi objek dalam bahasa PHP.
- Memahami proses pengujian perangkat lunak berorientasi objek.
- Memahami konsep pemrograman data base XAMPP.

**2.5 Prosedur Umum Pengujian**

**2.5.1 Pengenalan dan Latihan**

Penguji aplikasi ini hanya diberikan latihan kembali tentang SQL, dan pengenalan lebih lanjut tentang Net Beans dan Java. Pada dasarnya penguji telah memiliki pengetahuan tentang hal yang disebutkan sebelumnya tetapi latihan yang diberikan hanya bersifat penyegaran kembali.

**2.5.2 Persiapan Awal**

**2.5.2.1 Persiapan Prosedural**

Pengujian ini dilakukan di luar lingkungan kampus. Dimana pengujian ini dilakukan oleh tim penguji yang telah di tentukan oleh Dosen mata kuliah Rekayasa Perangkat Lunak (RPL). Alat yang digunakan 1 buah laptop dengan software yang telah di instalasi.

**2.5.2.2 Persiapan Perangkat Keras**
Perangkat keras yang perlu dipesiapkan adalah : Sebuah perangkat komputer yang dilengkapi dengan :
• Processor: Intel® Pentium Dual Core
• Memory: 2 GB DDR3
• Harddisk 100 GB

**2.5.2.3 Persiapan Perangkat Lunak**

Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows 7 adalah sebagai berikut : 1. Persiapkan sistem operasi Microsoft Windows. 2. Perangkat lunak yang akan di uji di copy ke sebuah direktori, misalnya C:\XAMPP\htdocs. 3. Browser Google Chrome. 4. Database di import ke phpMyAdmin di database db_konser. 5. Adobe Dreamweaver atau notepad ++ untuk melihat source code.
