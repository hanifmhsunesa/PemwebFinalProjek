			Spesifikasi Kebutuhan Perangkat Lunak
			
					Untuk
			
			Website E-commerce Fashion – Hasaris Store
				Versi 1.0 Disetujui
			
			
					Disusun Oleh: 
   			Ihda Anisa Ulfa (22091397019) 
			
			Hanif Ihsan Alim A. (22091397020) 
			
			Nurissa’idah (22091397030)
			
				D4 Manajemen Informatika
			
			Fakultas Vokasi Universitas Negeri Surabaya


					2022

Daftar Isi
Pengantar	1
Tujuan	1
Konvensi Dokumen	1
Audiens Yang Dituju	1
Lingkup Produk	2
Referensi	2
Deskripsi Keseluruhan	3
Perspektif Produk	3
Fungsi Produk	3
Kelas dan Karakteristik Pengguna	3
Lingkungan Pengembangan	4
Kendala Desain dan Implementasi	4
Dokumentasi Pengguna	4
Asumsi dan Dependensi	5
Persyaratan Antarmuka	6
Antarmuka Pengguna	6
Antarmuka Perangkat Keras	6
Antarmuka Perangkat Lunak	7
Antarmuka Komunikasi	11
Fitur Sistem	11
Deskripsi dan Prioritas	11
Fitur Sistem	11
Persyaratan Fungsional	12
Pers yaratan Fungsional Lainnya	12
Persyaratan Performa	12
Persyaratan Keamanan Pengguna	12
Persyaratan Keamanan Website	13
Atribut Kualitas Perangkat Lunak	13
Proses Bisnis	14
Persyaratan Lainnya	14



Riwayat Perubahan

Nama
Tanggal
Alasan Perubahan
Versi



















Pengantar

Tujuan

Tujuan pembuatan website Fashion Pria dan Wanita ( Hasaris store ) antara lain :
Menghasilkan sebuah website untuk pengguna yang sedang mencari barang kebutuhan fashion Pria dan Wanita dan memudahkan pemilik toko Hasaris untuk memasarkan dan mempromosikan barang toko kebutuhan fashion pria dan wanita.
Menjadikan website ini sebagai salah satu media layanan toko online untuk mempermudah pembeli mendapatkan produk yang dicari.
Dapat memfasilitasi pemilik toko dalam memasarkan dan mempromosikan  produk fashion untuk pria dan wanita, termasuk pakaian sehari-hari, pakaian formal, aksesoris, sepatu, tas, dan lainnya.
Mempermudah dan memperlancar proses transaksi jual beli karena penjual dan pembeli tidak harus bertemu langsung untuk melakukan transaksi.
Menyediakan informasi yang bermanfaat bagi pembeli dalam mencari produk produk yang dibutuhkan. 

Konvensi Dokumen

Website yang akan dikembangkan adalah website untuk e-commerce fashion yang dapat digunakan oleh para kaum pria dan wanita untuk mencari, menemukan, dan membeli barang kebutuhan busana dan aksesoris pria dan wanita secara mudah dan efisien. Hasaris store dapat melakukan hal-hal berikut ini :
Pembeli dapat mencari dan memilih barang.
Pembeli dapat memasukkan produk ke keranjang.
Pembeli dapat mengetahui penilaian produk.
Pembeli dapat melihat data produk.
Pembeli dapat memilih metode pembayaran dengan menghubungi contacts.
Fasilitas login untuk admin dan pembeli.
Admin dapat mengelola produk, data user, dan data transaksi.
Admin dapat mengirim data transaksi kepada pembeli.
Admin dapat menambah dan menghapus user.
Admin dapat melihat detail pesanan pembeli.












Audiens Yang Dituju

Dokumen ini ditujukan untuk pengembang website e-commerce Business-to-Consumer (B2C) Hasaris store. SRS ini, dibagi menjadi beberapa bagian, antara lain :
Pengembang website yang ingin mencari referensi mengenai sistem e- commerce Business-to-Consumer (B2C).
Membantu menambah literatur dalam bidang web development.
Menambah wawasan dan informasi mengenai sistem e-commerce.
Dokumen pengajuan.
1.4.       Lingkup Produk

Cakupan dari website Hasaris store ini terbilang sangat luas. mulai dari fashion baju, celana, sepatu, tas, jaket, aksesoris wanita dan pria. Jika dikelompokkan berdasarkan keseluruhan maka ruang lingkup Hasaris dapat dibagi menjadi :
Baju
Celana
Sepatu
Tas
Aksesoris wanita dan pria
Meskipun cakupan dari website Hasaris store ini cukup luas, namun, dapat membantu toko Hasaris membangun identitas merek yang kuat dan mengaitkannya dengan gaya, kualitas, dan kepercayaan diri dalam berpakaian untuk pria dan wanita. Ini membuat merek menjadi lebih mudah dikenali dan diingat oleh pelanggan.

1.5.       Referensi

Dokumen ini merujuk pada hasil observasi yang berkaitan dengan kebutuhan dan mencakup data secara umum, diperlukannya dan penulis dokumen berdasarkan pada :
2021. Apa itu E-commerce? Berikut Pengertian, Jenis, serta Manfaatnya!
2018. DOKUMEN SPESIFIKASI KEBUTUHAN PERANGKAT LUNAK DAISY : Aplikasi Pembanding Wedding Organizer.
Widyahardh. Pengertian E – Commerce
2014. DOKUMEN SPESIFIKASI KEBUTUHAN PERANGKAT LUNAK : Taking Order Application for Sales (TOAS) untuk PT Fashion Eservice Indonesia. Universitas Negeri Malang.
	2012. Seminar Nasional Teknologi Informasi & Komunikasi Terapan 2012 	(Semantik 2012) : DOKUMENTASI SEBAGAI BAGIAN DARI 		PERANGKAT LUNAK 

Deskripsi Keseluruhan

Perspektif Produk

Sudah banyak website sejenis ini akan tetapi Hasaris store memiliki banyak penunjang di dalamnya seperti peningkatan keamanan bagi penggunanya, responsif terhadap berbagai perangkat, waktu muat yang cepat dan kinerja yang lancar, Desain visual dan estetika website yang menarik dan mencerminkan merek Hasaris store serta tampilan yang memudahkan para penggunanya. Website lain tidak memiliki keunggulan seperti yang dimiliki oleh Hasaris store ini, dimana website lain kebanyakan tampilannya membosankan dan tidak user friendly. koleksi produk hasaris store sangat beragam dan selaras dengan tren fashion terkini. Maka dari itu website Hasaris store ini dibuat agar dapat menciptakan suasana baru untuk website jual beli barang fashion serta pelanggan toko Hasaris.

