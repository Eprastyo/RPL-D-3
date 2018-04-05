
<div align="center">
SOFTWARE REQUIREMENTS SPESIFICATION<br>
<br>
Version 1.0
<br>
<br>
7 Maret 2018
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

DokumenSoftware Requirement Specification (SRS) merupakan dokumen spesifikasiperangkat lunak untuk membangun ”Aplikasi Pemesanan Lapangan Futsal ”. Dokumen ini dibangun untuk memudahkan Prima Fusal dan Sintia Sinta Futsal .Dalam melakukan proses pemesanan lapangan futsal yang dilakukan oleh penyewa lapangan. Sehingga dokumen ini dapat di jadikan acuan teknis untuk membangun perangkat lunak "Let's Ball" Aplikasi Pemesanan Lapangan Futsal.

1.2 Lingkup proyek

Ssal merupakan aplikasi yang kita untuk pengguna bagi kalangan kaum umum untukpemesanan dan penjadwalan penggunaan lapangan futsal, serta dapat memberikaninformasi pemesanan lapangan dan penjadwalan futsal. dan mempermudah pelangganuntuk pemesanan lapangan futsal.

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

Aplikasi pemesanan lapangan futsal membantu user atau calon pelanggan untuk memesan lapangan

2.1 Perspektif Produk

Produk ini memiliki fungsi pemesanan lapangan futsal melalui_mobile apps_. Penggunaan sistemterbagi menjadi dua yaitu antar muka pelaggan menggunakan _mobile apps \*dan antarmuka admi menggunakan \*web apps_.Dibandingkan dengan aplikasi yang sudah ada sebagian besarberbasis website disamping itu belum ada aplikasi yang bernar-benar digunakan.Kemudian aplikasi memiliki keunggulan bisa mencatat transaksi pemesananlapangan untuk pemilik usaha futsal. Selain itu aplikasi ini sebagai promosipemilik futsal untuk meningkatkan pendapatan usahanya.

2.1.1 Antarmuka sistem

