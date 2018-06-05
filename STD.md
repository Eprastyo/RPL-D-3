
<html>
<body>
<div align="center"><h2>Software Testing Document</h2></div>

<p align="center"><b>Version 1.1 </b><br>
<p align="center">18 Mei 2018</b>
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

## BAB 1. PENDAHULUAN

### 1.1 Tujuan Pembuatan Dokumen

Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap perangkat lunak Pemesanan Lapangan Futsal SSAL APPS. Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditujukan untuk menguji perangkat lunak Pemesanan Lapangan Futsal SSAL APPS yang merupakan bagian dari tugas mata kuliah Rekayasa Perangkat Lunak.

### 1.2 Deskripsi Umum Sistem

Perangkat lunak yang akan diuji adalah “Pemesanan Lapangan Futsal SSAL APPS”. Perangkat lunak ini adalah perangkat lunak yang digunakan untuk melakukan transaksi pemesanan lapangan futsal di Satria Shintia Futsal. Sistem ini diimplementasikan melalui komunikasi di media antara sesama pengguna dengan sistem.

### 1.3 Deskripsi Dokumen (Ikhtisar)

Dalam dokumen ini berisi 3 bagian utama yaitu Pendahuluan, Identifikasi dan Rencana Pengujian, Deskripsi dan Uji Hasil.

### 1.4 Definisi dan Singkatan

- Software Requirements Spesification (SRS), dan merupakan spesifikasi dari perangkat lunak yang akan dikembangkan
- DFD adalah Data Flow Diagram, diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak.
- ERD adalah Entity Relationship Diagram, diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak.
- DPPL adalah kode yang digunakan untuk mengimplementasikan perancangan . dengan  xxxx adalah digit/nomor perancangan.

  
| Istilah | Arti | Deskripsi |
| ------- | ----------------------------------- | --------------|
| STD | *Software Testing Document* |  dokumen yang mendeskripsikan pengujian aplikasi yang dibuat.dokumen ini menjelaskan bagian aplikasi mana saja yang sudah di lakukan testing/ pengujian.|
| DFD | Data Flow Diagram  |  diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak.|
| ERD | Entity Relationship | diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak.|
| SRS | *Software Requirements Spesification* | dokumen yang mendeskripsikan spesifikasi kebutuhan dari aplikasi yang akan dibuat. pada dokumen ini dijelaskan bagaimana dan seperti apa rancangan aplikasi tersebut.|
### 1.5 Dokumen Referensi
|No | Referensi |
| --------------| -------------|
|1. |  Ernita H. GL03. Dokumen Uji Perangkat Lunak (DUPL) SDS. Bogor. |
| 2. | Sistem Pentiketan Elektronik Konser.2013. Spesifikasi Kebutuhan Perangkat Lunak (SKPL)SPEK. Bogor.|
|3. | Sistem Pentiketan Elektronik Konser.2013. Dokumen Perancangan Perangkat Lunak (DPPL)SPEK. Bogor.|

##  BAB 2. LINGKUNGAN PENGUJIAN PERANGKAT LUNAK
 
### 2.1 Perangkat Lunak Pengujian

Perangkat lunak ini (SPEK) diujikan dengan beberapa perangkat lunak lain, yaitu:
- Sistem operasi : Windows 10
- Framework : CI
- Data base : Mysql  

### 2.2 Perangkat Keras Pengujian

Perangkat keras yang diperlukan untuk menguji aplikasi SPEK ini adalah satu set komputer dengan minimal spesifikasi:
- Processor: Core i3
- Memory : 6-8GB
- Harddisk  : 500 GB

### 2.3 Material Pengujian

Pada program “Pemesanan Lapangan Futsal SSAL APPS” ini seorang calon pemesan dapat melakukan pendaftaran dan pemesanan lapangan tanpa melalui admin. Admin sendiri dapat memanipulasi data pembayaran. Pelanggan dapat langsung memesan lapangan futsal dengan masuk ke menu pemesanan lapangan yang ada di menu utama. Pelanggan melakukan pembayaran setelah memesan lapangan. Setelah pelanggan melakukan pembayaran maka si admin akan mengkonfirmasi pembayaran tersebut setelah si admin mengkonfirmasi pembayaran maka si pelanggan bisa melakukan mencetak bukti pembayaran dan menyerahkan ke petugas futsal.