Fungsi Produk

Seperti yang sudah dijelaskan sebelumnya banyak bisnis yang tidak hanya bergantung pada website E-commerce besar di Indonesia. Para penjual juga membutuhkan website E-commerce sendiri. Seperti Hasaris store memiliki fungsi utama yaitu menjual dan mempromosikan produk barang Fashion dengan jauh lebih mudah.

Dengan kendali penuh, maka bisnis yang akan dijalankan juga bisa lebih dikenal dan mampu menarik minat konsumen. Website Hasaris store dibuat secara user friendly agar mempermudah dalam meningkatkan pengalaman berkunjung pengguna.

Kelas dan Karakteristik Pengguna

Website Hasaris store memiliki beberapa tingkatan hak akses untuk setiap penggunanya antara lain :
Customer : Hak akses untuk pembeli
Seller / Admin : Hak akses untuk penjual
Karakteristik pengguna :
Customer : Dapat login dan melakukan transaksi jual beli seperti memasukan produk ke keranjang dan melakukan checkout. 
Seller / admin : Dapat mengakses halaman dashboard penjual yang berguna untuk mengupload produk yang ingin dijual dan melihat transaksi barang apa saja yang sudah di checkout customer dan dapat mengontrol semua hak akses pengguna.

Lingkungan Pengembangan

Website Hasaris store memiliki beberapa teknologi yang dipakai untuk mengembangkan website ini, antara lain :
Bahasa Pemrograman
HTML : HyperText Markup Language
Css
Javascript
Software Pengembangan
VSCode : Software Pemrograman

Kendala Desain dan Implementasi

Halangan atau tantangan dari website ini adalah perlu menggunakan jaringan internet 	untuk mengakses website ini, apabila tidak ada jaringan internet maka website ini 
tidak akan bekerja.

Dokumentasi Pengguna

SRS ini dibagi menjadi beberapa bagian, yaitu :
Pendahuluan yang berisi gambaran umum dari seluruh dokumen SRS. Pendahuluan SRS berisikan bagian-bagian berikut:
Tujuan Penulisan Dokumen
Konvensi Dokumen
Pembaca yang Dituju
Lingkup Produk
Referensi
Deskripsi umum perangkat lunak yang berisi penjelasan perangkat lunak secara umum. Dijelaskan melalui deskripsi umum sistem, fungsi produk, karakteristik pengguna, batasan, lingkungan operasi.
Kebutuhan Antarmuka Eksternal merincikan deskripsi masukan dan keluaran perangkat
lunak yang dispesifikasikan. Ada berbagai macam antarmuka eksternal, antara lain : antarmuka pengguna, antarmuka perangkat keras, antarmuka perangkat keras,
antarmuka komunikasi.
Fungsi Produk berisi fungsi utama dari perangkat lunak.
Kebutuhan Non Fungsional berisi bagian yang menspesifikasikan ukuran kuantitatif yang harus dipenuhi perangkat lunak.


Asumsi dan Dependensi
Asumsi:
Admin memiliki otoritas penuh dalam pendataan barang dan pengolahan orderan dari customer.
Admin harus mengetahui riset produk dan deskripsinya.
Website ini merupakan website yang bisa di akses dimana saja dan sistem operasi device manapun.
	Dependensi:
Sistem informasi berbasis website ini dapat diakses jika terdapat koneksi internet saja.
Catatan produk akan diantar apabila customer mempersetujui harga ongkir sesuai dengan pihak ketiga yaitu perusahaan jasa pengantaran.
Pembayaran sudah terintegrasi dengan beberapa pihak

Persyaratan Antarmuka

Antarmuka Pengguna

Hasaris Store mengusung konsep desain yang ramah untuk digunakan oleh pengguna. Navigasinya cukup mudah dan pengguna tidak akan kesulitan dalam berpindah halaman. Warna dibuat agar tidak norak dan dibuat agar nyaman dimata.


Antarmuka Perangkat Keras

Adapun antarmuka perangkat keras yang digunakan untuk mengakses website Hasaris store antara lain:
Smartphone : Hardware untuk mengakses situs Hasaris store.
Monitor : Menampilkan halaman website.
Keyboard : Untuk memasukkan input ke website.
Mouse / trackpad : Untuk mempermudah navigasi pengguna.
Hasaris Store mengusung konsep desain yang ramah untuk digunakan oleh pengguna. Navigasinya cukup mudah dan pengguna tidak akan kesulitan dalam berpindah halaman. Warna dibuat agar tidak norak dan dibuat agar nyaman dimata.


Antarmuka Perangkat Lunak
Tampilan Beranda

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/99be7cb2-9354-400d-9c59-3708e7b2c52b)

Tampilan Produk
![tapilan awal producrt](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/144761618/8569cd8e-a7f8-4143-a1b4-cbaf48357ba9)


Tampilan About

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/32af018d-be9c-444b-85c0-8b677a85f004)

Tampilan Contact

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/fc0fed9c-42c8-4d43-b1d6-bdc02c880962)

Tampilan Search

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/e47770c2-19e6-484a-80c3-9376635cb128)

Antarmuka Komunikasi

Website Hasaris store ini membutuhkan laptop atau smartphone yang terhubung ke jaringan internet. TCP/IP digunakan sebagai standar komunikasi data yang dipakai dalam proses tukar menukar data antar perangkat yang terhubung dalam jaringan.
Fitur Sistem

