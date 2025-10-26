# Nama :Syalsha Putri Ichwani
# NIM  :312410209
<br><br>



# Penjelasan langkah-langkah 

1. ` <!doctype html> ... <html lang="id"> `

Ini mendeklarasikan dokumen sebagai HTML5 dan menetapkan bahasa halaman (`lang="id" ` = bahasa Indonesia)
<br><br>
 
 2. `<head>` metadata dan dependensi
<br><br>

 `<meta charset="utf-8">`set encoding UTF-8 agar karakter Indonesia tampil benar.

`<meta name="viewport" content="width=device-width, initial-scale=1">` membuat halaman responsif di perangkat mobile.

`<title>Layout Sederhana - Bootstrap</title>` teks yang muncul di tab browser.

`<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">` memuat CSS Bootstrap (grid, utilitas, komponen).

`<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>` memuat jQuery (opsional di sini).

`<style>...</style>` CSS khusus halaman (mewarnai header, navbar, hero, lingkaran, widget, footer).

Outputnya: mempengaruhi tampilan seluruh halaman (lihat semua gambar style mengatur warna, padding, border, dan bentuk lingkaran).
<br><br>
3. `<body>` bagian visual halaman dimulai
<br><br>
4. Header / Brand bar

Kode:

` <div class="brand-bar py-3">`
 ` <div class="container">`
    ` <h1 class="h3 m-0">Layout Sederhana</h1> `
`  </div> `
` </div> `


Fungsi: menampilkan judul situs brand di bagian paling atas, dengan latar putih dan border bawah.

CSS terkait: `.brand-bar` memberi background putih dan border bottom `.brand-bar h1` mengatur warna dan ketebalan.

Outputnya: lihat gambar `01_header.png` (judul "Layout Sederhana" di bar atas).

 5. Navbar / Topbar

Kode:

`<nav class="topbar">`
 ` <div class="container">`
   ` <ul class="nav">`
    `  <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>`
      ...
 `   </ul>`
`  </div>`
`</nav>`


Fungsi: menu navigasi horizontal (Home, Artikel, About, Kontak).

CSS:` .topbar` membuat latar biru tua` .nav-link` mengatur warna teks putih, dan state `.active/` hover memberi latar lebih gelap.

Outputnya: lihat `02_navbar.png.`
<br><br>

6. Hero Section

Kode:

`<div class="container my-4">`
 ` <div class="hero p-4 p-md-5"> ... </div>`
`</div>`


Fungsi: area sorotan utama dengan judul besar ("Hello World!"), paragraf deskripsi, dan tombol "Learn more".

CSS:` .hero` latar abu-abu terang, border, border radius `.btn-learn` mengatur warna tombol.

Outputnya: lihat `03_hero.png` (blok hero dengan tombol di kanan bawah).
<br><br>

7. Main Layout (container dengan grid Bootstrap)

Struktur:` <div class="container mb-5"><div class="row g-4"> ... </div></div>`

Menggunakan grid Bootstrap dua kolom utama main (col-lg-8) dan` aside`/sidebar (col-lg-4).

Fungsi: membagi halaman menjadi area konten utama (kiri) dan sidebar (kanan).

Outputnya: keseluruhan layout terlihat pada` 04_left_columns.png `(kiri) dan` 05_sidebar.png` (kanan).

8.  Column tiga lingkaran (120×120)

Kode (bagian dalam` main`):

`<div class="row text-center mb-4">`
 ` <div class="col-md-4">`
  `  <div class="circle orange">120 × 120</div>`
  `  <h5>Heading</h5>`
  `  <p class="small text-muted">...</p>`
  `  <a class="btn btn-sm btn-outline-secondary">View detail</a>`
 ` </div>`
`  ... (3 kolom serupa)`
`</div>`


Fungsi: tiga kolom ringkas dengan lingkaran visual (profil/ikon), judul, teks singkat, dan tombol.

CSS: `.circle `mengatur ukuran 120×120 dan `border-radius: 50%` untuk membuat lingkaran kelas warna `.orange, .blue, .teal` memberi background berbeda.

Outputnya: bagian atas gambar `04_left_columns.png` (3 lingkaran).
<br><br>

9. Featurette 1 dan Featurette 2

Masing-masing featurette menampilkan kombinasi gambar placeholder (150×150) dan teks penjelasan.

Kode menggunakan row dengan kolom untuk tata letak gambar, teks, dan `order-sm-* `untuk mengubah urutan pada layar kecil.

Outputnya: bagian bawah `04_left_columns.png` menampilkan dua kotak featurette (satu gambar di kiri, teks di kanan, satunya teks di kiri, gambar di kanan).
<br><br>

10. Sidebar (Widgets)

Terdiri dari dua card` (.card`) bertumpuk: satu dengan header list link (menggunakan `list-group`), dan satu berisi teks keterangan.

CSS:` .widget .card-header` diberi background biru dan teks putih untuk kontras.

Outputnya: lihat `05_sidebar.png.`
<br><br>

11. Footer

Kode:

`<footer class="py-3">`
 ` <div class="container">`
  `  <small>© 2021 · Universitas Pelita Bangsa</small>`
`  </div>`
`</footer>`


Fungsi: menampilkan informasi hak cipta di bagian bawah, dengan latar gelap (`footer { background-color: #111111; color: #ffffff; }).`

Outputnya:` 06_footer.png.`
<br><br>

12. Skrip Bootstrap JS

kode:

`<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>`


Fungsi: memuat JavaScript Bootstrap (dropdown, modal, collapse, dll.) diperlukan bila menggunakan komponen interaktif Bootstrap.
