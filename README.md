## **Cara penggunaan git dan langkah-langkahnya lengkapi juga dengan screenshot prosesnya**

Berikut ini adalah langkah menggunakan Git
1. **Masuk Git**
Untuk login ke git, bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum
memiliki akun dari ketiga platform tersebut, bisa mendaftarkan diri lewat 
**Command Prompt** atau **Command Line**. Kemudian masukkan perintah di bawah
`$ git config --global user.name IsiDenganNamaAnda`   masukkan username
`$ git config --global user.email IsiDenganEmailAnda.com`  massukkan email
Selanjutnya untuk memastikan proses login berhasil atau tidak, ketik perintah
`$ git config --list`
2. **Masuk GitHub**
Untuk menggunakan Git, login ke dalam website [GitHub](https://github.com/) jika belum mempunyai 
akun GitHub. GitHub dan Git mempunyai hubungan khusus yaitu Git berperan sebagai 
Version Control System sedangkan GitHub berperan sebagai penyimpan kode pemrograman.
3. **Buat Repositori**
Setelah berhasil login ke GitHub, bisa mulai membuat repositori. Klik tombol **New**
pada menu **Repositories** untuk membuat repositori baru. kemudian diarahkan pada halaman
untuk membuat repositori baru. Detail dan penjelasan yaitu
a. Nama Repositori
b. Description Repository
c. Jenis Repository
4. **Buat Folder di Windows**
Selanjutnya membuat folder pada local disk komputer. Fungsinya untuk menyimpan update 
file dari repository GitHub yang telah dibuat
5. **Buka Folder Menggunakan GitBash**
Setelah berhasil membuat folder pada local disk computer, buka folder tersebut dengan
klik kanan, lalu pilih GitBash here. setelah itu command prompt akan muncul
6. **Ubah folder menjadi repository**
Setelah itu ubah folder tersebut menjadi repository menggunakan perintah 
`$ Git init` 
7. **Tambahkan file repository**
Untuk menambahkan file, perlu menerapkan langkah-langkah dibawah ini:
a. buat file di folder yang sudah dibuat contohnya, file index.php
b. Buka GitBash lalu masukkan perintah 
`$ Git add index.php`
8. **Buat komitmen**
Selanjutnya perlu membuat commit. commit pekerja untuk menambahkan file update serta 
komentar. jadi setiap kontributor bisa memberikan konfirmasi update proyek yang sedang 
dikerjakan. Masukkan perintah
`$ Git Commit -M" vierst commit`
9. **Repository jarak jauh GitHub**
Repository jarak jauh berfungsi untuk mengupload file yang dibuat sebelumnya 
di disk local. Masukkan perintah 
`$ Git, Remote add origin git@github.com:UserNameGit/NamaRepositori.git`
10. **Tekan ke GItHub**
Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari
langkah -langkah di atas. Masukkan perintah untuk melakukan push ke GitHub
`$ git push -u origin master`
Perintash diatas akan menampilkan pop up sign GitHub. Login untuk melanjutkan proses push
ke GitHub
11. **Cek File**
Cek repositori yang dibuat. Dan mendapatkan file-file yang telah didapatkan sebelumnya.