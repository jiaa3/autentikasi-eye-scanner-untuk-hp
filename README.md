---

# Autentikasi Pemindai Mata untuk Ponsel

Proyek ini mengimplementasikan sistem autentikasi biometrik inovatif menggunakan pemindai mata untuk ponsel. Teknologi ini memanfaatkan teknik computer vision untuk mengenali pola iris dan retina, memastikan autentikasi yang aman dan andal.

## Introduce
Nama : Nurjiha
NIM : 2400515
Kelas : 1b MKB

## Fitur
- **Pengenalan Iris**: Mengidentifikasi pola unik iris mata untuk autentikasi pengguna.
- **Pemindaian Retina**: Menganalisis pola retina untuk tingkat keamanan yang lebih tinggi.
- **Antarmuka Mobile**: Dikembangkan menggunakan Flutter/React Native, mendukung platform iOS dan Android.
- **Keamanan Biometrik**: Data biometrik disimpan secara lokal di perangkat menggunakan enkripsi dan trusted execution environment (TEE).
- **Optimasi Kinerja**: Algoritma yang dioptimalkan untuk berbagai kondisi pencahayaan dan penggunaan sumber daya perangkat yang efisien.

## Teknologi yang Digunakan
- **OpenCV**: Digunakan untuk deteksi wajah dan mata.
- **Dlib**: Digunakan untuk pelacakan fitur wajah.
- **Kotlin/Java**: Untuk pengembangan aplikasi Android dan integrasi kamera.
- **BiometricPrompt API**: Digunakan untuk autentikasi biometrik di perangkat Android.

## Cara Kerja
1. Sistem mendeteksi wajah dan mengekstrak area mata menggunakan OpenCV.
2. Setelah area mata diidentifikasi, sistem melakukan segmentasi iris/retina dan menganalisis pola unik.
3. Hasil analisis digunakan untuk verifikasi pengguna melalui BiometricPrompt API.

## Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/jiaa3/autentikasi-eye-scanner-untuk-hp.git
   ```
2. Instal dependensi:
   ```bash
   flutter pub get
   ```
3. Jalankan aplikasi di emulator atau perangkat:
   ```bash
   flutter run
   ```

## Ilustrasi Proyek
Berikut adalah ilustrasi proyek ini:

[![Ilustrasi Autentikasi Pemindai Mata](https://s0.bukalapak.com/uploads/content_attachment/5b775b9c244a2d1b0eef78b5/original/shutterstock_25297264.jpeg)](https://s0.bukalapak.com/uploads/content_attachment/5b775b9c244a2d1b0eef78b5/original/shutterstock_25297264.jpeg)

## Kontribusi
Kami menyambut kontribusi untuk pengembangan lebih lanjut! Silakan kirim pull request atau buka issue untuk diskusi.

## Lisensi
Proyek ini dilisensikan di bawah MIT License. Lihat berkas [LICENSE](LICENSE) untuk informasi lebih lanjut.

---
