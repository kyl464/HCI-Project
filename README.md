# HCI-Project

<h1>Penjelasan file Index.html</h1>

1.	Pada bagian <head>, terdapat judul halaman yang ditentukan dengan menggunakan tag <title>.

2.	Kemudian, terdapat file CSS yang dihubungkan dengan menggunakan tag <link> dan atribut rel yang memiliki nilai "stylesheet" untuk menghubungkan file style.css dengan halaman HTML.


3.	Selanjutnya, ada blok skrip JavaScript yang dimulai dengan tag <script>. Di dalamnya, terdapat sebuah fungsi bernama proses().

4.	Fungsi proses() digunakan untuk memvalidasi input pada form sebelum data dikirimkan.


5.	Variabel-variabel seperti nama, kelamin, tempat, tgl, agama, status, kerja, alamat, nomor, nik, dan kk diinisialisasi dengan nilai dari elemen-elemen form menggunakan metode getElementById().

6.	Dilakukan serangkaian pengecekan kondisi, seperti apakah nama, nik, tgl, tempat, agama, status, kerja, alamat, nomor, dan kk memiliki nilai kosong atau tidak.


7.	Jika salah satu kondisi tidak terpenuhi, akan muncul pesan peringatan menggunakan fungsi alert() dan fungsi akan mengembalikan nilai false untuk mencegah pengiriman form.

8.	Jika semua kondisi terpenuhi, akan muncul pesan yang berisi data yang diisi pada form menggunakan fungsi alert().


9.	Setelah itu, akan muncul kotak dialog konfirmasi menggunakan fungsi confirm() untuk memastikan apakah data sudah benar atau tidak.

10.	Jika pengguna menekan tombol "OK" pada kotak dialog, fungsi proses() akan mengembalikan nilai true untuk mengirimkan form. Jika pengguna memilih tombol "Cancel", fungsi akan mengembalikan nilai false untuk mencegah pengiriman form.


11.	Di dalam <body>, terdapat elemen <form> yang memiliki atribut onsubmit yang mengeksekusi fungsi proses() saat form dikirim.

12.	Pada elemen form, terdapat judul "Pendaftaran KTP" yang ditampilkan dengan menggunakan tag h1.

13.	Selanjutnya, terdapat beberapa elemen form seperti input teks, pilihan (dropdown), dan textarea yang digunakan untuk mengumpulkan data dari pengguna.

14.	Setiap elemen form diberi atribut name yang akan digunakan saat form dikirimkan.


15.	Terdapat juga atribut id pada masing-masing elemen form yang digunakan dalam skrip JavaScript untuk mendapatkan nilai dari elemen tersebut.

16.	Beberapa elemen form juga diberi atribut placeholder untuk memberikan petunjuk kepada pengguna mengenai format yang diharapkan pada input.


17.	Terdapat sebuah checkbox yang diberi atribut required untuk memastikan bahwa pengguna harus mencentangnya sebelum form dapat dikirimkan.

18.	Terakhir, terdapat sebuah tombol submit dengan nilai "Daftar" yang akan mengirimkan form saat diklik.

   	<h1>Penjelasan file style.css</h1>
1.	body: Mengatur properti untuk elemen <body>, seperti jenis font yang digunakan (font-family) dan warna latar belakang (background-color).

2.	form: Mengatur properti untuk elemen <form>, seperti lebar maksimum (max-width), margin, padding, border, dan warna latar belakang.

3.	h1: Mengatur properti untuk elemen h1, seperti penataan teks di tengah (text-align: center).

4.	input[type="text"], input[type="date"]: Mengatur properti untuk elemen input dengan tipe "text" dan "date", seperti lebar (width), padding, margin bawah, border, dan jenis font.

5.	select: Mengatur properti untuk elemen <select>, seperti lebar, padding, margin bawah, border, dan jenis font.

6.	input[type="submit"]: Mengatur properti untuk elemen input dengan tipe "submit", seperti 

7.	lebar, padding, warna latar belakang, warna teks, border, dan kursor saat diarahkan.

8.	input[type="submit"]:hover: Mengatur properti saat elemen input dengan tipe "submit" diarahkan menggunakan kursor, seperti perubahan warna latar belakang.

9.	textarea: Mengatur properti untuk elemen <textarea>, seperti lebar, padding, margin bawah, border, pengaturan ulang ukuran vertikal, dan jenis font.



10.	Media Query:

-	@media only screen and (max-width: 600px): Mengatur properti dalam halaman saat lebar layar maksimum adalah 600px, khususnya untuk elemen <form> dengan memperkecil lebar maksimumnya.
-	@media only screen and (max-width: 400px): Mengatur properti dalam halaman saat lebar layar maksimum adalah 400px, khususnya untuk elemen input dengan tipe "text", <select>, dan input dengan tipe "date" dengan memperkecil ukuran fontnya.
-	@media only screen and (max-width: 320px): Mengatur properti dalam halaman saat lebar layar maksimum adalah 320px, khususnya untuk elemen input dengan tipe "text", <select>, dan input dengan tipe "date" dengan memperkecil ukuran fontn
