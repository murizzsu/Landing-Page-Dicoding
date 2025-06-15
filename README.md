# 🚀 Latihan Membangun Landing Page - Dicoding

Proyek ini bertujuan untuk memahami dan menerapkan teknik dasar dalam membangun **landing page** menggunakan **HTML**, **CSS**, dan berbagai sumber daya tambahan.

## 📌 Alur Pengerjaan
Berikut langkah-langkah utama dalam membangun landing page:

### 1️⃣ Membuat dan Membuka Proyek Baru
- Buat folder proyek untuk menyimpan semua file yang dibutuhkan.
- Buka folder menggunakan **Visual Studio Code** atau editor pilihan Anda.

### 2️⃣ Membuat Struktur Proyek dan Aset-aset yang Dibutuhkan
- Siapkan folder `assets/` untuk menyimpan gambar, ikon, dan file lainnya.
- Buat file utama:  
  ```sh
  index.html
  style.css
  ```
- Pastikan semua file proyek berada dalam struktur yang tertata.

### 3️⃣ Membuat Struktur Navigation Bar
- Gunakan elemen `<nav>` untuk membangun bar navigasi:
  ```html
  <nav>
    <ul>
      <li><a href="#">Beranda</a></li>
      <li><a href="#">Tentang</a></li>
      <li><a href="#">Kontak</a></li>
    </ul>
  </nav>
  ```
- Gunakan **CSS Flexbox** untuk menata navigasi agar responsif.

### 4️⃣ Memasang Font Quicksand dari Google Fonts
Tambahkan link berikut di bagian `<head>` pada `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;700&display=swap" rel="stylesheet">
```
Lalu terapkan di `style.css`:
```css
body {
  font-family: 'Quicksand', sans-serif;
}
```

### 5️⃣ Menerapkan Styling Dasar Proyek dan Bar Navigasi
- Tambahkan aturan dasar dalam `style.css`:
  ```css
  body {
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
  }

  nav {
    display: flex;
    justify-content: space-between;
    background-color: #333;
    padding: 10px;
  }

  nav ul {
    list-style: none;
    display: flex;
  }

  nav ul li {
    margin: 0 15px;
  }

  nav ul li a {
    text-decoration: none;
    color: white;
  }
  ```
- Gunakan **Flexbox** agar tata letak navigasi lebih rapi.

### 6️⃣ Menambahkan Struktur Konten Utama pada Dokumen HTML
- Gunakan elemen `<section>` dan `<article>` untuk menampilkan konten:
  ```html
  <section class="hero">
    <h1>Selamat Datang di Landing Page!</h1>
    <p>Bangun halaman web yang menarik dan responsif.</p>
  </section>
  ```
- Pastikan menggunakan **div atau section** untuk pemisahan konten utama.

### 7️⃣ Menampilkan Ikon Sosial Media dengan Font Awesome melalui CDN
Tambahkan **CDN** Font Awesome di `<head>`:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
```
Gunakan ikon sosial media dalam HTML:
```html
<div class="social-icons">
  <a href="#"><i class="fab fa-facebook"></i></a>
  <a href="#"><i class="fab fa-twitter"></i></a>
  <a href="#"><i class="fab fa-instagram"></i></a>
</div>
```

### 8️⃣ Melakukan Styling pada Konten Utama Halaman
Tambahkan CSS agar konten utama tampak menarik:
```css
.hero {
  text-align: center;
  padding: 50px;
  background-color: #fff;
}

.hero h1 {
  font-size: 2.5rem;
  color: #333;
}

.social-icons {
  display: flex;
  justify-content: center;
  gap: 15px;
}
```

### 9️⃣ Menjalankan Dokumen HTML pada Browser
- Buka file `index.html` langsung di browser.
- Atau gunakan ekstensi **Live Server** di VS Code untuk melihat perubahan secara langsung.

## 🚀 Teknologi yang Digunakan
- **HTML5** → Struktur halaman.
- **CSS3** → Desain dan tampilan.
- **Google Fonts** → Font Quicksand untuk tampilan teks.
- **Font Awesome** → Ikon sosial media.
- **Flexbox & Grid** → Tata letak yang responsif.

## 🎯 Tujuan
Latihan ini bertujuan untuk memahami dan menerapkan teknik dasar dalam membangun **landing page** yang responsif dan menarik.

---


