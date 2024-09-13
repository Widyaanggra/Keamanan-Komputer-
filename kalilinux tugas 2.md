Nama : Widya Anggraini

NIM  : 09030582226025

Kelas: TK5A

Laporan KaliLinux Sublist3r

1. Langkah pertama adalah login ke Kali Linux menggunakan Virtual Machine
2. setelah login masuk ke terminal dan pastikan sudah melakukan update
![image](https://github.com/user-attachments/assets/f313be40-dea7-478a-83d3-8e8633d9f805)
3. kemudian install sublist3r dengan command "sudo apt install sublist3r"
![image](https://github.com/user-attachments/assets/a43018eb-257b-440d-b059-fdfdce1b5a75)
4. untuk melihat panduan penggunaan pada sublist3r menggunakan command "sublist3r -h"
![image](https://github.com/user-attachments/assets/53bc0653-d6ab-4db0-9e89-69fc43543c90)
5.kemudian untuk mencari sub-domain pada suatu website dapat menggunakan opsi -d , contohnya "sublist3r -d pusri.co.id"
![image](https://github.com/user-attachments/assets/b89eca60-f5ff-4e5a-9846-abe3f92d263f)
6.Dari contoh command di atas dapat ditambahkan dengan kombinasikan opsi lain, misalnya -t untuk melihat threads. contohnya seperti ini sublist3r -d netflix.com -t 10 dengan menggunakan -t 10 berfungsi untuk melihat threads sebanyak 10.
![image](https://github.com/user-attachments/assets/e9676c0c-122e-470f-96b0-58ce51a7dfd1)
7.Opsi yang bisa dicoba selanjutnya yaitu -p befungsi untuk melihat port yang aktif, contohnya sublist3r -d pusri.co.id -p 443,80 disini kita ingin mengecek port 443 , dan 80.
 ![image](https://github.com/user-attachments/assets/f02fc237-f091-4e66-b60b-85a79ac0fa79)
