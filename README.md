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

Section ini menerapkan komponen Navbar Bootstrap yang dilengkapi dengan:
1. Utility spacing (`ms-auto`) untuk mengatur posisi dan jarak antar elemen agar lebih rapi.
2. Collapse system (`navbar-toggler`, `collapse`, `data-bs-toggle`) untuk menyembunyikan menu dalam bentuk hamburger saat layar berukuran kecil.
3. Breakpoint `navbar-expand-lg` untuk memastikan navbar berubah secara otomatis berdasarkan ukuran layar, sehingga tetap responsif di berbagai device.`

### CSS
CSS mengatur warna, ukuran font, padding, efek blur, serta efek hover pada button.

</details>

---

<details>
   <summary>Hero Section</summary>

Hero Section terdiri dari deskripsi singkat diri, greetings, foto porfil dan button koneksi.

### HTML

<img src="https://github.com/user-attachments/assets/8b40abaf-4d2f-44fc-8e35-c65b7a962fa7" width="600" alt="Tampilan Desktop">

Section ini menerapkan komponen Bootstrap dan Interpolasi Vue Js sebagai berikut:
1. Grid system & breakpoint `col-12 col-lg-7` untuk membagi layout menjadi beberapa kolom dengan sistem 12 grid dan memastikan agar tampilan website tetap responsive di berbagai layar.
2. Spacing utilities `mt-4` untuk memberi spacing margin top.
3. Flex utilities`d-flex` untuk mengaktifkan display flexbox pada button sehingga dapat disusun secara horizontal.
4. Interpolasi Vue Js, `{{ tagline }}`, `{{ description }}`, untuk menampilkan data yang  disimpan pada vue.
5. Text alignment `text-center text-lg-end` untuk mengatur tata letak teks secara responsif.

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
3. **Flex utility** — `d-flex flex-wrap gap-2` untuk menampilkan tools dalam satu baris dengan gap yang sama.
4. **Interpolasi Vue JS `v-for`** — `v-for="skill in skills"` dan `:style="{ width: skill.level + '%' }"` untuk menampilkan daftar skill dari data yang sudah disimpan, jadi tidak perlu menulis satu per satu secara manual.

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
1. **Grid system** — `col-12 col-md-6 col-lg-4` untuk menampilkan card yang secara otomatis menyesuaikan ukurannya dengan layar device.
2. **Card component** — `card`, `card-img-top`, `card-body`, `card-title`, `card-text` merupakan komponen bootsrtrap yang akan mengisi tampilan sertifikat.
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

Section ini menerapkan komponen Bootstrap dan Vue JS sebagai berikut:
1. **Grid system** — `col-12 col-lg-6` untuk membagi dua kolom 50:50 di desktop dan satu kolom penuh di mobile.
2. **Flex utility** — `d-flex flex-wrap gap-3` untuk menyusun tombol sosial media secara horizontal dan otomatis wrap ke baris baru jika tidak muat.
3. **Spacing utility** — `mt-4` untuk memberi jarak antara deskripsi dan deretan tombol sosial media tanpa menambah CSS manual.
4. **Vue JS `:class` binding** — `:class="soc.icon"` dan `:class="info.icon"` untuk mengikat class ikon Bootstrap Icons secara dinamis dari data, sehingga ikon berbeda dapat dirender dari satu template yang sama.

### CSS

CSS mengatur visual badge ketersediaan dan efek animasi:
- **`@keyframes kedip`** mendefinisikan animasi opacity dari `1 → 0.3 → 1` yang diterapkan pada `.avail-dot` dengan `animation: kedip 2s infinite`, menciptakan efek titik berkedip (*blinking dot*) yang menandakan status aktif secara visual.
- **`border-radius: 50px`** pada `.social-btn` menciptakan bentuk *pill button* yang modern, dikombinasikan dengan `transition` multi-property untuk menganimasi perubahan warna, border, dan background sekaligus saat hover.

</details>

---

<details>
<summary>Footer</summary>

Footer menampilkan teks copyright di kiri dan tautan *Back to top* di kanan. Tampilannya minimal dan konsisten dengan gaya keseluruhan website.

### HTML

Footer menggunakan Bootstrap utility classes sepenuhnya untuk layout:
1. **Flex utility** — `d-flex justify-content-between` untuk menempatkan copyright di kiri dan link di kanan secara otomatis dalam satu baris.
2. **Spacing utility** — `py-2` untuk padding vertikal tipis dan `mb-0` untuk menghilangkan margin bawah default elemen `<p>` agar tinggi footer tetap rapi.
3. **Flex utility** — `flex-wrap gap-3` agar di layar sangat kecil kedua elemen dapat turun ke baris baru tanpa menyebabkan *overflow* horizontal.

### CSS

CSS mengatur tampilan visual footer secara minimal:
- **`border-top: 1px solid #ece8e1`** memberikan garis pemisah tipis antara footer dan section di atasnya — teknik *hairline border* yang umum digunakan untuk transisi section yang bersih tanpa bayangan.
- **`transition: color 0.25s ease`** + **`:hover { color: #e8718a }`** pada link *Back to top* menjaga konsistensi warna aksen merah muda yang digunakan di seluruh website sebagai identitas visual.

</details>


## 🛠️ Teknologi yang Digunakan

| Teknologi | Versi | Kegunaan |
|---|---|---|
| **HTML5** | — | Struktur dan konten halaman web |
| **CSS3** | — | Styling visual, animasi, dan tampilan |
| **Bootstrap 5** | 5.3.2 | Grid system, komponen UI, dan responsive layout |
| **Bootstrap Icons** | 1.11.3 | Ikon-ikon pada navbar, tools, contact, dsb |
| **Vue JS** | 3 (CDN) | Rendering data dinamis dengan interpolasi `{{ }}` |
| **Google Fonts** | Poppins | Tipografi utama seluruh halaman |

> **Catatan:** Bootstrap, Vue JS, Google Fonts, dan Bootstrap Icons dimuat via CDN. Pastikan perangkat terhubung ke internet saat membuka website.

---

*© 2025 — Nayla Camelia Indraswari*
