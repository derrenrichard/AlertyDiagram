# Proyek Analisis dan Desain Sistem Informasi: Alerty

Dokumentasi ini berisi detail proyek untuk mata kuliah **ISYS6677003 – INFORMATION SYSTEMS ANALYSIS AND DESIGN** di Universitas Bina Nusantara.

---

## Informasi Mata Kuliah

- **Universitas**: BINUS UNIVERSITY
- **Fakultas**: Information System
- **Laboratorium**: JAKARTA Laboratory
- **Mata Kuliah**: ISYS6677003 – INFORMATION SYSTEMS ANALYSIS AND DESIGN
- **Semester**: GANJIL 2024/2025

---

## Deskripsi Proyek: Alerty

> Saat ini banyak masyarakat yang mengalami kesulitan dalam mengakses nomor darurat dan melaporkan kejadian sosial secara efisien. Hal tersebut menyebabkan sebuah platform peringatan mulai dikembangkan dan sebagian masyarakat disarankan untuk menggunakan platform tersebut. Platform yang akan dikembangkan bernama Alerty yang merupakan sebuah mobile application yang dapat memudahkan pengguna dalam menghubungi nomor darurat dan mengajukan laporan sosial. Fitur yang tersedia dalam aplikasi Alerty mampu menjadi solusi terpadu bagi konsumen untuk mendapatkan bantuan darurat dan melaporkan masalah sosial dengan mudah. Alerty menggunakan teknologi mobile yang memungkinkan pengguna untuk menghubungi pihak berwenang dan mengirim laporan langsung melalui aplikasi dengan cepat dan mudah. Informasi yang dikirimkan dapat segera diteruskan kepada pihak berwenang yang relevan untuk tindakan lebih lanjut. Berdasarkan survei yang diadakan oleh tim pemasaran Alerty, sebesar 72% pengguna merasa bahwa sistem pelaporan melalui aplikasi sangat membantu dalam mengurangi waktu respon pihak berwenang dan mempermudah proses pelaporan tanpa harus melalui prosedur yang berbelit-belit. Melalui aplikasi Alerty, pengguna juga dapat melacak status laporan dan memberikan umpan balik terkait respons yang diterima.

---

## Proses Bisnis Aplikasi Alerty

Berikut ini adalah proses bisnis dari aplikasi Alerty:

### 1. Pendaftaran dan Login Pengguna
Pengguna yang ingin menggunakan aplikasi Alerty dapat men-download aplikasi Alerty terlebih dahulu melalui Play Store atau App Store. Setelah berhasil men-download aplikasi, pengguna harus melakukan login menggunakan akun yang telah terdaftar. Apabila pengguna belum mempunyai akun yang terdaftar, maka pengguna dapat melakukan sign up dengan mengisi data diri berupa nama lengkap, email, nomor handphone, gender, tanggal lahir, password, dan re-password. Setelah data diisi dengan lengkap, pengguna dapat menekan tombol next dan aplikasi akan menampilkan halaman survei kuesioner. Pada halaman survei kuesioner, pengguna dapat memilih masalah yang sering dihadapi dalam setiap kategori yang tersedia. Jika sudah terisi, pengguna dapat menekan tombol “Sign Up”. Kemudian, sistem akan menyimpan data pengguna dan halaman login akan terbuka. Pada halaman login, pengguna dapat mengisi email atau nomor handphone serta password sesuai dengan data yang telah didaftarkan sebelumnya. Kemudian, pengguna dapat menekan tombol login dan pengguna akan diarahkan ke halaman home.

### 2. Halaman Home dan Fitur Tombol Darurat
Pada halaman home, survei kuesioner yang telah diisi ditampilkan dalam bentuk rekomendasi penanganan pertama dan hal yang harus dilakukan oleh pengguna. Pengguna dapat melaporkan kejadian darurat secara cepat dengan menekan emergency button. Ketika pengguna menekan emergency button, pengguna akan terhubung dengan admin melalui telepon. Saat telepon sedang berlangsung, admin akan mengisi form emergency. Dalam form tersebut, admin diminta untuk mengisi data berupa nama pelapor, alamat, dan rincian kejadian. Setelah data telah diisi dengan lengkap, admin dapat menekan tombol “Submit” dan sistem akan menyimpan laporan tersebut dilengkapi dengan tanggal, waktu, dan status kejadian. Lalu, dilanjutkan juga dengan mengirim laporan tersebut kepada helpers. Kemudian, helpers akan segera datang ke lokasi dan membantu pengguna secara langsung. Setelah telepon selesai, sistem akan menyimpan data durasi telepon, tanggal telepon, dan nama akun penelpon. Ketika helpers telah selesai membantu pengguna, maka admin akan meng-update status form emergency menjadi “Done”.

