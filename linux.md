# Linux_basic
basic syntax for linux terminal for dummies 😄
- [User management](#user-management) 

- [File management](#file-management)

- [Task manager](#task-manager)

# User Management
### beralih super user

pada terminal linux user yang pertama kali kita gunakan adalah user biasa yang sering ditandai dengan logo `$` setelah nama user kita. disini kita bisa beralih ke super user dengan cara mengetik kan `su` pada terminal kita.

### menggunakan root akses
saat kita ingin menginstall sesuatu tetapi tidak ingin beralih pada super user, kita bisa menggunakan `$ sudo <perintah>` untuk mendapat akses root.

### mengganti password
untuk mengganti password dari user kita, kita bisa menuliskan `$ sudo passwd <NamaUser>` dengan NamaUser sesuai dengan nama user kita.

# File Management
### posisi path
untuk mengetahui posisi PATH dimana sekarang kita bisa ketik <br>`$ pwd`

### membuat direktori
untuk membuat direktori bisa dengan mengetik <br>`$ mkdir <nama direktori>`.

### isi direktori
untuk mengetahui isi dari direktori yang kita tuju kita bisa ketik <br> `$ ls`

### berpindah direktori
- untuk berpindah direktori kita bisa mengetik  `$ cd <namadirektori>` . 
- untuk kembali ke direktori awal `$ cd ..` .

### menghapus direktori atau file
- untuk menghapus direktori atau file kita bisa menggunakan `$ rm <namadirektori>`
- untuk menghapus direktori yang terisi file bisa pakai `rm -r <namadirektori>`

### memindah file atau direktori
kita bisa memindahkan file dengan cara mengetik <br> `$ mv <namafile> <tujuan>`

### copy file atau direktori
kita bisa copy file dengan cara mengetik <br> `$ cp <namafile> <tujuan>`


# Task Manager

### melihat task yang berjalan
untuk melihat task yang berjalan kita bisa menggunakan perintah `$ top` dan tekan Ctrl + C untuk menghentikan program.

### menghentikan task
untuk menhentikan task kita bisa mengetikkan `$ kill <nomorPIDtask>`
