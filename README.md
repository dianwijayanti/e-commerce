# Pengertian API E-Commerce
API (Application Programming Interface) merupakan kumpulan perangkat lunak yang memungkinkan aplikasi dan sistem yang berbeda untuk berkomunikasi. API e-commerce memungkinkan interaksi dan pertukaran data antara aplikasi pihak ketiga dan platform e-commerce untuk melakukan berbagai operasi seperti mengambil data produk, membuat pesanan, memperbarui inventaris, dan lainnya. Dengan menggunakan API ini, pengembang dapat mengambil informasi produk, harga, stok, serta melakukan operasi lainnya, seperti membuat, memperbarui, atau menghapus pesanan secara otomatis.

# Tugas API E-Commerce
Tugas ini mengenai tentang `Pembuatan Backend API untuk Aplikasi E-Commerce Sederhana`. Backend berperan penting dalam menjembatani antara aplikasi frontend dan database dalam sebuah sistem. Dalam pembuatan backend, server akan menangani permintaan dari aplikasi frontend dan memberikan respons yang sesuai serta bertanggung jawab dalam berkomunikasi dengan database untuk menyimpan dan mengambil data yang diperlukan. Tipe permintaan yang dimaksud disini meliputi `GET`, `POST`, `PUT`, dan `DELETE`. Pembuatan backend API ini memiliki ketentuan-ketentuan yang telah ditentukan, berikut diantaranya.
1.	Menggunakan request method pada API serta struktur tabel database yang telah ditentukan. 
2.	Body pada request POST dan PUT serta response yang diberikan oleh server API menggunakan format JSON.
3.	Otorisasi akses API menggunakan API key yg di set melalui ENV variable. 
4.	Data disimpan pada database SQLite, 
5.	Pengujian API menggunakan aplikasi Postman.
6.	Alamat Port menggunakan 3 digit terakhir dari NIM yaitu 069.
7.	Spesifikasi API GET, POST, dan PUT yang telah ditentukan.

## pom.xml
File `pom.xml` tersebut membahas mengenai pengaturan dan informasi yang diperlukan untuk mengelola proyek menggunakan Maven. Pada file ini akan mengelola dependensi, mengkoordinasikan kompilasi, dan menjalankan tugas-tugas lainnya dalam proses pengembangan perangkat lunak.

## ecommerce.db
Pada bagian ini, data-data akan disimpan pada database SQLitenya.

 ## src/main/java
Bagian ini berisikan pengimplementasian dari request method pada API

