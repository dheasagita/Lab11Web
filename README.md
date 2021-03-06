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


Kemudian buat file admin_index.php dalam folder (/app/Views/artikel/) untuk tampilan halaman admin.
![Screenshot (38)](https://user-images.githubusercontent.com/81453793/124137530-f5a07e00-daaf-11eb-9580-093cb8f73b2f.png)

Menu admin dapat diakses dengan alamat http://localhost:8080/admin/artikel
![N](https://user-images.githubusercontent.com/81453793/124140189-7791a680-dab2-11eb-8726-9ee2071e24db.jpg)



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

# PRAKTIKUM 12 (FRAMEWORK LANJUTAN - CRUD)

Nama : Dhea Sagita 
NIM  : 311910123

## Laporan Praktikum

### Buatlah Database seperti ini:
![Screenshot (33)](https://user-images.githubusercontent.com/81453793/123438349-cc3ca980-d5fa-11eb-90bf-b433b84bdd4f.png)


### Konfigurasi Database
![Screenshot (29)](https://user-images.githubusercontent.com/81453793/123432635-c93eba80-d5f4-11eb-8fca-4ba291a31e47.png)


 ### Membuat Model
 ![Screenshot (30)](https://user-images.githubusercontent.com/81453793/123433157-57b33c00-d5f5-11eb-933b-a799f98517cb.png)


### Membuat Controller
![Screenshot (31)](https://user-images.githubusercontent.com/81453793/123433931-2850ff00-d5f6-11eb-9a7f-c12859733c56.png)


### Membuat View
![Screenshot (32)](https://user-images.githubusercontent.com/81453793/123434701-f5f3d180-d5f6-11eb-84df-68a957066061.png)


Tidak ada data karena database kosong
![K](https://user-images.githubusercontent.com/81453793/123438577-060db000-d5fb-11eb-810b-2a02707ca46b.jpg)

Tambahkan data pada database untuk ditambahakan datanya.
![Screenshot (34)](https://user-images.githubusercontent.com/81453793/123438723-33f2f480-d5fb-11eb-88ec-5315676b6ab0.png)

Maka akan muncul seperti ini
![L](https://user-images.githubusercontent.com/81453793/123439063-8df3ba00-d5fb-11eb-8a3e-2eb3907652c2.jpg)

### Membuat Tampilan detail artikel
![Screenshot (35)](https://user-images.githubusercontent.com/81453793/123439677-2be78480-d5fc-11eb-8098-6b170eee93bb.png)

### Membuat View Detail
![Screenshot (36)](https://user-images.githubusercontent.com/81453793/123440389-ed9e9500-d5fc-11eb-9b29-4de88b033465.png)

### Membuat Route
![Screenshot (37)](https://user-images.githubusercontent.com/81453793/123440701-440bd380-d5fd-11eb-8425-6b26cad69138.png)

Maka Akan muncul tempilan seperti ini;
![M](https://user-images.githubusercontent.com/81453793/123440831-6867b000-d5fd-11eb-9ff0-e452e1182e99.jpg)

Kemudian buat file admin_index.php dalam folder (/app/Views/artikel/) untuk tampilan halaman admin. 
![Screenshot (38)](https://user-images.githubusercontent.com/81453793/124143858-a9583c80-dab5-11eb-9bca-e821a6885499.png)

Menu admin dapat diakses dengan alamat http://localhost:8080/admin/artikel
![N](https://user-images.githubusercontent.com/81453793/124143941-bd9c3980-dab5-11eb-8d94-1df971af22c2.jpg)


# Menambah Data Artikel

![O](https://user-images.githubusercontent.com/81453793/124144367-179cff00-dab6-11eb-8027-b543742e5f42.jpg)

Kemudian buat view untuk form tambah dengan nama form_add.php dalam folder (/app/Views/artikel/). SS17
![p](https://user-images.githubusercontent.com/81453793/124144374-1966c280-dab6-11eb-87ad-cca22678d96c.jpg)

Tampilannnya Seperti ini:
![Q](https://user-images.githubusercontent.com/81453793/124144512-4024f900-dab6-11eb-888f-be9f4c6bc974.jpg)

# Mengubah Data

![R](https://user-images.githubusercontent.com/81453793/124144852-87ab8500-dab6-11eb-8d2a-c1e05be07478.jpg)

![S](https://user-images.githubusercontent.com/81453793/124144861-89754880-dab6-11eb-96bc-39132782ba2f.jpg)

![T](https://user-images.githubusercontent.com/81453793/124144928-96923780-dab6-11eb-9196-fcc0daffb945.jpg)

# Menghapus Data

![U](https://user-images.githubusercontent.com/81453793/124144982-a27df980-dab6-11eb-9b5c-ab69bcba31b8.jpg)

## Pertanyaan dan Tugas
Selesaikan programnya sesuai Langkah-langkah yang ada. Anda boleh melakukan improvisasi.

Screnshootnya :
![1](https://user-images.githubusercontent.com/81453793/124145744-436cb480-dab7-11eb-9a2e-16573edee892.jpg)
![2](https://user-images.githubusercontent.com/81453793/124145750-45367800-dab7-11eb-9cae-5cbd7fb5eaa2.jpg)
![3](https://user-images.githubusercontent.com/81453793/124145755-45cf0e80-dab7-11eb-8f93-0d189cb1caa1.jpg)
![4](https://user-images.githubusercontent.com/81453793/124145760-4667a500-dab7-11eb-8296-195f7811e19d.jpg)
![5](https://user-images.githubusercontent.com/81453793/124145765-4798d200-dab7-11eb-9c90-f0baed8ef7c4.jpg)
![6](https://user-images.githubusercontent.com/81453793/124145766-48316880-dab7-11eb-9833-d405b6869870.jpg)
![7](https://user-images.githubusercontent.com/81453793/124145767-48316880-dab7-11eb-871b-0a1d26c7a5a7.jpg)
![8](https://user-images.githubusercontent.com/81453793/124145770-48c9ff00-dab7-11eb-93e5-e36e4773cfbb.jpg)



# PRAKTIKUM 13 (PEMOGRAMAN WEB - FRAMEWORK LANJUTAN - MODUL LOGIN)
### Nama  : Dhea Sagita 311910123 (TI.19.F1)

## 1. MEMBUAT MODEL USER
![1](https://user-images.githubusercontent.com/81453793/125095621-93bec480-e0fe-11eb-8241-68c2afd9412b.jpg)

## 2. MEMBUAT CONTROLLER USER
![2](https://user-images.githubusercontent.com/81453793/125095743-b224c000-e0fe-11eb-8613-ba19bf4f8014.jpg)

## 3. MEMBUAT VIEW LOGIN
![3](https://user-images.githubusercontent.com/81453793/125095859-cbc60780-e0fe-11eb-85fe-40dcc682749b.jpg)

## 4. MEMBUAT DATABASE SEEDER
![4](https://user-images.githubusercontent.com/81453793/125095961-e4362200-e0fe-11eb-8cc0-c625c0a70f22.jpg)

Buka file UserSeeder.php yang berada di lokasi direktori /app/Database/Seeds/UserSeeder.php kemudian isi dengan kode berikut:
![5](https://user-images.githubusercontent.com/81453793/125096110-05970e00-e0ff-11eb-861b-6fabe6c57eb4.jpg)

Lalu buka CLI lagi dan ketik perintah berikut: php spark db:seed UserSeeder
![6](https://user-images.githubusercontent.com/81453793/125096199-19db0b00-e0ff-11eb-8ac2-970e52c2f28f.jpg)

## 5. MEMBUAT AUTH FILTER
![7](https://user-images.githubusercontent.com/81453793/125096298-35deac80-e0ff-11eb-8ec9-eab205322a91.jpg)

## 6. MEMBUAT FUNGSI LOGOUT
![8](https://user-images.githubusercontent.com/81453793/125096413-5149b780-e0ff-11eb-9b7a-6d26940fd713.jpg)

Maka ketika menekan logout dan konfirmasi, akan kembali ke halaman login. 
![9](https://user-images.githubusercontent.com/81453793/125096497-69b9d200-e0ff-11eb-8117-66999404ee89.jpg)

# PRAKTIKUM 14 (PEMOGRAMAN WEB - PAGINATION DAN PENCARIAN)
### Nama : Dhea Sagita 311910123 (TI.19.F1)


## MEMBUAT PAGINATION
![A](https://user-images.githubusercontent.com/81453793/125098650-69223b00-e101-11eb-965c-4aad6b19ec77.jpg)

![B](https://user-images.githubusercontent.com/81453793/125098773-88b96380-e101-11eb-8640-fef343eb40a5.jpg)

![C](https://user-images.githubusercontent.com/81453793/125098781-89ea9080-e101-11eb-994f-188f85748341.jpg)

## MEMBUAT PENCARIAN
![D](https://user-images.githubusercontent.com/81453793/125098980-c0281000-e101-11eb-9e5c-8beb1473417f.jpg)

![E](https://user-images.githubusercontent.com/81453793/125098991-c1f1d380-e101-11eb-9d89-e94743b502af.jpg)

![F](https://user-images.githubusercontent.com/81453793/125098995-c28a6a00-e101-11eb-88c1-f11dbf662765.jpg)

## MEMBUAT UPLOAD GAMBAR
![G](https://user-images.githubusercontent.com/81453793/125099118-e2ba2900-e101-11eb-9c05-ebc714493f8b.jpg)

![H](https://user-images.githubusercontent.com/81453793/125099125-e483ec80-e101-11eb-876d-d695eee22841.jpg)
























