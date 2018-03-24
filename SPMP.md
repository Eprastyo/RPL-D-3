
<div align="center">
SOFTWARE PROJECT MANAGEMENT PLAN<br>
Version 1.0
 <br>
 <br>
7 Maret 2018
 <br>
 <br>
 
 
![img]( https://lh3.googleusercontent.com/f5f0-BxI6LDzD6bvooQXbVf8_EN2BxwaRxZdRM5CdSzp5OL9bh1lqaNDw8wCkIAYtjYvHENJuuo5=s300 "img01")        

Disusun oleh :


Eko Prastyo (1603096)<br>
Syahrul Gunaawan (1603113)<br>
Tuti Nurafni Amalia (1603116)<br>
Wulandiani (1603118)


JURUSAN TEKNIK INFORMATIKA <br>
POLITEKNIK NEGERI INDRAMAYU 2018<br>
</div>
<br>
<br>
<br>
<div align="center">
<b>BAB 1<br>
PENDAHULUAN</b>
</div>

**1.1 Gambaran Proyek**

Proyek yang sedang kami buat adalah membangun sebuah aplikasi *mobile* pemesanan lapangan Satria Shintia futsal. Dalam rencana pembangunan software,banyak hal yang harus diperhatikan oleh konsumen maupun produsen (programmer) terutama dalam hal pengelolaan waktu dan nilai yang harus dikeluarkan. Adanya kesalahan perhitungan tentu akan memberikan kerugian pada kedua pihak, hal-hal seperti yang harus kita minimalisir. Untuk itu sistem ini dibangun dengan fungsi utama melakukan planing terhadap proyek yang akan dibuat atau dipesan oleh konsumen. Dengan adanya fungsi tersebut, sistem ini dapat merencanakan pembuatan sebuah software dengan baik, dan pasti. Tentunya dalam membangun sistem ini kami butuh sebuah tim yang solid agar dalam proses pembuatannya tidak mengalami banyak kendala, tim kami terdiri dari manager,programmer, sekertaris, dan tester. Dengan struktur tim tersebut, kami bermaksud membagi beberapa tugas sesuai kriteria kemampuan masing-masing, yang nantinya satu sama lain diharapkan dapat bekerja sama dan melengkapi satu sama lain, sehingga dapat membangun sistem yang baik sesuai yang konsumen/pasar butuhkan.

**1.2 Dokumen-dokumen Dalam Proyek**

Saat mengerjakan projek ini, pencatatan kegiatan yang telah dilakukan ditulis didalam log book kelompok, anggota yang telah mengerjakan tugas sesuai projek kegiatannya dicatat dalam log book, selain log book dokumen yang berkaitan dengan projek ini meliputi requirtments, penjadwalan, pembagian tugas, dan referensi-referensi yang berkaitan dengan pembuatan projek kami.

**1.3 Revolusi SPMP**

Dokumen ini bersifat freeware, jadi siapa saja boleh untuk memanfaatkan dokumen ini untuk hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan dalam  pemanfaatan dokumen ini, seperti menjual belikan dokumen ini secara ilegal,atapun mengubah dokumen tanpa dasar yang jelas.

**1.4 Material Acuan**

Materi yang menjadi acuan dalam pembuatan projek ini menggunakan standar ESA, karena menyediakan kerangka kerja yang menggabungkan seluruh spektrum proses siklus hidup perangkat lunak. Dan juga standar ESA untuk membentuk model yang diakui secara internasional dari kehidupan perangkat lunak umum, siklus proses yang dapat direferensikan oleh industri perangkat lunak diseluruh dunia, untuk mempromosikan pemahaman diantara pihak bisnis dengan aplikasi umum serta mengakui proses, kegiatan dan tugas.

ESA *(European Space Agency)* merupakan standard perancangan rekayasa perangkat lunak dengan profesi Rekayasa Perangkat Lunak dan Standarisasi

Dalam Divisi Sistem Perangkat Lunak, Bagian Rekayasa Perangkat Lunak dan Standarisasi bertanggung jawab atas teknologi dan standar rekayasa perangkat lunak.Bagian ini memiliki keahlian dalam metode perangkat lunak, peralatan, arsitektur dan standar. Rekayasa Perangkat Lunak dengan tanggung jawab bagian mencakup seluruh siklus hidup perangkat lunak, dengan penekanan pada fase awal seperti rekayasa ulang sistem perangkat lunak, teknik persyaratan, desain, bahasa pengkodean dan lingkungan kompilator, pembuatan generasi kode dan uji validasi.

Beberapa studi memberikan blok bangunan untuk penggunaan potensial dalam arsitektur generik.Standarisasi perangkat lunak bagian ini sangat terlibat dalam standarisasi perangkat lunak, baik untuk standar ESA internal melalui co-chairmanship BSSC *(Board for Software Standardization andControl)*, dan untuk standar perangkat lunak eksternal - terutama dengan ECSS *(European Cooperation for SpaceStandardization)* dan terkadang dengan ISO. Kemudian Dukungan proyek bagian ini mendukung banyak proyek luar angkasa, termasuk Galileo (segmen ruang dandarat), EGNOS, percobaan gaya berat mikro dan muatan stasiun luar angkasa, ATV,ExoMars, Vega dan Ariane 5.

**1.5 Definisi dan Akronim (singkatan)**

Dalam  penulisan dokumen  pembuatan  projek ini,  ada  beberapa kata  yang mungkin akan sulit dipahami oleh orang awam berikut ini :

Tabel 1.1 Akronim

| Singkatan | Arti kata                   |
| --------- | --------------------------- |
| ESA       | *European Space  Agency*    |
| APK       | *Application  Package File* |
| BSSC      | *Board for Software Standardization andControl* |
| ECSS      | *European Cooperation for SpaceStandardization* |


 

ESA (European SpaceAgency) merupakan standard perancangan rekayasa perangkat lunak dengan profesi Rekayasa Perangkat Lunak,Standarisasi,dan dukungan proyek.

APK *file *adalah aplikasi mentah (bisa disebut *installer*) dari OS Android.

​<div align="center">
<b>BAB 2<br>
​ORGANISASI PROYEK</b>
</div

**2.1 Model Proses**

Dalam kesempatan ini kami menggunakan model V-model untuk membuat aplikasinya     

**2.1.1 Definisi**

Merupakan model pengembangan perangkat lunak yang didasarkan pada hubungan antara setiap fase pengembangan siklus hidup yang tercantum dalam model Watterfall yang merupakan pengembangan perangkat lunak dan fase yang terkait pengujian. Bisa dikatakan model ini merupakan perluasan dari model waterfall. Disebut sebagai perluasan karena tahap-tahapnya mirip dengan yang terdapat dalam model waterfall. Jika dalam model waterfall proses dijalankan secara linear, maka dalam model V proses dilakukan bercabang.

**2.1.2 Kelebihan**

1.*V Model* sangat fleksibel. *V Model* mendukung project tailoring dan penambahan dan pengurangan method dan tool secara dinamik. Akibatnya sangat mudah untuk melakukan tailoring pada V Model agar sesuai dengan suatu proyek tertentu dan sangat mudah untuk menambahkan method dan tool baru atau menghilangkan method dan tool yang dianggap sudah obsolete.

2.*V Model* dikembangkan dan di-maintainoleh publik. Userdari *V Model* berpartisipasi dalam change control boardyang memproses semua change requestterhadap *V Model*.

**2.1.3 Kekurangan**

1.V Model adalah model yang project oriented sehingga hanya bisa digunakan sekalidalam suatu proyek.

2.V Model terlalu fleksibel dalam arti ada beberapa activity dalam V Model yang digambarkan terlalu abstrak sehingga tidak bisa diketahui dengan jelas apa yang termasuk dalam activity tersebut dan apa yang tidak.

**2.1.4 Tujuan**

Untuk pengembangan versi pertambahan software secara cepat. untuk menyelesaikan sistem secara global terlebih dahulu, kemudian untuk feature dari sistem akan dikembangkan kemudian. Sehingga mempercepat dalam pengimplementasian project.

**2.1.5 Cara kerja**

Bentuk spiral memberikan gambaran bahwa makin iteraksinya membesar, maka menunjuk kan makin lengkapnya versi dari perangkat lunak yang digunakan. Selama awal  sirkuit, objektif,  alternatif dan  batasan didefinisikan  serta  resiko diidentifikasi dan dianalisa. Jika analisa resiko menunjukkan ada ketidak pastian terhadap kebutuhan, maka prototyping harus dibuat pada kuadran engineering. Simulasi dan pemodelan lain dapat digunakan untuk mendefinisikan masalah dan memperbaiki kebutuhan.Pelanggan mengevaluasi hasil engineering (kuadran customer evaluation) dan membuat usulan untuk perbaikan. Berdasarkan masukan dari pelanggan, fase berikutnya adalah planning dan analisis resiko. Setelah analisis resiko, selalu diperiksa apakah proyek diteruskan atau tidak, jika resiko terlalu besar, maka proyek dapat dihentikan.

**2.2 Struktur Organisasi**

![img](https://lh3.googleusercontent.com/-1wc-Rxvz5Q4/Wp9k0OL70zI/AAAAAAAAAJg/NQOauosBOwYQpEFvmQuhoU_O9bWhy5h1wCL0BGAs/w530-d-h193-n-rw/struktur%2Borganisasi.png)

**2.3  Batasan dan Antarmuka Organisasi**

Ketua/manager dimana harus mejadi pengawas dari anggotanya bilamana saat anggota lalai dengan tugasnya, Ketua berhak menegur dan bagi anggota tidak berhak melawan jika ditegur, dan untuk Ketua sendiri tidak berhak semena-mena dengan jabatanya. Tester dimana saat programmer melakukan kesalahan dalam mengkoding tester memiliki tanggung jawab untuk mengecek kesalahan koding yang dilakukan programmer.Designer bertugas membuat perancangan *mockup* aplikasi. Sekertaris  dimana  bertanggung jawab  untuk  menyimpan dokumen–dokumen yang diperlukan untuk penggarapan dan ahsil akhir project. Programmer dimana dia bertanggung jawab untuk membuat dan menyempurnakan suatu program. Analis dimana dia bertugas memberikan gambaran project dan alur pengkoding pada programmer. 

**2.4 Lingkup dan Tanggungjawab**

**2.4.1 Penjelasan**

Lingkup dan tanggungjawab ini berisi tugas dari setiap elemen anggota dalam pembuatan proyek RPL ini.

**2.4.2 Manager**

Manager adalah seseorang mempunyai tanggung jawab dan tugas yang besar dalam sebuah tim, tidak hanya terfokus pada hal-hal yang teknis sifatnya. Manager juga harus mampu memajemen tim dengan baik, agar target projek dapat tercapai. Selain itu memberi pengarahan, memonitoring kinerja tim, serta membagi tugas juga bagian tanggung jawab dari seorang manager.

**2.4.3 Programmer**

Dalam hal ini, seorang programer bertugas untuk mengimplementasikan dari sistem yang sudah dirancang didesain. Programmer dituntut dapat menuliskan code program dengan baik, dan efesien. Hal ini dimaksudakan untuk menghindari terjadinya banyak error dalam proses implementasinya.

**2.4.4 Tester**

Dalam proyek ini, tester bertugas untuk melakukan pengecekan terhadap sebuah software/aplikasi. Apakah ada error data bug didalamnya, seorang tester harus teliti dalam melakukan tugasnya, apabila ada error yang dilewatkan, maka konsumen akan dirugikan.

​<div align="center">
<b>BAB 3<br>
​PROSES MANAJERIAL</b>
</div>

**3.1 Tujuan dan Prioritas Manajemen**

**3.1.1 Prioritas Jadwal**

Prioritas jadwal yang dilakukan pada saat ini adalah membuat sistem yang akan dibuat,dokumen   projek, jadwal   kegiatan, struktur pembuatan projek dan organisasi

**3.1.2 Kemampuan (Kualitas dan Reusability)**

Projek yang kami buat saat ini mempunyai kelebihan dalam memanajemen pembuatan proyek,juga berbasis desktop yang membuat konsumen merasa lebih budah dalam interaksinya.

**3.2 Asumsi, Keterkaitan, dan Batasan**

**3.2.1 Asumsi**

Adapun aplikasi yang sejenis aplikasi manajemen berbasis dekstop, projek yang kami buat membutuhkan unit komputer sebagai media penghubungnya.

**3.2.2 Keterkaitan dan Batasan**

Dalam projek yang kami buat adapun beberapa software desktop yang mendukungnya, seperti xampp sebagai perantara mysql database. namun ada batasannya. 

**3.3 Manajemen Resiko**

**3.3.1 Dampak Positif**

A.Resiko          

1.Estimasi biaya dan waktu yang tidak realitis.

2.Mengembangkan sofware yang salah.

B.Penanganan Resiko

1.Membuat timeline yang jelas untuk pembuatan proyek.

2.Membuat berapa biaya etimasi Desain untuk biaya

3.Merekam dan menganalisa project yang akan dibuat. 

**3.4 Mekanisme Monitoring dan Kontroling**

**3.4.1 Monitoring**

Proses monitoring dilakukan secara tim, adapun proses pelaksanaannya dilakukan setiap satu minggu.

**3.4.2 Kontroling**

Sedangkan proses dilaksanakan setiap hari jumat, hal ini dilakukan agar hasil kerja proyek dapat dievaluasi pada hari terakhir kerja.

**3.5 Perencanaan Staff**

​Tabel 3.1 Perencanaan staf

| Tim project     | Job                 |
| --------------- | ------------------- |
| Syahrul Gunawan | Manager             |
| Eko Prastyo     | Programer           |
| Tuti Nurafni Amalia     | Sekertaris |
| Wulan Diani     | Designer |

<div align="center">
<b>BAB 4<br>
​METODE,TOOLS,DAN TEKNIK</b>
</div>

**4.1 Metoda**

Menguunakan Metoda standart UML ( Unified modeling Language ) digunakan untuk mendesain rancangan sistem dari aplikasi 

**4.1.1 Perangkat Keras**

​            1. Laptop

​            2. Perangkat smartphone        

**4.1.2 Perangkat Lunak**

1.Android studio

2.Sublime text

3.Xampp

4.Web browser

Android studio adalah lingkungan pengembangan terpadu

Integrated Development Environment (IDE) untuk pengembangan aplikkasi Android, berdasarkan Intelli J IDEA . Selain merupakan editor kode Intelli J dan alat pengembang yang berdaya guna, Android Studio menawarkan fitur lebih banyak untuk meningkatkan produktivitas  saat membuat aplikasi android , Misalnya :

1.Sistem versi berbasis Gradle yang fleksible 

2.Emulator yang cepat dan kaya fitur

3.Lingkungan yang menyatu untuk pengembangan bagi semua perangkat Android

4.Instant Run untuk mendorong perubahan ke aplikasi yang berjalan tanpa membuatAPK baru

5.Template kode dan integrasi GitHub untuk membuat fitur aplikasi yang sama dan mengimpor kode contoh

6.Alat pengujian dan kerangka kerja yang ekstensif

7.Alat Lint untuk meningkatkan kinerja, kegunaan, kompatibilitas versi, dan masalah-masalah lain

8.Dukungan C++ dan NDK

9.Dukungan bawaan untuk Google Cloud Platform, mempermudah pengintegrasian Google Cloud Messaging dan App Engine

**4.2 Dokumentasi Perangkat Lunak**

​            Dokumentasi perangkat lunak yang digunakan berdasarkan standar internasional dengan merujuk pada ESA, karena telah menyediakan kerangka kerja yang menghubungkan seluruh spektrum siklus hidup perangkat lunak.

**4.3 Fungsi-fungsi Pendukung Proyek**

Kami membutuhkan technical support di bagian desain project. Kami membutuhkan technical support di bagian coding program sebanyak 2 orang. Kami membutuhkan specialist di bagian database sebanyak 1 orang.

<div align="center">
<b>BAB 5<br>
​PAKET PEKERJAAN,JADWAL,DAN BUDGET</b>
</div>

**5.1 Paket pekerjaan**

| Nama             | Jabatan           | Modul                           | Pekerjaan                                            |
| :--------------- | :---------------- | :------------------------------ | :--------------------------------------------------- |
| Eko  Prastyo     | Programer         | Database  lapangan dan tarif    | Membuat  database menggunakan MySQL database         |
|                  |                   | Management  data lapangan admin | CRUD  database data lapangan                         |
|                  |                   | Konfirmasi  pembayaran          | Membuat  fungsi konfirmasi pebayaran calon pelanggan |
|                  |                   | Transaksi                       | Membuat  fungsi transaksi pemesan lapangan           |
|                  |                   | Kirim  bukti pembayaran         | Membuat  fungsi kirim bukti pemesanan                |
| Syahrul  Gunawan | Manager,Programer | Form Login          | Menbuat  fungsi login user                           |
|                  |                   | Data  lapangan kosong           | Membuat  fungsi tampilan data lapangan kosong        |
|                  |                   | Pemesan  lapangan               | Membuat  fungsi booking lapangan                     |
|                  |                   | Cetak  bukti pemesanan          | Membuat  fungsi   Cetak  bukti pemesanan             |
| Tuti Nurafni Amalia | Sekertaris | Form Registrasi           |  Membuat  fungsi register user                           |
| Wulandiani       | Designer          | Mockup                          | Membuat  rancangan tampilan                          |

**5.2 Ketergantungan dan Keterkaitan**

​            Dalam proses pengerjaan proyek yang kami buat ini,keterkaitan dari tugas masing-masing saling membantu agar terbentuknya ketelitian saat mengerjakan dan mendapatkan hasil yang bagus. Berikut adalah perinciaannya.

​Tabel 5.1 Ketergantungan dan Keterkaitan

| Dari    | Tugas untuk | Keterkaitan                                                  |
| ------- | ----------- | ------------------------------------------------------------ |
| Manager | Programer   | Tugas  manager adalah untuk memberi tugas programmer jika  saat mengerjakan projek anggotanya lalai  dengan tugasnya ketua tersebut berhak untuk menegur anggotanya dan yang  Menjadi anggota tidak berhak untuk melawan. |
| Manager | Sekretaris  | Meminta  sekretaris untuk mencatat semua dokumentasi pembuatan poyek |

**5.3 Kebutuhan Sumber Daya**

Tabel 5.2 Kebutuhan Software

| **No.** | **Jenis Software** | **Kebutuhan Software**        |
| :-----: | ------------------ | ---------------------------- |
|    1    | Sistem  Operasi    | Windows  8 or Higher         |
|    2    | Bahasa Pemrograman | Java,HTML,PHP                |
|    3    | Software Pengolah  | Android studio,Sublime  Text |
|    4    | Database Engine    | Xampp                        |

 

​Tabel 5.3 Kebutuhan Hardware

| **No.** | **Jenis  Hardware**  | **Kebutuhan Hardware**     |
| ------- | -------------------- | -------------------------- |
| 1       | Processor            | Minimal  Core i3 or Higher |
| 2       | Memory(RAM)          | Minimal 4 GB or Higher     |
| 3       | Penyimpanan(Hardisk) | 50 GB free space           |
| 4       | Layar(Monitor)       | Resolusi 1240 x 768 colors |
| 5       | Keyboard             | Compatible with Windows    |
| 6       | Mouse                | Compatible with Windows    |

**5.4 Alokasi Budget dan Sumber Daya**

Berikut adalah rincian biaya yang diperlukan untuk pengerjaan proyek kami, dapat dilihat pada tabel dibawah ini.

**5.4.1 Estimasi Biaya Software**

Tabel 5.4 Biaya Software

| **No.** | **Kebutuhan Software**  | **Biaya**       |
| ------- | ------------------- | --------------- |
| 1       | Windows 8 or Higher | Rp. 1.100.000,- |
| 2       | Android Studio      | Rp. 750.000,-   |
| 3       | Sublime Text        | Rp. 500.000,-   |
| 4       | Xampp               | Rp. 500.000,-   |

**5.4.2 Estimasi Biaya Hardware**

Tabel 5.5 Biaya hardware

| **No.** | **Jenis Hardware** | **Kebutuhan Hardware**                              | **Biaya**       |
| ------- | ------------------ | ----------------------------------------------- | --------------- |
| 1       | Komputer           | Minimal  Core i3 or     Higher                  | Rp. 7.000.000,- |
|         |                    | Minimal 2 GB or Higher                          |                 |
|         |                    | 4 GB free space                                 |                 |
|         |                    | Layar (monitor)  Resolusi     1240 x 768 colors | Rp. 1.200.000,- |
|         |                    | Keyboard                                        | Rp. 50.000,-    |
|         |                    | Mouse                                           | Rp. 30.000,-    |

**5.4.2 Estimasi Biaya Pekerja**

| 1    | Manager    | Rp.8000.000  |
| ---- | ---------- | ------------ |
| 2    | Programer  | Rp.6000.000  |
| 3    | Sekretaris | Rp.4.500.000 |

 5.5 Jadwal

Untuk menyelesaikan aplikasi pemesanan lapangan futsal ini diperlukan waktu kurang lebih 4 bulan. Dimana rincian jadwal kerja pembuatan aplikasi ini dapat dilihat pada tabel estimasi kerja berikut:

Tabel 5.6 Jadwal Perbulan

| No | Kegiatan                  | Februari |    |     |    | Maret |    |     |    | April |    |     |    | Mei |    |     |    |
|----|---------------------------|----------|----|-----|----|-------|----|-----|----|-------|----|-----|----|-----|----|-----|----|
|    |                           | I        | II | III | IV | I     | II | III | IV | I     | II | III | IV | I   | II | III | IV |
| 1  | Identifikasi Masalah      | *        | *  | *   |    |       |    |     |    |       |    |     |    |     |    |     |    |
| 2  | Analisis Kebutuhan Sistem |          |    |     | *  | *     | *  |     |    |       |    |     |    |     |    |     |    |
| 3  | Survey                    |          | *  |     |    |       |    |     |    |       |    |     |    |     |    |     |    |
| 4  | Membuat Proyek            |          |    |     | *  | *     | *  | *   | *  | *     | *  | *   |    |     |    |     |    |
| 5  | Uji Aplikasi              |          |    |     |    |       |    |     |    |       |    |     | *  |     |    |     |    |
| 6  | Revisi Aplikasi           |          |    |     |    |       |    |     |    |       |    |     | *  |     |    |     |    |
| 7  | Implementasi Aplikasi     |          |    |     |    |       |    |     |    |       |    |     |    | *   |    |     |    |
| 8  | Penyusunan Laporan        |          |    |     |    |       |    |     |    |       |    |     |    |     | *  |     |    |
| 9  | Presentasi                |          |    |     |    |       |    |     |    |       |    |     |    |     |    | *   |    |
| 10 | Revisi Laporan            |          |    |     |    |       |    |     |    |       |    |     |    |     |    |     | *  |


Tabel 5.7 Jadwal Perminggu

| No | Keterangan                                              | Minggu |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |
|----|---------------------------------------------------------|--------|---|---|---|---|---|---|---|---|----|----|----|----|----|----|----|
|    |                                                         | 1      | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 |
| 1  | Penyusunan proposal dan mencari mitra                   | *      | * |   |   |   |   |   |   |   |    |    |    |    |    |    |    |
| 2  | Perancangan Aplikasi                                    |        |   | * |   |   |   |   |   |   |    |    |    |    |    |    |    |
| 3  | Perancangan Database                                    |        |   | * |   |   |   |   |   |   |    |    |    |    |    |    |    |
| 4  | Membuat model tampilan                                  |        |   |   | * |   |   |   |   |   |    |    |    |    |    |    |    |
| 5  | Menyusun Database                                       |        |   |   |   | * |   |   |   |   |    |    |    |    |    |    |    |
| 6  | Membuat form login                                      |        |   |   |   | * |   |   |   |   |    |    |    |    |    |    |    |
| 7  | Mencoba dihubungkan dengan database dan input pemesanan |        |   |   |   |   | * |   |   |   |    |    |    |    |    |    |    |
| 8  | Membuat form input data pemesan                         |        |   |   |   |   |   | * |   |   |    |    |    |    |    |    |    |
| 9  | Mengecek jumlah pemesan di database                     |        |   |   |   |   |   |   | * |   |    |    |    |    |    |    |    |
| 10 | Membuat tampilan untuk menampilkan jumlah pemesan       |        |   |   |   |   |   |   |   | * |    |    |    |    |    |    |    |
| 11 | Membuat bentuk laporan pemesanan                        |        |   |   |   |   |   |   |   |   | *  |    |    |    |    |    |    |
| 12 | Menambahkan fungsi dapat mencetak laporan pemesanan     |        |   |   |   |   |   |   |   |   |    | *  |    |    |    |    |    |
| 13 | Mencoba keseluruhan fungsi-fungsi aplikasi              |        |   |   |   |   |   |   |   |   |    |    | *  |    |    |    |    |
| 14 | Menambahkan fitur lupa password                         |        |   |   |   |   |   |   |   |   |    |    |    | *  |    |    |    |
| 15 | Menguji kembali fitur-fitur dalam aplikasi              |        |   |   |   |   |   |   |   |   |    |    |    |    | *  |    |    |
| 16 | Memperbaiki Apabila terjadi kesalahan                   |        |   |   |   |   |   |   |   |   |    |    |    |    |    | *  |    |
| 17 | Membuat Laporan                                         |        |   |   |   |   |   |   |   |   |    |    |    |    |    |    | *  |
