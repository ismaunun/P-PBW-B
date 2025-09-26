# Pemrograman Berbasis Website

## Informasi Dosen
- *Nama Dosen:* Bambang Riono Arsad, S.Kom., MMSI

## Mahasiswa
- *Nama:* Syoba Ismaunun  
- *NPM:* 4523210107

## Tujuan
- Memahami konsep dasar pemrograman web.  
- Mampu membuat aplikasi web sederhana.  
- Menguasai alat dan teknologi yang diperlukan dalam pengembangan web.
- Menguasai Cara Menghubungkan Git ke GitHub

# Langkah-Langkah Pengerjaan
## 1. Bagian 1: Instalasi dan Konfigurasi Git
### Instalasi Git (Windows)
1. Unduh installer: https://git-scm.com/download/win 
2. Jalankan file .exe yang diunduh. 
3. Saat instalasi, biarkan pengaturan default lalu klik “Next” hingga selesai. 
4. Buka Command Prompt atau Git Bash, jalankan: git --version

### Konfigurasi Awal (Wajib) 
Buka terminal/Command Prompt, lalu konfigurasikan nama dan email (terekam pada setiap 
commit): 

git config --global user.name "Nama Kamu" 
git config --global user.email "email@kamu.com"


## Bagian 2: Alur Kerja Dasar Git
1. Buat Folder & Inisiasi Git

mkdir proyek-web 
cd proyek-web 
git init

2. Buat Beberapa File
   - Open VSCode
   - Buat File PHP
   - Code

echo "<h1>Selamat Datang</h1>" > index.html 
mkdir css 
echo "body { font-family: sans-serif; }" > css/style.css

3. Masuk ke Staging Area & Cek Status

git status 
git add .

4. Buat File Baru di Branch

echo "<h1>Halaman Kontak</h1>" > kontak.html

5. Gabungkan Branch (Merge)

git checkout main 
git merge fitur-kontak 


## Bagian 3: Cara mengaitkan Git ke Github
1. Buat Akun & Repository 
  ● Masuk ke https://github.com 
  ● Klik + → New repository 
  ● Beri nama (misal: proyek-web-pertama) 
  ● Penting: Jangan centang “Add a README file” 
  ● Klik Create repository 
2. Hubungkan & Push Proyek Lokal ke GitHub

git remote add origin 
https://github.com/NamaUserKamu/proyek-web-pertama.git 
git branch -M main 
git push -u origin main 

3. Apabila Ada teks dibawah berarti sudah terhubung ke git

Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 634 bytes | 317.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
