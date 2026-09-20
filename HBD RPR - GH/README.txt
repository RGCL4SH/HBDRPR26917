PANDUAN GITHUB PAGES - WEBSITE ULANG TAHUN

Folder:
website_ultah_github_pages/
├── index.html
├── .nojekyll
└── photos/
    ├── 001.jpg
    ├── 002.jpg
    ├── 003.jpg
    └── ... sampai 050.jpg

1. Masukkan foto ke folder photos.
2. Nama file harus:
   001.jpg
   002.jpg
   003.jpg
   ...
   050.jpg

3. Buka index.html memakai Notepad jika ingin mengubah:
   - nama teman
   - ucapan ulang tahun

4. Buat repository baru di GitHub.

5. Upload:
   index.html
   .nojekyll
   folder photos beserta semua foto

6. Di repository GitHub:
   Settings → Pages
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   Save

7. Link website biasanya:
   https://USERNAME.github.io/NAMA-REPOSITORY/

Untuk menambah foto:
- taruh foto baru ke folder photos
- misalnya 051.jpg
- kalau ingin lebih dari 50 foto, ubah:
  const MAX_PHOTOS = 50;
  menjadi jumlah yang diperlukan.

Untuk mengubah desain atau fitur, cukup ubah index.html lalu upload/push versi terbaru ke repository.
