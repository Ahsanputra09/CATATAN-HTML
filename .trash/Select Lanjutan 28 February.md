## AND
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT warna,pemilik FROM mobil WHERE warna="hitam" AND pemilik="Ahsan";
```
### Hasil
![](Assets/AND.jpg)
### Analisis
`SELECT warna,pemilik FROM mobil WHERE warna="hitam" AND pemilik="Ahsan";` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `warna, pemilik` : Nama kolom yang ingin ditampilkan dalam hasil query, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada kueri, `warna="hitam"` : Kondisi di mana nilai kolom `warna` harus sama dengan "hitam", `AND` : Operator logika yang digunakan untuk menggabungkan dua atau lebih kondisi, `pemilik="Ahsan"` : Kondisi di mana nilai kolom `pemilik` harus sama dengan "Ahsan".
### Kesimpulan
`SELECT warna, pemilik FROM mobil WHERE warna="hitam" AND pemilik="Ahsan";` digunakan untuk memilih nilai dari kolom "warna" dan "pemilik" dari tabel "mobil" di mana nilai kolom "warna" adalah "hitam" dan nilai kolom "pemilik" adalah "Ahsan".

---
## OR
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT warna,pemilik FROM mobil WHERE warna="hitam" OR pemilik="Ahsan";
```
### Hasil
![](Assets/OR.jpg)
### Analisis
`SELECT warna,pemilik FROM mobil WHERE warna="hitam" OR pemilik="Ahsan";` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `warna, pemilik` : Nama kolom yang ingin ditampilkan dalam hasil query, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `warna="hitam" OR pemilik="Ahsan"` : Kondisi di mana nilai kolom `warna` harus sama dengan "hitam" atau nilai kolom `pemilik` harus sama dengan "Ahsan".
### Kesimpulan
`SELECT warna, pemilik FROM mobil WHERE warna="hitam" OR pemilik="Ahsan";` digunakan untuk memilih nilai dari kolom "warna" dan "pemilik" dari tabel "mobil" di mana nilai kolom "warna" adalah "hitam" atau nilai kolom "pemilik" adalah "Ahsan".

---
## BETWEEN
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;
```
### Hasil
![](Assets/BETWEEN.jpg)
### Analisis
`SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `harga_rental BETWEEN 100000 AND 200000` : Kondisi di mana nilai kolom harga_rental berada di antara (termasuk) 100.000 dan 200.000.
### Kesimpulan
 `SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom harga_rental berada di antara (termasuk) 100.000 dan 200.000.
 
---
## NOT BETWEEN
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 200000;
```
### Hasil
![](Assets/NOT_BETWEEN.jpg)
### Analisis
`SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 200000;` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `harga_rental NOT BETWEEN 100000 AND 200000` : Kondisi di mana nilai kolom harga_rental tidak berada di antara (termasuk) 100.000 dan 200.000.
### Kesimpulan
 `SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 200000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom harga_rental tidak berada di antara (termasuk) 100.000 dan 200.000.
 
---
## <=
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental <=50000;
```
### Hasil
![](Assets/kurang=.jpg)
### Analisis
`SELECT * FROM mobil WHERE harga_rental <=50000;` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `harga_rental <=50000` : Kondisi di mana nilai kolom harga_rental kurang dari atau sama dengan 50.000.
### Kesimpulan
 `SELECT * FROM mobil WHERE harga_rental <=50000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom harga_rental kurang dari atau sama dengan 50.000.
 
---
## >=
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental >=50000;
```
### Hasil
![](Assets/lebih=.jpg)
### Analisis
`SELECT * FROM mobil WHERE harga_rental >=50000;` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `harga_rental >=50000` : Kondisi di mana nilai kolom harga_rental lebih besar dari atau sama dengan 50.000.
### Kesimpulan
 `SELECT * FROM mobil WHERE harga_rental >=50000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom harga_rental lebih besar dari atau sama dengan 50.000.

---
## <>
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental <> 50000;
```
### Hasil
![](Assets/besar-kecil.jpg)
### Analisis
`SELECT * FROM mobil WHERE harga_rental <> 50000;` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `harga_rental <> 50000` : Kondisi di mana nilai kolom harga_rental tidak sama dengan 50.000.
### Kesimpulan
 `SELECT * FROM mobil WHERE harga_rental <> 50000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom harga_rental tidak sama dengan 50.000.

---
## !=
### Struktur query
```MySQL

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental != 50000;
```
### Hasil
![](Assets/tidak=.jpg)
### Analisis
`SELECT * FROM mobil WHERE harga_rental != 50000;` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `harga_rental != 50000` : Kondisi di mana nilai kolom harga_rental tidak sama dengan 50.000.
### Kesimpulan
 `SELECT * FROM mobil WHERE harga_rental != 50000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom harga_rental tidak sama dengan 50.000.