### 2.4 Sumber Daya Manusia

Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian perangkat lunak ini adalah :
- Memahami proses pengujian perangkat lunak berorientasi Objek
- Memahami proses pengujian perangkat lunak berorientasi objek
- Memahami konsep pemrograman Database

### 2.5 Prosedur Umum Pengujian

**2.5.1 Pengenalan dan Latihan**

Penguji aplikasi ini hanya diberikan latihan kembali tentang SQL, dan pengenalan lebih lanjut tentang Net Beans dan Java. Pada dasarnya penguji telah memiliki pengetahuan tentang hal yang disebutkan sebelumnya tetapi latihan yang diberikan hanya bersifat penyegaran kembali.

**2.5.2 Persiapan Awal**

#####  2.5.2.1 Persiapan Prosedural

Pengujian ini dilakukan di luar lingkungan kampus. Dimana pengujian ini dilakukan oleh tim penguji yang telah di tentukan oleh Dosen mata kuliah Rekayasa Perangkat Lunak (RPL). Alat yang digunakan 1 buah laptop dengan software yang telah di instalasi.

##### 2.5.2.2 Persiapan Perangkat Keras
Perangkat keras yang perlu dipesiapkan adalah : Sebuah perangkat komputer yang dilengkapi dengan :

• Processor: Intel® Pentium Dual Core
• Memory: 4 GB DDR3
• Harddisk 100 GB

##### 2.5.2.3 Persiapan Perangkat Lunak

Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows 7 adalah sebagai berikut : 
1. Persiapkan sistem operasi Microsoft Windows.
2. Perangkat lunak yang akan di uji di copy ke sebuah direktori, misalnya C:\XAMPP\htdocs. 
3. Browser Google Chrome. 
 4. Database di import ke phpMyAdmin
5. Sublime Text 3  atau notepad ++ untuk melihat source code.

## BAB 3. IDENTIFIKASI DAN RENCANA PENGUJIAN 

###  Tabel Identifikasi dan rencana pengujian

<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Tingkat Pengujian</td>
	<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>STD</td>
		</tr>
<tr>
	<td rowspan="3" align="center"><strong>Login Web</td>
	<td>Email dan password yang di inputkan sudah terdaftar</td>
	<td>SRS 2.2.1 Login Admin</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
<tr>
	<td>Email dan password yang di inputkan belum terdaftar</td>
	<td>SRS 2.2.1 Login Admin</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
</tr>
<tr>
	<td>Kolom Email dan password kosong</td>
	<td>SRS 2.2.1 Login Admin</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Mengelola data lapangan Web</td>
	<td>Mengelola data lapangan sudah benar</td>
	<td>SRS 2.2.2 Mengelola data lapangan</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Syahrul</td>
<tr>
	<td>Mengelola data lapangan belum benar</td>
	<td>SRS 2.2.2 Mengelola data lapangan</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Syahrul</td>
</tr>
<tr>
	<td>Data lapangan kosong</td>
	<td>SRS 2.2.2 Mengelola data lapangan</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Syahrul</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Transaksi Pembayaran Web</td>
	<td>Mengelola data Transaksi sudah benar</td>
	<td>SRS 2.2.5 Transaksi Pembayaran</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
<tr>
	<td>Mengelola data Transaksi belum benar</td>
	<td>SRS 2.2.5 Transaksi Pembayaran</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
</tr>
<tr>
	<td> Data Transaksi kosong</td>
	<td>SRS 2.2.5 Transaksi Pembayaran</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Penampilkan data Pemesanan Web</td>
	<td>Penampilkan daftar pemesanan sudah benar</td>
	<td>SRS 2.2.4 Menampilkan daftar pemesanan</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Syahrul</td>
<tr>
	<td>Penampilkan daftar pemesanan belum benar</td>
	<td>SRS 2.2.4 Menampilkan daftar pemesanan</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Syahrul</td>
</tr>
<tr>
	<td>Daftar Pemesanan kosong</td>
	<td>SRS 2.2.4 Menampilkan daftar pemesanan</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Syahrul</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Konfirmasi Pembayaran Web</td>
	<td>Konfirmasi data pembayaran sudah benar</td>
	<td>SRS 2.2.3 Konfirmasi Pembayaran</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