![img9](https://lh3.googleusercontent.com/-ZHr32IgPcuc/Wp_HunwALqI/AAAAAAAAARE/0XQbDM7HrC4hppc7lRaCL5cYhV9lU7k6wCL0BGAs/w530-d-h187-n-rw/Antarmuka+Sistem.png)
<div align="center">Gambar 2.1 Antarmuka sistem</div><br>
Bagian sistem aplikasi untuk sisiuser menggunakan *mobile apps* yang bisa menampilkan menu daftar dan loginsebagai autentifikasi awal masuk ke sistem, kemudian bisa menampilkan formpemesanan lapangan kepada calon pelanggan, selanjutnya sistem mampu menampilkandaftar lapangan yang tersedia dan belum dipesan atau kosong. Disamping itusistem memliki fitur tampilan bukti pemesanan yang dapat dicetak oleh calonpelanggan kemudian mampu mengirim bukti pembayaran ke server.

Bagian sistem aplikasi untuk sisiadmin menggunakan _web apps_. Sistem mampumenampilkan tampilan login admin. Kemudian menampilkan fitur menipulasi datalapangan dan tarif, kemudian memiliki fitur menampilkan konfirmasi pembayaran,selanjutnya sistem mampu menampilkan daftar pelanggan yang memesan. Disampingitu sistem melakukan transaksi pemesanan lapangan.

2.1.2 Antarmuka pengguna

![img8](https://lh3.googleusercontent.com/-82R76oif8eA/Wp9qnbhVVBI/AAAAAAAAANc/OMISVh_uyfskuiNxZTuE5dJxkbBatYItwCL0BGAs/w414-d-h736-n-rw/daftar.jpg)
<div align="center">Gambar 2.2 Daftar user </div>

![daftar](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/2.%20daftar.PNG)

![login](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/1.%20login.PNG)

![menuutama](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/tampilan%20awal.PNG)

![pemesananlapangan](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/3%20booking.PNG)

![jadwal](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/4%20jadwal.PNG)

![konfirmasipembayaran](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/5%20konfirmasi%20pembayar.PNG)

![biodata](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/6%20biodata.PNG)

![editbiodata](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/7%20edit%20biodata.PNG)

![tentang](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/8.PNG)

![dashbord](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/dashboard.png)

![datapemesanan](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/data%20pemesan.png)

![editdatalapangan](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/edit%20data%20lapangan.png)

![keloladatalapangan](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/kelola%20data%20lapangan.png)

![laporantransaksi](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/Laporan%20transaksi.png)

![login](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/login.png)

![member](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/Member.png)

![transaksi](https://raw.githubusercontent.com/Eprastyo/RPL-D-3/master/Gambar/Transaksi.png)

2.1.3 Antarmuka perangkat keras

![img3](https://lh3.googleusercontent.com/-oBNUr2ecXmM/Wp9r1nNk8AI/AAAAAAAAAOM/slNzD-hEA8cWXpx9QV7D04ue047uR3DxACJoC/w530-h336-n/Antarmuka+Hardware+-+Antarmuka+Hardware%25281%2529.png)
<div align="center">Gambar</div>
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

![enter image description here](https://lh3.googleusercontent.com/-hgIXjw99-WY/WrK3akXSV7I/AAAAAAAAAKE/OWeRuaU9i_kSMU3b8sjcPnpluLW9PfvgACL0BGAs/w530-d-h431-n-rw/Use+Case+Admin.png)

 B. Usecase calon pelanggan<br>
 ![enter image description here](https://lh3.googleusercontent.com/-Vlo5snIVF6Y/WrK8QKFtiAI/AAAAAAAAALk/Msd2KO--qek-wooeuTxpGMHzn3V3doWCQCL0BGAs/w530-d-h441-n-rw/Use+Case+Member.png) 

2.2.1 Login Admin<br>
![enter image description here](https://lh3.googleusercontent.com/-EnMLWKoYQl0/WrK4J-zzCwI/AAAAAAAAAKk/nYA2h1cS9nw8HtUFskunsIL_bpLCjlo1ACL0BGAs/w530-d-h233-n-rw/Login+Admin.png)
<br>Admin bisa login ke aplikasi website dengan cara	:
1. Admin membuka aplikasi website
2. Admin mengisi username dan password
3. Admin mengkllik menu login Xref : bagian 3.2.7 <br>

2.2.2 Mengelola data lapangan<br>
![enter image description here](https://lh3.googleusercontent.com/bmgu-ozN_LOpWdiv3uh4yA2OBe9pjFGvAYxcaTJ8EuOTsMjhpOTXYSeUoju6pCXnJhJf-fzZuAcYi3T_XiE2dJY0FHxYDuVBDlSgaw=w293-h81-rw)
<br>Admin bisa mengelola data lapangan dengan cara	:
1. Admin membuka aplikasi website
2. Admin login aplikasi
3. Admin mengklik menu kelola data lapangan  
4. Admin bisa mengelola data lapangan Xref : bagian 3.2.8 <br>

2.2.3 Konfirmasi pembayaran<br>
![enter image description here](https://lh3.googleusercontent.com/UzCCK0tjwzZmWFpkcqVWYlTKnW5kpZSX_yr9XH2ILMap5ZwgWfX9swbbhqk5F0z6yBCp25GiaVUCs7F896lTbC3oXLorFBUlNKYETQ=w293-h81-rw)
<br>Admin bisa mengonfirmasi pembayaran dengan cara	:
1. Admin membuka aplikasi website
2. Admin login aplikasi
3. Admin mengklik menu kelola data lapangan  
4. Admin mengklik tombol konfirmasi
5. Admin bisa mengonfirmasi pembayaran Xref : bagian 3.2.9 <br>

2.2.4 Menampilkan daftar pemesan<br>
![enter image description here](https://lh3.googleusercontent.com/LhLWsEVJW2MzTCUwnIp__bPb8JBXj_zkS6C-XwhFB1WErNZIRJEfRWPzUz0OT_28YGhFenmwLzyMsoKZSgCvGj61rrPx_o1d-PSrBw=w293-h81-rw)
<br>Admin bisa menampilkan data pemesan dengan cara	:
1. Admin membuka aplikasi website
2. Admin login aplikasi
3. Admin mengklik menu data pemesan  
4. Admin bisa melihat data pemesan Xref : bagian 3.2.10 <br>

2.2.5 Transaksi pembayaran<br>
![enter image description here](https://lh3.googleusercontent.com/Is0OA9n2A_2bs8kg6XWzBb0UOEJVGjr41KpFWKVMw_3DoxpaNgf7PqmrXBsvpgjMEJANVUxJL_JNOV7CIO0ZWSKA3aQ-bMfxU1X78g=w293-h81-rw)
<br>Admin bisa mengonfirmasi pembayaran dengan cara	:
1. Admin membuka aplikasi website
2. Admin login aplikasi
3. Admin mengklik menu transaksi 
4. Admin bisa melakukan transaksi pembayaran Xref : bagian 3.2.11<br>

2.2.6 Pendaftaran Pelanggan<br>
![enter image description here](https://lh3.googleusercontent.com/-PCMeo5YOweQ/WrK9S-K68NI/AAAAAAAAAMM/pCciC5Sbo-ESASmP0R1Mgvfsw8BElijYgCL0BGAs/w530-d-h184-n-rw/pendaftaran+pelanggan.png)
<br>Calon pelanggan bisa mendaftarkan dengan cara	:
1. Calon pelanggan membuka aplikasi android
2. Calon pelanggan mengklik tombol daftar
3. Calon pelanggan mengisi biodata  
4. Calon pelanggan memiliki akun untuk login Xref : bagian 3.2.1 <br>

2.2.7 Login calon pelanggan<br>
![enter image description here](https://lh3.googleusercontent.com/uOOSa-HSXUXUJh9TPIdZrE1UKJ8V-hoEflKkGkevh1wEFdKstaish_5MKX-TjQvgXxu4rYnUxae0bXOqH0kPTaDqGau2faJ3J-8Fww=w530-h220-rw)
<br>Calon pelanggan bisa login dengan cara	:
1. Calon pelanggan membuka aplikasi android
2. Calon pelanggan mengisi username dan password
3. Calon pelanggan mengklik login
4. Calon pelanggan bisa masuk ke aplikasi Xref : bagian 3.2.2 <br>

2.2.8 Menampilkan data lapangan<br>
![enter image description here](https://lh3.googleusercontent.com/fO6gnS82-vAEU5XzKsLiACaIxctDC6EjFlzdxlumH0bEX5_2PGNlIWeHKJusDwQd1lZbL2FkVOfVRsIdJLX4xRbE25j2bq6efhMjLA=w322-h81-rw)
<br>Calon pelanggan bisa melihat lapangan kosong dengan cara	:
1. Calon pelanggan membuka aplikasi android
2. Calon pelanggan login aplikasi
3. Calon pelanggan mengklik menu lihat lapangan  
4. Calon pelanggan bisa melihat daftar lapangan tersedia Xref : bagian 3.2.3 <br>

2.2.9 Memesan lapangan<br>
![enter image description here](https://lh3.googleusercontent.com/K43ityKT7vxL9vIFj0fpkQWDUdDvPvY8dn2AB6ktiw8e0T8F5x4ykDagjO60EOPjmgEFiEtzhMNoJe3-4A-2qQGCDz-GNB-1boLu0A=w322-h81-rw)
<br>Calon pelanggan bisa memesan lapangan dengan cara	:
1. Calon pelanggan membuka aplikasi android
2. Calon pelanggan login aplikasi
3. Calon pelanggan mengklik menu pesan lapangan  
4. Calon pelanggan bisa memesan lapangan Xref : bagian 3.2.4 <br>

2.2.10 Cetak bukti pemesanan<br>
![enter image description here](https://lh3.googleusercontent.com/Y7oyJbpNMsOdoH3f4PczKxNsoSCz_18HCxa9To2xKOOuT8kpSd2cAjjAPsh-BBRY0nJ21BagtsPYA8sndJUwuehN9pCvWkYSczlfxA=w530-h220-rw)
<br>Calon pelanggan bisa cetak bukti pemesanan dengan cara	:
1. Calon pelanggan membuka aplikasi android
2. Calon pelanggan login aplikasi
3. Calon pelanggan mengklik menu cetak bukti pemesanan  
4. Calon pelanggan bisa mengunduh bukti pemesanan Xref : bagian 3.2.5 <br>

2.2.11 Mengirim bukti pembayaran<br>
![enter image description here](https://lh3.googleusercontent.com/skUHZIikDpq4JvMEFNgATyVj--J34qJOyxY6AwmlwX1xbd8mg4-t-k9H63j-8QKTisa1ptvYgr1eX88g3YMlWl4qGGPY7h19CmPrmw=w530-h220-rw)
<br>Calon pelanggan bisa kirim bukti pembayaran dengan cara	:
1. Calon pelanggan membuka aplikasi android
2. Calon pelanggan login aplikasi
3. Calon pelanggan mengklik menu kirim bukti pembayaran  
4. Calon pelanggan upload foto bukti pembayaran Xref : bagian 3.2.6 <br>

2.3 Spesifikasi kebutuhan Non-Fungsional
-   Usability
Kebutuhan yang digunakan dalam aplikasi untuk mempermudah pemakaian. Seperti penggunaan Bootsrap yang digunakan untuk mebuat tampilan aplikasi yang lebih menarik.  
-	Security
Untuk keamanan user dan admin harus login terlebih dahulu sebelum mengakses sistem aplikasi.

2.4 Karakteristik pengguna

|  Kategori Pengguna| Tugas |
|--|--|
| Administrator |  Mengelola data lapangan|
|  |  Melihat daftar pemesan|
|  |  Mengonfirmasi pembayaran|
|  |  Mencetak transaksi pembayaran|
| Pelanggan |  Input data pendaftaran|
|  | Masuk aplikasi |
|  |  Memesan lapangan|
|  |  Melihat data lapangan|
|  |  Mencetak bukti pemesanan|
|  |  Mengirim bukti pembayaran|

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

Aplikasi ini dapat diakses jika terhubung dengan internet dan memiliki sistem operasi android.

3.2 Persyaratan Fungsional

3.2.1 Daftar user
	
| Nama fungsi | Daftar pelanggan |
|--|--|
| Ref | Bag 2.2.6,Daftar user |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman pendaftaran pelanggan  |
| Basic patch | 1. Pelanggan mengklik fungsi register<br>2. Sistem menampilkan halaman pendaftaran<br>3. Pelanggan memasukan nama lengkap,nama pengguna,email,password,dan no handphone<br>4. Pelanggan mengklik tombol register<br>5. Sistem menyimpan ke database |
| Alternative | Tidak ada |
| Post Condition | Pelanggan bisa mendaftarkan akun kemudian bisa mengakses aplikasi |
| Exception push | Tidak ada koneksi |

3.2.2 Menu Login
	
| Nama fungsi | Login pelanggan |
|--|--|
| Ref | Bag 2.2.7,Login |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman login  |
| Basic patch | 1. Pelanggan membuka aplikasi<br>2. Sistem menampilkan halaman login<br>3. Pelanggan mengisi form login<br>4. Pelanggan mengklik tombol login<br>5. Sistem melakukan validasi login<br>6. Jika benar, sistem menampilkan menu utama<br>7. Jika salah kembali menu login   |
| Alternative | Tidak ada |
| Post Condition | Pelanggan bisa masuk ke menu aplikasi |
| Exception push | Tidak ada koneksi |

3.2.3 Menu melihat lapangan

| Nama fungsi | Melihat data lapangan |
|--|--|
| Ref | Bag 2.2.8,Melihat data lapangan |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman lihat data lapangan  |
| Basic patch | 1. Pelanggan membuka aplikasi<br>2. Pelanggan login aplikasi <br>3. Pelanggan megklik menu lihat lapangan <br>4. Sistem menampilkan data lapangan   |
| Alternative | Tidak ada |
| Post Condition | Pelanggan bisa melihat data lapangan |
| Exception push | Tidak ada koneksi |
3.2.4 Menu pemesanan lapangan

| Nama fungsi | Pemesanan lapangan |
|--|--|
| Ref | Bag 2.2.9,Pemesanan lapangan |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman pemesanan lapangan  |
| Basic patch | 1. Pelanggan membuka aplikasi<br>2. Pelanggan login aplikasi <br>3. Pelanggan megklik menu pesan lapangan <br>4. Pelanggan mengisi nama lapangan dan durasi<br>5. Jika benar, sistem menyimpan ke database pemesanan
| Alternative | Tidak ada |
| Post Condition | Pelanggan bisa memesan lapangan |
| Exception push | Tidak ada koneksi |

3.2.5 Menu cetak bukti pemesanan

| Nama fungsi | Mencetak bukti pemesanan  |
|--|--|
| Ref | Bag 2.1.10,Mencetak bukti pemesanan  |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman cetak bukti pemesanan   |
| Basic patch | 1. Pelanggan membuka aplikasi<br>2. Pelanggan login aplikasi <br>3. Pelanggan memilih menu cetak bukti pemesanan <br>4. Sistem menampilkan download bukti pemesanan |
| Alternative | Tidak ada |
| Post Condition | Pelanggan bisa mengunduh bukti pemesanan |
| Exception push | Tidak ada koneksi |
3.2.6 Mengirim bukti pembayaran

| Nama fungsi | Mengirim bukti pembayaran  |
|--|--|
| Ref | Bag 2.2.11,Mengirim bukti pembayaran  |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman kirim bukti pembayaran  |
| Basic patch | 1. Pelanggan membuka aplikasi<br>2. Pelanggan login aplikasi <br>3. Pelanggan mengklik menu kirim bukti pembayaran <br>4. Sistem menampilkan form upload gambar bukti pembayaran |
| Alternative | Tidak ada |
| Post Condition | Pelanggan bisa mengirim bukti pembayaran |
| Exception push | Tidak ada koneksi |

3.2.7 Login Admin

| Nama fungsi | Login Admin  |
|--|--|
| Ref | Bag 2.2.1,Login Admin  |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Halaman login  |
| Basic patch | 1. Admin membuka aplikasi website<br>2. Admin mengisi username dan password <br>3. Admin mengklik tombol login<br>4. Sistem menampilkan halaman dashboard admin |
| Alternative | Tidak ada |
| Post Condition | Admin bisa masuk aplikasi |
| Exception push | Tidak ada koneksi |

3.2.8 Mengelola data lapangan

| Nama fungsi | Mengelola data lapangan  |
|--|--|
| Ref | Bag 2.2.2,Mengelola data lapangan  |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Tampilan kelola data lapangan  |
| Basic patch | 1. Admin membuka aplikasi website<br>2. Login aplikasi<br>3. Admin mengklik kelola data lapangan<br>4. Sistem menampilkan halaman kelola data lapangan |
| Alternative | Tidak ada |
| Post Condition | Admin bisa mengelola data lapangan |
| Exception push | Tidak ada koneksi |

3.2.9 Konfirmasi Pembayaran

| Nama fungsi | Konfirmasi pembayaran  |
|--|--|
| Ref | Bag 2.2.3,Mengonfirmasi pembayaran  |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Tampilan konfirmasi pembayaran  |
| Basic patch | 1. Admin membuka aplikasi website<br>2. Login aplikasi<br>3. Admin mengklik kelola data lapangan<br>4. Admin mengklik tombol konfirmasi |
| Alternative | Tidak ada |
| Post Condition | Admin bisa mengonfirmasi |
| Exception push | Tidak ada koneksi |


3.2.10 Data pemesan

| Nama fungsi | Melihat data pemesan  |
|--|--|
| Ref | Bag 2.2.4,Melihat data pemesan  |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Tampilan data pemesan  |
| Basic patch | 1. Admin membuka aplikasi website<br>2. Login aplikasi<br>3. Admin mengklik data pemesan<br>4. Sistem menampilkan semua data pemesan |
| Alternative | Tidak ada |
| Post Condition | Admin bisa melihat data pemesan lapangan |
| Exception push | Tidak ada koneksi |

3.2.11 Transaksi

| Nama fungsi | Proses transaksi pembayaran  |
|--|--|
| Ref | Bag 2.2.5,Transaksi pembayaran  |
| Trigger | Membuka aplikasi SSAL |
| Precondition | Tampilan kelola data lapangan  |
| Basic patch | 1. Admin membuka aplikasi website<br>2. Login aplikasi<br>3. Admin mengklik kelola data lapangan<br>4. Admin mengklik tombol transaksi |5. Sistem menampilkan hasil transaksi
| Alternative | Tidak ada |
| Post Condition | Admin bisa mengunduh atau mencetak transaksi |
| Exception push | Tidak ada koneksi |

3.3 Struktur detail kebutuhan Non-Fungsional
3.3.1 Logika Struktur Data

![enter image description here](https://lh3.googleusercontent.com/-Qrsxt_SsBG4/WsXN7IHZfmI/AAAAAAAAA18/5TSJ0Bflj28g1uE-v0FpZ7pcYAB5l11EgCL0BGAs/w530-d-h372-n-rw/ERD.png)
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
<tr>
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
<td>Nama lapangan</td>
</tr>
<tr>
<td>harga_sewa</td>
<td>Integer</td>
<td>Harga sewa lapangan</td>
</tr>
<tr>
<td>keterangan</td>
<td>Varchar</td>
<td>Keterangan lapangan</td>
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
<tr>
<td>id_member</td>
<td>Integer</td>
<td>Nomor id pelanggan</td>
</tr>
<tr>
<td>Tanggal</td>
<td>Integer</td>
<td>Tanggal pemesanan</td>
</tr>
<tr>
<tr>
<td>Durasi</td>
<td>Integer</td>
<td>Waktu pemesanan</td>
</tr>
<tr>
<td>bukti_pembayaran</td>
<td>Image</td>
<td>Mencetak bukti pembayaran</td>
</tr>
</table>
</html>

3.3.2 Keamanan

PC tempat admin berada akan memiliki keamanan sendiri. Hanya admin yang memiliki akses fisik ke mesin dan program di dalamnya. Tidak ada perlindungan khusus yang ada di dalam sistem ini.
