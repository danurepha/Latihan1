# **#Latihan1**

## Apa Itu Git ?
![1280px-git-logo svg](https://user-images.githubusercontent.com/46738960/51690083-90b4e400-202a-11e9-8c54-d9586558eb8b.png)

**Git** adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. **Git** dikenal juga dengan _**distributed revision control**_ (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

## **Install GIT di Windows**

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

1. Buka [https://gitforwindows.org/](url) dan download installer GIT untuk Windows.
2. Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

## **Beberapa Perintah Dasar Pada GIT**

1. **git init**, perintah untuk membuat repository local.
2. **git add**, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
3. **git commit**, perintah untuk menyimpan perubahan kedalam database git.
4. **git push -u origin master**, perintah untuk mengirim perubahan pada repository local menuju server repository.
5. **git clone [url]**, perintah untuk membuat working directory yang diambil dari repositry sever.
6. **git remote add origin [url]**, perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).

## **Langkah-Langkah Menggunakan GIT**

### 1. Jalankan software Git pada Desktop dengan cara klik kanan > Git Bash Here.
![1](https://user-images.githubusercontent.com/46738960/51692334-484bf500-202f-11e9-8206-436a1cc794f8.jpg)
![2](https://user-images.githubusercontent.com/46738960/51692333-47b35e80-202f-11e9-8977-75448d969160.jpg)

### 2. Buat Repository Local dengan mengetik "cd" & "mkdir" ("cd" untuk masuk ke folder & "mkdir" untuk membuat foldernya).
![cd mkdir](https://user-images.githubusercontent.com/46738960/51692459-8ba66380-202f-11e9-8956-e7fcd61374b5.jpg)

### 3. Mengkonfigurasikan e-mail dan user name kita di GIT.
![login](https://user-images.githubusercontent.com/46738960/51692757-2b63f180-2030-11e9-9e10-2da61ef8786a.jpg)

### 4. Kita buat Repository Localnya menjadi _master_ dengan melakukan inisialisai "git init".
![git init](https://user-images.githubusercontent.com/46738960/51693128-e9877b00-2030-11e9-938e-283fc453f13e.jpg)


### 5. Buat file project pada folder kita dengan mengetik "echo" dan cek apakah sudah ada filenya di dalam folder kita dengan mengetik "ls -l".
![echo](https://user-images.githubusercontent.com/46738960/51693576-d0cb9500-2031-11e9-9da1-8aaf2596aa8e.jpg)

### 6. Siapkan file project kita yang akan di upload pada Repository Server dengan mengetik "git add".
![git add](https://user-images.githubusercontent.com/46738960/51694406-53088900-2033-11e9-91c6-72805f099a0e.jpg)

### 7. Buatlah Repository Servernya pada [https://github.com](url) yang sudah di sign in oleh kita.
![guthub](https://user-images.githubusercontent.com/46738960/51694564-b2669900-2033-11e9-89d4-86933f2e0f96.jpg)

### 8. Update file project yang akan di upload ke Repository Online dengan mengetik "git commit".
![git commit](https://user-images.githubusercontent.com/46738960/51694853-49335580-2034-11e9-8de3-cd789f753df4.jpg)

### 9. Kemudian ketikkan alamat HTTPS Repository Online yang akan kita tuju dengan diawali "git remote add origin" & upload project filenya, untuk alamat HTTPS bisa dilihat pada tanda di gambar berikut.
![https](https://user-images.githubusercontent.com/46738960/51695277-379e7d80-2035-11e9-9140-730cb24d0e1a.jpg)

![git remote](https://user-images.githubusercontent.com/46738960/51695276-379e7d80-2035-11e9-8969-4efa760b19b4.jpg)

### 10. Untuk mengisi teks pada file projectnya, kita bisa ketik "nano" lalu kalian masukkan teks yang kalian inginkan lalu simpan dengan cara "Ctrl + S".
![nano 2](https://user-images.githubusercontent.com/46738960/51695852-a16b5700-2036-11e9-9d34-d0c875aba2a9.jpg)

### 11. Finally yaitu kita mengirim file project kita ke Repository Server di Github dengan mengetik "git push -u origin master" & jangan lupa untuk melakukan ini kita membutuhkan jaringan internet, pada proses ini kita juga akan diminta untuk memasukkan username dan password.
![git push](https://user-images.githubusercontent.com/46738960/51695925-cd86d800-2036-11e9-8e04-d0d9f48176ef.jpg)
