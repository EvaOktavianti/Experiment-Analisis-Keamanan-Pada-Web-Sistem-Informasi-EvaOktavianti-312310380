Experiment 
1. Menjalankan Apache dan Mysql melalui aplikasi XAMPP.
![image](https://github.com/user-attachments/assets/e783a317-b3f9-41e6-85ce-740246063b48)
2. Buatkan database untuk menghubungkan ke web tersebut 
3. untuk membuat database buka lah web browser lalu ketikan http://localhost/phpmyadmin
![Gambar2](https://github.com/user-attachments/assets/53a9fd32-2fa2-44cf-9a2d-41168d757cc3)
4. setelah dibuat databasenya lalu koneksikan ke database dengan kode tersebut 
![Gambar3](https://github.com/user-attachments/assets/18656b07-6fc3-4e78-ad82-b65bf4ed86de)	
5. setelah di koneksikan berhasil lalu memasukan kode register untuk membuat akun pada tampilan login
![Gambar4](https://github.com/user-attachments/assets/08686b54-3b35-4999-beea-94d89aba667a)
6. jika sudah dimasukan kode tersebut akan menampilkan halaman seperti ini
![image](https://github.com/user-attachments/assets/3f09c8b6-6bf2-4e06-9b0c-ab890013f4da)
8. Lalu masukan kode index.php untuk memunculkan halaman login di bagian web.
![image](https://github.com/user-attachments/assets/c74cac54-e300-4359-bc51-3dc321037f58)
9. berikut tampilan halaman pada login yang sudah dimasukan kode diatas 
![image](https://github.com/user-attachments/assets/fd10275e-0807-45c7-8375-3a0381ea37ff)
10. Setelah memasukan kode index lalu masukan kode welcome untuk menampilkan halaman setelah login.
![image](https://github.com/user-attachments/assets/069420cb-e96e-4cc7-b08e-8f41406b59f1)
11. setelah berhasil membuat kode tersebut akan menampilkan halaman seperti ini
![image](https://github.com/user-attachments/assets/ab5ee5ee-054a-40df-b59a-a4ff71198789)
12. Terakhir masukan kode logout untuk kembali ke tampilan awal pada halaman web 
![image](https://github.com/user-attachments/assets/36b0523e-d2bd-4d10-bb1e-00d74a361f5b)
Hasil Experiment
Pada bagian admin.php di bawah ini : 
 ![image](https://github.com/user-attachments/assets/115dd54b-77f3-4be4-89b5-f55b3d3b7b2b)
Pada penggunaan metode seperti ini :
•	get()
•	get_where()
•	select_sum()
menggunakan framework code igniter yang berarti pada bagian admin.php aman dari serangan sql injection.
Pada bagian login admin tedapat username dan password jika memasukan kode seperti ini
 ![image](https://github.com/user-attachments/assets/9dce4410-52a5-4798-831e-4023e95e46bb)
Maka username dan password pada bagian website akan terbuka oleh kode diatas 
![image](https://github.com/user-attachments/assets/8bad5766-d442-4252-8c36-a1f590f70ea6)
Tetapi setelah di coba untuk memasukan kode tersebut tidak berhasil masuk ke dalam admin 
![image](https://github.com/user-attachments/assets/4d21ad3e-4744-4f01-acc6-6a139b34f148)

lalu muncul peringatan username belum terdaftar jadi kesimpulan nya web yang telah dibuat tidak dapat terkena serangan sql injection. 
