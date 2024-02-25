# Struktur Dasar HTML
```html
<!DOCTYPE html>
<html>
<head>
<title>ini adalah judul</title>
</head>
<body>
<p>ini adalah paragraf yang di tampilkan di browser</p>
</body>
</html>
```

```html
<!DOCTYPE html>
<html>
<head>
<title>ini adalah judul</title>
</head>
<body>
<p>pilihan hanya ada 2, tempe dan tahu</p>
<p>kesuksesan itu seperti banyak nya tempe</p>
<p>tidak ada yang tau</p>
</body>
</html>
```

Tag `<!DOCTYPE html>` memberitahukan web browser bahwa dokumen html adalah versi 5.

Tag pembukaan `<html>` menandai awal sebuah dokumen html sampai dengan tag penutup `</html>`.

Tag pembukaan `<head>` berisi informasi tentang halaman html sebagai dengan tag penutup `</head>`. Biasanya dalam tag head terdapat tag `<title>`untuk memberikan informasi judul halaman HTML.

Apapun tag yang berada diantara tag pembukaan
`<body>` sampai dengan tag penutup `</body>` akan tampil di web browser.

![screenshot](ssweb.jpg)

---

# Anatomi Elemen HTML

**Elemen** adalah suatu kesatuan dan sebuah Tag yang dimulai dari ==Tag pembuka== hingga ke ==Tag penutup==. **ELEMEN** HTML secara garis besar terdiri atas tiga bagian yaitu **Tag pembuka**, **konten/Isi tag**, dan **tag penutup**
## Kode program

```html
<a href="https://www.instagram.com/accounts/login/">klik untuk login Instagram</a>
```
## Hasil program
> [! faq]- hasil anatomi elemen html
> ![hasil html](hasilss.jpg)

---

## Tag pembuka & penutup
### Tag pembuka
`<a` adalah Tag Pembuka. Digunakan untuk membuat tautan atau hyperlink dalam dokumen web.

### Tag penutup
`/a>` adalah Tag Penutup. Digunakan untuk menutup tag `<a>`. Penutupan tag ini menandai akhir dari tautan atau hyperlink yang telah dibuat dengan tag pembuka `<a>`.

## Atribut tag 
### Nama atribut
`href` adalah Nama Atribut. Digunakan untuk menentukan URL atau alamat tujuan tautan, danmengarahkan tautan tersebut ke halaman login Instagram di https://www.instagram.com/accounts/login/.

### Nilai atribut
`"https://www.instagram.com/accounts/login/"` adalah Nilai Atribut. Sebagai URL atau alamat web yang menunjuk ke halaman login Instagram. Dengan menentukan URL ini dalam atribut `href` tag HTML `<a>`, tautan tersebut akan membuka halaman login Instagram ketika diklik.

`klik untuk login instagram` adalah konten atau Isi Tag. Ini berfungsi sebagai deskripsi atau petunjuk bagi pengguna untuk mengetahui bahwa tautan tersebut akan membawa mereka ke halaman login Instagram ketika diklik.

## Konten atau isi tag
Teks `klik untuk login Instagram` akan muncul sebagai tautan di halaman web, dan ketika pengguna mengkliknya, mereka akan diarahkan ke URL yang ditentukan dalam atribut `href`.

---

# Tag Dasar 

## Heading
### `<h1>` sampai `<h6>`
#### Penjelasan
Tag dasar `<h1>` hingga `<h6>` digunakan dalam HTML untuk membuat heading atau judul pada halaman web. Heading `<h1>` merupakan yang paling tinggi, sedangkan `<h6>` adalah yang paling rendah dalam tingkatannya, Semakin tinggi level heading, semakin kecil ukuran teksnya secara default.. Contohnya:

`<h1>` :  Heading Level 1
`<h2>` :  Heading Level 2
`<h3>` :  Heading Level 3
`<h4>` :  Heading Level 4
`<h5>` :  Heading Level 5
`<h6>` :  Heading Level 6

#### Kode program
```html
<p><h1>yang ini h1</h1></p>
<p><h2>yang ini h2</h2></p>
<p><h3>yang ini h3</h3></p>
<p><h4>yang ini h4</h4></p>
<p><h5>yang ini h5</h5></p>
<p><h6>Yang ini h6</h6></p>
```

#### Hasil program
![hasil header](Header.jpg)

---

## Paragraf

### `<p>`
#### Penjelasan
Tag `<p>` dalam HTML digunakan untuk membuat paragraf teks, memberikan struktur yang terorganisir pada halaman web.
Tag `</p>` adalah tag penutup untuk elemen paragraf `<p>` dalam HTML. 

