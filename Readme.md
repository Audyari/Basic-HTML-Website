# Website Multi-Halaman HTML Dasar

Website multi-halaman responsif yang dibuat dengan HTML murni dan CSS, menampilkan tata letak CV/portofolio profesional.

## 📁 Struktur Proyek

```
d:/Belajar Web/HTML/Basic HTML Website/
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

### Fitur CSS3

- CSS Variables (Custom Properties)
- Flexbox untuk layout
- Media queries untuk responsivitas
- Transisi hover dan efek
- Box-shadow untuk kedalaman
- Border-radius untuk tampilan modern

### Aksesibilitas

- Struktur HTML semantik
- Label formulir yang tepat
- Kontras warna tinggi
- Ukuran font yang mudah dibaca
- Focus states (bisa ditambahkan)

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
3. **Update Warna**: Ubah CSS variables di bagian `<style>`
4. **Tambah Proyek**: Salin struktur project-item di Projects.html
5. **Tambah Artikel**: Salin struktur article-item di Articles.html
6. **Update Kontak**: Ganti detail kontak dan link media sosial

## 🚀 Langkah Selanjutnya

- [ ] Tambahkan link proyek aktual
- [ ] Buat artikel/konten nyata
- [ ] Implementasi backend formulir kontak (PHP, Node.js, dll.)
- [ ] Deploy ke hosting service
- [ ] Tambahkan JavaScript untuk interaktivitas yang lebih baik
- [ ] Implementasi dark mode toggle

## 📋 Kompatibilitas Browser

- Chrome/Edge: ✅ Dukungan penuh
- Firefox: ✅ Dukungan penuh
- Safari: ✅ Dukungan penuh
- Browser mobile: ✅ Dukungan penuh

---

**Dibuat dengan HTML & CSS murni - Tanpa framework!**