---
## TANTANGAN LOGIN
### Struktur query
```MySQL

```
### Contoh query
```sql
select pemilik from mobil where pemilik="Ahsan";
```
### Hasil
![](Assets/tantangan_login.jpg)
### Analisis
`select pemilik from mobil where pemilik="Ahsan";` : `SELECT` : Kata kunci yang digunakan untuk memilih kolom atau nilai dari tabel, `pemilik` : Nama kolom yang ingin ditampilkan dalam hasil query, `FROM` : Kata kunci yang menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Kata kunci yang digunakan untuk menerapkan kondisi pada query, `pemilik="Ahsan"` : Kondisi di mana nilai kolom pemilik harus sama dengan "Ahsan".
### Kesimpulan
 `SELECT pemilik FROM mobil WHERE pemilik="Ahsan";` digunakan untuk memilih nilai dari kolom "pemilik" dari tabel "mobil" di mana nilai kolom "pemilik" sama dengan "Ahsan".

---
## IN
### Struktur query
```MySQL

```
### Contoh query
```MySQL
SELECT * FROM mobil WHERE warna IN('pink','Hitam');
```
### Hasil
![hasil select IN](Assets/select_IN.jpg)
### Analisis
`SELECT * FROM mobil WHERE warna IN('pink','Hitam');` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `warna IN('pink','Hitam')` : Kondisi di mana nilai kolom warna adalah 'pink' atau 'Hitam'.
### Kesimpulan
 `SELECT * FROM mobil WHERE warna IN('pink','Hitam');` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom warna adalah 'pink' atau 'Hitam'.
 
---
## IN+AND
### Struktur query
```MySQL

```
### Contoh query
```MySQL
SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') AND harga_rental = 50000;
```
### Hasil
![hasil in and](Assets/IN_AND.JPG)
### Analisis
`SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') AND harga_rental = 50000;` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `warna IN ('Hitam','Biru')` : Kondisi di mana nilai kolom warna adalah 'Hitam' atau 'Biru', `AND` : Operator logika yang digunakan untuk menggabungkan dua atau lebih kondisi, `harga_rental = 50000` : Kondisi di mana nilai kolom harga_rental adalah 50000.
### Kesimpulan
 `SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') AND harga_rental = 50000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom warna adalah 'Hitam' atau 'Biru', dan nilai kolom harga_rental adalah 50000.
 
---
## IN+OR
### Struktur query
```MySQL

```
### Contoh query
```MySQL
SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') OR harga_rental = 50000;
```
### Hasil
![hasil in or](Assets/IN_OR.JPG)
### Analisis
`SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') OR harga_rental = 50000;` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `warna IN ('Hitam','Biru')` : Kondisi di mana nilai kolom warna adalah 'Hitam' atau 'Biru', `OR` : Operator logika yang digunakan untuk menggabungkan dua atau lebih kondisi, `harga_rental = 50000` : Kondisi di mana nilai kolom harga_rental adalah 50000.
### Kesimpulan
 `SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') OR harga_rental = 50000;` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom warna adalah 'Hitam' atau 'Biru', atau nilai kolom harga_rental adalah 50000.