<tr>
	<td>Konfirmasi data pembayaran belum benar</td>
	<td>SRS 2.2.3 Konfirmasi data pembayaran</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
</tr>
<tr>
	<td>Konfirmasi data pembayaran kosong</td>
	<td>SRS 2.2.3 Konfirmasi pembayaran</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
</tr>
<tr>
<td rowspan="3" align="center"><strong>Login Mobile</td>
<td>Email dan password yang di inputkan sudah terdaftar</td>
<td>SRS 2.2.7 Login calon pelanggan</td>
<td>STD 1.0</td>
<td>Sistem</td>
<td>Black Box</td>
<td>Wulan</td>
</tr>
<tr>
<td>Email dan password yang di inputkan belum terdaftar</td>
<td>SRS 2.2.7 Login calon pelanggan</td>
<td>STD 1.1</td>
<td>Sistem</td>
<td>Black Box</td>
<td>Wulan</td>
</tr>
<tr>
<td>Kolom Email dan password kosong</td>
<td>SRS 2.2.7 Login calon pelanggan</td>
<td>STD 1.2</td>
<td>Sistem</td>
<td>Black Box</td>
<td>Wulan</td>
</tr>
	<tr>
	<td rowspan="3" align="center"><strong>Konfirmasi Pembayaran Mobile</td>
	<td>Mengkonfirmasi Pembayaran sudah benar</td>
	<td>SRS 2.2.3  Konfirmasi Pembayaran</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
	</tr>
<tr>
	<td>Mengkonfirmasi Pembayaran belum benar</td>
	<td>SRS 2.2.3 Konfirmasi Pembayaran</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
</tr>
<tr>
	<td>Mengkonfirmasi Pembayaran Kosong</td>
	<td>SRS 2.2.3 Konfirmasi Pembayaran</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Pemesanan Lapangan Futsal Mobile</td>
	<td>Pelanggan memesan lapangan sudah benar</td>
	<td>SRS 2.2.9 Memesan lapangan</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
<tr>
	<td>Pelanggan memesan lapangan belum benar</td>
	<td>SRS 2.2.9 Memesan lapangan </td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>STD 1.1</td>
	<td>Eko</td>
</tr>
<tr>
	<td>Pemesanan lapangan futsal Kosong</td>
	<td>SRS 2.2.9 Memesan lapangan</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Eko</td>
</tr>
<tr>
	<td rowspan="3" align="center"><strong>Mengirim bukti pembayaran Mobile</td>
	<td>Mengunggah gambar  bukti pembayaran sudah benar</td>
	<td>SRS 2.2.11 Mengirim bukti pembayaran</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
<tr>
	<td>Mengunggah gambar bukti pembayaran belum benar </td>
	<td>SRS 2.2.11 Mengirim bukti pembayaran</td>
	<td>STD 1.1</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
</tr>
<tr>
	<td>Bukti pembayaran kosong</td>
	<td>SRS 2.2.11 Mengirim bukti pembayaran</td>
	<td>STD 1.2</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Tuti</td>
</tr>




</thead>  
</table>

## BAB 4. DESKRIPSI DAN HASIL UJI

