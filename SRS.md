<div align="center">
SOFTWARE REQUIREMENTS SPESIFICATION<br>
<br>
Version 1.0
<br>
<br>
7 Maret 2018
<br>
<br>

![enter image description here](https://lh3.googleusercontent.com/f5f0-BxI6LDzD6bvooQXbVf8_EN2BxwaRxZdRM5CdSzp5OL9bh1lqaNDw8wCkIAYtjYvHENJuuo5=s300 "img01")


Disusun oleh :


Eko Prastyo (1603096)<br>
Syahrul Gunaawan (1603113)<br>
Tuti Nurafni Amalia (1603116)<br>
Wulandiani (1603118)

JURUSAN TEKNIK INFORMATIKA <br>
POLITEKNIKNEGERI INDRAMAYU 2018<br>
</div>
<br>
<br>
<br>
<div align="center">
BAB 1<br>
PENDAHULUAN
</div>
1.1 Tujuan

DokumenSoftware Requirement Specification (SRS) merupakan dokumen spesifikasiperangkat lunak untuk membangun ”Aplikasi Pemesanan Lapangan Futsal ”. Dokumenini dibangun untuk memudahkan Prima Fusal dan Sintia Sinta Futsal .Dalam melakukan proses pemesanan lapanganfutsal yang dilakukan oleh penyewa lapangan. Sehingga dokumen ini dapatdijadikan acuan teknis untuk membangun perangkat lunak "Let's Ball" AplikasiPemesanan Lapangan Futsal.

1.2 Lingkup proyek

Lets'sBall merupakan aplikasi yang kita untuk pengguna bagi kalangan kaum umum untukpemesanan dan penjadwalan penggunaan lapangan futsal, serta dapat memberikaninformasi pemesanan lapangan dan penjadwalan futsal. dan mempermudah pelangganuntuk pemesanan lapangan futsal.

1.3 Definsi,akronim,singkatan

| Istilah | Arti                                             |
| ------- | ------------------------------------------------ |
| SRS     | *Software  Requirement Specifications*           |
| IEEE    | Institute of Electrical and Electronics Engineer |

1.4 Referensi

\[1\]IEEE Software Engineering Standards Committee, “IEEE Std 830-1998, IEEERecommended

Practicefor Software Requirements Specifications”, October 20, 1998.

\[2\]Feldt R,”re\_lecture5b\_100914”, unpublished.

BAB 2

GAMBARAN UMUM

Aplikasipemesana lapangan futsal membantu user atau calon pelanggan untuk memesanlapangan

2.1 Perspektif Produk

Produk ini memiliki fungsi pemesanan lapangan futsal melalui_mobile apps_. Penggunaan sistemterbagi menjadi dua yaitu antar muka pelaggan menggunakan _mobile apps \*dan antarmuka admi menggunakan \*web apps_.Dibandingkan dengan aplikasi yang sudah ada sebagian besarberbasis website disamping itu belum ada aplikasi yang bernar-benar digunakan.Kemudian aplikasi memiliki keunggulan bisa mencatat transaksi pemesananlapangan untuk pemilik usaha futsal. Selain itu aplikasi ini sebagai promosipemilik futsal untuk meningkatkan pendapatan usahanya.

2.1.1 Antarmuka sistem

![img9](https://lh3.googleusercontent.com/-ZHr32IgPcuc/Wp_HunwALqI/AAAAAAAAARE/0XQbDM7HrC4hppc7lRaCL5cYhV9lU7k6wCL0BGAs/w530-d-h187-n-rw/Antarmuka+Sistem.png)

Bagian sistem aplikasi untuk sisiuser menggunakan *mobile apps* yang bisa menampilkan menu daftar dan loginsebagai autentifikasi awal masuk ke sistem, kemudian bisa menampilkan formpemesanan lapangan kepada calon pelanggan, selanjutnya sistem mampu menampilkandaftar lapangan yang tersedia dan belum dipesan atau kosong. Disamping itusistem memliki fitur tampilan bukti pemesanan yang dapat dicetak oleh calonpelanggan kemudian mampu mengirim bukti pembayaran ke server.

Bagian sistem aplikasi untuk sisiadmin menggunakan _web apps_. Sistem mampumenampilkan tampilan login admin. Kemudian menampilkan fitur menipulasi datalapangan dan tarif, kemudian memiliki fitur menampilkan konfirmasi pembayaran,selanjutnya sistem mampu menampilkan daftar pelanggan yang memesan. Disampingitu sistem melakukan transaksi pemesanan lapangan.

2.1.2 Antarmuka pengguna

![img8](https://lh3.googleusercontent.com/-82R76oif8eA/Wp9qnbhVVBI/AAAAAAAAANc/OMISVh_uyfskuiNxZTuE5dJxkbBatYItwCL0BGAs/w414-d-h736-n-rw/daftar.jpg)

Gambar 2.1 Daftar user

​ Menudaftar user menggunakan form tampilan text edit,password dan button menggunakanwarna merah dan memiliki latar belakang orang menendang bola ,kemudian terdapatlink login berwaran biru.

![img7](https://lh3.googleusercontent.com/-Yzb95U1nufc/Wp9qkgZTegI/AAAAAAAAANQ/q_fNGhPBNKADYXes5v9yuh2b5aY55aJ0gCL0BGAs/w414-d-h736-n-rw/login.jpg)

Gambar 2.2 Tampilan login

​ Tampilanlogin terdapat text edit email dan password dilengkapi icon email dan kunci. Disisiatas terdapat header berwarna merah dengan tulisan berwarna putih. Disisi bawahterdapat button login,link lupa password,dan link register.

![img6](https://lh3.googleusercontent.com/-PIzm7F4EZyE/Wp9qhuFa51I/AAAAAAAAANE/m33W0qFaQY45VH-yL0cVt_4DfoHG5A3UQCL0BGAs/w414-d-h736-n-rw/menu%2Bawal.jpg)

Gambar 2.3 Menu awal

​ Tampilanmenu awal terdapat header berwarna merah dengan tulisan berwarna putih. Kemudiandibawah header terdapat icon fitur utama berwarna merah.

![img5](https://lh3.googleusercontent.com/-FEWKudkYP9E/Wp9odATlfuI/AAAAAAAAAMQ/qOPc5y4f5FQ5RPAqPxVC15BRyK9w6rsgQCJoC/w414-h736-n-rw/daftar%2Bllapangan.jpg)

Gambar 2.4 Tampilan list lapangan

​ Tampilan list lapangan terdapat header berwarna merah dengan tulisan berwarna putih dandi sisi kiri terdapat icon panah berwarna putih. Kemudian dibawahnya terdapat 3textview dan 2 button.

![img4](https://lh3.googleusercontent.com/-Sf8iaxYabm4/Wp9qqfazAzI/AAAAAAAAANo/zLstdCq4wQ016zSE_Y4PuYPK33z_uN_wACL0BGAs/w414-d-h736-n-rw/daftar%2Bpemesan.jpg)

Gambar 2.5 Tampilan daftar pemesan

​ Tampilandaftar menggunakan data tabel berwarana abu dengan jumlah kolom sebanyak 4 kemudiandisetiap baris divarriasi warna putih dan abu-abu.

2.1.3 Antarmuka perangkat keras

![img3](https://lh3.googleusercontent.com/-oBNUr2ecXmM/Wp9r1nNk8AI/AAAAAAAAAOM/slNzD-hEA8cWXpx9QV7D04ue047uR3DxACJoC/w530-h336-n/Antarmuka+Hardware+-+Antarmuka+Hardware%25281%2529.png)

Antarmuka perangkat keras calon pemesan menggunakandevice \*smartphone \*android untuk bisamemesan pertama kali device harus terhubung ke internet kemudian membukaaplikasi sistem maka terhubung ke server. Kemudiann antarmuka perangkat kerasadmin menggunakan device computer atau laptop dan pastikan terhubung denganinternet selanjutnya buka website sistem admin.

2.1.4 Antarmuka perangkat lunak

Tidak ada antarmuka perangkat lain yang dibutuhkan dalam pengembangan Aplikasi Sistem pemesanan lapangan futsal.

2.1.5 Antarmuka komunikasi

ada antarmuka komunikasi yang dibutuhkan dalam aplikasi ini yaitu antarmuka untuk melakukan koneksi dalam jaringan internet yaitu:

    1.Antarmuka komunikasi pada sisi Server

Sebuah aplikasi web berkomunikasi dengan perangkat lunak client melalui HTTP. HTTP, sebagai protokol yang berbicara menggunakan request dan response menjadikan aplikasi web bergantung kepada siklus ini untuk menghasilkan dokumen yang ingin diakses oleh pengguna. Secara umum, aplikasi web yang akan kita kembangkan harus memiliki satu cara untuk membaca HTTP Request dan mengembalikan HTTP Response ke pengguna.

2.1.6 Operasi-operasi

| Operasi |Fungsi  |
|--------------|-----------------------------------------|
|Register| Digunakan mendaftar pelanggan|
|Login| Digunakan masuk akses aplikasi|
|Booking lapangan| Digunakan memesan lapangan|
|Jadwal lapangan| Melihat lapangan kosong|
|Konfirmasi pembayaran| Mengirim bukti pembayaran|
|Cetak| Digunakan untuk mencetak bukti pemesanan|
|Logout| Keluar aplikasi|
|Edit data lapangan| Mengelola data lapangan|
|Edit tarif | Mengelola data tarif harga lapangan  |
|Lihat pemesan | Melihat daftar pemesan|
|Konfirmasi| Mengonfirmasi pembayaran pelanggan |
|Transaksi| Melakukan pendataan transaksi |

​ Sistem ke calon pelanggan mampu menampilkan menu login untuk autentifikasi pertama danmenampilkan form pendaftaran pelanggan yang belum memiliki akun, selanjutnya menampilkandaftar lapangan yang tersedia, menampilkan form pemesanan lapangan, menampilkanbukti pemesan untuk dicetak, dan mengirim bukti pembayaran lapangan.

​ Sistemke admin menampilkan menu login admin. Kemudian menampilkan fiturr manipulasi datalapangan dan tarif harga, menampilan daftar pelanggan yang memesan lapangan. Kemudianmenampilkan konfirmasi pembayaran dan transaksi.

2.1.7 Kebutuhan-kebutuhan dalam tahapan adaptasi

2.2 Spesifikasi kebutuhan fungsional

​ A. Usecase admin

![img2](https://lh3.googleusercontent.com/-oMzaRahEeOc/Wp9sFFv2HGI/AAAAAAAAAOk/ySSSblqSDlAPgUcRWB5r1jyM16dF9GLdQCL0BGAs/w530-d-h416-n-rw/Use%2BCase%2BMember%2B-%2BUse%2Bcase%2Bdiagram%2Badmin%25281%2529.png)

 B. Usecase calon pelanggan<br>
 ![img1](https://lh3.googleusercontent.com/-uRmM-vI1VvA/Wp9r9D9d9PI/AAAAAAAAAOY/C6hPd-uAw5wF_YrJG_qqST7Xo_qe-qL7ACL0BGAs/w530-d-h433-n-rw/Use%2BCase%2BMember%2B-%2BUse%2Bcase%2Bdiagram%2Bpelanggan%25282%2529.png) 

2.2.1 Usecase pelanggan<br>
Use case: Login
2.3 Spesifikasi kebutuhan Non-Fungsional

2.4 Karakteristik pengguna
	  
|  Kategori Pengguna| Tugas |
|--|--|
| Administrator |  Mengelola data lapangan|
|  |  Mengelola data tarif|
|  |  Melihat daftar pemesan|
|  |  Mengonfirmasi pemesan|
|  |  Cetak transaksi|
| Pelanggan |  Input username dan password|
|  |  Input data pendaftaran|
|  |  Pesan lapangan|
|  |  Konfirmasi pemesan|
|  |  Melihat data lapangan|
|  |  Mencetak bukti pemesanan|

2.5 Batasan-batasan<br>
	Batasan-batasan yang digunakan pada pengembangan perangkat lunak ini 		adalah :
 - Perangkat harus terhubung dengan internet
 - Hanya digunakan di wilayah Kabupaten Indramayu
 
2.6 Asumsi-asumsi keterkaitan

2.7 Kebutuhan penyeimbang

BAB 3

PERSYARATAN KEBUTUHAN

3.1 Persyaratan antarmuka eksternal

	3.1.1 Antarmuka pemakai

Pemilik Futsal dan Pelanggan sebagai user yang dapat mengoperasikan aplikasi sistem informasi pemesanan lapangan futsal dengan menggunakan smartphone yang berupa android.

	3.1.2 Antarmuka perangkat lunak

Aplikasi ini dapat diakses jika terhubung dengan internet dan memiliki OS android.


3.2 Persyaratan Fungsional

	3.2.1 Daftar user
	
| Nama fungsi | Daftar pelanggan |
|--|--|
| Ref | Bag 2.1.2,Daftar pelanggan |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman pendaftaran pelanggan  |
| Basic patch | 1. Pelanggan mengklik fungsi register<br>2. Sistem menampilkan halaman pendaftaran<br>3. Pelanggan memasukan nama lengkap,nama pengguna,email,password,dan no handphone<br>4. Pelanggan mengklik tombol register<br>5. Sistem menyimpan ke database |
| Alternative | Tidak ada |
| Post Condition | Pelanggan dapat daftar kemudian bisa mengakses aplikasi |
| Exception push | Tidak ada koneksi |

	3.2.2 Halaman booking lapangan
	
|Nama fungsi  | Halaman booking lapangan |
|--|--|
|Ref  |Bag 2.1.2,Menu   |
|Trigger | Membuka aplikasi SSAL,user sudah terdaftar |
| Precondition | Halaman pemesanan |
| Basic Path | 1. Pelanggan menekan fitur booking lapangan<br>2. Sistem membuka halaman pemesanan<br>3. Pelanggan memilih lapangan dan waktu main  |
| Alternative | Tidak ada |
| Post Condition | Pelanggan dapat memesan lapangan  |
| Exception push | Halaman pemesanan |<br>

3.3 Struktur detail kebutuhan Non-Fungsional

3.3.1 Logika Struktur Data

![img](https://lh3.googleusercontent.com/-S5Ss0ZEHb-8/Wp_45OtZhlI/AAAAAAAAASA/plSBKH2JflgeUzG5p1dLOxHUg8Na_-_NACL0BGAs/w530-d-h379-n-rw/ERD.png)

3.3.2 Keamanan

PC tempat admin berada akan memiliki keamanan sendiri. Hanya admin yang memiliki akses fisik ke mesin dan program di dalamnya. Tidak ada perlindungan khusus yang ada di dalam sistem ini.
