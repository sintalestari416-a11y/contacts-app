# 📱 Contacts App - React Management System

Selamat datang di **Contacts App**! Proyek ini adalah aplikasi manajemen kontak dinamis yang saya bangun untuk mendalami arsitektur komponen di React, pengelolaan *state* yang kompleks, serta alur data antar komponen.

## 🌟 Fitur Utama
* **Manajemen State Dinamis**: Menambahkan kontak baru dengan ID unik berbasis *timestamp* dan menghapus kontak berdasarkan ID secara instan tanpa reload halaman.
* **Controlled Form Components**: Mengimplementasikan form input yang tersinkronisasi sepenuhnya dengan *state* React untuk menangkap data nama dan tag pengguna.
* **Modular Component Architecture**: Membagi antarmuka menjadi komponen-komponen kecil yang dapat digunakan kembali (*reusable*) seperti `ContactItem`, `ContactList`, dan `DeleteButton`.
* **Data Persistence Logic**: Menggunakan logika *filtering* array untuk proses penghapusan data dan *spread operator* untuk penambahan data baru ke dalam list.

## 🛠️ Tech Stack & Library
* **React 18**: Pustaka inti untuk membangun antarmuka deklaratif.
* **Vite**: Build tool modern yang memberikan pengalaman pengembangan sangat cepat.
* **JavaScript (ES6+)**: Mengoptimalkan fitur terbaru seperti *destructuring*, *arrow functions*, dan *classes*.
* **CSS3**: Penataan letak kustom yang diimpor melalui `style.css`.

## 📂 Bedah Struktur Folder
* **`src/components/`**: Berisi seluruh komponen UI aplikasi.
    * `ContactApp.jsx`: *Brain* dari aplikasi yang memegang *source of truth* (state kontak).
    * `ContactInput.jsx`: Menangani logika input dan pengiriman data ke komponen induk.
    * `ContactList.jsx`: Bertugas memetakan (*mapping*) data kontak menjadi elemen visual.
* **`src/utils/`**: 
    * `data.js`: Menyediakan data *mockup* awal untuk inisialisasi aplikasi.
* **`Root Files`**:
    * `index.html`: Wadah utama untuk melakukan *mounting* aplikasi React.
    * `.prettierrc`: Standar pemformatan kode agar kodingan tetap bersih dan seragam.

## 🚀 Cara Menjalankan Secara Lokal
1. Pastikan Node.js sudah terinstal di perangkatmu.
2. Clone repositori ini.
3. Buka terminal, arahkan ke folder proyek, dan jalankan:
   ```bash
   npm install
