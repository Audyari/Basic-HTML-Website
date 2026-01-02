# Website Multi-Halaman HTML Dasar

Website multi-halaman responsif yang dibuat dengan HTML murni dan CSS, menampilkan tata letak CV/portofolio profesional.

## ✅ Fitur yang Sudah Diimplementasikan

Berikut adalah fitur-fitur yang sudah berhasil diimplementasikan dalam proyek ini:

### 1. ✅ Create Multiple Pages in a Website

- **Homepage.html**: Halaman utama CV/Portofolio dengan informasi lengkap
- **Projects.html**: Halaman showcase proyek dengan 4 project items
- **Articles.html**: Halaman blog/artikel dengan 4 preview artikel
- **Contact.html**: Halaman kontak dengan formulir dan informasi kontak

### 2. ✅ Structure a Website Using HTML in a Semantic Way

- Menggunakan elemen HTML5 semantik: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Hierarki heading yang tepat (h1, h2, dll.)
- Struktur konten yang logis dan terorganisir
- Elemen formulir semantik dengan label yang tepat

### 3. ✅ Structure in a Way That You Can Easily Add Styles Later

- **File CSS Terpisah**: Setiap halaman memiliki file CSS di folder `css/`
- **CSS Variables**: Semua warna, font, dan nilai yang sering digunakan didefinisikan di `:root`
- **Modular Components**: CSS dibagi menjadi kategori yang jelas
- **Class Naming**: Konsisten dan deskriptif
- **Separation of Concerns**: HTML untuk struktur, CSS untuk styling

### 4. ✅ Add SEO Meta Tags to the Website

- Meta tag viewport untuk responsive design
- Judul halaman yang deskriptif untuk setiap page
- Meta description untuk SEO
- Open Graph tags untuk social media sharing
- Twitter Card metadata

### 5. ✅ Contact Page with Form

- Formulir kontak lengkap dengan field:
  - Your Name (text input)
  - Your Email (email input)
  - Subject (text input)
  - Message (textarea)
  - Send Message button
- Semua field memiliki `required` attribute
- Placeholder text untuk panduan pengguna
- Label untuk accessibility
- Method POST untuk pengiriman data

## 📁 Struktur Proyek

```
d:/Belajar Web/HTML/Basic HTML Website/
├── css/             # Folder CSS terpisah
│   ├── homepage.css # Style untuk Homepage
│   ├── projects.css # Style untuk Projects
│   ├── articles.css # Style untuk Articles
│   └── contact.css  # Style untuk Contact
├── Homepage.html    # Halaman utama CV/Portofolio
├── Projects.html    # Halaman showcase proyek
├── Articles.html    # Halaman blog/artikel
├── Contact.html     # Halaman informasi kontak dan formulir
└── README.md        # File ini
```

## 🚀 Ringkasan Halaman

### Homepage.html

- **Tujuan**: Halaman utama CV/Portofolio
- **Konten**:
  - Header profesional dengan nama dan judul
  - Showcase proyek (2 item)
  - Bagian pengalaman kerja
  - Latar belakang pendidikan
  - Ulasan/testimoni guru
  - Footer dengan hak cipta

### Projects.html

- **Tujuan**: Portofolio proyek detail
- **Konten**:
  - 4 item proyek dengan deskripsi
  - Tag teknologi untuk setiap proyek
  - Link untuk melihat proyek
  - Efek hover untuk UX yang lebih baik

### Articles.html

- **Tujuan**: Postingan blog dan artikel
- **Konten**:
  - 4 preview artikel
  - Waktu baca dan tanggal publikasi
  - Kategori/tag artikel
  - Link "Baca Selengkapnya"

### Contact.html

- **Tujuan**: Informasi kontak dan komunikasi
- **Konten**:
  - Detail kontak (email, telepon, lokasi, LinkedIn)
  - Tombol media sosial
  - Formulir kontak (nama, email, subjek, pesan)
  - Tata letak responsif untuk mobile

## 🎨 Fitur Desain

### Sistem Desain Konsisten

- **Warna**:

  - Utama: `#2c3e50` (Dark Blue/Grey)
  - Aksen: `#3498db` (Biru)
  - Background: `#f4f4f4` (Light Grey)
  - Kertas: `#ffffff` (Putih)

