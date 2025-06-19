# Simulasi UTBK CBT (Computer Based Test)

Proyek ini berisi simulasi UTBK berbasis HTML yang dapat dijalankan secara offline maupun online. Dirancang untuk latihan soal TPS dan TKA bagi siswa SMA dan peserta UTBK.

## 🎯 Fitur
- Soal pilihan ganda dengan skor otomatis
- Tampilan mirip CBT asli
- Bisa dijalankan di browser (PC & HP)
- Tidak butuh aplikasi tambahan untuk pengguna PC

## 📱 Cara Membuka di HP (Android)
File HTML **tidak bisa langsung dibuka di HP**, harus melalui **localhost** menggunakan server ringan. Berikut panduan:

### 🔧 Langkah-langkah via Termux:
1. Install **Termux** dari F-Droid (bukan Play Store)
2. Buka Termux, ketik:
   ```bash
   pkg update
   pkg install python
   cd /sdcard/NamaFolderHTML
   python -m http.server 8080

3. Buka browser HP dan akses:

http://localhost:8080


4. Klik index.html untuk memulai kuis



📌 Alternatif: Upload ke GitHub Pages atau Netlify untuk akses tanpa server lokal

💻 Cara Menjalankan di PC

1. Download atau clone repository ini


2. Buka file index.html langsung di browser (Chrome/Firefox)



🚀 Struktur Folder

index.html → Halaman utama kuis

assets/ → File pendukung (gambar, audio, dll)

style.css, script.js → (jika ada) tampilan & logika kuis


👨‍🎓 Untuk Siapa?

Siswa SMA

Peserta UTBK

Guru atau bimbel yang ingin memberikan latihan CBT



---

💡 Proyek ini gratis untuk digunakan, dibagikan, dan dimodifikasi untuk keperluan pendidikan.
