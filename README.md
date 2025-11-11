# Lab7Web

Nama    : Zizantara Arzeva Cakra Kahana

NIM     : 312410398

Kelas   : TI.24.A.3

## 🐘 Belajar PHP Dasar

Proyek ini berisi kumpulan contoh kode PHP dasar untuk memahami konsep-konsep fundamental seperti output sederhana, variabel, form input, operator, kondisi, dan perulangan.
Setiap file dibuat secara bertahap untuk membantu pemula memahami logika dan sintaks PHP dengan mudah.

### 📂 Struktur File
`php_dasar.php`	Menampilkan teks dengan `echo`, penggunaan variabel, dan penerapan `$_GET`

`latihan2.php`	Contoh form input `POST`, operator aritmatika, kondisi `if` dan `switch`, serta perulangan `for`, `while`, `do while`

`praktikum.php`	Form input data diri dengan perhitungan umur dan gaji berdasarkan pekerjaan

### 💡 Penjelasan Fitur Utama
1️⃣ Output Dasar dan Variabel

File pertama (php_dasar.php) memperkenalkan konsep dasar:

```
echo "Hello World";
$nama = 'Zizantara Arzeva Cakra Kahana';
$nim = '312410398';
```

➡️ Menampilkan teks dan data menggunakan variabel PHP serta menampilkan nilai dari parameter $_GET.

2️⃣ Form Input dan Logika Dasar

File kedua (`phpdasar2.php`) memperlihatkan:

Form input dengan metode POST

Perhitungan gaji dan pajak

Kondisi IF dan SWITCH

Perulangan For, While, Do-While

Contoh logika sederhana:
```
$gaji = 1000000;
$pajak = 0.1;
$thp = $gaji - ($gaji * $pajak);
```

➡️ Menghitung gaji bersih setelah dikurangi pajak.

Kondisi hari juga diuji menggunakan `if-elseif` dan `switch-case`.

3️⃣ Form Data Diri Dinamis

File ketiga (`formdatadiri.php`) adalah versi yang lebih kompleks:

- Menggunakan form HTML dengan input nama, tanggal lahir, dan pekerjaan

- Menghitung umur otomatis berdasarkan tanggal lahir

- Menentukan gaji berdasarkan pilihan pekerjaan

- Menampilkan hasil secara rapi di bagian output

Contoh perhitungan:
```
$tanggal_lahir_obj = new DateTime($tanggal_lahir);
$hari_ini = new DateTime();
$umur = $hari_ini->diff($tanggal_lahir_obj)->y;
```

➡️ Memanfaatkan class `DateTime()` untuk menghitung umur secara otomatis.

🧮 Contoh Output

Input Form Data Diri:
```
Nama: Zizantara Arzeva Cakra Kahana
Tanggal Lahir: 2003-08-17
Pekerjaan: Programmer
```

Output:
```
Nama: Zizantara Arzeva Cakra Kahana
Tanggal Lahir: 2003-08-17
Umur: 22 tahun
Pekerjaan: Programmer
Gaji: Rp 10.000.000
```

### ⚙️ Cara Menjalankan Program

1. Simpan semua file di dalam folder htdocs (untuk XAMPP) atau www (untuk Laragon).

2. Jalankan server lokal melalui XAMPP Control Panel → klik Start pada Apache.

3. Buka browser dan akses:
```
http://localhost/php_dasar.php
http://localhost/latihan2.php
http://localhost/praktikum.php
```

4. Isi form sesuai instruksi dan amati hasilnya di halaman web.

🧠 Konsep yang Dipelajari

- ✅ Struktur dasar file PHP
- ✅ Variabel dan tipe data
- ✅ Metode `GET` dan `POST`
- ✅ Operator aritmatika
- ✅ Struktur kontrol (`if`, `switch`)
- ✅ Perulangan (`for`, `while`, `do while`)
- ✅ Penggunaan objek `DateTime()`
- ✅ Menampilkan output dengan format yang rapi