#### Kode program
```html
<p>pilihan hanya ada 2, tempe dan tahu</p>
<p>kesuksesan itu seperti banyak nya tempe</p>
<p>tidak ada yang tau</p>
```

#### Hasil program
![hasil paragraf](ssweb.jpg)

---

### `<b>`
#### Penjelasan
Tag `<b>` dalam HTML digunakan untuk membuat teks bold atau tebal.
Tag penutup `</b>` digunakan untuk mengakhiri efek bold atau tebal yang dimulai dengan tag pembuka `<b>`. 

#### Kode program
```html
<p><b>untuk membedakan yang memakai tulisan bold</b></p>
<p><b>tulisan ini memakai blod</b></p>
<p>tulisan ini tidak memakai bold</p>
```

#### Hasil program
![tulisan bold](bold.jpg)

---

### `<u>`
#### Penjelasan
Tag `<u>` dalam HTML digunakan untuk memberi teks garis bawah atau menggaris bawahi kontennya.
Tag `</u>` digunakan untuk menutup atau mengakhiri efek garis bawah yang dimulai dengan tag `<u>`.

#### Kode program
```html
<p><u>untuk membedakan yang memakai tulisan garis bawah</u></p>
<p><u>tulisan ini memakai garis bawah</u></p>
<p>tulisan ini tidak memakai garis bawah</p>
```

#### Hasil program
![garis bawah](garisbawah.jpg)

---

### `<i>`
#### Penjelasan
Tag `<I>` dalam HTML digunakan untuk memberikan efek italik atau menyeluruh pada teks di dalamnya.
Tag `</i>` digunakan untuk menutup atau mengakhiri efek italik yang dimulai dengan tag `<i>`.

#### Kode program 
```html
<p><i>untuk membedakan yang memakai tulisan italik</i></p>
<p><i>tulisan ini memakai italik</i></p>
<p>tulisan ini tidak memakai italik</p>
```

#### Hasil program
![tulisan italic](miring.jpg)

---

### `<br>`
#### Penjelasan 
Tag `<br>` dalam HTML digunakan untuk menyisipkan pemutus baris (line break) dalam teks atau konten, digunakan untuk membuat pemutus baris, memindahkan teks atau konten ke baris berikutnya.

#### Kode program
```html
<p>ini adalah tulisan barisan pertama</p><br><p>ini adalah tulisan barisan ke dua.</p><br><p>ini adalah tulisan barisan ke tiga.</p>
```

#### Hasil program 
![tulisan baris baru](barisbaru.jpg)

---

### Atribut `align`
#### **Penjelasan**
Atribut `align` berguna untuk mengontrol penempatan atau perataan elemen dalam sebuah dokumen atau tampilan halaman web.
`align="left"` akan membuat paragraf menjadi rata kiri.
`align="right"` akan membuat paragraf menjadi rata kanan.
`Align="center"` akan membuat paragraf menjadi rata tengah.
`align="justify"`akan membuat paragraf rata kanan dan kiri.

#### **Kode program** 
```html
<h3>Belajar Menggunakan Elemen Tag HTML p</h3>
<p align="left">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.<\p>
<p align="right">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.</p>
<p align="center">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.</p>
<p align="justify">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.</n>

```

#### **Hasil program**
![hasil align](align.jpg)


---

### **Komentar** 
#### Penjelasan
Html juga mempunyai Tag khusus untuk komentar.Untuk membuat komentar di HTML kita menggunakan awalan `<!--` dan penutup `-->`.

> [!faq]- Guide Komentar 
>  Komentar tidak akan di tampilkan pada halaman website namun programmer biasanya menggunakan komentar untuk memperjelas kode program

#### **Kode program**
```html
<!-- ini komentar,tidak akan tampil di browser -->
<p>ini bukan komputer, dan akan tampil di browser</p>
```

#### **Hasil program**
![hasil komentar](komentar.jpg)

___
### **List**
#### Penjelasan
List adalah fungsi dalam HTML yang digunakan untuk menampilkan daftar dari sesuatu.Tag HTML terdiri dari 2 jenis ,`<ol>` ordered list (berurutan),dan `<ul> `urdered list (tidak berurutan). oredered list `<ol>` akan ditampilkan dengan angka atau huruf sedangkan undered list `<ul>`dengan bulatan atau kotak ataupun simbol lainnya.

>[!faq]- Guide list
>!! Untuk menampilkan list dalam HTML dapat menggunakan tag `<ol>`...`<\ol>` atau` <ul>`...`</ul>`namun perlu dengan menyisipkan elemen `<li>` untuk membuat daftar list

