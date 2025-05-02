Experiment 
1. Menjalankan Apache dan Mysql melalui aplikasi XAMPP.
![Gambar1](https://github.com/user-attachments/assets/64cf6ad7-748b-4eb3-8252-adbb44f5da8c)









2. Buatkan database untuk menghubungkan ke web tersebut 
3. untuk membuat database buka lah web browser lalu ketikan http://localhost/phpmyadmin
![Gambar2](https://github.com/user-attachments/assets/53a9fd32-2fa2-44cf-9a2d-41168d757cc3)















4. setelah dibuat databasenya lalu koneksikan ke database dengan kode tersebut 
![Gambar3](https://github.com/user-attachments/assets/18656b07-6fc3-4e78-ad82-b65bf4ed86de)








	
5. setelah di koneksikan berhasil lalu memasukan kode register untuk membuat akun pada tampilan login
![Gambar4](https://github.com/user-attachments/assets/08686b54-3b35-4999-beea-94d89aba667a)

















6. jika sudah dimasukan kode tersebut akan menampilkan halaman seperti ini 
 
7. Lalu masukan kode index.php untuk memunculkan halaman login di bagian web.
![Gambar5](https://github.com/user-attachments/assets/5efaaf20-4cc3-4cf5-bff6-f7e664f84e8a)














8. berikut tampilan halaman pada login yang sudah dimasukan kode diatas 
 
9. Setelah memasukan kode index lalu masukan kode welcome untuk menampilkan halaman setelah login.
![Gambar6](https://github.com/user-attachments/assets/e6435e3c-3b50-4483-8afb-be4b2da4d067)










11. setelah berhasil membuat kode tersebut akan menampilkan halaman seperti ini




12. Terakhir masukan kode logout untuk kembali ke tampilan awal pada halaman web 








Hasil Experiment
Pada bagian admin.php di bawah ini : 
 
Pada penggunaan metode seperti ini :
•	get()
•	get_where()
•	select_sum()
menggunakan framework code igniter yang berarti pada bagian admin.php aman dari serangan sql injection.
Pada bagian login admin tedapat username dan password jika memasukan kode seperti ini
 
Maka username dan password pada bagian website akan terbuka oleh kode diatas 







Tetapi setelah di coba untuk memasukan kode tersebut tidak berhasil masuk ke dalam admin 








lalu muncul peringatan username belum terdaftar jadi kesimpulan nya web yang telah dibuat tidak dapat terkena serangan sql injection. 

