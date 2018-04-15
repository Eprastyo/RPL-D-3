<div align ="justify">
	
<div align ="center">
	
<b>SOFTWARE DESIGN DOCUMENT (SDD)</b>

Versi 1.0

10 Maret 2018

<br>
<br>

![logo](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/POLINDRA.png)

<br>
<br>

Disusun Oleh: 

Eko Prastyo 			(1603096)<br>
Syahrul Gunawan 		(1603113)<br>
Tuti Nurafni Amalia		(1603116)<br>
Wulan Diani			(1603118)<br>

<br>
<br>
<br>

<b>Aplikasi Pemesanan Lapangan Futsal "SsaL"</b>
<b>JURUSAN TEKNIK INFORMATIKA<br>
POLITEKNIK NEGRI INDRAMAYU <br>
</b>

</div>

<br>
<br>
<br>
<br>
<br>


<div align="center">
<b>BAB 1 PENDAHULUAN</b>
</div>	    
	    
**1.1 Tujuan**
 
Tujuan pembuatan SDD(Software Design Description) ini adalah untuk menjelaskan langkah-langkah design dan proses-proses dalam pembuatan sistem aplikasi "Pemesanan Lapangangan Futsal " yang disebut dengan nama S'SAL, dan juga memberikan definisi untuk sistem , spesifikasi kebutuhan fungsional. Fungsi utama dari S'SAL ini adalah pemesanan lapangan futsal secara online berbasis android untuk pengguna dan pemilik, serta berbasis web untuk admin dan juga dapat mengetahui informasi lapangan kosong, serta transaksi pemesanan lapangan futsal. <br> 
Aplikasi ini digunakan untuk kalangan kaum umum untuk pemesanan dan penjadwalan penggunaan lapangan futsal, serta dapat memberikan informasi pemesanan lapangan dan penjadwalan futsal. dan mempermudah pelangganuntuk pemesanan lapangan futsal.

**1.2  Lingkup proyek**

Hasil dari SDD ini adalah aplikasi yang berbasis web dan android , yang digunakan untuk membantu pemesanan lapangan futsal di sebuah tempat futsal "Satria Shinta" dalam hal : 
<ul>
	<li> mencatat lapangan yang kosong</li>
	<li> pengguna melihat lapangan yang kosong </li>
	<li> pengguna memesan lapangan yang kosong </li>
	<li> pengguna dapat mengupload bukti konfirmasi pembayaran</li>
	<li> pengguna dapat mencetak bukti pemesanan </li>
	<li> mencatat transaksi pemesanan lapangan oleh admin(DP)</li>
	<li> mengkonfirmasi pembayaran oleh admin</li>
	<li> membuat laporan harian oleh admin</li>
	<li> pemilik dapat melihat laporan harian </li>
</ul>

**1.3  Definsi,akronim,singkatan**

| Istilah | Arti                                             |
| ------- | ------------------------------------------------ |
| SDD     | *Software Design Document*                       |
| SBB     | sebagai berikut	                             |
| DP      | Down Payment (uang muka)                         |
| S'SAL   | Satria Shintia futsal			     |
| IEEE    | Institute of Electrical and Electronics Engineer |
| CI       | Code Igniter				     |
| IEEE    | Institute of Electrical and Electronics Engineer |

**1.4 Referensi**

[1]IEEE Software Engineering Standards Committee, IEEE Std 830-1998, IEEERecommended
[2]https://en.wikipedia.org/wiki/SDD<br>
[3]https://yohanesgunawan.files.wordpress.com/2007/10/sdd-aeromodeling-store_final.pdf


**1.5 Ikhtisar Dokumen**

Penulisan dokumen ini dibagi menjadi beberapa bab sbb : 

<ul>
	<li> Bab 1, adalah pendahuluan yang menjelaskan mengenai tujuan perangkat lunak, ruang lingkup, definisi, referensi serta ikhtiar dokumen </li>
	<li> Bab 2, adalah Deskripsi perancangan global, yang bersisi tengtang rancangan lingkungan iplementasi, deskripsi data dan deskripsi modul.</li>
	<li> Bab 3, adalah Deskripsi perancangan rinci, yang berisi tentang Diagram konteks, Deskripsi rinci tabel, Deskripsi rinci modul, dan matriks kerunutan.</li>