#### **Kode program**
```html
Undered list

<h1>list peralatan kelas</h1>
<ul>
<li>Sapu</Li>
<li>pel</Li>
<li>dispenser</Li>
<li>kipas</Li>
<li>gelas</Li>
</ul>

Ordered listl

<h1>list Kalimat</h1>
<ol>
<li>Ini kalimat pertama</Li>
<li>ini kalimat kedua</Li>
<li>ini kalimat ketiga</Li>
<li>ini kalimat ke empat</Li>
<li>ini kalimat ke lima</Li>
</ol>


```

#### **Hasil program**
##### **Underedlist**
![hasil undered](undered.jpg)

##### **Orderet List**
![foto ordered](ordered.jpg)

---

### Link
#### Penjelasan
Link dapat ditemukan di hampir semua halaman web. Link/Tautan memungkinkan sebuah teks yang ketika di-klik akan pindah ke halaman lainnya. HTML Menggunakan tag `<a>` untuk keperluan ini. Link ditulis dengan `<a>` yang merupakan singkatan dari anchor (jangkar). 

Setiap tag `<a>` setidaknya memiliki sebuah atribut `href` Dimana `href` berisi alamat yang dituju. `href` adalah singkatan dari hypertext reference. 

Atribut Penting Lainnya dari tag `<a>` adalah `target` . Atribut target menentukan tempat untuk membuka dokumen yang ditautkan. Atribut `target` memiliki beberapa nilai salah satunya `_blank` yang berfungi untuk membuka tautan di tab baru. 

#### Kode Program
```html
<h3>Menggunakan Tag Anchor</h3>
<a href ="https://www.google.com" target="_blank">klik disini untuk ke google</a><br>
<a href ="halaman_lain.html">klik disini untuk ke halaman lain yang saya buat!</a>
```

#### **Hasil program**
![hasil program](ss_link.jpg)

---

## multimedia
### Gambar
#### Penjelasan
Dalam HTML gambar didefinisikan dengan tag `<img>` . Tag `<img>` adalah tag kosong, hanya berisi atribut saja, dan tidak memiliki tag penutup. 

Atribut `src` setidaknya mesti ada dalam tag ini untuk menentukan URL (alamat web) dari gambar yang ingin ditampilkan. 

Atribut `alt` menyediakan teks alternatif untuk gambar, jika pengguna karena beberapa alasan tidak dapat melihatnya (karena koneksi lambat, kesalahan pada atribut `src` ,atau jika web browser telah disetting untuk tidak menampilkan gambar). Jika browser tidak dapat menentukan gambar, maka akan muncul nilai pada atribut `alt` . 

Dalam tag `<img>` terdapat juga atribut `width` dan `height` untuk mengatur ukuran gambar, pada versi HTML5 standar satuan ukuran gambar adalah pixel

- Misalnya dalam folder root terdapat file gambar bernama logo.png. untuk menampilkan gambar tersebut kita hanya perlu mengisi nama gambar beserta jenis ekstensi file gambar ke dalam atribut src , Contohnya src = "logo.png" 
- untuk menampilkan dari internet carilah link gambar yang akan ditampilkan lalu masukkan dalam nilai atribut `src` , contohnya **`https://namasitus.com/gambar.png`**

#### **Kode program**
```html
<img src="alter.png" alt="Logo_alter_negro" width="100%" height="100%">
```

#### **Hasil program**
![Hasil web negro](web_ae.jpg)

#### **Screenshot hasil folder**
![folder](ss_folder.jpg) 

---
### vidio
#### Penjelasan
Fitur HTML 5 mencakup dukungan audio dan video asli tanpa memerlukan flash. tag `<audio>` dan `<vidio>` pada HTML 5 mempermudah penambahan media ke dalam halaman web. Yang penting untuk diatur pada tag ini adalah atribut `src` yang berfungsi untuk mengidentifikasi sumber media. Selain itu, terdapat pula atribut `controls`agar pengguna dapat memutar dan menjeda media.

#### **Kode Program** 
```html
<video src="dero.mp4"controls width="400" height="500">
</video>
```

#### **Hasil Program** 
![hasil web vidio](ss_dero.jpg)

---
### Audio
#### Penjelasan
Seperti yang telah dibahas sebelumnya bahwasanya tag `<audio>` merupakan bagian fitur HTML5 untuk menampilkan audio asli dihalaman web tanpa memerlukan flash sebagaimana pada HTML versi 4. Yang penting untuk diatur pada tag ini adalah atribut `src` yang berfungi untuk mengidentifikasi sumber media. Selain itu, terdapat pula atribut `controls` agar pengguna dapat memutar dan menjeda media. 

