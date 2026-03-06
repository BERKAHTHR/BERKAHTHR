# 🌙 BerkahTHR - Program Berbagi Berkah Ramadhan & Idul Fitri

![BerkahTHR Banner](https://img.shields.io/badge/Status-Aktif-success) ![License](https://img.shields.io/badge/License-Free-blue)

## 📖 Tentang Proyek
**BerkahTHR** adalah sebuah aplikasi web interaktif *Single Page Application* (SPA) yang dirancang untuk membagikan Tunjangan Hari Raya (THR) secara digital melalui tautan atau QR Code DANA Kaget. Web ini mengusung tema Ramadhan dan Idul Fitri, memberikan pengalaman interaktif yang menyenangkan dan bermakna bagi pengunjung sebelum mengklaim rezeki mereka.

Proyek ini sangat cocok digunakan oleh *content creator*, komunitas, atau individu yang ingin berbagi saldo DANA dengan cara yang unik dan tidak biasa.

## ✨ Fitur Utama
* ⏳ **Sistem Hitung Mundur (Countdown):** Akses klaim dan kuis akan terkunci hingga waktu yang telah ditentukan (contoh: 21 Maret 2026).
* 🎵 **Smart Audio Player:** * Memutar lagu nasyid khusus saat masa tunggu (countdown).
    * Memutar lagu berbeda saat masa klaim sudah dibuka.
    * Menggunakan trik *Pop-Up Interaktif* untuk mem-bypass pemblokiran *autoplay* pada browser modern.
* 📝 **Kuis Wawasan Islami:** Pengunjung diwajibkan menjawab beberapa pertanyaan pilihan ganda seputar bulan Ramadhan sebagai syarat verifikasi.
* 💰 **Integrasi DANA Kaget:** Menampilkan QR Code yang bisa diunduh dan tombol tautan langsung (Direct Link) untuk klaim saldo DANA.
* ☁️ **Real-time Database:** Terintegrasi langsung dengan **Firebase Firestore** untuk merekam nama lengkap pengunjung dan riwayat jawaban kuis mereka secara aman.
* 📱 **Responsive & Modern UI:** Menggunakan desain *Card 3D*, animasi *floating*, dan skema warna bernuansa hijau-emas yang elegan.

## 🛠️ Teknologi yang Digunakan
* **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6)
* **Backend/Database:** Firebase Firestore (BaaS)
* **Assets:** Audio (MP3) & Gambar (JPG/PNG)

## 🚀 Persiapan & Cara Penggunaan
Jika kamu ingin menggunakan *source code* ini untuk program bag-bagi THR kamu sendiri, ikuti langkah berikut:

1. **Clone/Download Repository:**
   ```bash
   git clone [https://github.com/USERNAME_KAMU/berkah-thr.git](https://github.com/USERNAME_KAMU/berkah-thr.git)
