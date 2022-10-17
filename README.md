## **Cara penggunaan git dan langkah-langkahnya lengkapi juga dengan screenshot prosesnya**

Berikut ini adalah langkah-langkah menggunakan Git
1. **Masuk Git**
, Untuk login ke git, bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum
memiliki akun dari ketiga platform tersebut, bisa mendaftarkan diri lewat 
**Command Prompt** atau **Command Line**. Kemudian masukkan perintah di bawah
`$ git config --global user.name IsiDenganNamaAnda`   masukkan username
`$ git config --global user.email IsiDenganEmailAnda.com`  massukkan email
Selanjutnya untuk memastikan proses login berhasil atau tidak, ketik perintah
`$ git config --list`
![vcs1](foto_langkah\vcs1.png)
2. **Masuk GitHub**
, Untuk menggunakan Git, buat akun [GitHub](https://github.com/) jika belum mempunyai 
akun GitHub. GitHub dan Git mempunyai hubungan khusus yaitu Git berperan sebagai 
Version Control System sedangkan GitHub berperan sebagai penyimpan kode pemrograman.
3. **Buat Repositori**
, Setelah berhasil login ke GitHub, bisa mulai membuat repositori. Klik tombol **New**
pada menu **Repositories** untuk membuat repositori baru. kemudian diarahkan pada halaman
untuk membuat repositori baru. Detail dan penjelasan yaitu
![vcs2](foto_langkah\vcs2.png)
1) **Nama Repositori**, digunakan untuk identitas repository yang dibuat
2) **Description Repository**, untuk deskripsi Repository
3) **Jenis Repository**, jenis repository dibagi menjadi **public** dan **private**. 
   **Public**, orang lain dapat melihat repository yang dibuat sedangkan **private**,
   hanya dibaca oleh pemilik itu sendiri
![vcs3](foto_langkah\vcs3.png)
4. **Buat Folder di Windows**
, Selanjutnya membuat folder pada local disk komputer. Fungsinya untuk menyimpan update 
file dari repository GitHub yang telah dibuat
![vcs4](foto_langkah\vcs4.png)
5. **Buka Folder Menggunakan GitBash**
, Setelah berhasil membuat folder pada local disk computer, buka folder tersebut dengan
klik kanan, lalu pilih GitBash here. setelah itu command prompt akan muncul
![vcs5](foto_langkah\vcs5.png)
6. **Ubah folder menjadi repository(master)**
, Setelah itu ubah folder tersebut menjadi repository(master) menggunakan perintah 
`$ git init` 
![vcs6](foto_langkah\vcs6.png)
7. **Tambahkan file repository**
, Untuk menambahkan file, perlu menerapkan langkah-langkah dibawah ini:
a. buat file di folder yang sudah dibuat contohnya, file index.php
b. Buka GitBash lalu masukkan perintah 
`$ git add README.md`
8. **Buat komitmen**
, Selanjutnya perlu membuat commit. commit pekerja untuk menambahkan file update serta 
komentar. jadi setiap kontributor bisa memberikan konfirmasi update proyek yang sedang 
dikerjakan. Masukkan perintah
`$ git Commit -M "first commit"`
![vcs7](foto_langkah\vcs7.png)
9. **ikuti langkah pada GitHub**
, Masuk ke Github. Masuk repository di GitHub. ikuti langkah pada persegi biru atau 
masukkan perintah
`$ git remote add origin https://github.com/Kudav5/NamaRepository.git`
`$ git branch -M main`  <- akan berubah (master) menjadi (main)
`$ git push -u origin main`
contoh:
![vcs8](foto_langkah\vcs8.png)
Jika ada kesalahan error: remote origin already exists ketika memasukkan perintah
`$ git remote` masukkan perintah
`$ git remote remove origin` dan ulangi langkah awal `$ git remote`
seperti pada gambar
![vcs9](foto_langkah\vcs9.png)
11. **Cek File**
, Cek repositori yang dibuat di GitHub