#### **Kode Program**

```html 
<audio src="Audio09.mp3" controls >
  Browser anda tidak mendukung elemen 
  <audio>.</audio>
```

#### **Hasil Program**
![ss](ss_audio.jpg)
> [!INFO]
> Konten berupa teks "Browser anda tidak mendukung elemen `<audio>`." Pada tag `<audio>` akan ditampilkan jika browser tidak mendukung elemen tersebut. Sehingga sebenarnya bagian ini dapat dihilangkan.

---
### Halaman web lain
#### Penjelasan
Elemen <`iframe>` dapat digunakan untuk menampilkan halaman website lain dalam suatu website. Atau menampilkan dokumen html lain dalam sebuah website. Mudahnya, bisa dibilang website dalam website
 
Contoh penggunaannya seperti ini. Jika kita mempunyai website sekolah, lalu di website tersebut ingin menampilkan alamat dalam google maps sekolah. Agar memudahkan pengunjung website,kita bisa langsung tampilkan saja halaman sekolah yang ada digoogle maps

Dalam tag inframe ada beberapa atribut yang penting seperti : 
- src,untuk mencari sumber halaman html atau web yang akan ditampilkan didalam frame
- width dan height, untuk mengatur ukuran panjang dan lebar dari frame.

#### **Kode program :**
```html
<iframe src="https://smkn7makassar.sch.id/"
width="300" height="600"</iframe>
```

#### **Hasil program :** 
![ss web sekolah](web_sekolah.jpg)

---
## **Tabel**
### Penjelasan 
Tabel dalam HTML didefinisikan dengan tag `<table>`.
- Setiap baris tabel didefinisikan dengan tag `<tr>`.
- Header/judul tabel didefinisikan dengan tag `<th>`.Secara default, header tabel memiliki teks tebal dan berada di tengah.
- Data tabel/sel didefinisikan dengan tag `<td>`karena sel merupakan bagian terkecil dari tabel maka dari itu tag ini selalu berada di dalam tag `<tr>`.

### **Contoh kode program**
```html
<table Border="1">
<tr>
  <th>nama</th>
  <th>asal industri</th>
</tr>
<tr>
  <td>ahsan</td>
  <td>TVRI</td>
</tr>
<tr>
  <td>Muh.Taufik</td>
  <td>FAJAR</td>
</tr>
```

### **Contoh hasil program**
![hasil dasar tabel](dasar_tabel.jpg)

> [!info]  Perhatikan bahwa pada tag `<table>` terdapat sebuah atribut `<border>`. Atribut digunakan untuk memberikan nilai garis tepi dari tabel. Nilai ini dalam ukuran pixel. `border="1"`, berarti kita menginstruksikan kepada web browser bahwa tabel tersebut akan memiliki garis tepi sebesar 1 pixel. Jika tidak ditambahkan, secara default tabel tidak memiliki garis tepi.

Selain itu, terdapat pula beberapa atribut tabel yang penting untuk diketahui yaitu:
- `rowspan` merupakan atribut HTML yang berfungsi untuk menggabungkan beberapa baris (ke bawah).
- `colspan`atau colomn span merupakan atribut html yang berfungsi untuk menggabungkan beberapa kolom (ke samping).
- `width`berfungsi untuk mengatur lebar kabel yang nilainya didefinisikan dalam satuan pixel secara default.
- `heigt`berfungsi untuk mengatur tinggi tabel yang nilainya didefinisikan dalam satuan pixel secara default.
- `align` berfungsi untuk mengatur perataan teks pada tabel. Nilai atribut yang dapat diberikan yaitu `left` untuk perataan teks ke kiri, `right` untuk perataan teks ke kanan, dan `center` untuk perataan teks ke tengah.

### **Contoh Kode program**
```html
<table Border="2">
<tr>
<th rowspan="2">nama</th>
<th colspan="2">Asal institusi</th>
</tr>
<tr>
<th width="150">sekolah</th>
<th width="150">kampus</th>
</tr>
<tr>
  <td>Ibrahim Malommbasang</td>
  <td>SMKN 7 Makassar</td>
  <td>Universitas Negeri Makassar</td>
</tr>
<tr>
  <td>Condrado Alain Sharon</td>
  <td rowspan="2"> SMKN 7 Makassar</td>
  <td align="center" rowspan="2">-</td>
</tr>
<tr>
  <td>Rezeky Awalya</td>
</tr>
  <td>Muzhawir Amri</td>
  <td>SMAN 1 Palu</td>
  <td>STMTK Dipanegara</td>
</tr>
</table>
```

### **Hasil program**
![tabel](tabel.jpg)

