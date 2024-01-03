# Pengenalan Wajah Redis-DeepFace

## Ikhtisar
Repositori ini berisi proyek pengenalan wajah yang memanfaatkan DeepFace untuk verifikasi wajah dan Redis untuk penyimpanan data. Kode ini mengekstrak embedding wajah dan membandingkannya untuk kemiripan.

## Struktur Repositori
- `tests/`: Direktori yang berisi gambar-gambar
- `.gitignore`: File gitignore yang menentukan file-file yang tidak terlacak untuk diabaikan.
- `Redis-DeepFace-Recognition.ipynb`: Jupyter notebook dengan implementasi pengenalan wajah utama.
- `Redis-Deepface.ipynb`: Jupyter notebook yang berisi dasar-dasar atau pengenalan tentang penggunaan DeepFace dan Redis.
- `requirements.txt`: Daftar paket python yang diperlukan untuk menjalankan proyek.
- `source.jpg`: Sebuah file gambar yang digunakan sebagai sumber dalam pengenalan wajah.
- `target.png`: Sebuah file gambar yang digunakan sebagai target dalam pengenalan wajah.

Baik, saya akan menambahkan langkah untuk mengkloning repositori menggunakan git sebelum langkah instalasi ketergantungan:

## Pengaturan dan Instalasi
Untuk menjalankan proyek ini, pertama-tama klon repositori menggunakan perintah berikut:

```bash
git clone https://github.com/z0zero/implementasi-vektor-redis.git
```
Pastikan untuk menjalankan perintah `git clone` di terminal atau command prompt pada direktori di mana Anda ingin proyek disimpan. Setelah kloning selesai, lanjutkan dengan instalasi ketergantungan menggunakan `pip`.

Kemudian instal ketergantungan yang diperlukan seperti yang terdaftar di `requirements.txt`:

```bash
pip install -r requirements.txt
```

Pastikan Anda telah menginstal dan menjalankan Redis di mesin lokal atau server Anda.

## Penggunaan
Jalankan buku catatan Jupyter untuk melakukan tugas pengenalan wajah:

- `Redis-DeepFace-Recognition.ipynb` untuk tugas pengenalan utama.
- `Redis-Deepface.ipynb` untuk fungsionalitas tambahan atau tes.

## Berkontribusi
Jangan ragu untuk mem-fork repositori ini dan berkontribusi dengan mengirimkan pull request.

## Lisensi
Proyek ini bersifat open source dan tersedia di bawah [Lisensi MIT](LICENSE).
