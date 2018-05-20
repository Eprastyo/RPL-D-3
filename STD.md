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
• Memory: 2 GB DDR3
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
	<td rowspan="3" align="center"><strong>Login Mobile</td>
	<td>Email dan password yang di inputkan sudah terdaftar</td>
	<td>SRS 2.2.7 Login calon pelanggan</td>
	<td>STD 1.0</td>
	<td>Sistem</td>
	<td>Black Box</td>
	<td>Wulan</td>
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


</thead>  
</table>

## BAB 4. DESKRIPSI DAN HASIL UJI

<table>  
	<thead> 
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

