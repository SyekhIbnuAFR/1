#LATIHAN 1

TUGAS TUTORIAL MEMBUAT GITHUB

BAHASA PEMPROGRAMAN 1 
  



 



N I M 		:311810628

NAMA 		:SYEKH IBNU ACHMAD FAUZI RIDWAN

KELAS 		:TI.18.A-3

ANGKATAN 	:2018/2019
	
     .
Dikumpulkan hari  Rabu, 23 Januari 2019
Dosen : Agung Nugroho, S.Kom.  -  agung@pelitabangsa.ac.id    








Tutorial Cara Penggunaan Github
Ada beberapa langkah yang perlu dilakukan untuk menggunakan git yaitu :

1. Membuat akun pada layanan github
Buka website github, buat akun baru terlebih dahulu.

 
Halaman utama github
Setelah itu pada pojok kanan atas terdapat tombol “+”, klik button tersebut dan pilih “new repository”.

2. Membuat Repositori online
 
Tombol add


Lalu akan diarahkan ke halaman pembuatan repository, pembuatan repository ini tergantung dari project yang mau di upload.

 
Form repository
Untuk mengisi, ada beberapa hal yang perlu di perhatikan :
•	Repository name : nama repository(isi saja dengan nama proyek), akan lebih rapi kalau misalnya nama repository juga di beri jenis pemogramannya juga .
•	Description : deskripsi repository (bisa kisah project dan siapa yang terlibat).
•	Public/Private : kondisi repository mau di public (di buat umum) atau private(di buat pribadi atau tertutup).
•	Intiallize the repository with README : ini adalah isi dokumentasi pada project yang dikerjakan.

 
Contoh project “latihan1”
Setelah di isi sesuai dengan keinginan, klik saja tombol “create repository”, maka pada halaman selanjutnya akan menampilkan repositori yang sudah dibuat, dan tahap selanjutnya adalah upload project ke repository online.
 
3. Mengupload folder(repository lokal)
        Jika sudah memiliki proyek yang ingin diletakkan di repository online, buka saja folder project tersebut dengan perintah command line.

git init 
git add . 
git commit -m "first commit" 
git remote add origin https://github.com/SyekhIbnuAFR/latihan1.git 
git push -u origin master

“Keterangan perintah diatas seperti ini” :

-git init
Untuk meng-set folder yang digunakan tersebut sebagai repo local git. bisa di bilang ini instalasi git pertama kali
-git add “.” atau nama file
Untuk menambah file project yang mau di upload sebelum di commit, tanda titik setelah kata “add” pada perintah tersebut adalah keseluruhan file dan folder project tersebut, saat awal upload bisa menggunakan perintah tersebut. Namun saat commit atau upload ke repository selanjutnya bisa menggunakan perintah add dengan “nama file” untuk memberikan status commit. 

-git commit -m “isi commit”
Untuk menambah keterangan/status perubahaan saat upload ke repo online, untuk memasukkan keterangan tersebut setelah “git commit -m” ditambah tanda petik lalu komentar(lihat di list perintah untuk contoh).
-git remote add origin “link repo online”
Untuk meng-setting remote origin dari repo online, repo online bisa dilihat pada link yang tersedia di bagian atas Project dengan format “.git”, diperlukan ini untuk mengakses ke repo tersebut sehingga kita bisa melakukan apapun di repo online tersebut.
-git push origin “nama branch”
Perintah untuk mengupload file yang ada pada repo lokal ke repo online yang diletakkan pada branch yang sudah tersedia di repo online.
Setelah melakukan semua perintah silahkan cek di github, 

 

 
Screenshot Langkah-Langkah Proses Penyimpanan File Di Github.