</ul>


<div align="center">
<b>BAB 2 Deskripsi Perancangan Global </b>
</div>
<br>

**2.1 Rancangan Lingkungan Implementasi**
pada proses pembuatan aplikasi ini , hal-hal yang mendukung dalam pemrosesan pembuatan aplikasi seperti sistem operasi yang digunakan untuk membuat aplikasi SSAL ini adalah : 

<ul>
	<li> Pada Admin yang berbasis Web menggunakan PHP, HTML, Framework model code igninter (CI) , Bootstrap dan CSS sebagai pendukung pembuatan design  </li>
	<li> pada pengguna dan pemilik dalam pembuatannya menggunakan android studio , DBMS yang di gunakan adalah firebase </li>
	<li> sublime </li>
</ul>
	
**2.2 Deskripsi Data**
![enter image description here](https://lh3.googleusercontent.com/-Mj1A3Gw089w/WsXPzyQ7gVI/AAAAAAAAA20/vf53InwHcQ8hWyb-U82-7oAjusPt6GXEwCL0BGAs/w530-d-h372-n-rw/ERD.png)  
<br>  
Pembayaran  
<html>  
<table>  
<tr>  
<th>Data item</th>  
<th>Type</th>  
<th>Deskripsi</th>  
</tr>  
<tr>  
<td>id_pembayaran</td>  
<td>Integer</td>  
<td>Nomor id pembayaran</td>  
</tr>  
<tr>  
<td>id_pemesanan</td>  
<td>Integer</td>  
<td>Nomor id pemesanan</td>  
</tr>  
<tr>  
<tr>  
<td>bukti pembayaran</td>  
<td>Integer</td>  
<td>gambar bukti pembayaran</td>  
</tr>  
<tr>  
<td>status</td>  
<td>Varchar</td>  
<td>Status Pembayaran</td>  
</tr>  
<tr>  
<td>no_rekening</td>  
<td>Integer</td>  
<td>Nomer rekening pembayaran</td>  
</tr>  
<tr>  
<td>ke_rekening</td>  
<td>Varchar</td>  
<td>keterangan</td>  
</tr>  
<tr>  
<td>total_bayar</td>  
<td>Integer</td>  
<td>Jumlah pembayaran</td>  
</tr>  
</table>  
</html>  
  
Jam  
  
<html>  
<table>  
<tr>  
<th>Data item</th>  
<th>Type</th>  
<th>Deskripsi</th>  
</tr>  
<tr>  
<td>id_jam</td>  
<td>Integer</td>  
<td>Jam pemesanan</td>  
</tr>  
<tr>  
<td>mulai</td>  
<td>Varchar</td>  
<td>keterangan waktu</td>  
</tr>  
<tr>  
<td>selesai</td>  
<td>Varchar</td>  
<td>keterangangan waktu selesai</td>  
</tr>  
</table>  
</html>  
  
  
Member  
  
<html>  
<table>  
<tr>  
<th>Data item</th>  
<th>Type</th>  
<th>Deskripsi</th>  
</tr>  
<tr>  
<td>id_member</td>  
<td>Integer</td>  
<td>Nomor id anggota</td>  
</tr>  
<tr>  
<td>username</td>  
<td>Varchar</td>  
<td>Username pengguna</td>  
</tr>  
<tr>  
<td>Password</td>  
<td>Varchar</td>  
<td>Password pengguna</td>  
</tr>  
<tr>  
<td>level</td>  
<td>Varchar</td>  
<td>Admin</td>  
</tr>  
<tr>  
<td>Alamat</td>  
<td>Varchar</td>  
<td>Alamat pengguna</td>  
</tr>  
<tr>  
<td>telepon</td>  
<td>Integer</td>  
<td>Nomor telepon pengguna</td>  
</tr>  
</tr>  
</table>  
</html>  
  
  
  
Lapangan  
<html>  
<table>  
<tr>  
<th>Data item</th>  
<th>Type</th>  
<th>Deskripsi</th>  
</tr>  
<tr>  
<td>id_lapangan</td>  
<td>Integer</td>  
<td>Nomor id lapangan</td>  
</tr>  
<tr>  
<td>nama</td>  
<td>Varchar</td>  
<td>Nama</td>  
</tr>  
<tr>  
<td>harga_sewa</td>  
<td>Integer</td>  
<td>Harga sewa lapangan</td>  
</tr>  
<tr>  
<td>keterangan</td>  
<td>Varchar</td>  
<td>Keterangan</td>  
</tr>  
<tr>  
<td>gambar</td>  
<td>Image</td>  
<td>Gambar lapangan</td>  
</tr>  
</tr>  
</table>  
</html>  
  
Pemesanan  
<html>  
<table>  
<tr>  
<th>Data item</th>  
<th>Type</th>  
<th>Deskripsi</th>  
</tr>  
<tr>  
<td>id_pemesanan</td>  
<td>Integer</td>  
<td>Nomor id pemesanan</td>  
</tr>  
<tr><tr>  
<td>id_member</td>  
<td>Integer</td>  
<td>Nomor id pelanggan</td>  
</tr>  
<tr><tr>  
<td>id_lapangan</td>  
<td>Integer</td>  
<td>Nomor id lapangan</td>  
</tr>  
<td>Tanggal</td>  
<td>Integer</td>  
<td>Tanggal pemesanan</td>  
</tr>  
<tr>  
<tr>  
<td>id_jam</td>  
<td>Integer</td>  
<td>Waktu pemesanan</td>  
</tr>  
</table>  
</html>

***2.2.1 Definisi Domain/type***

***2.2.2 Conceptual Data Model***

***2.2.3 Physical Data Model***

***2.2.4 Daftar tabel Aplikasi***

**2.3 Deskripsi Modul**


<div align="center"> 
<b>BAB 3 DFD</b>
</div>
<br>

**3.1 Diagram konteks**<br>
![enter image](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/DFD%20CONTEX.PNG)

***3.1.1 DFD level 0*** <br>
![enter image](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/DFD%20LEVEL%200.PNG)

****3.1.1.1 DFD Level 1 Proses Mengelola Data Member****<br>
![enter image](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/DFD%20LEVEL%201%20MEMBER.PNG)
<br>
****3.1.1.2 DFD level 1 Proses Mengelola Data Pemesanan <br>****
![enter image]https://github.com/Eprastyo/RPL-D-3/blob/master/Gambar/DFD%20LEVEL%201%20PEMESANAN.PNG()
<br>



****3.1.1.3 DFD Level 1 Proses Mengelola Data Pembayaran****<br>
![enter image](https://github.com/Eprastyo/RPL-D-3/blob/master/Gambar/DFD%20LEVEL%201%20PEMBAYARAN.PNG)
<br>

****3.1.1.2 DFD level 1 Proses Mengelola Data Lapangan <br>****
![enter image](https://github.com/Eprastyo/RPL-D-3/blob/master/Gambar/DFD%20LEVEL%201%20LAPANGAN.PNG)
<br> 
**3.2 Deskripsi Rinci Tabel**

***3.2.1 Tabel A***

***3.2.2 Tabel B***

**3.3 Deskripsi Rinci Modul**

***3.3.1 "Modul"***

****3.3.1.1 Fungsi modul****

****3.3.1.2 Spesifikasi Layar Utama****

****3.3.1.3 Spesifikasi Query (jika ada)****

****3.3.1.4 Spesifikasi Field Data Layar****

****3.3.1.5 Spesifikasi Obyek Pada layer****

****3.3.1.6 Spesifikasi Proses/Algoritma****

***3.3.2 "Modul"***

**3.4 Matriks Kerunutan**

</div>
