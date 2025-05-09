# 🏎️ RaceBox GPS

**RaceBox GPS** adalah web app berbasis HTML, CSS, dan JavaScript yang memungkinkan pengguna mengukur kecepatan dan waktu tempuh kendaraan secara real-time menggunakan **GPS**, menargetkan jarak tertentu, serta menampilkan grafik kecepatan dan hasil pengukuran dalam file **CSV**.

---

## ✨ Fitur

- ⏱️ Mengukur waktu tempuh dari titik awal ke jarak yang ditentukan.
- 📡 Mendapatkan kecepatan kendaraan secara real-time menggunakan **GPS**.
- 📈 Menampilkan **grafik kecepatan** selama pengukuran.
- 📁 Menyimpan hasil ke dalam **file CSV** yang bisa diunduh.
- 🔁 Peringatan otomatis agar pengguna menggunakan **mode landscape** (miring) untuk tampilan optimal.
- 📱 Desain responsif dan cocok untuk digunakan di **smartphone/tablet**.

---

## 🚀 Cara Menggunakan

1. Buka file `index.html` di browser smartphone dengan akses GPS (Chrome/Safari).
2. Masukkan jarak target dalam meter (misalnya: `100`).
3. Klik **Mulai**.
4. Berjalan atau berkendara hingga mencapai jarak tersebut.
5. Setelah selesai:
   - Waktu dan kecepatan akan ditampilkan.
   - Grafik kecepatan akan muncul.
   - Anda dapat menekan tombol **Download CSV** untuk menyimpan datanya.

---

## 📦 Struktur File

racebox-gps/
│
├── index.html # Halaman utama web
└── README.md # Dokumentasi ini

---

## 📊 Contoh Output CSV

Waktu (detik),Kecepatan (km/h),Total Jarak (meter)
0,0.00,0
1,12.34,5
2,16.50,15


---

## ⚠️ Catatan

- Aplikasi membutuhkan **izin lokasi GPS**.
- Akurasi tergantung perangkat dan kondisi sinyal GPS.
- Ideal digunakan untuk jarak > 50 meter.

---

## 🛠️ Dibangun dengan

- HTML5, CSS3
- JavaScript Vanilla
- Chart.js
- SweetAlert2

---

## 📃 Lisensi

Proyek ini bersifat open-source dan bebas digunakan untuk keperluan pribadi maupun edukasi.

---

