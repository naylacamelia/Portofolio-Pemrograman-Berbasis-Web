**Nama**: Nayla camelia indraswari

**NIM**: 2409116009

**Kelas**: A

# Website Portofolio

---
## 💻 Tampilan Website

<img width="1920" height="983" alt="Screenshot 2026-03-01 192634" src="https://github.com/user-attachments/assets/8ef87a3f-1b9d-44c2-943f-5313d304bab0" />

<img width="1919" height="972" alt="image" src="https://github.com/user-attachments/assets/5ae96c94-4f31-41b8-9128-2232d6a8ef47" />

<img width="1919" height="972" alt="image" src="https://github.com/user-attachments/assets/72bd1bfb-4d8f-49dd-97ec-ae7f491c0019" />

<img width="1920" height="980" alt="Screenshot 2026-03-01 192656" src="https://github.com/user-attachments/assets/8fb1bdf8-5f4d-422b-8b2d-5ae95e8dbcf5" />

---

## 📄 Penjelasan Kode
 

<details>
   <summary>Navbar Section</summary>
  
Navbar terdiri dari tiga button yang terhubung dengan setiap section pada website, yakni button Home, About me, Certificate dan Contact. 

### HTML

<img width="904" height="328" alt="image" src="https://github.com/user-attachments/assets/be13c1f9-cad2-4f68-a125-ea0bdf3a26d8" />

