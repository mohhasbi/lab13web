# lab13web

# Nama : Moh. Hasbi Hasbiyah
# NIM : 311910711
# Kelas : TI 19 B2

# 1. Membuat table user
![Screenshot (36)](https://user-images.githubusercontent.com/81578584/123659252-aca4bb80-d85c-11eb-98ff-8f516a33df42.png)

# 2. Membuat model untuk memproses data login. Buat file baru pada directory app/models dengan nama UserModel.php
![1](https://user-images.githubusercontent.com/81578584/123659799-42404b00-d85d-11eb-9e62-f1fb8c981c56.PNG)

# 3. Membuat controller baru dengan nama user.php pada directory app/controlers
# Kemudian tambahkan method index () untuk menampilkan daftar user dan method login () utnuk proses login.
![2](https://user-images.githubusercontent.com/81578584/123664581-a7963b00-d861-11eb-8501-a6cd14463cda.PNG)
![3](https://user-images.githubusercontent.com/81578584/123664582-a7963b00-d861-11eb-927b-214dd806ca3e.PNG)

# 4. Membuat directory baru dengan nama user pada directory app/views, Kemudian buat file baru dengan nama login.php![4](https://user-images.githubusercontent.com/81578584/123665420-779b6780-d862-11eb-8898-3f433de88df9.PNG)

# 5. Database seeder digunakan untuk membuat data dummy. Untuk keperluan ujicoba modul login, kita perlu memasukkan data user dan password kedaalam database. Untuk itu buat database seeder untuk tabel user. Buka CLI, kemudian tulis perintah berikut:
![5](https://user-images.githubusercontent.com/81578584/123666401-5edf8180-d863-11eb-83b9-1b4f8bb680af.PNG)

# Selanjutnya, buka file UserSeeder.php yang berada di lokasi direktori /app/Database/Seeds/UserSeeder.php kemudian isi dengan kode berikut :
![6](https://user-images.githubusercontent.com/81578584/123666587-8d5d5c80-d863-11eb-823f-f92a50bf6c10.PNG)

# Selanjutnya buka kembali CLI dan ketik perintah berikut :
![7](https://user-images.githubusercontent.com/81578584/123666836-c5649f80-d863-11eb-81a4-828e7551bedc.png)

# Selanjutnya buka url http://localhost:8080/user/login seperti berikut :
![Screenshot (37)](https://user-images.githubusercontent.com/81578584/123667582-7c611b00-d864-11eb-8c2c-147f1a2414b5.png)

# 6. Selanjutnya membuat filer untuk halaman admin. Buat file baru dengan nama Auth.php pada direktori app/Filters.
![8](https://user-images.githubusercontent.com/81578584/123667953-d19d2c80-d864-11eb-8eeb-bcb8727dc210.PNG)

# 7. Selanjutnya buka file app/Config/Filters.php tambahkan kode berikut :
![9](https://user-images.githubusercontent.com/81578584/123668394-41abb280-d865-11eb-9d2b-bf8c3fb55fb7.PNG)

# 8. Selanjutnya buka file app/Config/Routes.php dan sesuaikan kodenya
![10](https://user-images.githubusercontent.com/81578584/123668730-951e0080-d865-11eb-94b2-cc0849738c49.PNG)

# 9. Percobaan Akses Menu Admin
# Buka url dengan alamat http://localhost:8080/admin/artikel ketika alamat tersebut diakses maka, akan dimuculkan halaman login
![Screenshot (38)](https://user-images.githubusercontent.com/81578584/123669096-f2b24d00-d865-11eb-9361-f7ee5a7c1dc9.png)

# Tambahkan method logout pada Controller User seperti berikut :
![11](https://user-images.githubusercontent.com/81578584/123669486-550b4d80-d866-11eb-926f-0e8971c7f71b.PNG)

# Login
![Screenshot (39)](https://user-images.githubusercontent.com/81578584/123669996-ea0e4680-d866-11eb-8878-1bc533cd38ae.png)

# Tampilan setelah login
![Screenshot (40)](https://user-images.githubusercontent.com/81578584/123673586-d82ea280-d86a-11eb-9f04-c8a8757e6e16.png)

# Tampilan sebelum logout
![Screenshot (41)](https://user-images.githubusercontent.com/81578584/123673672-f0062680-d86a-11eb-9fc0-dbda3b3ace49.png)

# Tampilan setelah logout
![Screenshot (42)](https://user-images.githubusercontent.com/81578584/123673755-0b713180-d86b-11eb-83b3-ddcdb0c05afe.png)







