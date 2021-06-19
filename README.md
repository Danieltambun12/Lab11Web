# Lab11Web
# Nama : Daniel tambun
# kelas : TI 19 C1
# Nim : 311910490


# Langkah langkah praktikum 
# Buat folder baru dengan nama lab11_php_ci pada docroot webserver (htdocs)
![pr11 g1](https://user-images.githubusercontent.com/56190893/122629288-206cf880-d0e6-11eb-81e4-30f47b57a74a.PNG)

# Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini
![pr11 g2](https://user-images.githubusercontent.com/56190893/122629421-14356b00-d0e7-11eb-919d-2540e694668d.png)

# Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.
![pr11 g3](https://user-images.githubusercontent.com/56190893/122629455-5b236080-d0e7-11eb-99b8-285f836fff03.png)

# Instalasi Codeigniter 4
Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.
![pr11 g4](https://user-images.githubusercontent.com/56190893/122629478-7ee6a680-d0e7-11eb-9526-0f118528aaae.PNG)

# Menjalankan CLI (Command Line Interface)
Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah: ( php spark ) 
![pr11 g5](https://user-images.githubusercontent.com/56190893/122629509-c10fe800-d0e7-11eb-80b7-55fa481e2be4.jpg)

# Mengaktifkan Mode Debugging
Ketika terjadi error pada aplikasi akan ditampilkan pesan kesalahan seperti berikut.
![pr11 g6](https://user-images.githubusercontent.com/56190893/122629569-22d05200-d0e8-11eb-99a5-92112520e544.png)

# Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable CI_ENVIRINMENT menjadi development
![pr11 g7](https://user-images.githubusercontent.com/56190893/122629591-57440e00-d0e8-11eb-8a62-14181601d3ab.PNG)

# Contoh error yang terjadi. Untuk mencoba error tersebut, ubah kode pada file app/Controller/Home.php hilangkan titik koma pada akhir kode.
![pr11 g8](https://user-images.githubusercontent.com/56190893/122629609-79d62700-d0e8-11eb-8ca0-ee7e8fc2e8fd.PNG)

# Routing dan Controller
Router terletak pada file app/config/Routes.php
![pr11 g9](https://user-images.githubusercontent.com/56190893/122629636-bace3b80-d0e8-11eb-920f-6e9faaf30fa5.PNG)

# buka CLI dan jalankan perintah berikut.
yaitu php spark
![pr11 g10](https://user-images.githubusercontent.com/56190893/122629663-e94c1680-d0e8-11eb-83fe-b9a9073f7a96.jpg)

Selanjutnya coba akses route yang telah dibuat dengan mengakses alamat url http://localhost:8080/about
![pr11 g11](https://user-images.githubusercontent.com/56190893/122629708-2f08df00-d0e9-11eb-98a8-0c1f704b5924.PNG)


# Membuat Controller
Selanjutnya adalah membuat Controller Page. Buat file baru dengan nama page.php pada direktori Controller kemudian isi kodenya seperti berikut.
![pr11 g12](https://user-images.githubusercontent.com/56190893/122629727-5495e880-d0e9-11eb-91a9-fcd8a3d1a37e.PNG)
Selanjutnya refresh Kembali browser,
![pr11 g13](https://user-images.githubusercontent.com/56190893/122629745-7becb580-d0e9-11eb-87ae-f5273ccc2063.PNG)


# Tambahkan method baru pada Controller Page seperti berikut.
![pr11 g14](https://user-images.githubusercontent.com/56190893/122629774-a6d70980-d0e9-11eb-9e4e-ad06e90eb950.PNG)


# Method ini belum ada pada routing, sehingga cara mengaksesnya dengan menggunakan alamat: http://localhost:8080/page/tos
![pr11 g15](https://user-images.githubusercontent.com/56190893/122629788-cbcb7c80-d0e9-11eb-805e-86bc73cbf733.PNG)
Buat file css pada direktori public dengan nama style.css
![pr11 g16](https://user-images.githubusercontent.com/56190893/122629803-e998e180-d0e9-11eb-8be6-f83fd652177c.PNG)

# Kemudian buat folder template pada direktori view kemudian buat file header.php dan footer.php
![pr11 g17](https://user-images.githubusercontent.com/56190893/122629828-0df4be00-d0ea-11eb-807e-533ddb3aac24.png)

# footer.php
![pr11 g18](https://user-images.githubusercontent.com/56190893/122629853-311f6d80-d0ea-11eb-938b-7082212fc3e3.png)

# Kemudian ubah file app/view/about.php seperti berikut
![pr11 g19](https://user-images.githubusercontent.com/56190893/122629901-53b18680-d0ea-11eb-83bc-56f1c5a667f1.PNG)

# selanjutnya refresh tampilan tersebut:
![pr11 g20](https://user-images.githubusercontent.com/56190893/122629927-852a5200-d0ea-11eb-93a1-c460ed856505.png)