Deskripsi dan Prioritas
Fitur Fitur Menu Beranda
Fitur menu beranda merupakan fitur utama pada Website Hasaris store. Dengan fitur ini, customer dapat melihat beberapa tampilan, seperti rekomendasi produk paling laris dan produk terfavorit. Pada tampilan beranda juga ada beberapa pilihan kategori untuk customer.
Fitur Menu Produk
Fitur menu produk ini bertujuan untuk menampilkan produk-produk barang yang dijual di Hasaris store untuk customer. Pada fitur ini, customer dapat melihat berbagai macam produk barang fashion menarik disertai harga dan deskripsi produk.
Fitur Menu Keranjang 
Fitur menu Keranjang terdapat beberapa produk yang dimasukkan customer ke keranjang beserta detailnya. Jika ingin mengcheckout pesanan dapat mengisi shipping details seperti data diri, kurir, dan pembayaran.
Fitur Menu Checkout 
Fitur Menu Checkout akan menampilkan detail pesanan yang sudah di checkout, status pemesanan
Fitur Menu Login
Fitur menu login merupakan proses customer untuk mendapatkan hak akses.Dengan adanya fitur ini, customer dapat menggunakan hak akses lebih optimal.









Fitur Sistem
Login	: Masuk ke sistem Hasaris store jika sudah mendaftar.
Daftar	: Membuat akun jika belum mempunyai.
Dashboard	: Halaman yang bisa diakses oleh penjual atau admin untuk mengelola produk dan data transaksi.
Keranjang 	: Menambah produk ke keranjang yang nantinya akan dibeli.
Dashboard 	: Halaman yang bisa diakses oleh penjual atau admin untuk mengelola produk dan data transaksi
Tambah produk	: Fitur Admin Hasaris store untuk menambahkan produknya.
Transaksi	: Melihat data transaksi pembeli 
Fitur search 	: Mencari produk yang diinginkan

Persyaratan Fungsional

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/1c4043c6-1c88-4f0c-8478-562ed6a1d4fd)

Persyaratan Fungsional Lainnya

Persyaratan Performa

Persyaratan hardware dan software :
Minimum windows 7 atau lebih
Google chrome atau browser versi terbaru
Akses internet

Persyaratan Keamanan Pengguna

Data diri dan password pengguna terjamin keamanannya karena tidak bisa diakses oleh sembarang orang dan password sudah di enkripsi.
Persyaratan Keamanan Website

Website sudah menggunakan domain.com dan SSL sebagai sertifikasi keamanan website agar tidak mudah diretas oleh pihak yang tidak bertanggung jawab.

Proses Bisnis

Dari banyaknya jenis proses bisnis yang ada, aktivitas transaksi antara penjual dan pembeli merupakan salah satu hal dasar yang harus dipahami.

Pada gambar diatas bisa dilihat bahwa pemilik toko Hasaris store yang ingin menawarkan barang yang dijualnya. Dengan bermodalkan sebuah website penjual dapat memberikan berbagai informasi yang berkaitan dengan produk yang ditawarkan. Sebagai calon pembeli, internet menyediakan akses yang luas dan bebas terhadap apa yang ingin diakses. Dalam Website E-Commerce Hasaris store ini, pemilik toko Hasaris menjadi admin atau seller yang memiliki dan memasarkan produknya. Setelah aktivitas pertukaran informasi dilakukan, proses bisnis selanjutnya adalah melakukan pemesanan produk yang telah disepakati. Kedua pihak yang bertransaksi harus melakukan aktivitas perjanjian tertentu, sehingga proses jual beli dapat dilakukan dengan sah, benar, dan aman.







Didalam proses bisnis ini, ada empat aliran entiti yang harus dikelola dengan baik :
Flow of Goods (Aliran Produk)
Flow of Information (Aliran Informasi)
Flow of Money (Aliran Uang)
Flow of Documents (Aliran Dokumen)

Fitur E-Commerce Hasaris store  harus dapat mensinkronisasikan keempat aliran diatas, sehingga proses transaksi dapat berjalan secara efisien, efektif, dan terkontrol dengan baik.

Persyaratan Keamanan Website

Website sudah menggunakan domain.com dan SSL sebagai sertifikasi keamanan website agar tidak mudah diretas oleh pihak yang tidak bertanggung jawab.



Persyaratan Lainnya

Lampiran A : Glosarium

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/1446f890-ebdb-4712-b787-f46390d9cc16)


Lampiran B : Model Analisis
DFD Level 0

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/4d8ec449-92ae-49d5-a269-7777c8e99d70)

DFD Level 1

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/74af4a65-3245-44be-9949-2933228ecf2f)


Flowchart 

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/bb6281cf-ff4e-450b-810e-5817b3d47327)

UML Activity Diagram Sistem Checkout

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/a5fe43c9-7129-451a-b810-a62b3636cc9d)

UML Activity Diagram Sistem Login

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/8b48bd9e-799f-4d85-b082-2786d824d594)

Use Case Diagram E-Commerce

![image](https://github.com/hanifmhsunesa/PemwebFinalProjek/assets/124480469/99ebb87a-bcef-41c2-a176-8a6511412291)

Lampiran C : Daftar Fitur Yang Akan Ditentukan
Pada lampiran ini berisi mengenai fitur-fitur yang belum ditentukan pada website Hasaris store, antara lain yaitu pembuatan IP agar website Hasaris store agar dapat digunakan pada aplikasi mobile, dan membuat Hasaris store menjadi aplikasi yang dapat digunakan pada android.

PENJELASAN SCRIPT PROGRAM
A. Laman Index

1. HTML

a) head

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/121718997/b67e28a8-84ed-41f5-aa8c-dc0f90d627f2)