Section ini menerapkan komponen Navbar Bootstrap yang dilengkapi dengan:
1. **Utility spacing** (`ms-auto`) untuk mengatur posisi dan jarak antar elemen agar lebih rapi.
2. **Collapse system** (`navbar-toggler`, `collapse`, `data-bs-toggle`) untuk menyembunyikan menu dalam bentuk hamburger saat layar berukuran kecil.
3. **Breakpoint** `navbar-expand-lg` untuk memastikan navbar berubah secara otomatis berdasarkan ukuran layar, sehingga tetap responsif di berbagai device.`

### CSS

<img width="496" height="368" alt="image" src="https://github.com/user-attachments/assets/abdb0f4f-16eb-4952-93b7-6974ea8358cc" />

CSS mengatur warna, ukuran font, padding, efek blur, serta efek hover pada button.

</details>

---

<details>
   <summary>Hero Section</summary>

Hero Section terdiri dari deskripsi singkat diri, greetings, foto porfil dan button koneksi.

### HTML

<img src="https://github.com/user-attachments/assets/8b40abaf-4d2f-44fc-8e35-c65b7a962fa7" width="600" alt="Tampilan Desktop">

Section ini menerapkan komponen Bootstrap dan Interpolasi Vue Js sebagai berikut:
1. **Grid system & breakpoint** `col-12 col-lg-7` untuk membagi layout menjadi beberapa kolom dengan sistem 12 grid dan memastikan agar tampilan website tetap responsive di berbagai layar.
2. **Spacing utilities** `mt-4` untuk memberi spacing margin top.
3. **Flex utilities**`d-flex` untuk mengaktifkan display flexbox pada button sehingga dapat disusun secara horizontal.
4. **Interpolasi Vue Js**, `{{ tagline }}`, `{{ description }}`, untuk menampilkan data yang  disimpan pada vue.
5. **Text alignment** `text-center text-lg-end` untuk mengatur tata letak teks secara responsif.

### CSS

<img src="https://github.com/user-attachments/assets/3c02937f-5c24-432b-8eb6-73e6d9e3a47d" width="400" alt="Tampilan Mobile">

CSS mengatur warna, ukuran font, padding, efek blur, serta efek hover pada button.

</details>

---

<details>
<summary>About Me Section</summary>

About Me terbagi menjadi dua bagian, section kiri berisi pengalaman, section kanan berisi deskripsi skill, progress bar skill, dan daftar tools yang dikuasai. Section ini telah menerapkan bootstrap dan interpolasi Vue Js.

### HTML

<img width="465" height="166" alt="image" src="https://github.com/user-attachments/assets/0930cc0c-5875-4de4-8ece-a4420fa2f3f3" />

Section ini menerapkan komponen Bootstrap dan Vue JS sebagai berikut:
1. **Grid system** `col-12 col-lg-5`  dan `col-12 col-lg-7`  uigunakan untuk membagi tampilan menjadi dua bagian dan ketika di layar kecil otomatis menjadi satu kolom sehingga web bersifat responsift.
2. **Progress bar** menggunakan `<div class="progress-bar">` untuk memanggil komponen progress bar bawaan Bootstrap.
3. **Flex utility** `d-flex flex-wrap gap-2` untuk menampilkan tools dalam satu baris dengan gap yang sama.
4. **Interpolasi Vue JS `v-for`**  `v-for="skill in skills"` dan `:style="{ width: skill.level + '%' }"` untuk menampilkan daftar skill dari data yang sudah disimpan, jadi tidak perlu menulis satu per satu secara manual.

### CSS

<img width="438" height="203" alt="image" src="https://github.com/user-attachments/assets/13f18ff4-1234-42c9-b53b-e4f1c57f3433" />

CSS mengatur background, warna & kuran font, padding, efek blur pada experience section serta warna progress bar.

</details>

---

<details>
<summary>Certificates Section</summary>

Section Certificates menampilkan daftar sertifikat dalam layout grid kartu. Setiap kartu memiliki gambar sertifikat, instansi penerbit, judul, deskripsi, dan tag skill yang dipelajari.

### HTML

<img width="760" height="236" alt="image" src="https://github.com/user-attachments/assets/2513ec45-31b1-47fc-b5a3-4c86db7d71cc" />

Section ini menerapkan komponen Bootstrap dan Vue JS sebagai berikut:
1. **Grid system** `col-12 col-md-6 col-lg-4` untuk menampilkan card yang secara otomatis menyesuaikan ukurannya dengan layar device.
2. **Card component** `card`, `card-img-top`, `card-body`, `card-title`, `card-text` merupakan komponen bootsrtrap yang akan mengisi tampilan sertifikat.
3. **Interpolasi Vue JS `v-for` nested** — `v-for="cert in certificates"` untuk menampilkan sertifikat dari data yang telah tersimpan di vue.

### CSS

<img width="674" height="268" alt="image" src="https://github.com/user-attachments/assets/931b05ea-9f7b-486a-a0a3-7d0e50e30a39" />

CSS mengatur tampilan kartu mulai dari font pada deksirpsi informasi sertifikat, ukuran gambar yang ditampilkan hingga efek blur ketika dilakukan hover pada kartu.

</details>

---

<details>
<summary>Contact Section</summary>

Section Contact terbagi menjadi dua kolom utama, section kiri berisi informasi sosial media yang dapat dihubungi, sedangkan section kanan berisi data diri singkat.

### HTML

<img width="912" height="313" alt="image" src="https://github.com/user-attachments/assets/15ecd969-142b-46aa-91eb-c277966511fb" />

Section ini menerapkan komponen Bootstrap dan Vue JS sebagai berikut:
1. **Grid system** `col-12 col-lg-6` untuk membagi tampilan menjadi dua kolom dengan ukuran yang sama.
2. **Flex utility** `d-flex flex-wrap gap-3` untuk menyusun tombol sosial media secara horizontal dan otomatis ke baris baru jika tidak muat.
3. **Spacing utility** `mt-4` untuk memberi jarak antara elemen sehingga tidak perlu menambah CSS manual.
4. **Vue JS `:class` binding** `:class="soc.icon"` dan `:class="info.icon"` untuk menampilkan daftar social media, link, serta bootstrap icon yang sudah tersimpan di vue.

### CSS

<img width="534" height="532" alt="image" src="https://github.com/user-attachments/assets/fd755d97-b03d-4e00-9641-e35ac8797657" />

CSS mengatur warna section, ukuran dan warna font, serta  menambahkan efek visual seperti animasi titik yang berkedip (pada availability) dan perubahan warna tombol saat dihover.

</details>

---

<details>
<summary>Footer</summary>

Footer menampilkan teks copyright di kiri dan tautan *Back to top* di kanan yang, ketika diklik, akan membawa pengguna ke halaman awal website.

### HTML

<img width="739" height="187" alt="image" src="https://github.com/user-attachments/assets/0d47bfe7-144d-4165-adaf-b95e96248877" />

Footer menggunakan Bootstrap utility classes sepenuhnya untuk layout:
1. **Flex utility** `d-flex justify-content-between` untuk menempatkan copyright di kiri dan link di kanan secara otomatis dalam satu baris.
2. **Spacing utility** `py-2` untuk padding vertikal tipis dan `mb-0` untuk menghilangkan margin bawah default

### CSS

<img width="447" height="241" alt="image" src="https://github.com/user-attachments/assets/328e1847-b2c9-40b6-9885-9c5d77be7511" />

CSS mengatur ukuran dan warna font, menambah garis tipis diatas footer untuk memberikan batasan dengan section sebelumnya serta mengatur perubahan elemen ketika melakukan hover pada *Back to top*.

</details>


## Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| **HTML** | Digunakan untuk membangun struktur utama website seperti navbar, hero section, about, certificates, contact, dan footer. |
| **CSS** | Digunakan untuk mengatur tampilan visual website seperti warna, layout tambahan, animasi hover, dan efek transisi |
| **Bootstrap 5** | Membantu dalam pembuatan layout responsif menggunakan grid system, serta menyediakan komponen siap pakai seperti navbar, card, progress bar, dan utility class untuk spacing dan alignment. |
| **Bootstrap Icons** | Digunakan untuk menampilkan ikon pada bagian navbar, tools, social media, status pada badge profil yang membuat tampilan lebih menarik. |
| **Vue JS** | Digunakan untuk menampilkan data secara dinamis seperti nama, deskripsi, daftar skill, sertifikat, dan social media tanpa menulis ulang elemen HTML secara manual. |

---