> [! info ] perhatikan para konten elemen `<td` yang berisi `Rezeky Awalya`, hanya terdapat satu elemen `<td>` disana. Hal ini dikarenakan konten elemen `<td>` sebelumnya yaitu `SMKN 7 Makassar` dan `-` pada data `fatur` mengandung atribut `rowspan` dengan bernilai `2` yang secara otomatis mengisi data di bawahnya yakni data `Rezeky awalya`. Nilai `2` menunjukkan bahwa ada dua baris yang digabungkan menjadi satu.
>  Konsep ini juga sama dengan apa yang terjadi pada `<th rowspan="2">nama</th>` dan `<th colspan="2">Asal institusi</th>`

---
### Tugas Tabel Hari & Bulan
#### Kode Program 
```html
<table Border="1">
<tr>
  <th bgcolor="green" colspan="2">Nama Hari</th>
  <th bgcolor="green" colspan="2">Nama Bulan</th>
</tr>
<tr>
  <td>senin</td>
  <td>selasa</td>
  <td>april</td>
  <td rowspan="2">Juni</td>
</tr>
<tr>
  <td>rabu</td>
  <td>kamis</td>
  <td>mei</td>
</tr>
</table>
```

### Hasil Program
#### Analisis program:
- `<table>` untuk membuat sebuah tabel di halaman website.
- `Border="1"` memberikan garis tabel sebesar 1 pixel pada tabel halaman website.
- `<tr>` untuk membuat kolom pada tabel websitenya, dan menutup tag `<tr>` dengan menggunakan tag `</tr>`.
- `<th>` untuk membuat header atau judul pada sebuah tabel, dan menutup tag `<th>` dengan menggunakan tag `</th>`.
- `bgcolor="green"` untuk membuat warna pada background tabel, `green` untuk mewarnai background dengan warna hijau 
- `colspan="2"` untuk menggabungkan colom tabel dengan kolom lainnya, dan yang bernilai `"2"`, untuk menggabungkan kolom sebesar 2 kolom menjadi 1 kolom.
- `<td>` untuk menginput data atau membuat teks pada tabel, dan menutup tag `<td>` dengan menggunakan tag `</td>`.
- `Rowspan="2"` untuk menggabungkan baris tabel dengan baris lainnya, dan yang bernilai `"2"`, untuk menggabungkan baris sebesar 2 baris untuk menjadi 1 baris.

![hasil tugas tabel](tugastabel.jpg)

---
## Form
### Penjelasan
Elemen `<form>` HTML digunakan untuk mendefinisikan form yang digunakan untuk mengumpulkan inputan dari pengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata.

>[!note] - Dengan kata lain tag `<form>` merepresentasikan sebuah "formulir" di mana satu formulir bisa memiliki banyak kolom isian.

Form HTML berisikan elemen-elemen `<form>`  lainnya. Elemen `<form>` digunakan untuk menampung macam-macam elemen yang berkaitan dengan sebuah `form`, seperti `text` `fields`, `checkbox`, `radio button`, `tombol subalt`, dan banyak lagi yang dapat diedit kemudian ditulis untuk dikirim pada sebuah server untuk selanjutnya diproses guna mendapatkan informasi tertentu dari atau untuk user.

Umumnya, sebuah website selalu memiliki fitur form, contoh paling umum yang sering kita temui adalah seperti form login, form sign up, form komentar di suatu blog/media.

### *Input*
Elemen `<input>` adalah elemen `form` yang paling penting. Elemen `<input>` dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut `type` yang digunakan. Request Berikut adalah beberapa contoh nilai dari atribut `type`:
- `text` digunakan untuk mengambil isian berupa teks. Contohnya seperti nama.
- `password` digunakan untuk mengambil isian berupa kata sandi atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat.
- `Radio` digunakan sebagai kolom isian bertipe pilihan yang menawarkan beberapa opsi kepada user namun tetapi hanya satu opsi saja yang boleh dipilih. Contohnya seperti jenis kelamin atau agama.

> [!note] - Perlu diperhatikan bahwa untuk penggunaan tipe radio yang berkategori set pilihan yang sama mengharuskan nilai-nya juga sama.

Opsi default dapat dilakukan dengan menambahkan atribut checked pada elemen opsi yang dijadikan sebagai opsi default.

- `checkbox` digunakan untuk memberikan **daftar pilihan dalam satu set opsi**. User dapat memilih satu atau bahkan lebih dari satu pilihan pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu `radio` yang hanya memungkinkan user untuk memilih satu  pilihan saja. Contoh penggunaan `checkbox` seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.

