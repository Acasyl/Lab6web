# Nama :Syalsha Putri Ichwani
# NIM  :312410209
<br><br>



# Penjelasan langkah-langkah 

1.` home.html `


Brand Bar (Header Atas): Bagian paling atas yang berisi judul utama "Layout Sederhana".

Navbar (Menu Navigasi): Garis menu horizontal berwarna biru kustom (.navblue) yang berisi tombol-tombol utama seperti Home, Artikel, About, dan Kontak.

Hero Section (Area Sambutan): Bagian besar di bawah menu yang menyambut pengunjung ("Hello syalsha!") dan berisi deskripsi singkat serta tombol besar ` "Learn more ".` 

Konten Utama (Main + Sidebar): Bagian isi halaman dibagi menjadi dua:

Kolom Besar (Kiri): Tempat Anda meletakkan konten penting, seperti tiga lingkaran ikon` (.circle) `dan dua artikel Featurette (yang menampilkan gambar `(.thumb) `dan teks secara bergantian).

Sidebar (Kanan): Kolom samping yang berisi blok-blok informasi tambahan yang disebut Widget (seperti daftar link dan kotak teks).

Footer (Kaki Halaman): Bagian paling bawah yang menampilkan informasi hak cipta "© 2021 - Universitas Pelita Bangsa".

Skrip (Fungsi): Di bagian akhir, halaman memuat jQuery dan Bootstrap JS (untuk fitur seperti menu dropdown dan toggler mobile), serta `bootstrap.bundle.min.js` (untuk fungsi kustom).
<br><br>


<img width="1416" height="848" alt="Cuplikan layar 2025-10-27 121543" src="https://github.com/user-attachments/assets/91680026-492d-4808-9eef-ae8f3fa38275" />


2. ` bootstrap.min.css`
Warna Dasar,Mengubah latar belakang halaman menjadi abu-abu sangat terang/off-white `(#f9f9fb)` dan membuat teks berwarna abu-abu gelap (#444).

Navbar` (.navblue)`	Memberi warna biru lembut terang` (#94b9e2)` pada menu navigasi. Saat menu disentuh (hover) atau aktif, warnanya menjadi biru lembut lebih gelap` (#6a9ac9).`
<br><br>
Lingkaran  `(.circle)`	Menciptakan tiga lingkaran kecil (120x120px) dengan warna oranye, biru, dan teal yang telah disesuaikan agar cocok dengan palet soft blue baru.
<br><br>
Widget Sidebar	Memberikan header berwarna biru lembut lebih gelap dan mengatur jarak serta garis pemisah yang rapi pada daftar link di sidebar.
<br><br>
Footer	Memberikan latar belakang biru gelap/arang `(#2c3e50)` yang kontras di bagian bawah.

<img width="1139" height="888" alt="Cuplikan layar 2025-10-27 133413" src="https://github.com/user-attachments/assets/055101f4-7075-44ea-be31-bf4516ffee07" />


3. `bootstrap.bundle.min.js` 
Ini adalah kode JavaScript (menggunakan jQuery) yang memberikan sedikit kecerdasan pada halaman web Anda agar bisa merespons tindakan pengguna.

Menunggu Halaman Siap: Semua kode menunggu sampai semua elemen HTML selesai dimuat sebelum dijalankan, agar tidak ada error.

Mengaktifkan Menu Otomatis: Skrip ini memeriksa nama file halaman saat ini (misalnya,` home.html`). Kemudian, ia secara otomatis menambahkan tanda active pada link menu Navigasi yang sesuai, sehingga pengunjung tahu sedang berada di halaman mana.

Demo Klik`"View detail"`: Skrip ini mendengarkan setiap kali tombol` "View detail" ``(.btn-ghost) `diklik.

Alih-alih pergi ke link baru, ia akan memunculkan kotak alert `(pop-up).`

Pop-up tersebut akan menampilkan pesan "Detail item:" diikuti dengan judul` (<h5>) `dari lingkaran ikon yang berada tepat di atas tombol tersebut. Ini hanya sebuah demonstrasi fungsi.


<img width="1048" height="886" alt="Cuplikan layar 2025-10-27 122227" src="https://github.com/user-attachments/assets/3551f914-ace4-463f-984c-2184e0889ed7" />


