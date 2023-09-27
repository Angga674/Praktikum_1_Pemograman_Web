# Pertemuan 2
## Pemograman Web
## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Dafa Alfiana Erlangga |
| **NIM** | 312210446 |
| **Kelas** | TI.22.A.4 |
| **Mata Kuliah** | Bahasa Pemrograman |

### Intruksi Praktikum
1. Persiapkan text editor misalnya VSCode. 
2. Buat file baru dengan nama lab1_tag_dasar.html 
3. Buat struktur dasar dari dokumen HTML. 
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya. 
5. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org 

## Langkah-langkah Praktikum
1. **Buka VSCode atau text editor**
 ![App Screenshot](https://1drv.ms/i/s!Amo3nt9pyMsBxjyDt9WozCAfAduf?e=FOE716)

2. Kemudian buat file **lab1_tag_dasar.html**

3. **Buatlah struktur dasar html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tag HTML Dasar</title>
</head>
<body>
    
</body>
</html>
```

4. **Buat Paragraf**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tag HTML Dasar</title>
</head>
<body>
    <!-- Ini adalah paragraf pertama-->
    <h1>Belajar Dasar HTML</h1>
    <p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi<br>
        Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat<br>
        adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar<br>
        HTML.</p>
    <!-- Ini adalah paragraf kedua -->
    <h2>Paragraf pada HTML</h2>
    <p align="left">Ini merupakan sebuah paragraf yang terdiri dari beberapa<br>
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat<br>
    dengan menggunakan tag dasar html.</p>
```
Saya menggunakan align pada tag paragraf yaitu untuk mengatur paragraf yang nanti berisi right, left, justify, maupun center

5. **Menambahkan Judul menggunakan h1 sampai h6 tergantung dengan kebutuhan** 
```html
<!-- Ini adalah paragraf pertama-->
    <h1>Belajar Dasar HTML</h1>
<!-- Ini adalah paragraf kedua -->
    <h2>Paragraf pada HTML</h2>
```

6. **Memformat teks**
```html
<p align="center">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi<br>
        Teknik Informatika <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat<br>
        adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar<br>
        HTML.</p>
<p align="left">Ini merupakan sebuah paragraf yang terdiri dari beberapa<br>
    kalimat yang saling mendukung sehingga menjadi satu kesatuan.<br> Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
```

7. **Menyisipkan gambar**
```html
<img src="Logo Universitas Pelita Bangsa.png" width="200" title="Logo Universitas Pelita Bangsa">
```

8. **Menambahkan Hyperlink**
```html
<nav> 
    <a href="lab1_tag_dasar.html">Dasar HTML</a> 
    <a href="lab1_halaman2.html">Halaman 2</a> 
    <a href="http://www.google.com">Halaman Web Eksternal Google</a> 
    </nav> 
    <hr> 
```


## Jawab pertanyaan Berikut
```
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah 
error ketika terjadi kesalahan penulisan tag? 
Jawab : Jika sesuai dengan tag atau kode yang dipakai tidak mengalami error, tetapi jika tidak sesuai dengan tag atau kode tidak terjadi perubahan apa-apa 
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya! 
Jawab : untuk tag <p> digunakan untuk membuat paragraf, untuk <br> digunakan untuk memberikan efek enter
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya! 
Jawab : Atribut title akan muncul jika kursor diarahkan keobjek/gambar, sedangkan atribut alt(alternatif) akan muncul jika user tidak bisa menampilkan gambar atau jaringan internet tidak bisa menginput gambar.
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar 
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! 
Jawab : Sebaiknya hanya mengisi atribut width karena width sudah termasuk dengan height, semisal yang saya ketik width "200" maka height nya juga mengikuti width nya jadi height "200"
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, 
_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut? 
Jawab : 
_blank: Ketika Anda menggunakan target="_blank", tautan akan dibuka dalam jendela atau tab browser yang baru, terpisah dari halaman saat ini. Ini akan memungkinkan pengguna tetap berada di halaman asal sambil mengakses tautan yang dibuka dalam jendela baru.</mark></li>

_self: Nilai ini adalah nilai default. Ketika Anda menggunakan target="_self", tautan akan dibuka dalam jendela atau tab yang sama dengan halaman saat ini. Ini adalah perilaku standar jika Anda tidak menentukan nilai target.</mark></li>

_top: Ketika Anda menggunakan target="_top", tautan akan membuka halaman baru dalam jendela atau tab yang sama seperti _self, namun jika halaman tersebut merupakan frame dalam struktur frame HTML, maka halaman baru tersebut akan menggantikan seluruh frame tersebut. Ini akan mengarahkan tautan ke halaman yang paling atas dalam hierarki frame.</mark></li>

_parent: Jika Anda menggunakan target="_parent", tautan akan membuka halaman baru dalam jendela atau tab yang sama seperti _self, tetapi jika halaman tersebut merupakan bagian dari struktur frame HTML, maka halaman baru tersebut akan menggantikan frame yang berisi halaman saat ini (frame yang berada satu tingkat di atas dalam hierarki)</mark>.</li>
```