> [!note] - Perlu diperhatikan bahwa untuk penggunaan tipe checkbox yang berkategori set pilihan yang sama mengharuskan nilai name -nya juga sama.

- `Number` digunakan untuk membatasi isian user hanya pada karakter numerik saja. Browser akan menambahkan dua buah tombol atas dan bawah untuk mengubah angka isian.
Beberapa atribut untuk tipe `number`:
    - `min`-menentukan angka minimal
    - `max`-menentukan angka maksimal
    - `step`-smenentukan kelipatan (nilai yang tidak sesuai kelipatan tidak bisa di-input, dan default dari atribut ini adalah 1)

- `Date` digunakan untuk memberikan isian berupa tanggal. Atribut `min` dan `max` dapat pula difungsikan pada tipe ini untuk mengatur tanggal minimal dan tanggal maksimal yang diinginkan. Nilai `min` dan `max` tersebut ditulis dengan format: `YYYY-em-dd`.

- `File` digunakan untuk memungkinkan pengguna memuat file. Atribut `accept` juga dapat disisipkan pada tipe ini dengan maksud untuk mengatur file apa saja yang boleh di-upload. Beberapa contoh value dari atribut `accept` yaitu:

    -`accept-"image/png,inage/jpg.Image/jpeg` - untuk file gambar seperti `png`. `jpg`. atau `jpeg`
    -`accept="pdf"` - untuk file pdf
    -`accept="pdf"` - untuk file pdf
    -`accept-".doc, docx"` - untuk file `doc` atau `docx`
    -`accept-".ppt, pptx"` untuk file `ppt` atau `pptx`

- `submit` ditampilkan dalam bentuk tombol untuk mengirim data pada `<form>` yang menjadi pembungkusnya. Atribut `value` digunakan untuk mengisi teks yang ingin ditampilkan pada tombol.

- `reset` berguna untuk mengembalikan state (keadaan) atau data dari suatu form ke nilai awalnya. Jika nilai awal sebuah input adalah kosong, maka ketika direset ia akan kembali kosong. Tapi jika nilai awalnya sudah terisi sesuatu, maka ketika direset datanya akan kembali seperti yang sudah diset sebelumnya.

- `button` berguna untuk membuat inputan berupa sebuah tombol. Tombol ini nantinya bisa difungsikan sesuai dengan keinginan dari pengembang web.

### *Label*
Elemen `<label>` memiliki fungsi khusus untuk melabeli sebuah kolom inputan. Ketika screen reader membaca konten halaman HTML, lalu menemukan sebuah inputan, ia akan membaca label yang bersangkutan. 
Fungsi lain dari tag `<label>` adalah ketika kita mengklik label, maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya. Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah `<label>` dan `<input>` dengan atribut for untuk label, dan atribut id pada `<input>` dengan nilai untuk kedua atribut tersebut mesti sama persis.

### *Select*
Elemen `<select>` berguna dalam mendefinisikan sebuah tombol dropdown yang dimana user dapat memilih salah satu dari banyak pilihan.

>[!note] - Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi. 

 Elemen `<select>` hampir mirip fungsinya dengan `<input type ="radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan `<input type ="radio">` lebih baiknya untuk digunakan jika user diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.
Penting untuk diketahui bahwasanya opsi yang aktif secara default adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara default dengan menambahkan atribut selected pada suatu `<option>` yang ingin dijadikan sebagai opsi default.

### *Text Area*
Elemen `<textarea>` berguna untuk mengambil inputan user berupa teks yang dapat memuat lebih dari satu baris. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element `<textarea>` bisa diisi lebih dari satu baris dengan menekan enter.

Atribut yang dapat digunakan untuk mengatur kuran dari textarea yaitu rows untuk jumlah baris, sedangkan atribut cols untuk lebarnya.

### *Button*
Elemen `<button>` yang berada di dalam sebuah `form` akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-submit `<form>` dapat dilakukan dengan menambahkan atribut `type="button"`.

### Contoh Kode Program 
```html
<form>
  <label for="nama">Nama:</label>
  <input type="text" required id="nama"></input><br><br>
  <label for="password">Password:</label>
  <input type="password" required id="password"></input><br><br>
  <label for="JS">Jenis Kelamin:</label>
  <input type="radio" name="JS" id="JS" checked>Laki-Laki</input>
  <input type="radio" name="JS" id="JS">Perempuan</input><br> <br>
  <input type="checkbox" name="">WEB</input>
  <input type="checkbox" name="">MOBILE</input>
  <input type="checkbox" name="">DESKTOP</input><br><br>
  <button type="submit">Kirim</button>
  <button type="reset">Reset</button><br><br>
  <label>Pesan Pesanan Anda:</label><br>
  <textarea></textarea>
