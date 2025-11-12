# 🌍 PT United Tractors Tbk — Landing Page Website

![Screenshot Halaman Utama](./screenshot-homepage.png)
> 🖼️ *Ganti gambar di atas dengan hasil tangkapan layar (screenshot) halaman websitemu.*

---

## 📘 Deskripsi Proyek

Website ini merupakan **landing page resmi fiktif PT United Tractors Tbk**, dirancang untuk menampilkan profil perusahaan, lini bisnis utama, dan informasi kontak dalam tampilan modern dan responsif berbasis **Tailwind CSS**.  
Tujuan pembuatan halaman ini adalah untuk **menunjukkan citra profesional perusahaan industri alat berat** dengan pendekatan visual yang bersih, elegan, dan mudah diakses dari berbagai perangkat.

---

## 🧩 Fitur Utama

### 🟡 **1. Navigasi Responsif**
- Navbar tetap (fixed top) dengan logo dan menu interaktif.
- Dropdown “Layanan & Produk” dengan animasi `fade-in-up`.
- Menu mobile dengan tombol hamburger yang otomatis menyesuaikan layar kecil.

### ⚙️ **2. Hero Section (Halaman Utama)**
- Latar belakang foto industri (`background-image`) dengan overlay gradasi hitam transparan.
- Animasi teks masuk (`animate-fade-in-up`) dari bawah.
- Tombol CTA:
  - **Jelajahi Solusi**
  - **Hubungi Kami**

### 🏗️ **3. Lini Bisnis (Fitur Utama)**
Tiga kategori utama:
- **Mesin Konstruksi**
- **Kontraktor Penambangan**
- **Energi & Konstruksi**

Setiap kategori ditampilkan dalam *card* dengan efek hover interaktif dan ikon SVG.

### 🧱 **4. Detail Setiap Lini Bisnis**
- Menampilkan gambar (`konstruksi.png`, `pertambangan.png`, `energi.png`)
- Deskripsi lengkap per sektor dengan tata letak grid responsif (`lg:grid-cols-2`)

### 🏢 **5. Tentang Kami**
- Bagian profil perusahaan dengan efek dekoratif (border kuning & pola titik).
- Teks menjelaskan sejarah berdirinya perusahaan sejak 1972.

### ✉️ **6. Hubungi Kami**
- Informasi kontak kantor pusat, UT Call, dan Instagram resmi.
- Formulir kontak interaktif dengan animasi pesan sukses.
- Efek blur dekoratif dengan lingkaran berwarna.

### ⚫ **7. Footer**
- Empat kolom navigasi: *Perusahaan, Solusi, Bantuan, dan Profil*.
- Hak cipta dan tautan kebijakan privasi.

---

## 🛠️ **Teknologi yang Digunakan**

| Teknologi | Keterangan |
|------------|-------------|
| **HTML5** | Struktur halaman dan elemen semantik |
| **Tailwind CSS (via CDN)** | Framework CSS utility-first untuk styling cepat |
| **JavaScript (Vanilla)** | Efek interaktif seperti form dan navbar scroll |
| **Google Fonts - Roboto** | Font utama website |
| **Unsplash** | Sumber gambar bebas lisensi |

---

## 🧾 **Struktur File Utama**

```bash
project-folder/
│
├── index.html                 # File utama website
├── konstruksi.png             # Gambar untuk section mesin konstruksi
├── pertambangan.png           # Gambar untuk section kontraktor tambang
├── energi.png                 # Gambar untuk section energi
├── screenshot-homepage.png    # Screenshot tampilan web (untuk README)
└── README.md                  # Dokumentasi proyek
