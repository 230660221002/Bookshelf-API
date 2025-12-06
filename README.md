**Bookshelf API – Dicoding Submission**

Bookshelf API adalah sebuah layanan backend sederhana yang dibangun menggunakan Hapi.js. API ini digunakan untuk mengelola data buku, seperti menambah, menampilkan, memperbarui, dan menghapus data buku. Proyek ini dibuat sebagai bagian dari tugas Belajar Membuat Aplikasi Back-End untuk Pemula dari Dicoding.

**📌 Fitur Utama:**

Bookshelf API menyediakan fitur berikut:

- Menambahkan buku baru
- Menampilkan seluruh buku
- Menampilkan detail buku berdasarkan ID
- Memperbarui data buku
- Menghapus buku
Seluruh data disimpan di dalam array lokal (books.js) tanpa database eksternal.

**📁 Struktur Proyek**

```
bookshelfapi/
├── src/
│   ├── server.js
│   ├── routes/
│   │   └── books.js
│   ├── handler/
│   │   └── booksHandler.js
│   └── books.js
│   └── server.js
├── package.json
└── package-lock.json
```

**🚀 Cara Menjalankan Proyek**

### 1. Clone Repository & Masuk ke Folder
```bash
cd Bookself-API
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Jalankan di Mode Development
```bash
npm run start-dev
```

### 4. Server akan berjalan di:
```
http://localhost:9000
```

**📜 Lisensi & Hak Cipta**
```
© 2025 Galih Permana.
All rights reserved.
```