</form>
```
### Hasil Program
#### Analisis Program
- `<form>`&`</form>`  ini menandai awal dan akhir untuk membuat formulir html.
- `label for="nama">Nama:</label>` dan `<input type="text" required id="nama"></input>:` Ini adalah label dan input untuk membuat dan memasukkan nama pengguna. Atribut `for` pada `<label>` mengaitkan label dengan input menggunakan nilai `id`.
- `<label for="password">Password:</label>` dan `<input type="password" required id="password"></input>:` Label dan input untuk membuat dan memasukkan password pengguna. Tipe `password` digunakan untuk menyembunyikan karakter input.
- `<label for="JS">Jenis Kelamin:</label>` dan  kode html ini digunakan untuk membuat teks label yang bervariabel `"JS"` yang dimana, `for`  memiliki fungsi untuk mengaitkan label dengan elemen formulir tertentu yang memiliki nilai `id`.
- `<input type="radio" name="JS" id="JS" checked>Laki-Laki</input>`:  `type="radio":` Menentukan bahwa ini adalah elemen radio button, `name="JS"`: Menunjukkan bahwa radio button ini termasuk dalam grup dengan nama "JS", `id="JS"` digunakan untuk mengaitkan label dengan Radio button, `checked` tag ini akan menandakan bahwa radio button ini akan dipilih secara default, `Laki-Laki` ini akan yang di tampil dengan kode radio tadi.
- `<br>` untuk membuat garis baru.
- `<input type="checkbox" name="">WEB</input>` , `<input type="checkbox" name="">MOBILE</input>` , `<input type="checkbox" name="">DESKTOP</input>` kode html ini digunakan untuk memilih satu satu lebih pilihan. `type="checkbox"`: Menentukan bahwa ini adalah elemen checkbox, `name` digunakan untuk mengelompokkan checkbox sehingga hanya satu grup checkbox yang dapat dipilih oleh pengguna. `WEB` `mobile` , `DESKTOP`  yang akan tampil menjadi sebuah pilihan di halaman website formulir kita.
- `<button type="submit">Kirim</button>` , `<button type="reset">Reset</button>` :  `button` kode html untuk membuat tombol, `type` untuk menentukan jenis tombol, `"submit"` untuk mengirim data form ke server untuk di proses, `reset` digunakan untuk mengembalikan formulir ke keadaan awalnya, menghapus atau mengatur ulang semua data yang telah dimasukkan oleh pengguna.
- `<label>Pesan Pesanan Anda:</label><br>` , `<textarea></textarea>` untuk menampilkan  Pesan` Pesanan Anda` di halaman website, `<textarea></textarea>` kode ini juga berfungsi untuk Pengguna untuk dapat menulis atau memasukkan teks ke dalam textarea, dan nilai teks tersebut dapat diakses dan diolah saat formulir di-submit.
#### Hasil program
![hasil program](tugasform.jpg)

---
### **Contoh Kode Program**
```html
<h1>Formulir Pendaftaran</h1>
<form action="">
  <div>
    <label for="nama-lengkap"><b>Nama Lengkap:</b></label
    ><br />
    <input
      type="text"
      id="nama-lengkap"
      name="nama_lengkap"
      placeholder="Masukkan nama lengkap"
      required
    />
  </div>
  
  <div>
    <label for="password"><b>Password:</b></label
    ><br />
    <input
      type="password"
      id="password"
      name="password"
      placeholder="Masukkan password"
      required
    />
  </div>
  
  <div>
    <b>Jenis Kelamin:</b><br />
    <input id="lk" type="radio" name="jenis_kelamin" checked />
    <label for="lk">Laki-Laki</label>
    <input id="pr" type="radio" name="jenis_kelamin" />
    <label for="pr">Perempuan</label>
  </div>
  
  <div>
    <label for="isian-usia"><b>Usia:</b></label
    ><br />
    <input
      type="number"
      id="isian-usia"
      name="usia"
      min="17"
      max="25"
      value="19"
      required
    />
    Tahun
  </div>

  <div>
    <label for="tgl-ijazah"><b>Tanggal Ijazah:</b></label> <br />
    <input
      type="date"
      id="tgl-ijazah"
      name="tgl_ijazah"
      min="2021-01-01"
      value="2023-06-20"
      required
    />
  </div>

  <div>
    <label for="opsi-agama"><b>Agama:</b></label
    ><br />
    <select id="opsi-agama" name="agama" required>
      <option disabled>---Pilih Agama----</option>
      <option value="islam">Islam</option>
      <option value="kristen">Kristen</option>
      <option value="katolik">Katolik</option>
      <option value="hindu">Hindu</option>
      <option value="buddha">Buddha</option>
      <option value="atheis" disabled>Atheis</option>
    </select>
  </div>

  <div>
    <label for="alamat"><b>Alamat:</b></label> <br />
    <textarea
      id="alamat"
      name="alamat"
      cols="25"
      rows="5"
      placeholder="Harap masukkan alamat secara lengkap"
      required
    ></textarea>
  </div>

  <div>
    <b>Kemampuan Berbahasa Asing:*</b><br />
    <input type="checkbox" id="inggris" name="bahasa_asing" />
    <label for="inggris">Inggris</label>
    <input type="checkbox" id="arab" name="bahasa_asing" />
    <label for="arab">Arab</label>
    <input type="checkbox" id="jepang" name="bahasa_asing" />
    <label for="jepang">Jepang</label>
  </div>

  <div>
    <label for="isian-foto"><b>Foto 4x6:*</b></label
    ><br />
    <input
      type="file"
      id="isian-foto"
      name="foto"
      accept="image/png,image/jpg,image/jpeg"
    />
  </div>

  <br />
  <input type="submit" value="Kirim" />
  <input type="reset" value="Batal" />
  <i>*opsional (tidak wajib diisi)</i>
