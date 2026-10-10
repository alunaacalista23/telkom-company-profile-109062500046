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