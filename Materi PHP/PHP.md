# Apa itu web dinamis dan PHP?
- Sebuah website dinamis adalah situs web yang kontennya dapat berubah secara dinamis berdasarkan input pengguna, interaksi, atau data yang diterima dari sumber eksternal. 
- PHP adalah bahasa pemrograman server-side yang sering digunakan untuk membuat website dinamis. Dengan PHP, Anda dapat membuat halaman web yang dapat berinteraksi dengan database, menghasilkan konten secara dinamis, dan melakukan berbagai tugas pemrosesan data lainnya.
# Echo & commentar
"Echo" dalam konteks PHP adalah perintah yang digunakan untuk menampilkan teks atau variabel ke dalam halaman web. Ini digunakan untuk menghasilkan output yang terlihat oleh pengguna.

Contoh penggunaan "echo" dalam PHP:
```php
<?php
echo "Hello, world!";
?>
```

Sementara itu, "commentar" (kemungkinan maksudnya adalah "comment" atau "komentar") adalah bagian dari kode yang tidak dieksekusi oleh interpreter, tetapi digunakan untuk memberikan penjelasan atau dokumentasi tentang bagian kode tersebut. Di PHP, komentar bisa ditulis menggunakan dua cara:

1. Komentar satu baris dengan tanda dua garis miring:
```php
// Ini adalah komentar satu baris
```

2. Komentar multi-baris dengan tanda slash dan asterisk:
```php
/*
Ini adalah
komentar multi-baris
*/
```
# Variable, const, operator
Variabel adalah suatu simbol yang digunakan untuk menyimpan nilai yang dapat berubah selama proses eksekusi program. Di PHP, variabel dideklarasikan dengan menggunakan tanda dollar ($) diikuti dengan nama variabelnya.

Contoh:
```php
$nama = "John";
$umur = 25;
```

Konstanta, di sisi lain, adalah nilai yang tidak dapat berubah selama eksekusi program. Mereka didefinisikan menggunakan fungsi `define()` dan tidak dapat diubah nilai atau nilai kembali setelah didefinisikan.

Contoh:
```php
define("PI", 3.14);
```

Operator adalah simbol atau kata kunci yang digunakan untuk melakukan operasi pada variabel dan nilai. Di PHP, operator dibagi menjadi beberapa jenis, seperti operator aritmatika (+, -, *, /), operator perbandingan (==, !=, <, >), operator logika (&&, ||, !), dan banyak lagi.

Contoh:
```php
$a = 10;
$b = 5;

// Operator aritmatika
$jumlah = $a + $b; // Hasilnya 15

// Operator perbandingan
if ($a > $b) {
    echo "Nilai a lebih besar dari b";
}

// Operator logika
if ($a > 0 && $b > 0) {
    echo "Kedua nilai positif";
}
```