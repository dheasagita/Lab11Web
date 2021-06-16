# Lab11Web
## PHP Framework
### Nama : Dhea Sagita (311910123)
### Kelas : TI.19.F1

## Laporan Praktikum

Persiapan

Mengaktifkan beberapa ekstensi php, diantaranya:
 php-json ekstension untuk bekerja dengan JSON;
 php-mysqlnd native driver untuk MySQL;
 php-xml ekstension untuk bekerja dengan XML;
 php-intl ekstensi untuk membuat aplikasi multibahasa;
 libcurl (opsional), jika ingin pakai Curl
![Screenshot (17)](https://user-images.githubusercontent.com/81453793/122224763-9f8fe000-cede-11eb-8afb-b09d596acee9.png)

Hapus tanda ; (titik koma) pada bagian extension yang akan diaktifkan.
![Screenshot (18)](https://user-images.githubusercontent.com/81453793/122225152-044b3a80-cedf-11eb-88a7-f73b20195bca.png)

## Instalasi CodeIgniter 4

Codeigniter dapat didownload dari website https://codeigniter.com/download
Extrak file zip Codeigniter ke direktori htdocs/lab11_php_ci.
Ubah nama direktory framework-4.x.xx menjadi ci4.
Buka browser dengan alamat http://localhost/lab11_php_ci/ci4/public/ SS3
![B](https://user-images.githubusercontent.com/81453793/122225342-2e046180-cedf-11eb-92c2-054e018d66d1.jpg)
![C](https://user-images.githubusercontent.com/81453793/122225507-555b2e80-cedf-11eb-9ec4-f8ff27619fc7.jpg)

Codeigniter juga menyediakan mode debugging/development yang dapat menampilkan error/kesalahan dalam kode program. Cara mengaktifkannya dengan mengubah nama file env menjadi .env kemudian buka filenya dan ubah nilai CI_ENVIRONMENT menjadi development.
![D](https://user-images.githubusercontent.com/81453793/122225745-88052700-cedf-11eb-8fb0-a2f92581b5bd.jpg)

Maka Pesan Kesalahan akan ditampilkan
![E](https://user-images.githubusercontent.com/81453793/122225990-bbe04c80-cedf-11eb-8a0a-b40349d5f777.jpg)


Langkah 1 - Membuat Route

    Router terletak pada file app/config/Routes.php

    Untuk mengetahui route yg ada atau telah berjalan dapat menggunakan perintah php spark routes SS18

    Selanjutnya mencoba akses route yang telah dibuat dengan mengakses http://localhost:8080/contact

    Terjadi error file not found dikarenakan tidak ada file/page untuk halaman contact. SS7

## Langkah 2 - Membuat Controller

  ![H](https://user-images.githubusercontent.com/81453793/122226252-ffd35180-cedf-11eb-992a-4bffa4690a3f.jpg)
  
  
  ![F](https://user-images.githubusercontent.com/81453793/122226385-21343d80-cee0-11eb-9567-b849e51365f5.jpg)



![Screenshot (23)](https://user-images.githubusercontent.com/81453793/122227397-08785780-cee1-11eb-8fa2-22f33cc5ba2b.png)
![i](https://user-images.githubusercontent.com/81453793/122227858-7a50a100-cee1-11eb-9915-ee22b79bdbbf.jpg)
![J](https://user-images.githubusercontent.com/81453793/122227866-7cb2fb00-cee1-11eb-8f34-d0082c499f00.jpg)


  
  