---
## IN+AND+OPERATOR
### Struktur query
```MySQL

```
### Contoh query
OPERATOR ==`>`==
```MySQL
SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') AND harga_rental > 50000;
```

OPERATOR ==`<`==
```MySQL
SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') AND harga_rental < 100000;
```
### Hasil
OPERATOR ==`>`==
![hasil operator lebih dari](Assets/LEBIH_DARI.JPG)

OPERATOR ==`<`==
![hasil operator kurang dari](Assets/KURANG_DARI.JPG)

### Analisis
`SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') AND harga_rental > 50000;` ,
`SELECT * FROM mobil WHERE warna IN ('Hitam','Biru') AND harga_rental < 100000;`
`SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `warna IN ('Hitam','Biru')` : Kondisi di mana nilai kolom warna adalah 'Hitam' atau 'Biru', `AND` : Operator logika yang digunakan untuk menggabungkan dua atau lebih kondisi, `harga_rental > 50000` : Kondisi di mana nilai kolom harga_rental lebih besar dari 50000, `harga_rental < 100000` : Kondisi di mana nilai kolom harga_rental kurang dari 100000.
### Kesimpulan
bahwa kondisi `harga_rental > 50000` memilih data di mana harga sewa mobil lebih dari 50000, sementara kondisi `harga_rental < 100000` memilih data di mana harga sewa mobil kurang dari 100000.

---
## LIKE
### MENCARI AWALAN
#### Struktur query
```MySQL

```
#### Contoh query
```MySQL
SELECT * FROM mobil WHERE peminjam LIKE 'T%';
```
#### Hasil
![hasil like mencari awal](Assets/like-cari_awalan.jpg)
#### Analisis
`SELECT * FROM mobil WHERE peminjam LIKE 'T%';` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `peminjam LIKE 'T%'` : Kondisi di mana nilai kolom peminjam dimulai dengan huruf 'T'.
#### Kesimpulan
 `SELECT * FROM mobil WHERE peminjam LIKE 'T%';` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom peminjam dimulai dengan huruf 'T'.

---
### MENCARI AKHIRAN
#### Struktur query
```MySQL

```
#### Contoh query
```MySQL
SELECT * FROM mobil WHERE peminjam LIKE '%N';
```
#### Hasil
![hasil like cari akhiran](Assets/like-cari_akhiran.jpg)
#### Analisis
`SELECT * FROM mobil WHERE peminjam LIKE '%N';` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `peminjam LIKE '%N'` : Kondisi di mana nilai kolom peminjam diakhiri dengan huruf 'N'.
#### Kesimpulan
 `SELECT * FROM mobil WHERE peminjam LIKE '%N';`  digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom peminjam diakhiri dengan huruf 'N'.

---
### MENCARI AWALAN & AKHIRAN
#### Struktur query
```MySQL

```
#### Contoh query
```MySQL
SELECT * FROM mobil WHERE peminjam LIKE 'f%r';
```
#### Hasil
![hasil awal dan akhir](Assets/like-awal_akhir.jpg)
#### Analisis
`SELECT * FROM mobil WHERE peminjam LIKE 'f%r';` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `peminjam LIKE 'f%r'` : Kondisi di mana nilai kolom peminjam dimulai dengan 'f' dan diakhiri dengan 'r', dengan karakter apa pun di antara keduanya.
#### Kesimpulan
 `SELECT * FROM mobil WHERE peminjam LIKE 'f%r';` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom peminjam dimulai dengan 'f' dan diakhiri dengan 'r', dengan karakter apa pun di antara keduanya.

---
### MENCARI BERDASARKAN TOTAL KARAKTER
#### Struktur query
```MySQL

