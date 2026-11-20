
# Rancangan Pipeline CI/CD

## Nama Proyek
Aplikasi Toko Online Sederhana

## 1. Source Control
- Platform: GitHub
- Version Control: Git
- Repository: hello-world
- Branch utama: master

## 2. Build
- Bahasa pemrograman: PHP
- Menyiapkan file aplikasi.
- Memeriksa struktur dan dependensi proyek.
- Tools: PHP dan Composer.

## 3. Test
- Menjalankan pengujian aplikasi.
- Memeriksa kesalahan kode PHP.
- Tools: PHPUnit dan PHP CodeSniffer.

## 4. Security Scanning
- Memeriksa kerentanan dependensi.
- Memeriksa potensi masalah keamanan pada kode.
- Tools: GitHub Dependabot dan Composer Audit.

## 5. Artifact Generation
- Mengumpulkan file aplikasi.
- Membuat file ZIP sebagai hasil build.
- Menyimpan artifact agar dapat digunakan pada tahap deployment.

## 6. Deployment
- Mengunggah aplikasi ke server.
- Memastikan aplikasi dapat diakses.
- Melakukan pengecekan setelah deployment.

## Trigger Pipeline
- Branch: master
- Event: push dan pull request.
- Pipeline dijalankan ketika terdapat perubahan kode yang dikirim ke branch master.