1. `<!DOCTYPE html>`: Ini adalah deklarasi dokumen yang mengindikasikan bahwa halaman ini adalah dokumen HTML. Ini adalah elemen wajib yang ditempatkan di bagian atas dokumen HTML.
2. `<html lang="en">`: Ini adalah elemen root dari halaman HTML, yang menyatakan bahwa halaman ini ditulis dalam bahasa Inggris ("en" adalah kode bahasa Inggris). Semua elemen HTML akan berada di dalam elemen `<html>` ini.
3. `<head>`: Ini adalah bagian kepala dari dokumen HTML, yang berisi informasi-informasi terkait dengan halaman web, seperti metadata dan tautan ke berkas eksternal. Semua elemen dalam bagian `<head>` ini tidak akan ditampilkan di halaman web itu sendiri, tetapi digunakan untuk mengatur tampilan dan perilaku halaman.
•	`<meta charset="UTF-8">`: Ini adalah elemen meta yang menentukan pengkodean karakter yang digunakan oleh halaman web. UTF-8 adalah pengkodean karakter yang umum digunakan untuk mendukung berbagai karakter dari berbagai bahasa.
•	`<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ini adalah elemen meta yang mengatur tampilan halaman web di perangkat mobile. Dengan mengatur `viewport`, halaman akan menyesuaikan lebar tampilan dengan lebar perangkat dan mengatur tingkat pembesaran awal (scale) ke 1.0.
•	 `<title>HasarisStore</title>`: Ini adalah judul halaman web yang akan ditampilkan di tab browser. Isi dalam elemen `<title>` adalah "HasarisStore."
•	`<link rel="stylesheet" href="style.css">`: Ini adalah tautan (link) ke berkas eksternal dengan tipe "stylesheet" yang digunakan untuk memuat gaya (CSS) dari berkas "style.css." Ini memungkinkan halaman web untuk mengambil aturan gaya dari berkas eksternal ini, sehingga Anda dapat mengatur tampilan halaman dengan lebih terperinci.
•	`<link href="images/logo-removebg-preview.png" rel="icon">`: Ini adalah tautan ke berkas gambar yang akan digunakan sebagai ikon (favicon) untuk halaman web. Ikon ini akan muncul di tab browser ketika halaman web dibuka.

   
A. Laman login
1. HTML

a) head

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/40287d00-26a3-4af9-a82f-296c66f8540c)

1) "!DOCTYPE html": adalah deklarasi dokumen yang menentukan jenis dokumen HTML yang digunakan (HTML5).
2) (html lang="en"): adalah elemen root (teratas) dari dokumen HTML yang menunjukkan dokumen yang dibuat dalam bahasa Inggris ("en").
3) (head): adalah bagian kepala dokumen HTML yang berisi informasi tentang dokumen, seperti metadata, judul halaman, dan tautan ke file eksternal.
- (meta charset="UTF-8"): mengatur pengkodean karakter dokumen menjadi UTF-8, yang merupakan standar umum untuk pengkodean karakter dalam dokumen web.
- (meta name="viewport" content="width=device-width, initial-scale=1.0"): adalah elemen meta yang mengatur tampilan halaman web agar sesuai dengan lebar perangkat (device-width) dan skala awal (initial-scale) adalah 1.0. Ini penting untuk responsifitas desain web.
- (link rel="stylesheet" href="login.css"): adalah tautan ke file CSS eksternal dengan nama "login.css" yang digunakan untuk mengatur tampilan halaman.
4) "<title>Login</title>": adalah elemen yang menentukan judul halaman web yang akan ditampilkan di tab peramban.

b) body

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/8b0cb72e-d66e-49b5-b8d0-3c810ee2503a)

1) "body": adalah elemen yang berisi konten aktual dari halaman web.
2) (div class="login-container"): adalah div yang berfungsi sebagai wadah untuk seluruh konten login.
3) (div class="login-frame"): adalah div yang digunakan untuk elemen latar belakang dengan efek frame yang mengelilingi elemen-elemen login.
4) (div class="login-content"): adalah div yang berisi konten utama dari halaman login.
5) "h2>Login</h2>": adalah elemen heading level 2 (h2) yang menampilkan teks "Login".
6) (<div class="input-group">): adalah div yang berisi elemen input untuk "Username".
7) (<label for="username">Username</label>): adalah label yang menggambarkan input "Username" dan terkait dengan input tersebut menggunakan atribut for yang sesuai.
8) (input type="text" id="username" name="username" required): adalah elemen input teks dengan atribut type "text" dan atribut name "username". Atribut "required" menunjukkan bahwa input ini wajib diisi.
9) (div class="input-group"): adalah div yang berisi elemen input untuk "Password".
10) (label for="password")Password</label>": adalah label yang menggambarkan input "Password" dan terkait dengan input tersebut menggunakan atribut for yang sesuai.
11) (input type="password" id="password" name="password" required): adalah elemen input sandi dengan atribut type "password". Atribut "required" menunjukkan bahwa input ini wajib diisi.
12) "(a href="product.html" class="register-link")Login</a>": Ini adalah tautan yang mengarah ke "product.html" dengan teks "Login" yang digunakan sebagai tombol login. memiliki kelas "register-link" untuk mengatur gaya tombol.
13) (a href="#" class="register-link")Registrasi</a>": adalah tautan yang memiliki teks "Registrasi" dan juga memiliki kelas "register-link" untuk mengatur gaya tombol.
14) (div class="login-image"): adalah div yang berisi gambar yang digunakan sebagai ilustrasi dalam halaman login.
15) (img src="images/logo-removebg-preview.png" alt="User Image"): adalah elemen gambar yang menampilkan gambar dengan sumber (src) "images/logo-removebg-preview.png" dan teks alternatif (alt) "User Image".
	
2. Css
   
a). body

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/9a656664-64ea-4461-850e-9f83dea8fa05)

1) "font-family: 'Arial', sans-serif;": mengatur jenis font teks menjadi "Arial" atau font sans-serif sebagai font default jika "Arial" tidak tersedia di perangkat.
2) "background: linear-gradient(to right, #ffd6d6, #ffd6d6);": membuat latar belakang memiliki gradien linier dari kiri ke kanan dengan warna awal (#ffd6d6 dan warna akhir #ffd6d6), yang pada dasarnya menghasilkan latar belakang berwarna merah muda.
3) "display: flex;": mengubah perilaku tata letak elemen di dalam body menjadi flex, sehingga elemen-elemen dalam body dapat diatur menggunakan properti flex.
4) "justify-content: center;" dan "align-items: center;": memusatkan elemen-elemen di dalam body baik secara horizontal maupun vertikal, sehingga semua elemen yang ada berada di tengah halaman.
5) "height: 100vh;": Ini mengatur tinggi body (viewport height) menjadi 100% dari tinggi jendela browser, sehingga seluruh halaman akan ditampilkan pada satu layar.
6) "margin: 0;": menghapus margin bawaan yang mungkin ada pada elemen body.

b) .login-container

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/6953a7f0-5648-4b6e-a01a-29df84a74e12)

1) "background-color: #fff;": mengatur warna latar belakang dari kotak login menjadi putih (#fff).
2) "border-radius: 8px;": membentuk sudut kotak login menjadi bentuk yang lebih bulat.
3) "box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);": menambahkan bayangan ke kotak login untuk memberikan efek tiga dimensi.
4) "text-align: center;": mengatur teks di dalam kotak login menjadi berada di tengah.
5) "padding: 20px;": menambahkan jarak antara konten di dalam kotak login dengan batas kotak.
6) "position: relative;": mengatur posisi kotak login sebagai relatif sehingga elemen-elemen lain dapat diatur berdasarkan posisi kotak ini.
7) "display: flex;" dan "align-items: center;": mengatur tata letak elemen-elemen di dalam ".login-container" menggunakan flex.

c) .login-frame:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/c3a2700c-1b77-46a3-8e03-9e764f3f67d4)

1) "position: absolute;": mengatur posisi ".login-frame" sebagai absolut sehingga elemen ini dapat menggantung di atas ".login-container".
2) "top, left, right, bottom": mengatur jarak dari elemen .login-container, yang membuat ".login-frame" terlihat lebih besar dan melebar di luar kotak login.
3) "border: 2px solid white;": membuat garis luar dengan lebar 2px dan warna putih di sekitar kotak login.
4) "border-radius: 10px;": membuat sudut elemen ".login-frame" menjadi bentuk yang lebih bulat.
5) "z-index: -1;" : mengatur elemen ".login-frame" berada pada lapisan di bawah elemen-elemen lain di halaman.

d) .login-content

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/f807c958-ca47-448d-acd0-a7fbfc635eda)

1) "flex: 1;": membuat ".login-content" mengisi sebanyak mungkin ruang yang tersedia dalam ".login-container".
2) "text-align: left;": mengatur teks di dalam ".login-content" menjadi rata kiri.
3) "padding: 20px;": menambahkan jarak antara konten di dalam ".login-content" dengan batas ".login-content".

e) h2:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/124ed668-6f33-40b3-ac41-d4e7937b82c2)

1) "color: #ff6f61;": mengatur warna teks elemen "h2" menjadi merah muda "#ff6f61".
2) "font-size: 24px;": mengatur ukuran font teks elemen "h2" menjadi "24px".
3) "margin-bottom: 20px;": Ini menambahkan jarak bawah di bawah elemen "h2" sejauh "20px".

f) .input-group:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/d2658eab-3792-4490-9e4b-d5a3c748ddb2)

1) "margin-bottom: 20px;": memberikan jarak bawah antara elemen-elemen yang memiliki kelas "input-group" sejauh 20px.
2) "text-align: left;": mengatur teks di dalam elemen-elemen "input-group" agar rata kiri.

g) label:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/86dc92a3-8cb2-411e-9d81-5f9d523daa30)

1) "display: block;": mengubah elemen label menjadi blok, sehingga label akan ditampilkan dalam baris yang berbeda.
2) "font-size: 14px;": mengatur ukuran font teks label menjadi 14px.
3) "color: #333;": mengatur warna teks label menjadi abu-abu tua (#333).
4) "margin-bottom: 5px;": memberikan jarak bawah antara elemen-elemen label dan elemen-elemen input sejauh 5px.
5) "font-weight: bold;": membuat teks label menjadi tebal (bold).

h) input[type="text"], input[type="password"]:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/b2d98de8-c26e-4545-a383-0590ab4ed2d9)

1) Ini adalah aturan gaya untuk elemen input dengan tipe "text" dan "password".
2) "width: 100%;": membuat input tipe teks dan sandi memenuhi lebar parent elemennya (".input-group").
3) "padding: 10px;": memberikan jarak dalam input sejauh 10px di sekitar kontennya.
4) "border: none;": menghilangkan border (garis tepi) dari elemen input.
5) "border-bottom: 2px solid #ff6f61;": menambahkan border bawah dengan lebar 2px dan warna merah muda (#ff6f61) pada elemen input.
6) "background: transparent;": membuat latar belakang elemen input menjadi transparan.
7) "outline: none;": menghilangkan outline (garis pinggiran) pada elemen input saat elemen tersebut dalam fokus.
8) "color: #333;": mengatur warna teks dalam input menjadi abu-abu tua (#333).
9) "font-size: 16px;": mengatur ukuran font teks dalam input menjadi 16px.
10) "transition: border-bottom-color 0.3s ease-in-out;": mengatur efek transisi pada perubahan warna border bawah ketika elemen input berfokus dan tidak berfokus.

i) input[type="text"]:focus, input[type="password"]:focus:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/a0da3ebb-36b0-4516-8f0e-d7fd8b31b5d8)

1) Ini adalah aturan gaya yang berlaku ketika elemen input tipe teks atau sandi sedang dalam fokus (kursor berada di dalamnya).
2) "border-bottom-color: #ff9191;": mengubah warna border bawah elemen input menjadi merah muda yang lebih terang (#ff9191) saat elemen tersebut dalam fokus.
   
j) button:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/14886b77-7fda-4999-b9c9-fc0c2a581be9)

1) "background-color: #ff6f61;": mengatur warna latar belakang tombol menjadi merah muda (#ff6f61).
2) "color: #fff;": mengatur warna teks tombol menjadi putih.
3) "padding: 12px 24px;": mengatur jarak antara konten dalam tombol dan batas tombol.
4) "border: none;": menghilangkan border (garis tepi) tombol.
5) "border-radius: 25px;": memberikan sudut tombol bentuk yang lebih bulat.
6) "cursor: pointer;": mengubah ikon kursor saat di atas tombol, menunjukkan bahwa itu adalah elemen yang dapat diklik.
7) "font-weight: bold;": membuat teks pada tombol menjadi tebal (bold).
8) "font-size: 16px;": mengatur ukuran font teks tombol menjadi 16px.
9) "transition: background-color 0.3s ease-in-out;": mengatur efek transisi pada perubahan warna latar belakang tombol saat tombol dihover.

k) button:hover:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/80865fea-ca5f-4805-9e61-eee00655f972)

1) Ini adalah aturan gaya yang berlaku saat tombol sedang dihover (kursor berada di atasnya).
2) "background-color: #ff9191;": mengubah warna latar belakang tombol menjadi merah muda yang lebih terang (#ff9191) saat tombol dihover.
   
l) .login-image:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/bedb6f14-cf20-491f-94ee-21bd74543f6e)

1) "flex: 1;": membuat elemen dengan kelas "login-image" mengisi sebanyak mungkin ruang yang tersedia dalam parent (".login-container").
2) "text-align: center;": mengatur teks di dalam elemen "login-image" agar berada di tengah.
   
m) .login-image img:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/bf15854e-396f-4c8c-8632-cc071df0040d)


1) Ini adalah aturan gaya yang berlaku pada elemen gambar yang berada di dalam elemen dengan kelas "login-image".
2) "max-width: 100%;": mengatur lebar maksimum gambar menjadi 100% dari lebar parent (".login-image").
3) "height: auto;": menjaga aspek rasio gambar saat gambar diperbesar atau diperkecil.
4) "border-radius: 8px;": memberikan sudut gambar bentuk yang lebih bulat.

n) .register-link:

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/6a9604c2-65da-43ab-b209-36c53c028837)


1) "background-color: #ff6f61;": mengatur warna latar belakang tautan dengan kelas "register-link" menjadi merah muda (#ff6f61).
2) "color: #fff;": mengatur warna teks tautan menjadi putih.
3) "padding: 12px 24px;": mengatur jarak antara konten dalam tautan dan batas tautan.
4) "border: none;": menghilangkan border (garis tepi) tautan.
5) "border-radius: 25px;": memberikan sudut tautan bentuk yang lebih bulat.
6) "cursor: pointer;": mengubah ikon kursor saat di atas tautan, menunjukkan bahwa itu adalah elemen yang dapat diklik.
7) "font-weight: bold;": membuat teks pada tautan menjadi tebal (bold).
8) "font-size: 16px;": mengatur ukuran font teks tautan menjadi 16px.
9) "text-decoration: none;": enghilangkan garis bawah pada tautan.
10) "display: inline-block;": membuat tautan menjadi elemen inline-block sehingga dapat diatur seperti blok, namun tetap mempertahankan aliran inline.

o) .register-link:hover 

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/7faf5448-b5f5-461b-a9f4-41a4c4d5b9c0)

1) ".register-link:hover": adalah selector CSS untuk memilih tautan dengan kelas "register-link" ketika tautan tersebut sedang dalam kondisi dihover, artinya ketika pengguna mengarahkan kursor mouse ke atas tautan tersebut.
2) "background-color: #ff9191;": adalah peraturan gaya yang diterapkan ketika tautan "register-link" dalam keadaan dihover. Ini mengubah warna latar belakang tautan menjadi merah muda yang lebih terang (#ff9191) saat pengguna mengarahkan kursor mouse ke atasnya.

B. Laman Registrasi 
1. HTML

a) head

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/526c20a2-a62d-4c51-aed5-d06969f194fd)

1) "!DOCTYPE html": adalah deklarasi untuk mengidentifikasi tipe dokumen HTML yang digunakan oleh halaman.
2) (html lang="en"): adalah elemen root atau akar yang menandakan dimulainya dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa yang digunakan dalam dokumen ini adalah bahasa Inggris.
3) "head": Bagian ini berisi informasi tentang halaman, seperti metadata dan tautan ke file eksternal, yang biasanya tidak terlihat oleh pengguna ketika mengunjungi halaman web.
4) (meta charset="UTF-8"): Mengatur karakter encoding halaman web ke UTF-8, yang mendukung karakter internasional.
5) (meta name="viewport" content="width=device-width, initial-scale=1.0"): adalah tag meta yang digunakan untuk mengoptimalkan tampilan halaman web pada perangkat berbasis ponsel dan tablet.
6) (link rel="stylesheet" href="login.css"): adalah tautan ke file CSS eksternal (login.css) yang digunakan untuk mengatur tampilan halaman.
7) (link href="images/logo-removebg-preview.png" rel="icon"): menentukan favicon, gambar kecil yang ditampilkan di tab browser.
8) "title": menentukan "Registrasi" sebagai judul halaman web yang akan ditampilkan di tab browser.

b) body

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/4f312f16-4247-4ea5-8e85-50e374b794f0)

"body": adalah elemen yang berisi konten yang akan ditampilkan kepada pengguna di halaman web.

1) (div class="login-container"): adalah kontainer utama untuk seluruh konten halaman registrasi.
2) (div class="login-frame") dan (div class="login-content"): adalah dua elemen div yang mungkin digunakan untuk mengelompokkan konten dan tampilan halaman.
3) "(h2)Registrasi(/h2)": adalah judul halaman yang ditampilkan kepada pengguna.
4) Elemen-elemen (div class="input-group") digunakan untuk mengelompokkan label dan input form untuk username, email, password, dan konfirmasi password.
5) Elemen-elemen (label) digunakan untuk memberikan label pada input form.
6) Elemen-elemen (input) digunakan untuk memasukkan informasi seperti username, email, dan password.
7) "(a href="login.html" class="register-link")Daftar(/a)" adalah tautan (link) yang mengarah ke halaman "login.html" dengan teks "Daftar," mungkin digunakan untuk membawa pengguna ke halaman login.
8) (div class="login-image") berisi gambar profil atau logo yang akan ditampilkan di samping konten form registrasi.

2. css

a) "body"
	adalah gaya yang diterapkan ke elemen <body> halaman web.
 
![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/9f144a6a-7c1c-44f4-a883-b15668e0392f)

1) "font-family: 'Arial', sans-serif;": Mengatur jenis font teks pada halaman web ke "Arial" atau ke font sans-serif yang umum.
2) "background: linear-gradient(to right, #ffd6d6, #ffd6d6);": Mengatur latar belakang halaman web dengan efek gradien linier dari kiri ke kanan, dengan dua warna yang sama (#ffd6d6) sehingga latar belakang memiliki warna yang seragam.
3) "display: flex;": Menggunakan tampilan fleksibel pada elemen body, yang memudahkan pengaturan tata letak elemen di dalamnya.
4) "justify-content: center;": Mendata elemen-elemen di dalam body secara horizontal, sehingga elemen-elemen berada di tengah halaman.
5) "align-items: center;": Mendata elemen-elemen di dalam body secara vertikal, sehingga elemen-elemen berada di tengah halaman secara vertikal.
6) "height: 100vh;": Mengatur tinggi body menjadi 100% dari tinggi tampilan (viewport height), sehingga body akan mengisi seluruh tinggi tampilan.

b) ".login-container"
	adalah gaya yang diterapkan pada elemen dengan kelas "login-container."
 
![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/f36950f3-aa6f-4957-8c31-747b3917021f)

1) ".login-container": Ini adalah gaya yang diterapkan pada elemen dengan kelas "login-container."
2) "background-color: #fff;": Mengatur latar belakang elemen ini menjadi putih.
3) "border-radius: 8px;": Memberikan elemen sudut yang melengkung (border radius) sebesar 8 piksel.
4) "box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);": Memberikan bayangan (shadow) pada elemen, sehingga terlihat lebih mendalam.
5) "text-align: center;": Mengatur teks di dalam elemen ini menjadi terpusat.
6) "padding: 20px;": Memberikan ruang tambahan (padding) sebesar 20 piksel di sekitar elemen.
7) "position: relative;": Mengatur posisi elemen ini sebagai relatif terhadap posisi normalnya.
8) "display: flex;": Menggunakan tampilan fleksibel pada elemen, yang memungkinkan penggunaan flex pada cabang elemen.

c) ".login-frame"
	adalah gaya yang diterapkan pada elemen dengan kelas "login-frame."
 
 ![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/a7df8dbc-e97b-4ecb-add4-43a126a101c2)
 
1) "position: absolute;": Mengatur posisi elemen ini sebagai elemen dengan posisi absolut (di luar aliran dokumen normal).
2) "top", "left", "right", "bottom": Memberikan elemen ini jarak dari sisi atas, kiri, kanan, dan bawah dengan nilai -10 piksel, menciptakan efek border di sekitar elemen.
3) "border: 2px solid white;": Mengatur border elemen dengan ketebalan 2 piksel dan warna putih.
4) "border-radius: 10px;": Memberikan sudut yang melengkung pada border elemen sebesar 10 piksel.
5) "z-index: -1;": Mengatur elemen ini memiliki z-index -1, sehingga berada di bawah elemen-elemen lain di halaman.

d) ".login-content"
	adalah gaya yang diterapkan pada elemen dengan kelas "login-content."

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/fe63196a-2f7f-4557-a93c-6c1eb30e8a4d)

1) "flex: 1;": Membuat elemen ini mengisi sebanyak mungkin ruang yang tersedia di dalam ."login-container".
2) "text-align: left;": Mengatur teks di dalam elemen ini menjadi rata kiri.
3) "padding: 20px;": Memberikan ruang tambahan (padding) sebesar 20 piksel di sekitar elemen.

 e) ".h2"
 	adalah gaya yang diterapkan pada elemen "h2", yang merupakan judul di dalam ".login-content".

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/01f299fe-95ff-4638-a12c-8d0ad99f3daf)

1) "color: #ff6f61;": Mengatur warna teks judul menjadi merah muda.
2) "font-size: 24px;": Mengatur ukuran font judul menjadi 24 piksel.
3) "margin-bottom: 20px;": Memberikan margin bawah sebesar 20 piksel pada judul.

f) ".input-group"
	adalah gaya yang diterapkan pada elemen dengan kelas "input-group," yang digunakan untuk mengelompokkan label dan input form.

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/cf947d91-2aab-41a5-838f-0b0cd9c4b9e4)

1) "margin-bottom: 20px;": Memberikan margin bawah sebesar 20 piksel pada setiap grup input.

g) "label"
	adalah gaya yang diterapkan pada elemen-elemen "label".

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/d681a841-8c6e-42d7-9a2b-8318842ea14a)

1) "display: block;": Mengubah tampilan elemen label menjadi tampilan blok, sehingga masing-masing label dan input form akan ada di baris yang terpisah.
2) "font-size: 14px;": Mengatur ukuran font label menjadi 14 piksel.
3) "color: #333;": Mengatur warna teks label menjadi abu-abu.
4) "margin-bottom: 5px;": Memberikan margin bawah sebesar 5 piksel pada label.
5) "font-weight: bold;": Mengatur teks label menjadi tebal.

h) "input[type="text"]", "input[type="email"]", "input[type="password"]", "input[type="date"]"
	adalah gaya yang diterapkan pada elemen input dengan jenis tertentu (text, email, password, date).

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/ed9ab85c-2a28-487b-b00f-28a8617d2a34)

1) "width: 100%;": Mengatur lebar input menjadi 100% dari lebar elemen yang mengandungnya.
2) "padding: 10px;": Memberikan padding sebesar 10 piksel pada input.
3) "border: none;": Menghilangkan border bawaan pada input.
4) "border-bottom: 2px solid #ff6f61;": Menambahkan border bawah sebesar 2 piksel pada input dengan warna merah muda.
5) "background: transparent;": Mengatur latar belakang input menjadi transparan.
6) "outline: none;": Menghilangkan garis luar (outline) pada saat input fokus.
7) "color: #333;": Mengatur warna teks input menjadi abu-abu.
8) "font-size: 16px;": Mengatur ukuran font input menjadi 16 piksel.
9) "transition: border-bottom-color 0.3s ease-in-out;": Menerapkan efek transisi (transition) pada perubahan warna border bawah saat input berfokus.

i) "input[type="text"]:focus", "input[type="email"]:focus", "input[type="password"]:focus", "input[type="date"]:focus": adalah gaya yang diterapkan pada input saat mendapatkan fokus.

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/02f2bdee-b1bf-4f20-8edf-75cca44a1884)

1)"border-bottom-color: #ff9191;": Mengubah warna border bawah input menjadi merah muda yang lebih terang saat input berfokus.

j) "button" 
	adalah gaya yang diterapkan pada elemen-elemen tombol.

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/dce8a7cf-87f1-497c-a3e1-93ebb42a8b50)

1) "background-color: #ff6f61;": Mengatur warna latar belakang tombol menjadi merah muda.
2) "color: #fff;": Mengatur warna teks tombol menjadi putih.
3) "padding: 12px 24px;": Memberikan padding sebesar 12 piksel di atas dan bawah serta 24 piksel di sisi kiri dan kanan tombol.
4) "border: none;": Menghilangkan border pada tombol.
5) "border-radius: 25px;": Memberikan sudut yang sangat melengkung (border radius) pada tombol sebesar 25 piksel.
6) "cursor: pointer;": Mengubah kursor menjadi tanda panah (pointer) saat pengguna mengarahkan kursor ke tombol.
7) "font-weight: bold;": Mengatur teks tombol menjadi tebal.
8) "font-size: 16px;": Mengatur ukuran font teks tombol menjadi 16 piksel.
9) "transition: background-color 0.3s ease-in-out;": Menerapkan efek transisi pada perubahan warna latar belakang tombol saat disorot.

k) "button:hover"
	adalah gaya yang diterapkan pada tombol saat tombol tersebut disorot (hover).

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/490e85b1-5f7b-459a-b458-73f23743ec38)

1) "background-color: #ff9191;": Mengubah warna latar belakang tombol menjadi merah muda yang lebih terang saat tombol disorot.

l) ".login-image" 
	adalah gaya yang diterapkan pada elemen dengan kelas "login-image."

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/e4246f78-5b57-4653-96dc-b9557c8cc9d2)

1) "flex: 1;": Membuat elemen ini mengisi sebanyak mungkin ruang yang tersedia di dalam .login-container.
2) "text-align: center;": Mengatur teks di dalam elemen ini menjadi terpusat.

 m) ".login-image img"
 	adalah gaya yang diterapkan pada elemen gambar di dalam ".login-image".

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/055d5536-0f5d-45b0-b054-dd3562d180b7)

1) "max-width: 100%;": Mengatur lebar gambar agar tidak melebihi lebar elemen yang mengandungnya.
2) "height: auto;": Mengatur tinggi gambar agar sesuai dengan aspek rasio aslinya.
3) "border-radius: 8px;": Memberikan sudut yang melengkung pada gambar sebesar 8 piksel.

n) ".register-link"
	adalah gaya yang diterapkan pada elemen dengan kelas "register-link,"  adalah tautan (link) untuk melakukan registrasi.

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/8adab3af-da81-465c-a689-99c6221e698a)

1) "background-color: #ff6f61;": Mengatur warna latar belakang tautan menjadi merah muda.
2) "color: #fff;": Mengatur warna teks tautan menjadi putih.
3) "padding: 12px 24px;": Memberikan padding sebesar 12 piksel di atas dan bawah serta 24 piksel di sisi kiri dan kanan tautan.
4) "border: none;": Menghilangkan border pada tautan.
5) "border-radius: 25px;": Memberikan sudut yang sangat melengkung (border radius) pada tautan sebesar 25 piksel.
6) "cursor: pointer;": Mengubah kursor menjadi tanda panah (pointer) saat pengguna mengarahkan kursor ke tautan.
7) "font-weight: bold;": Mengatur teks tautan menjadi tebal.
8) "font-size: 16px;": Mengatur ukuran font teks tautan menjadi 16 piksel.
9) "text-decoration: none;": Menghilangkan dekorasi tautan seperti garis bawah atau garis coret.
10) "display: inline-block;": Mengatur tautan agar ditampilkan sebagai elemen blok.
11) "margin-top: 10px;": Memberikan margin atas sebesar 10 piksel pada tautan.

C) Halaman Kedua

1) HTML

a) head

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/42f97385-0844-4703-9c5f-8d9f32096fa5)

1) "!DOCTYPE html": adalah deklarasi dokumen yang memberi tahu browser bahwa halaman web akan menggunakan versi HTML5.
2) "html lang="en"": mengindikasikan bahwa bahasa dokumen ini adalah bahasa Inggris.
3) "head": Bagian "head" dari halaman web berisi informasi tentang dokumen, seperti metadata dan tautan ke berkas-berkas luar, seperti CSS (Cascading Style Sheets) dan ikon favicon.
4) (meta charset="UTF-8"): mengatur karakter encoding (pemetaan karakter) untuk dokumen menjadi UTF-8.
5) (meta name="viewport" content="width=device-width, initial-scale=1.0"): adalah tag meta yang mengatur tampilan halaman web agar responsif pada perangkat seluler dengan menyesuaikan lebar (width) ke lebar perangkat (device-width) dan skala awal (initial-scale) adalah 1.0.
6) "title"HasarisStore"/title": mengatur judul halaman web, yang akan ditampilkan pada tab browser.
7) (link rel="stylesheet" href="halaman_kedua.css"): adalah tautan ke berkas CSS eksternal yang digunakan untuk memformat tampilan halaman web.
8) (link href="images/logo-removebg-preview.png" rel="icon"): mengaitkan gambar sebagai favicon, yang akan muncul di tab browser.

b) body

![image](https://github.com/22091397020HanifIhsanAlimAkbar/PemwebFinalProjek/assets/124480469/87979ab8-00b5-44bf-9612-105698402824)

1. "body": adalah bagian utama dari halaman web yang akan ditampilkan kepada pengguna.
- (div class="header"): adalah div (elemen blok) dengan kelas "header" yang umumnya digunakan untuk bagian atas halaman web, berisi logo, navigasi, dan elemen header lainnya.
-  (section id="home"): adalah elemen "section" dengan ID "home" yang digunakan untuk merinci bagian tertentu dari halaman web. Biasanya digunakan dalam mengorganisasi konten.
- (div class="navbar"): adalah div dengan kelas "navbar" yang berisi navigasi situs web.
- (div class="logo"): adalah div dengan kelas "logo" yang berisi logo situs web.
- (nav): adalah elemen navigasi yang berisi daftar tautan ke halaman lain dalam situs.
- "ul": adalah daftar tak terurut (unordered list) yang berisi tautan navigasi.
- "li": adalah elemen daftar (list item) yang berisi tautan ke halaman lain.
- (div class="row"): adalah div dengan kelas "row" yang digunakan untuk mengatur konten dalam baris.
- (div class="col-2"): adalah div dengan kelas "col-2" yang digunakan untuk mengatur konten dalam dua kolom.
- "h1" dan "p": adalah elemen heading dan paragraf yang digunakan untuk menampilkan judul dan teks pada halaman.
- (img src="images/slide.png"): adalah elemen gambar yang menampilkan gambar "slide.png" pada halaman.
2. (div class="footer"): adalah div dengan kelas "footer" yang mewakili bagian bawah halaman web.
- (div class="sosialicon"): adalah div yang mungkin digunakan untuk menampilkan ikon-ikon media sosial.
- (div class="footerbottom"): adalah div dengan kelas "footerbottom" yang berisi informasi hak cipta dan pengarang situs.
- (p)copyright &copy;2023: Designed by (span class="designer")HasarisStore(/span)(/p): adalah elemen paragraf yang berisi informasi hak cipta dan pengarang situs.
- (/body): Menandai akhir dari elemen body, yang menutup semua konten utama halaman web.
- (/html): Menandai akhir dari elemen HTML, menutup seluruh dokumen HTML.

2) css

