LEMBUR PKS - HTML MURNI (TANPA NODE.JS / NPM)

JALANKAN DI XAMPP:
1. Ekstrak folder lembur-pks-web-html ke C:\xampp\htdocs\
2. Jalankan Apache dari XAMPP Control Panel.
3. Buka http://localhost/lembur-pks-web-html/

FITUR ARSIP PERIODE:
- Data disimpan terpisah per bulan di browser yang sama.
- Bulan sebelumnya tampil di menu kiri sebagai arsip dan hanya bisa dilihat, tidak bisa diedit.
- Bulan berjalan bisa diisi dan diedit; pergantian bulan tidak menghapus arsip bulan sebelumnya.
- Penyimpanan menggunakan localStorage browser ini; data tidak tersinkronisasi otomatis antarperangkat.
- Ekspor CSV per periode dapat dibuka di Excel.

Kolom input: Jam Masuk, Jam Keluar, Istirahat Mulai, Istirahat Selesai.
Jam mulai lembur, jam selesai lembur, dan total lembur dihitung otomatis.
Untuk deploy Vercel, upload isi folder ini ke repository GitHub lalu import sebagai project static. Tidak perlu build command.
