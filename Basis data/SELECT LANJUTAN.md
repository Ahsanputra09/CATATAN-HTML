## AND
### Struktur query
### Contoh query
```sql
SELECT warna,pemilik FROM mobil WHERE warna="hitam" AND pemilik="Ahsan";
```
### Hasil
![](Assets/and.jpg)
### Analisis
`SELECT warna,pemilik FROM mobil WHERE warna="hitam" AND pemilik="Ahsan";` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `warna, pemilik` : Nama kolom yang ingin ditampilkan dalam hasil query, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada kueri, `warna="hitam"` : Kondisi di mana nilai kolom `warna` harus sama dengan "hitam", `AND` : Operator logika yang digunakan untuk menggabungkan dua atau lebih kondisi, `pemilik="Ahsan"` : Kondisi di mana nilai kolom `pemilik` harus sama dengan "Ahsan".
### Kesimpulan
`SELECT warna, pemilik FROM mobil WHERE warna="hitam" AND pemilik="Ahsan";` digunakan untuk memilih nilai dari kolom "warna" dan "pemilik" dari tabel "mobil" di mana nilai kolom "warna" adalah "hitam" dan nilai kolom "pemilik" adalah "Ahsan".

---
## OR
### Struktur query
### Contoh query
```sql
SELECT warna,pemilik FROM mobil WHERE warna="hitam" OR pemilik="Ahsan";
```
### Hasil
![](Assets/or.jpg)
### Analisis
`SELECT warna,pemilik FROM mobil WHERE warna="hitam" OR pemilik="Ahsan";` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `warna, pemilik` : Nama kolom yang ingin ditampilkan dalam hasil query, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `warna="hitam" OR pemilik="Ahsan"` : Kondisi di mana nilai kolom `warna` harus sama dengan "hitam" atau nilai kolom `pemilik` harus sama dengan "Ahsan".
### Kesimpulan
`SELECT warna, pemilik FROM mobil WHERE warna="hitam" OR pemilik="Ahsan";` digunakan untuk memilih nilai dari kolom "warna" dan "pemilik" dari tabel "mobil" di mana nilai kolom "warna" adalah "hitam" atau nilai kolom "pemilik" adalah "Ahsan".

---
## BETWEEN
### Struktur query
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;
```
### Hasil
![](Assets/between.jpg)
### Analisis
### Kesimpulan

---
## NOT BETWEEN
### Struktur query
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 200000;
```
### Hasil
![](Assets/not_between.jpg)
### Analisis
### Kesimpulan

---
## <=
### Struktur query
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental <=50000;
```
### Hasil
![](Assets/kurang=.jpg)
### Analisis
### Kesimpulan

---
## >=
### Struktur query
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental >=50000;
```
### Hasil
![](Assets/lebih=.jpg)
### Analisis
### Kesimpulan

---
## <>
### Struktur query
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental <> 50000;
```
### Hasil
![](Assets/besar-kecil.jpg)
### Analisis
### Kesimpulan

---
## !=
### Struktur query
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental != 50000;
```
### Hasil
![](Assets/tidak=.jpg)
### Analisis
### Kesimpulan

---
## TANTANGAN LOGIN
### Struktur query
### Contoh query
```sql
select pemilik from mobil where pemilik="Ahsan";
```
### Hasil
![](Assets/tantangan_login.jpg)
### Analisis
### Kesimpulan

---
