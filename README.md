Nama : Rio Rinto Saki

NIM : 312210715

Kelas : TI.22.C.9


# Cara Penggunaan Git

## Install Git
Unduh git di website resminya [Git](git-scm.com), unduh sesuai arsitektur komputer yang digunakan (34bit/64bit), lalu install file yang telah diunduh.

![Screenshot (4)](https://user-images.githubusercontent.com/123881535/215333941-8e33bb9d-e8ef-45f3-a368-635b6c78b305.png)
![Screenshot (5)](https://user-images.githubusercontent.com/123881535/215333944-6cc55f91-8cab-4863-9c69-9b5baa2e3417.png)

Setelah di-install akan muncul jendela gitbash, jika tidak muncul maka buka dari windows lalu ketik gitbash

![Screenshot (6)](https://user-images.githubusercontent.com/123881535/215334459-156a63a2-72ec-4f29-a455-71b8a852afa5.png)
![Screenshot (7)](https://user-images.githubusercontent.com/123881535/215334466-7a0ee3ac-64cb-495f-8abc-2a4f6370d5bc.png)

Kemudian konfigurasikan username dan email dengan mengetikan kode.
- $ git config --global user.name “nama_user”
- $ git config --global user.email “nama_user”

![Screenshot (8)](https://user-images.githubusercontent.com/123881535/215334974-6bc760f2-9cef-443d-bf09-dd5d5b0919b2.png)

## Membuat Repository Local
Buka File Explorer lalu pilih/buat direktori yang akan digunakan untuk percobaan contohnya (d:\labs_pemrograman1).
Kemudian klik kanan pada direktori tersebut lalu pilih "Git Bash here"

![Screenshot (9)](https://user-images.githubusercontent.com/123881535/215335175-4ced40e3-4b3c-4e67-baf5-9268ab7fd164.png)

Kemudian buat folder/direktori baru dengan nama LatihanVCS dengan kode:
- $ mkdir LatihanVCS

![Screenshot (11)](https://user-images.githubusercontent.com/123881535/215335364-1e27c69a-ecaa-4ce4-898d-4f458eb6e384.png)

lalu masuk ke folder tersebut dengan kode
- $ cd LatihanVCS

![Screenshot (12)](https://user-images.githubusercontent.com/123881535/215335448-47150fbb-da3e-4d38-96fb-de62d6b5990b.png)

Untuk membuat repository local ketikan kode :
- $ git init

![Screenshot (13)](https://user-images.githubusercontent.com/123881535/215335684-7ee4232e-edf5-4311-a34f-bd66f45e7505.png)

Setelah repository baru selesai terinisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git , maka pada direktori tersebut semua perubahan pada working directory akan disimpan.

## Menambahkan File Baru pada Repository

Untuk membuat file baru dengan contoh file "Readme.md" bisa dengan mengetikkan kode :
- $ echo “# LatihanVCS” >> README.md

![Screenshot (14)](https://user-images.githubusercontent.com/123881535/215335868-30cdc92f-31fb-4ab9-be30-2edbd6d108dd.png)

Setelah file Readme.md berhasil dibuat, kita tambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
- $ git add README.md

![Screenshot (17)](https://user-images.githubusercontent.com/123881535/215335952-d25a3a93-c0fa-4b24-b292-f41db462334b.png)

Kemudian simpan perubahan yang ada kedalam database repository local, gunakan perintah
- git commit -m “komentar commit”

![Screenshot (19)](https://user-images.githubusercontent.com/123881535/215336033-37ac21f2-d114-48ac-9cdb-2bbe5815e186.png)

## Membuat Repository Server

Server reopsitory yang akan digunakan adalah [http://github.com](http://github.com)
Untuk itu harus mendaftarkan akun terlebih dahulu pada website tersebut dengan memilih menu "Sign Up" lalu memasukan username baru, email, dan password, lalu verivikasi kode yang akan diterima pada email tersebut.

![Screenshot (24)](https://user-images.githubusercontent.com/123881535/215336328-281e488f-59b4-4ebb-a8fb-fa6f0c5b5f4f.png)

![Screenshot (21)](https://user-images.githubusercontent.com/123881535/215336336-355ea736-f2bd-428a-92ba-324bef758a20.png)

![Screenshot (23)](https://user-images.githubusercontent.com/123881535/215336342-b7ed0129-694a-4c3d-830d-f4ada6fe13ad.png)

Setelah akun berhasil terdaftar, buka halaman utama github kemudian pilih icon mnenu (+) lalu klik New Repository

![Screenshot (25)](https://user-images.githubusercontent.com/123881535/215336422-c3c7408c-340d-4ab0-b6ad-4d63f94eb5fc.png)

Isi nama repositorynya, lalu klik Create Repository

## Menambahkan Remote Repository

Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
Untuk menambahkan remote repository server, gunakan perintah
- git remote add origin [url]
Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
- $ git push -u origin master

![Screenshot (26)](https://user-images.githubusercontent.com/123881535/215336519-a381304e-375e-4953-ba26-cd94b0c8caa4.png)

## Melihat hasilnya pada server repository

Buka website [github.com](https://github.com), arahkan pada repositori-nya. Maka perubahan akan terlihat pada laman tersebut.

![Screenshot (27)](https://user-images.githubusercontent.com/123881535/215336654-c67f4645-705d-4a46-a0cc-f2d8da180473.png)

# Sekian dan terimakasih.
