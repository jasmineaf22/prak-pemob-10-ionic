Jasmine Adzra Fakhirah
H1D022071
Prak Mobile Shift D
![alt text](Animation.gif)


Autentikasi Login dengan Google

Login dengan Google:

Pengguna diminta untuk mengklik tombol "Login dengan Google" pada halaman login.
Setelah mengklik tombol tersebut, pengguna akan diarahkan ke halaman otentikasi Google, di mana mereka harus memasukkan kredensial akun Google mereka (email dan password).
Verifikasi dan Otorisasi:

Setelah pengguna berhasil login, Google akan meminta izin untuk membagikan informasi dasar pengguna dengan aplikasi, seperti nama lengkap dan foto profil.
Pengguna dapat memilih untuk memberikan izin atau menolak. Jika izin diberikan, aplikasi akan menerima data pengguna.
Akses Token:

Aplikasi akan menerima token otentikasi dari Google yang digunakan untuk melakukan panggilan API ke Google untuk mendapatkan data pengguna yang relevan.
Mendapatkan Data Pengguna:

Dengan token yang diterima, aplikasi melakukan permintaan API ke Google untuk mengambil data pengguna, seperti:
Nama lengkap
Foto profil
Alamat email
Data ini digunakan untuk memperbarui tampilan profil pengguna di aplikasi, memberi pengalaman pengguna yang lebih personal.
Menampilkan Profil:

Setelah data berhasil diambil, aplikasi akan menampilkan nama dan foto profil pengguna di halaman utama atau dashboard aplikasi.