# Cara Menggunakan Git
Git adalah salah satu software penting dalam pengembangan website. Fungsi Git adalah untuk mengatur versi dari source code program Anda dengan memberikan tanda baris dan kode mana yang ditambah atau diganti. Di artikel ini kami akan membahas lengkap soal Git, dari cara install Git, cara login ke Git, hingga cara menggunakan Git.
## Cara Install Git di Windows dan Linux
Sebelum mempelajari bagaimana cara menggunakan Git, Anda perlu menginstalnya terlebih dahulu di perangkat yang Anda gunakan. Anda bisa memasang Git baik di Windows maupun di Linux. Berikut adalah panduan memasang Git di kedua sistem operasi tersebut:

## Cara Install Git di Windows
Cara install Git di Windows terdiri dari 10 langkah. Berikut adalah penjelasannya:

## 1. Download File Git
Untuk menginstall Git, Anda perlu mengunduh file-nya terlebih dahulu di situs resminya. Download sesuai tipe sistem operasi pada komputer Anda. Apabila tipe sistem operasi komputer Anda 64bit,  pilih Git yang mendukung Windows 64bit. Tujuannya adalah agar tidak terjadi error saat proses instalasi Git.

## 2. Install Git
Setelah selesai mengunduh file Git, buka setup aplikasi Git untuk memulai proses instalasi. Halaman awal setelah Anda membuka setup aplikasi Git adalah tampilan Document License dari Git. Klik Next untuk melanjutkan instalasi.
![Screenshot_181](https://user-images.githubusercontent.com/72786548/95837339-b4720d80-0d6a-11eb-9e1e-63ab3f584ba9.png)

## 3. Tentukan Lokasi Instalasi Git
Selanjutnya, pilih lokasi untuk install Git pada komputer Anda. Pada tutorial ini kami menginstall di lokasi C:\Program Files\Git. Setelah menentukan lokasi instalasi Git, klik Next untuk melanjutkan.

![image](https://user-images.githubusercontent.com/72786548/95966612-8c9bac00-0e35-11eb-80e3-1c0ca43d35af.png)

## 4. Pilih Komponen Tambahan
Kemudian pilih komponen tambahan untuk install Git. Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar. Sesuaikan komponen tambahan yang dipilih seperti pada gambar di bawah ini. Jika sudah klik Next untuk melanjutkan instalasi.

![image](https://user-images.githubusercontent.com/72786548/96060234-25740b00-0eba-11eb-9674-1bc9e0f69f52.png)

## 5. Tentukan Nama Aplikasi Git
Sebenarnya Anda bebas mengganti nama aplikasi Git yang akan ditampilkan pada Start Menu. Akan tetapi, demi kemudahan saat mencari aplikasi ini, sebaiknya gunakan nama Git saja.

![image](https://user-images.githubusercontent.com/72786548/96060273-3886db00-0eba-11eb-9b64-634fc72469e2.png)

## 6. Tentukan File Editor
Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Pada tutorial ini, kami menggunakan Vim Editor. Klik Next apabila Anda sudah menentukan file editor yang akan Anda gunakan.

![image](https://user-images.githubusercontent.com/72786548/96061433-66215380-0ebd-11eb-9384-66bc05c531c4.png)

## 7. Atur Path Environment
Selanjutnya adalah pengaturan Path Environment. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih **_Git from the command line and also from 3rd-party software_** agar saat menjalankan perintah Git dapat dikenali di **Command Prompt (CMD)**.

![image](https://user-images.githubusercontent.com/72786548/96061488-8c46f380-0ebd-11eb-885b-a64505f5b0d7.png)

## 8. Pilih Aplikasi SSH
Kemudian untuk mengeksekusi SSH, Anda bisa menggunakan aplikasi dari Git atau  dari platform lain seperti PuTTY dan Bitvise. Pada tutorial ini kami menggunakan **_Use OpenSSH_**, aplikasi default SSH dari Git. Klik **Next** untuk melanjutkan instalasi.

![image](https://user-images.githubusercontent.com/72786548/96061542-b8627480-0ebd-11eb-839b-0e140b1679f7.png)

## 9. Pilih Line Ending
Selanjutnya, Anda perlu memilih pengaturan line ending. Pada tutorial ini kami memilih **_Checkout Windows-style, commit Unix-style line endings_**. Klik **Next** untuk melanjutkan instalasi.

![image](https://user-images.githubusercontent.com/72786548/96062441-e0eb6e00-0ebf-11eb-9755-9ee15aacaa77.png)

## 10. Pilih Emulator Terminal
Setelah itu, Anda perlu memilih emulator terminal yang akan digunakan. Anda bisa menggunakan Command Prompt atau MinTTY. Karena ingin menggunakan Command Prompt, pada tutorial ini kami memilih **_Use Windows’ default console windows_**. Klik **Next** untuk melanjutkan instalasi.

![image](https://user-images.githubusercontent.com/72786548/96062469-f2cd1100-0ebf-11eb-8b0d-873748716470.png)

## 11. Tentukan Opsi ekstra
Terdapat beberapa opsi ekstra yang bisa Anda pilih. Pertama, pilih Enable File System Caching agar Git memiliki fungsi system caching. Kedua, pilih Enable Git Credential Manager agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub. Klik **Next** untuk melanjutkan instalasi.

![image](https://user-images.githubusercontent.com/72786548/96073074-ddf87980-0ecf-11eb-9679-fb386260aa9f.png)

## 12. Mulai Proses Instalasi
Setelah menambahkan konfigurasi ekstra pada Git, Anda bisa memulai proses instalasi Git. Klik **Install** untuk melanjutkan proses.

![image](https://user-images.githubusercontent.com/72786548/96073104-f072b300-0ecf-11eb-911d-263380839a23.png)

Berikut ini adalah tampilan proses instalasi Git. Tunggu hingga proses selesai dan Anda bisa menggunakan Git pada Windows.

![image](https://user-images.githubusercontent.com/72786548/96073587-edc48d80-0ed0-11eb-8c14-629601126ca8.png)

## 13. Cek Versi Git
Setelah proses instalasi selesai, Anda perlu mengecek apakah instalasi Git berhasil atau tidak. Anda bisa mengeceknya melalui **Command Prompt**. Klik Win+R lalu ketik **_CMD_** untuk membuka **Command Prompt** seperti di bawah ini.



Selanjutnya masukkan perintah berikut untuk cek versi git dan cek apakah Git sudah terinstall di komputer Anda.

git --version