```
#### Contoh query
```MySQL
SELECT * FROM mobil WHERE warna LIKE 'H____';
```

```MySQL
SELECT * FROM mobil WHERE peminjam LIKE '_____';
```
#### Hasil
![hasil mencari h & 4 underscore](Assets/like-mencari_h.jpg)

![hasil mencari karakter 5 underscore](Assets/like-mencari_5u.jpg)
#### Analisis
`SELECT * FROM mobil WHERE warna LIKE 'H____';` , `SELECT * FROM mobil WHERE peminjam LIKE '_____';` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `warna LIKE 'H____'` : Kondisi di mana nilai kolom warna dimulai dengan 'H', diikuti oleh empat karakter apa pun, `peminjam LIKE '_____'` : Kondisi di mana nilai kolom peminjam memiliki panjang tepat lima karakter.
#### Kesimpulan
`SELECT * FROM mobil WHERE warna LIKE 'H____';` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom `warna` dimulai dengan 'H' dan diikuti oleh empat karakter apa pun.
`SELECT * FROM mobil WHERE peminjam LIKE '_____';` digunakan untuk memilih semua kolom dari tabel "mobil" di mana nilai kolom `peminjam` memiliki panjang tepat lima karakter.

---
### KOMBINASI
#### Struktur query
```MySQL

```
#### Contoh query
```MySQL
SELECT * FROM mobil WHERE warna LIKE '__t%';
```

```MySQL
select * from mobil where peminjam like '_a%';
```
#### Hasil
![hasil kombinasi 2 underscore](Assets/like-2USt.jpg)

![hasil 1 underscore](Assets/like-1USa.jpg)
#### Analisis
`SELECT * FROM mobil WHERE warna LIKE '__t%';` , `select * from mobil where peminjam like '_a%';` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `warna LIKE '__t%'` : Kondisi di mana nilai kolom warna memiliki dua karakter di awal, diikuti oleh 't', dan kemudian diikuti oleh nol atau lebih karakter apa pun, `peminjam like '_a%'` : Kondisi di mana nilai kolom peminjam memiliki satu karakter di awal, diikuti oleh 'a', dan kemudian diikuti oleh nol atau lebih karakter apa pun.
#### Kesimpulan
`SELECT * FROM mobil WHERE warna LIKE '__t%';` digunakan untuk memilih data dari tabel "mobil" di mana nilai kolom `warna` memiliki dua karakter di awal, diikuti oleh 't', dan kemudian diikuti oleh nol atau lebih karakter apa pun.
`SELECT * FROM mobil WHERE peminjam LIKE '_a%';` digunakan untuk memilih data dari tabel "mobil" di mana nilai kolom `peminjam` memiliki satu karakter di awal, diikuti oleh 'a', dan kemudian diikuti oleh nol atau lebih karakter apa pun.

---
### NOT LIKE
#### Struktur query
```MySQL

```
#### Contoh query
```MySQL
SELECT * FROM mobil WHERE warna NOT LIKE 'H%';
```
#### Hasil
![hasil not like](Assets/like-not_like.jpg)

#### Analisis
`SELECT * FROM mobil WHERE warna NOT LIKE 'H%';` : `SELECT` : Digunakan untuk memilih kolom atau nilai dari tabel, `*` : Tanda asterisk yang digunakan dalam SELECT untuk menunjukkan bahwa semua kolom dalam tabel akan dipilih, `FROM` : Digunakan untuk menunjukkan tabel yang digunakan untuk mengambil data, `mobil` : Nama tabel dari mana data akan diambil, `WHERE` : Digunakan untuk menerapkan kondisi pada query, `warna NOT LIKE 'H%'` : Kondisi di mana nilai kolom warna tidak dimulai dengan 'H'. 
#### Kesimpulan
 `SELECT * FROM mobil WHERE warna NOT LIKE 'H%';` digunakan untuk memilih data dari tabel "mobil" di mana nilai kolom warna tidak dimulai dengan 'H'.
 
---