<table>  
	<thead> 
	4.1 Login Customer Android <br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Customer dengan data user-id dan password benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengecek apakah user sudah </td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Ketikkan email dan password</li>
					<li>2.Tekan button login</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>email : wulandiani04@gmail.com</li>
					<li>password : wulandiani</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>customer berhasil masuk ke aplikasi dengan akun yang benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>button login dapat di-klik jika field email dan password sudah terisi</li>
					<li>jika field belum di isi kemudian menekan button login maka sistem akan menampilkan peringatan "kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
	4.2 Login Admin Benar<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Admin menggunkan username dan password</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi login berfungsi dengan benar </td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses halaman login</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">18 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Mengakses halaman login</li>
					<li>2.Menginputkan username dan password</li>
					<li>2.Kemudian tekan tombol login</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>username : admin</li>
					<li>password : admin123</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin berhasil masuk ke aplikasi dengan akun yang benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Jika username dan password yang dimasukan salah tidak sesuai yang terdaftar di database maka terdapat peringatan username dan password salah</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
	4.3 Login Admin Salah<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Admin menggunkan username dan password yang salah</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi login berfungsi dengan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses halaman login</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">18 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Mengakses halaman login</li>
					<li>2.Menginputkan username dan password</li>
					<li>2.Kemudian tekan tombol login</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>username : asd</li>
					<li>password : asd</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin tidak bisa masuk ke sistem</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Jika username dan password yang dimasukan salah tidak sesuai yang terdaftar di database maka terdapat peringatan username dan password salah sehingga tidak bisa masuk ke sistem</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Gagal</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
	4.4 Input data lapangan benar<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tambah data lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi tambah data lapangan berfungsi dengan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses input data lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">18 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Masuk ke form input lapangan</li>
					<li>2.Menginputkan data lapangan</li>
					<li>3.Kemudian tekan tombol upload</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Nama Lapangan : Lapangan A</li>
					<li>Harga Sewa : 80000</li>
					<li>Keterangan : Baik</li>
					<li>Jumlah : 2</li>
					<li>Upload gambar  lapangan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data lapangan tersimpan ke database</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Jika data lapangan yang diinputkan berhasil maka langsung reload  ke daftar lapangan keseluruhan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
	4.5 Input data lapangan salah<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengujian kesalahan input data lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi kesalahan jika tidak terdapat gambar yang diupload </td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses form input data lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">18 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Masuk ke form input lapangan</li>
					<li>2.Menginputkan data lapangan</li>
					<li>3.Upload gambar dikosongkan</li>
					<li>4.Kemudian tekan tombol upload</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Nama Lapangan : Lapangan A</li>
					<li>Harga Sewa : 80000</li>
					<li>Keterangan : Baik</li>
					<li>Jumlah : 2</li>
					<li>Upload gambar  lapangan kosong</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data tidak tersimpan ke database</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Jika gambar lapangan kosong maka terdapat peringatan kamu belum memilih gambar untuk diupload</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Gagal</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
	4.6 Hapus data lapangan<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengujian fungsi hapus lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi hapus berfungsi dengan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses data lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">18 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Masuk data lapangan</li>
					<li>2.Menekan tombol hapus</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Menekan tombol hapus</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data lapangan dapat dihapus</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Setelah data lapangan terhapu maka daftar lapangan berkurang </li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Gagal</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
	4.7 Edit data lapangan<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengujian fungsi edit lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi edit lapanganberfungsi dengan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses data lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">18 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Masuk data lapangan</li>
					<li>2.Menekan tombol edit</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>1.Menekan tombol edit</li>
					<li>2.Masuk ke form edit lapangan</li>
					<li>3.Memilih data lapangan yang diupdate</li>
					<li>4.Menekan tombol simpan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data lapangan dapat diedit</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Setelah data lapangan diedit maka langsung direload ke daftar lapangan </li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
	4.8 Daftar Pemesanan Lapangan<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Pengujian fungsi Daftar Pemesanan lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi Daftar lapangan berfungsi dengan benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses daftar lapangan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Masuk daftar lapangan</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>1.Menekan tombol daftar lapangan</li>
					<li>3.Memilih daftar lapangan yang diupdate</li>
					<li>4.Menekan tombol simpan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Data daftar lapangan dapat di CRUD</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Setelah data lapangan di CRUD maka langsung muncul pembaruan daftar lapangan yang sudah memesan lapangan atau yang sudah selesai memesan lapangan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>
<table>  
	<thead> 
	4.9 Transaksi Pembayaran Benar<br><br>
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">-------</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Admin mengecek halaman bukti transaksi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">Apakah fungsi Transaksi berfungsi dengan benar </td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">Admin mengakses halaman Transaksi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 Mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Eko Prastyo</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Mengakses halaman Transaksi</li>
					<li>2.Mengecek Bukti Transaksi</li>
					<li>2.Kemudian tekan tombol Konfirmasi</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>Konfirmasi Transaksi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Admin berhasil untuk mengkonfirmasi Transaksi untuk pemesanan yang di lakukan oleh pelanggan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Jika bukti tidak di upload maka pemesanan lapangan dibatalkan</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>------</li>
					<li>------</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>