</form>
```
### **Contoh hasil program :**
![hasil formulir ](formulir.jpg)

Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:
- **==name==** - digunakan sebagai nama variabel yang akan diproses oleh web server (contoh menggunakan PHP).
- **==Required==** - digunakan untuk memastikan bahwa pengguna harus memasukkan nilai pada input tersebut sebelum dapat melakukan proses submit formulir.
- **==placeholder==** - menuliskan teks pada elemen input. Placeholder sangat bermanfaat untuk memberikan teks bantuan kepada user untuk inputan form yang kompleks.
- **==value==** - menentukan nilai awal dari sebuah elemen input.
- **==disabled==** - digunakan untuk menonaktifkan inputan pada elemen yang diberi atribut ini.

### **Bagaimana Cara Memproses Form?**

Ketika sebuah `<form>` disubmit, baik menggunakan elemen `<button>` mau pun `<input type="submit">`, browser akan mengirimkan data tersebut kepada URL yang didefinisikan pada atribut `action` di dalam tag `form`.

Ada pun jika atribut `action` tidak didefinisikan, maka *browser* akan menggunakan URL sekarang sebagai tujuan pengiriman data.

#### **Contoh kode program :**
```html
**<form** action**=**"/proses-pendaftaran"**>**
  ...
**</form>**
```

Pada contoh di atas, ketika form di-*submit*, *browser* akan mengirimkan data yang ada  menuju URL `/proses-pendaftaran`.

### Apa yang terjadi pada URL `/proses-pendaftaran`?

Pada URL tersebut terdapat sebuah aplikasi/program yang berjalan di *server* (bukan di *browser*). Tugas dari program tersebut adalah mengelola data yang dikirim seperti misalnya menyimpan data tersebut ke dalam sebuah *database*.

Bahasa yang umum digunakan di dalam server adalah python, nodejs, PHP, dan lain sebagainya.

Untuk mendapatkan gambaran lebih jelas, sebenarnya akan dijelaskan pada modul selanjutnya yang berkaitan dengan materi PHP atau juga bisa dengan membaca tutorial berikut:
https://jagongoding.com/web/php/web-dinamis/membuat-dan-menangani-form/
## DIV & SPAN
### `<div>`
#### Penjelasan
 `Div` sendiri adalah elemen HTML yang digunakan sebagai kontainer blok untuk mengelompokkan elemen-elemen HTML lainnya dalam sebuah dokumen dan memberikan styling atau logika secara terpisah.
#### Kode Program
```html
<div>ini dibuat menggunakan div</div>
<div>ini juga menggunakan div</div>
```
#### Hasil
![hasil menggunakan div](div.jpg)

---
### `<span>`
#### Penjelasan
Tag `<span>` adalah elemen dalam HTML yang digunakan untuk memberikan gaya atau format pada sebagian teks dalam dokumen HTML tanpa mengubah struktur atau makna teks tersebut. `<span>` biasanya digunakan ketika tidak ada elemen yang lebih tepat untuk menandai bagian tertentu dari teks, atau ketika gaya atau format yang diberikan hanya berlaku untuk sebagian kecil dari teks.
#### Kode Program
```html
<span>ini dibuat menggunakan span</span>
<span>ini juga menggunakan span</span>
```
#### Hasil
![hasil menggunakan span](span.jpg)

---