### 3. Fitur Pelaporan Sosial
Pengguna juga dapat melaporkan kejadian yang sedang terjadi dengan menekan tombol “Add Laporan” dan memilih kategori laporan. Kategori laporan tersebut ditampilkan dengan informasi berupa nama kategori dan deskripsi kategori. Dalam satu kali pelaporan, pengguna dapat memilih lebih dari 1 kategori laporan. Setelah memilih kategori, pengguna diminta untuk mengisi data form laporan sosial berupa judul laporan, nama pelapor, nomor telepon, alamat kejadian, deskripsi kejadian, dan foto kejadian. Apabila data telah terisi dengan lengkap, pengguna dapat menekan tombol ”Submit” dan sistem akan menyimpan data tersebut. Kemudian, admin akan mengirimkan pesan pemberitahuan kepada helpers untuk menuju lokasi yang membutuhkan bantuan. Apabila helpers telah selesai membantu pengguna, maka helpers perlu mengisi form konfirmasi bantuan dengan memilih laporan yang telah selesai dibantu. Hal tersebut dilakukan untuk membuktikan bahwa bantuan telah diselesaikan dengan baik. Dalam form konfirmasi tersebut, helpers diminta untuk mengisi data berupa foto bukti, deskripsi kejadian, dan waktu penyelesaian. Apabila data telah diisi dengan lengkap, helpers dapat menekan tombol “Submit” dan sistem akan meng-update status laporan menjadi “Done”.

### 4. Halaman Profil, Riwayat, dan Ulasan
Ketika pengguna mengakses halaman profile, aplikasi akan menampilkan data diri pengguna. Selain itu, juga terdapat riwayat laporan pengguna yang telah diselesaikan oleh para helpers. Pengguna dapat memberikan review terhadap riwayat laporan sosial dengan memilih salah satu riwayat yang telah selesai ditangani. Kemudian, aplikasi akan menampilkan halaman form review laporan. Pada halaman form review laporan, pengguna akan diminta untuk mengisi data berupa rating dengan skala 1 sampai 5 untuk penyelesaiannya, rating dengan skala 1 sampai 5 untuk helpers, deskripsi review, serta foto (opsional) untuk review tersebut. Apabila data telah diisi dengan lengkap, pengguna dapat menekan tombol “Submit” dan sistem akan menyimpan data review tersebut.

### 5. Fitur Feedback Aplikasi
Fitur lainnya yang tersedia dalam aplikasi Alerty adalah pengguna dapat memberikan feedback terhadap aplikasi Alerty. Pengguna yang ingin memberikan feedback dapat menekan tombol “Add” pada halaman profile dan aplikasi akan menampilkan form feedback Alerty. Pada halaman form feedback, pengguna diminta untuk mengisi rating dengan skala 1 sampai 5, keluhan aplikasi, dan foto keluhan (opsional). Apabila data telah terisi, pengguna dapat menekan tombol “Submit” dan sistem akan menyimpan data feedback aplikasi Alerty.

### 6. Laporan Statistik Bulanan (Admin)
Setiap akhir bulan, admin Alerty akan membuat laporan statistik jumlah laporan yang diterima pada bulan tersebut berdasarkan kategori laporannya. Laporan statistik tersebut berisi periode bulan, kategori, dan total jumlah laporan. Kemudian, laporan statistik akan diberikan kepada manajer Alerty sebagai bahan evaluasi operasional Alerty.

---

## Tugas Proyek

Sebagai seorang system analyst, Anda diminta untuk membuat:

1.  **Activity Diagram** (LO 1, LO 2)
2.  **Use Case Diagram** (LO 2)
3.  **Domain Model Class Diagram** (LO 3)
4.  **State Machine Diagram** (LO 3)
5.  **Use Case Description** (LO 2, LO 4)
6.  **Activity Diagram for Use Case** (LO 2, LO 4)
7.  **Use Case: System Sequence Diagram** (LO 4)
8.  **Use Case and CRUD** (LO 4)

---

## Referensi

1.  John W Satzinger, Robert B Jackson, Stephen D Burd. (2016). *Systems Analysis and Design in a Changing World 7th Edition*. (7th). CENGA. ISBN: 9781305117204.
2.  Alexander Osterwalder, et al. (2014). *Value proposition design: How to create products and services customers want*. (1st). John Wiley & Sons. ISBN: 9781118968055.
3.  Isabell Osann, Lena Mayer , Inga Wiele. (2020). *The Design Thinking Quick Start Guide: A 6-step Process for Generating and Implementing Creative Solutions*. (1st). Willey. ISBN: 9781119679899.
4.  Jake Knapp, John Zeratsky , Braden Kowitz, Dan Bittner. (2016). *Sprint: How to solve big problems and test new ideas in just five days*. (1st). Simon and Schuster. ISBN: 9781442397682.
