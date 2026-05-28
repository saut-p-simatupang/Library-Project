# 📚 Perpustakaan Digital Desa Tambaksari

> Website perpustakaan digital modern untuk desa – katalog buku online dari Google Drive dengan antarmuka seperti Netflix/Gramedia.

🌐 Live Demo
https://perpustakaan-desa-tambaksari.netlify.app

## ✨ Fitur Unggulan

- 📖 **Koleksi Buku Otomatis** – Staf desa cukup upload PDF ke Google Drive, website langsung menampilkan.
- 🏷️ **Kategori Dinamis** – Nama folder di Drive otomatis menjadi kategori buku.
- 🔍 **Pencarian & Filter** – Cari judul buku, filter berdasarkan kategori.
- 📌 **Bookmark** – Pengguna bisa menandai buku favorit (tersimpan di browser).
- 📱 **Responsif & Modern** – Tampilan nyaman di desktop, tablet, dan ponsel.
- 🌙 **Dark Mode First** – Desain elegan dengan latar gelap, nyaman dibaca.
- ⚡ **Cepat & Ringan** – Memanggil Google Drive API secara langsung, tanpa backend.
- 🎨 **UI/UX Kelas Profesional** – Terinspirasi dari Google Books, Gramedia Digital, dan Netflix.

## 🛠️ Teknologi yang Digunakan

- **HTML5**, **CSS3**, **JavaScript (ES6)**
- **Google Drive API v3** – untuk membaca file PDF dan thumbnail
- **Font Awesome** – ikon keren
- **Google Fonts (Inter)** – tipografi modern
- **LocalStorage** – menyimpan data bookmark

## 🚀 Cara Deploy (Gratis)

1. **Clone repo ini** atau download file `index.html`
2. **Buat API Key** di [Google Cloud Console](https://console.cloud.google.com) (aktifkan Google Drive API)
3. **Buat folder publik** di Google Drive, isi dengan file PDF, lalu bagikan dengan akses "Anyone with the link can view"
4. **Ganti `API_KEY` dan `FOLDER_ID`** di file `index.html`
5. **Deploy ke Netlify** – drag and drop folder ke [netlify.com](https://netlify.com) → selesai!

Atau Anda bisa langsung menggunakan versi live demo (ganti dengan URL Netlify Anda nanti).

## 📂 Struktur Folder Google Drive (Contoh)
📁 Buku Perpustakaan (ID: 1qMGVgwfiTm...)
├── 📁 PENDIDIKAN
│   ├── matematika.pdf
│   └── ipa.pdf
├── 📁 NOVEL
│   └── tenggelamnya-kapal-van-der-wijck.pdf
├── 📁 BANK SOAL
│   ├── soal-um-ugm-2016.pdf
│   └── soal-um-ugm-2017.pdf
├── 📁 UMUM
│   └── peraturan-desa.pdf
└── 📁 ANAK
    └── dongeng-kancil.pdf

