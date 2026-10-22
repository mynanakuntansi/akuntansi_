# AKUN LMS

AKUN LMS adalah prototipe antarmuka Learning Management System untuk siswa SMK jurusan Akuntansi dan Keuangan Lembaga (AKL).

## Fitur demo
- Dashboard dengan dua tampilan peran: Guru dan Siswa.
- Navigasi sidebar responsif dan navbar.
- Ringkasan statistik, grafik nilai, daftar kelas, aktivitas, dan tugas.
- Daftar materi dengan pencarian dan filter.
- Form tambah materi, tugas, dan LKPD.
- Form pengerjaan tugas dan penilaian demo.
- Penyimpanan perubahan pada `localStorage` browser.
- Tampilan responsif untuk desktop, tablet, dan ponsel.

## Menjalankan secara lokal
1. Unduh atau clone repositori ini.
2. Buka `index.html` di browser. Untuk pengalaman pengembangan yang lebih baik, jalankan dengan ekstensi Live Server pada VS Code.

Tidak diperlukan proses build atau instalasi dependensi.

## Deploy ke GitHub Pages
1. Buat repositori baru di GitHub.
2. Unggah `index.html`, `style.css`, `app.js`, `README.md`, dan `.gitignore` ke direktori utama repositori.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu tekan **Save**.
6. Tunggu proses publikasi selesai. URL website akan muncul di bagian GitHub Pages.

## Catatan penting
Ini adalah **prototipe frontend/demo**, bukan sistem produksi. Data contoh dan perubahan disimpan di browser pengguna melalui `localStorage`; data tidak tersinkron antarperangkat dan tidak dibagikan kepada guru atau siswa lain. Login, keamanan akun, database terpusat, upload file sungguhan, dan pengelolaan hak akses produksi belum diterapkan. Untuk LMS sekolah yang dipakai sungguhan, tambahkan backend/API, database, autentikasi aman, validasi server, dan aturan akses per peran.

## Struktur proyek
```text
akun-lms-github/
├── index.html
├── style.css
├── app.js
├── README.md
└── .gitignore
```

## Identitas visual
- Navy: `#173B57`
- Biru: `#3478B8`
- Teal: `#35A99A`
- Latar: `#F6F8FB`
- Font: Inter
