# belajar-github
1. Pentingnya Penggunaan Command Line
2. Langkah Langkah Push Repository
3. Langkah Langkah Clone Repository
4. Langkah Langkah Pull dan Push Repository

1. Pentingnya Penggunaan Command Line

Command Line (CLI) itu penting karena:

Lebih cepat & efisien dibanding GUI (tinggal ketik perintah).
Kontrol penuh terhadap sistem dan Git (fitur lengkap ada di CLI).
Dipakai di banyak tools developer (server, deployment, automation).
Membantu memahami cara kerja Git secara lebih dalam, bukan sekadar klik-klik.
2. Langkah-Langkah Push Repository
<img src="/images/git push.jpg">

Push = mengirim perubahan dari lokal ke repository online (misalnya GitHub).

Langkah:

Masuk ke folder project:

cd nama-folder

Inisialisasi Git (jika belum):

git init

Tambahkan file:

git add .

Commit perubahan:

git commit -m "pesan commit"

Hubungkan ke repository online:

git remote add origin link-repo

Push ke GitHub:

git push -u origin main
3. Langkah-Langkah Clone Repository

Clone = mengambil repository dari internet ke komputer lokal.

Langkah:

Ambil link repository

Jalankan:

git clone link-repo

Masuk ke folder:

cd nama-repo
4. Langkah-Langkah Pull dan Push Repository
Pull (ambil update terbaru dari online):
git pull origin main
Push (kirim update ke online):

Tambahkan perubahan:

git add .

Commit:

git commit -m "update terbaru"

Push:

git push origin main.33
