# Telkom University Company Profile - Praktikum  

Project simulasi HTML, CSS, PHP native, MySQL/MariaDB, dan Git.

## Dokumentasi Merge Conflict

Merge conflict terjadi ketika branch `main` dan `feature-navbar` mengubah baris label navigasi yang sama dengan isi berbeda. Git tidak dapat menentukan perubahan yang harus dipertahankan secara otomatis.

Penyelesaian dilakukan dengan membuka `includes/header.php`, memeriksa perubahan dari kedua branch, memilih label navigasi yang digunakan, dan menghapus penanda konflik `<<<<<<<`, `=======`, serta `>>>>>>>`. Setelah file diperbaiki, perubahan ditambahkan menggunakan `git add` dan merge diselesaikan melalui commit.

Perintah yang digunakan:
- `git merge feature-navbar`
- `git status`
- `git add includes/header.php`
- `git commit -m "merge: selesaikan conflict navbar"`

## Riwayat Praktikum Git

### 1. Pengembangan Project
Project company profile dikelola menggunakan Git dengan commit terpisah untuk konfigurasi repository, layout, stylesheet, halaman profil, koneksi database, program studi, berita, dan formulir kontak.

### 2. Feature Branch dan Merge
Branch `feature-navbar` dibuat untuk mengembangkan perubahan navigasi secara terpisah. Setelah perubahan selesai, branch digabungkan ke `main` menggunakan perintah `git merge`.

### 3. Penyelesaian Merge Conflict
Simulasi konflik dilakukan dengan mengubah baris label navigasi yang sama pada branch `main` dan `feature-navbar`. Konflik diselesaikan dengan memilih isi akhir yang sesuai, menghapus penanda konflik, lalu membuat commit merge.

### 4. Simulasi Kolaborasi
Repository di-clone ke folder kedua. Perubahan README dilakukan dan di-commit dari folder kedua, kemudian di-push ke GitHub dan di-pull kembali pada folder pertama.

### 5. Release
Tag `v1.0.0` dibuat sebagai penanda versi final project praktikum.

### 6. Riwayat Commit
Output `git log --oneline --graph --decorate --all` dilampirkan di bawah bagian ini.

* 01366d9 (HEAD -> main, origin/main) docs: tambahkan riwayat praktikum Git
* 96f1024 (tag: v1.0.0) docs: dokumentasikan penyelesaian merge conflict
*   cd884f6 merge: selesaikan conflict navbar
|\  
| * 8331164 (feature-navbar) feat: perbarui label profil pada feature branch
* | bec894a style: perbarui label profil pada main
|/  
* 984e833 (origin/feature-navbar) feat: ubah label navigasi profil
* 643c7e8 feat: tambahkan formulir kontak
* e96c33d feat: tambahkan daftar dan detail berita
* 544c924 feat: tampilkan data program studi
* 79ed25e feat: hubungkan aplikasi dengan database
:
* 01366d9 (HEAD -> main, origin/main) docs: tambahkan riwayat praktikum Git
* 96f1024 (tag: v1.0.0) docs: dokumentasikan penyelesaian merge conflict
*   cd884f6 merge: selesaikan conflict navbar
|\  
| * 8331164 (feature-navbar) feat: perbarui label profil pada feature branch
* | bec894a style: perbarui label profil pada main
|/  
* 984e833 (origin/feature-navbar) feat: ubah label navigasi profil
* 643c7e8 feat: tambahkan formulir kontak
* e96c33d feat: tambahkan daftar dan detail berita
* 544c924 feat: tampilkan data program studi
* 79ed25e feat: hubungkan aplikasi dengan database
* b64a5d7 feat: tambahkan halaman beranda dan profil
* d64e3c9 style: tambahkan stylesheet company profile
* 63330bf feat: tambahkan layout header dan footer
* 75fb98d chore: inisialisasi konfigurasi repository
* df1ad44 first commit
~
~
~
~
~
(END)
* 01366d9 (HEAD -> main, origin/main) docs: tambahkan riwayat praktikum Git
* 96f1024 (tag: v1.0.0) docs: dokumentasikan penyelesaian merge conflict
*   cd884f6 merge: selesaikan conflict navbar
|\  
| * 8331164 (feature-navbar) feat: perbarui label profil pada feature branch
* | bec894a style: perbarui label profil pada main
|/  
* 984e833 (origin/feature-navbar) feat: ubah label navigasi profil
* 643c7e8 feat: tambahkan formulir kontak
* e96c33d feat: tambahkan daftar dan detail berita
* 544c924 feat: tampilkan data program studi
* 79ed25e feat: hubungkan aplikasi dengan database
* b64a5d7 feat: tambahkan halaman beranda dan profil
* d64e3c9 style: tambahkan stylesheet company profile
* 63330bf feat: tambahkan layout header dan footer
* 75fb98d chore: inisialisasi konfigurasi repository
* df1ad44 first commit
~
~
~
~
~
~
(END)
* 01366d9 (HEAD -> main, origin/main) docs: tambahkan riwayat praktikum Git
* 96f1024 (tag: v1.0.0) docs: dokumentasikan penyelesaian merge conflict
*   cd884f6 merge: selesaikan conflict navbar
|\  
| * 8331164 (feature-navbar) feat: perbarui label profil pada feature branch
* | bec894a style: perbarui label profil pada main
|/  
* 984e833 (origin/feature-navbar) feat: ubah label navigasi profil
* 643c7e8 feat: tambahkan formulir kontak
* e96c33d feat: tambahkan daftar dan detail berita
* 544c924 feat: tampilkan data program studi
* 79ed25e feat: hubungkan aplikasi dengan database
* b64a5d7 feat: tambahkan halaman beranda dan profil
* d64e3c9 style: tambahkan stylesheet company profile
* 63330bf feat: tambahkan layout header dan footer
* 75fb98d chore: inisialisasi konfigurasi repository
* df1ad44 first commit
~
~
~
~
~
~
~
(END)