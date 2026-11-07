# Pemrograman Web Dasar - Formatif

Repository ini merupakan kumpulan tugas formatif mata pelajaran _Pemrograman Web Dasar (PWD)_ kelas X TKJ 1 di SMK Kristen Immanuel 1 Pontianak.

Proyek ini berisi latihan membuat website portofolio pribadi menggunakan HTML dan CSS. Setiap halaman dan komponen dibuat untuk mempelajari berbagai elemen HTML, pengaturan tampilan CSS, serta cara membuat halaman website yang lebih menarik. Selain itu, proyek ini juga melatih kemampuan dalam menyusun struktur folder, menghubungkan file HTML dengan CSS, memperbaiki kesalahan kode, serta menggunakan Git dan GitHub untuk mengelola perkembangan proyek.

## Identitas Murid

- **Nama:** Forentya Sheren
- **Kelas:** X TKJ 1
- **Sekolah:** SMK Kristen Immanuel 1 Pontianak
- **Mata Pelajaran:** Pemrograman Web Dasar

## Struktur Repository

**assets/**

- fonts/
  - Opensans
  - Poppins
- icons/
- images/
  - About.jpg
  - badge.jpg
  - card.png
  - foto.jpeg
  - proyek1.png
  - proyek2.png
  - proyek3.png
  - proyek4.png
  - proyek5.png
  - proyek6.png
- videos/

**components/**

- button-set.html
- card.html
- card-badge.html
- navbar.html
- sidebar.html
- interactive.html

**pages/**

- profile.html
- about.html
- contact.html
- gallery.html
- hero.html

**styles/**

- index.css
- about.css
- gallery.css
- hero.css
- navbar.css
- interactive.css

**index.html** : Halaman utama

## Penjelasan Folder dan File

### 1. assets

Folder ini digunakan untuk menyimpan aset yang dibutuhkan dalam website, seperti `font, gambar, vidio dan ikon`. Aset tersebut kemudian dipanggil, seperti menggunakan atribut `img` atau `@fontface` pada elemen HTML.
Contohnya adalah foto untuk profil, gambar proyek, dan gambar untuk tampilan background.

### 2. components

Folder ini berisi kumpulan komponen website yang dibuat untuk mempelajari berbagai elemen HTML dan penerapan CSS.

- **button-set.html:**
  Membuat kumpulan tombol dengan variasi warna, bentuk, dan efek hover menggunakan CSS Internal. Pada bagian ini, saya belajar tentang selector tag, class, descendant, grouping, serta pseudo-class `:hover`.

- **card.html:**
  Membuat kartu proyek yang berisi gambar, judul, deskripsi, dan tautan menggunakan CSS Internal. Pada bagian ini, saya belajar tentang box model yang meliputi width, padding, border, dan margin, serta selector universal.

- **card-badge.html:**
  Membuat kartu dengan tambahan badge atau label serta tombol navigasi untuk kembali ke bagian atas halaman menggunakan CSS Internal. Pada bagian ini, saya belajar tentang properti position (`relative`, `absolute`, dan `fixed`), anchor, serta selector ID.

- **navbar.html:**
  Membuat navigasi horizontal yang berisi menu Beranda, Tentang, Proyek, dan Kontak menggunakan CSS Eksternal. Pada bagian ini, saya belajar menyusun menu menggunakan Flexbox serta memahami selector child.

- **sidebar.html:**
  Membuat navigasi samping menggunakan layout Flexbox yang membagi area menu dan konten utama. Pada bagian ini, saya belajar menyusun dua kolom yang berdampingan menggunakan Flexbox dan Grid dengan CSS Internal.

- **interactive.html:**
  Membuat menu navigasi dan tombol dengan efek interaksi menggunakan CSS Eksternal. Pada bagian ini, saya belajar menggunakan properti `transition`, mulai dari menentukan properti yang berubah, durasi perubahan, hingga kecepatan atau timing function (easing).

### 3. pages

Folder ini berisi halaman-halaman utama yang membentuk website portofolio pribadi.

- **profile.html:**
  Membuat halaman profil pribadi yang berisi foto, nama, kelas, deskripsi diri, dan hobi menggunakan CSS Inline. Pada bagian ini, saya belajar menerapkan CSS langsung pada elemen HTML untuk mengatur warna dan tampilan tulisan.

- **about.html:**
  Membuat halaman tentang saya yang berisi perkenalan dan ketertarikan dalam pengembangan web menggunakan CSS Eksternal. Pada bagian ini, saya belajar menghubungkan file CSS dengan HTML, menggunakan selector ID dan descendant, serta mengatur gambar latar belakang.

- **contact.html:**
  Membuat halaman kontak yang berisi formulir untuk mengisi nama, email, dan pesan menggunakan CSS Internal. Pada bagian ini, saya belajar mengatur tampilan formulir menggunakan selector ID, class, descendant, grouping, serta pseudo-class `:focus`.

- **gallery.html:**
  Membuat halaman galeri yang menampilkan beberapa contoh proyek dalam bentuk kumpulan gambar dan judul menggunakan CSS Eksternal. Pada bagian ini, saya belajar menyusun galeri menggunakan CSS Grid, termasuk mengatur jumlah kolom, satuan `fr`, dan jarak antar elemen (`gap`), serta memahami selector child.

- **hero.html:**
  Membuat bagian pembuka website yang berisi sapaan, nama, deskripsi singkat, dan tombol untuk melihat proyek menggunakan CSS Eksternal. Pada bagian ini, saya belajar membuat animasi sederhana menggunakan `@keyframes`, serta menerapkan selector grouping yang dikombinasikan dengan descendant.

### 4. styles

Folder ini digunakan untuk menyimpan file CSS eksternal yang mengatur tampilan halaman website.

- **index.css:**
  Mengatur tampilan halaman utama, seperti warna background, header, konten, dan footer pada index.html.
- **about.css:**
  Mengatur desain halaman tentang saya pada about.html.
- **gallery.css:**
  Mengatur tata letak dan tampilan galeri proyek pada gallery.html.
- **hero.css:**
  Mengatur tampilan bagian pembuka atau hero section pada hero.html.
- **navbar.css:**
  Mengatur desain navigasi horizontal pada navbar.html.
- **interactive.css:**
  Mengatur tampilan menu dan tombol interaktif pada interactive.html.

### 5. index.html

File ini merupakan halaman utama atau beranda website. Di dalamnya terdapat judul portofolio dan menghubungkan daftar tautan menuju seluruh komponen ataupun halaman yang telah dibuat. Dengan CSS Eksternal saya dapat belajar menyatukan proyek: halaman utama, selector tag dan id, struktur folder, dan riwayat commit di GitHub..

## Materi yang Dipelajari

Selama mengerjakan proyek ini, terdapat beberapa materi HTML dan CSS yang dipelajari dan diterapkan.

- Mengenal selector berdasarkan elemen, class, dan id.
- Mengatur warna menggunakan nama warna, HEX, RGB, dan RGBA.
- Mengatur margin, padding, border, dan border-radius.
- Memahami konsep box model dan penggunaan `box-sizing`.
- Mengatur tata letak menggunakan `display`, Flexbox, dan properti seperti `justify-content`, `flex-direction` serta `align-items`.
- Menggunakan `position` seperti relative, absolute, dan fixed.
- Membuat efek interaksi menggunakan pseudo-class `:hover` dan `:focus`.
- Menggunakan `transition` untuk membuat perubahan tampilan lebih halus.
- Mengatur gambar menggunakan `object-fit`.
- Membuat background dengan pola polkadot.
- Menggunakan font dari fontgoogle.com secara online maupun lokal.
- Menghubungkan CSS ke HTML menggunakan inline, internal, dan external CSS.
- Mengatur ukuran dan jarak elemen.
- Menggunakan elemen semantik seperti `header`, `main`, `section`, `article`, `nav`, `aside`, dan `footer`.
- Menggunakan atribut `id` dan `class` untuk menghubungkan elemen dengan CSS.

## Index.html

http://127.0.0.1:5500/index.html
