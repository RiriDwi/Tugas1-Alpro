RIRI DWI SETYAWATI / 162012133031

Inisialisasi repository menggunakan git (CLI) dan buat clonenya di Github. 

1. Pertama, download dan install git terlebih dahulu

2. Lalu membuat folder (Tugas1-Alpro) di direktori local (laptop) dan membuat file README.md di dalamnya. Setelah itu, buka file README.md dan tuliskan sesuatu di dalamnya lalu disave. 

3. Log in pada akun github kita terlebih dahulu dan membuat repository baru. Lalu saya menamai repository di github sama dengan yang di local direktori yaitu  Tugas1-Alpro. Jika sudah selesai diberi nama maka klik creat repository.

4. Setelah itu, klik kanan pada folder Tugas-1-Alpro-II, dan klik git bash here.

5. Setelah klik git bash here kita melakukan konfigurasi awal menggunakan git config untuk username dan email sesuai akun github kita.

6. Lalu menggunakan git init untuk inisialisasi atau untuk membuat repository pada file local sehingga nantinya akan ada folder .git.

7. Untuk mengetahui status dari repository kita, gunakan git status agar kita dapat mengetahui apabila ada perubahan pada file.

8. Selanjutnya kita menge-track file README.md dengan git add terlebih dahulu agar kita bisa melakukan commit pada tahap selanjutnya. Kita cek lagi status file kita dengan git status.

9. Kita lakukan commit dengan menggunakan git commit –m “(menuliskan pesan )”, pada percobaan ini saya menuliskan “Mencoba commit tugas pertama”. Git commit ini digunakan untuk menyimpan perubahan yang dilakukan.

10. Lalu kita gunakan git remote untuk mengelola server pusat untuk hosting repository git kita. Kita tuliskan git remote add origin dan tambahkan link github kita.

11. Selanjutnya untuk memasukkan clone ke github dari repository local, kita gunakan git push dengan menuliskan git push –u origin master.

12. Terakhir, cek di repository apakah projek README.md sudah terupload atau belum.


Git Basic Operations

1. Git config = digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll.

2. Git init = digunakan untuk membuat repositori baru

3. Git add = digunakan untuk menambahkan file ke index. 

4. Git clone = digunakan untuk checkout repositori

5. Git commit = digunakan untuk melakukan commit pada perubahan ke head

6. Git status = untuk mengetahui status dari repository lokal

7. Git push = untuk mengirimkan perubahan file setelah di commit ke remote repository

8. Git checkout = menukar branch yang aktif dengan branch yang dipilih

9. Git remote = untuk membuat user terhubung ke remote repository

10. Git branch = digunakan untuk me-list, membuat atau menghapus branch

11. Git pull = Untuk menggabungkan semua perubahan yang ada di remote repository ke direktori lokal

12. Git merge = untuk menggabungkan branch yang aktif dan branch yang dipilih

13. git diff = untuk menampilkan conflicts

14. git tag = digunakan untuk menandai commits tertentu

15. git log = digunakan untuk menampilkan daftar commits yang ada di branch beserta detail-nya

16. git reset = digunakan untuk me-reset index dan bekerja dengan kondisi commit paling baru

17. git remove 

18. git restore