- **Tipografi**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Tata Letak**: Container terpusat dengan tampilan seperti kertas
- **Responsif**: Pendekatan mobile-first dengan media queries

### Navigasi

- Navigasi konsisten di semua halaman
- Indikasi state aktif
- Efek hover
- Mobile-friendly (terstack pada layar kecil)

### SEO & Meta Tags

- Meta tag viewport yang tepat
- Judul dan deskripsi deskriptif

## 🔧 Fitur Teknis

### Elemen Semantik HTML5

- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Hierarki heading yang tepat
- Elemen formulir semantik

### Struktur CSS yang Terorganisir

- **File CSS Terpisah**: Setiap halaman memiliki file CSS di folder `css/`
- **CSS Variables**: Semua warna, font, dan nilai yang sering digunakan didefinisikan di `:root`
- **Modular Components**: CSS dibagi menjadi kategori yang jelas:
  - Variables & Reset
  - Layout & Container
  - Header Components
  - Navigation Components
  - Typography & Sections
  - Project/Article/Contact Components
  - Footer Components
  - Responsive Design
- **Flexbox untuk layout**: Konsisten di semua halaman
- **Media queries**: Breakpoint di 600px untuk mobile
- **Transisi hover**: Efek halus pada interaktifitas

### Aksesibilitas

- Struktur HTML semantik
- Label formulir yang tepat
- Kontras warna tinggi
- Ukuran font yang mudah dibaca
- Focus states (bisa ditambahkan)

### Kemudahan Pengembangan

- **CSS Variables**: Mudah mengubah warna dan tema
- **Class Naming**: Konsisten dan deskriptif
- **Component-based**: Setiap bagian memiliki class sendiri
- **Scalable**: Mudah menambahkan style baru
- **Separation of Concerns**: HTML untuk struktur, CSS untuk styling

## 📱 Desain Responsif

Website ini sepenuhnya responsif dengan breakpoint di:

- **Desktop**: Default (max-width: 800px container)
- **Mobile**: ≤600px (navigasi terstack, padding disesuaikan)

## 🎯 Penggunaan

1. **Buka Homepage**: Klik ganda `Homepage.html` atau buka di browser
2. **Navigasi**: Gunakan menu navigasi untuk beralih antar halaman
3. **Kontak**: Isi formulir di Contact.html (memerlukan backend untuk pengiriman aktual)

## 🔗 Alur Navigasi

```
Homepage.html → Projects.html
            → Articles.html
            → Contact.html
```

Setiap halaman memiliki link kembali ke semua halaman lain melalui menu navigasi yang konsisten.

## 📝 Kustomisasi

Untuk mengkustomisasi website ini:

1. **Update Nama**: Ganti "Audyari Wiyono" dengan nama Anda
2. **Update Konten**: Modifikasi teks di setiap file HTML
3. **Update Warna**: Ubah CSS variables di file CSS di folder `css/`
4. **Tambah Proyek**: Salin struktur project-item di Projects.html
5. **Tambah Artikel**: Salin struktur article-item di Articles.html
6. **Update Kontak**: Ganti detail kontak dan link media sosial
7. **Style Baru**: Tambahkan class dan style baru di file CSS terpisah

### Struktur CSS

- Semua style dipisahkan ke folder `css/`
- Setiap halaman memiliki file CSS sendiri
- Mudah mengubah theme dengan mengedit variabel CSS di `:root`

## 🚀 Langkah Selanjutnya

- [ ] Tambahkan link proyek aktual
- [ ] Buat artikel/konten nyata
- [ ] Implementasi backend formulir kontak (PHP, Node.js, dll.)
- [ ] Deploy ke hosting service
- [ ] Tambahkan JavaScript untuk interaktivitas yang lebih baik
- [ ] Implementasi dark mode toggle
- [ ] Optimasi performa dan loading

## 📋 Kompatibilitas Browser

- Chrome/Edge: ✅ Dukungan penuh
- Firefox: ✅ Dukungan penuh
- Safari: ✅ Dukungan penuh
- Browser mobile: ✅ Dukungan penuh

---

**Dibuat dengan HTML & CSS murni - Tanpa framework!**
