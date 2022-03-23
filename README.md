### Nama : Ananda Prasca Appandi
### Nim  : 312010157   
### Kelas : TI.20.A1

# laporan pratikum

1. Persiapkan text editor misalnya VSCode
<p align="center">
	<img src="SS\persiapan awal.jpg" alt="">
</p>

2. Buat file baru dengan nama lab2_css_dasar.html
<p align="center">
	<img src="SS\membuat file.jpg" alt="">
</p>

3. Buat struktur dasar dari dokumen HTML
<p align="center">
	<img src="SS\membuat contoh dokumen html.jpg" alt="">
</p>

4. Langkah langkah membuat css
berikut merupakan kerangka dasar html
<p align="center">
	<img src="SS\membuat contoh dokumen html.jpg" alt="">
</p>

5. hasil output html
<p align="center">
	<img src="SS\hasil output dokumen html.jpg" alt="">
</p>

5. mendeklarasikan css internal 
berikut merupakan coding css internal

```html
<head>
 <title>CSS Dasar</title>
 <style>
 body {
 font-family:'Open Sans', sans-serif;
 }
 header {
 min-height: 80px;
 border-bottom:1px solid #77CCEF;
 }
 h1 {
 font-size: 24px;
 color: #0F189F;
 text-align: center;
 padding: 20px 10px;
 }
 h1 i {
 color:#6d6a6b;
 }
 </style>
</head>
```
6. hasil output css internal
<p align="center">
	<img src="SS\hasil output internal html.jpg" alt="">
</p>

7. menambahkan inline css

```html
<p style="text-align: center; color: #ccd8e4;">
```
hasil output inline css
<p align="center">
	<img src="SS\menambahkan inline css.jpg" alt="">
</p>

8. membuat external css
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut

```html
nav {
background: #20A759;
color:#fff;
padding: 10px;
}
nav a {
color: #fff;
text-decoration: none;
padding:10px 20px;
}
nav .active,
nav a:hover {
background: #0B6B3A;
}
```
Kemudian tambahkan tag ``<link>`` untuk merujuk file css yang sudah dibuat pada bagian ``<head>``
``html
<head>
 <!-- menyisipkan css eksternal -->
 <link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>
```

9. hasil output css external
<p align="center">
	<img src="SS\External Navigasi.jpg" alt="">
</p>

10. menambahkan css selektor
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css, tambahkan kode berikut.

```html
/* ID Selector */
#intro {
background: #418fb1;
border: 1px solid #099249;
min-height: 100px;
padding: 10px;
}
#intro h1 {
text-align: left;
border: 0;
color: #fff;
}
/* Class Selector */
.button {
 padding: 15px 20px;
background: #bebcbd;
color: #fff;
display: inline-block;
margin: 10px;
text-decoration: none;
}
.btn-primary {
background: #E42A42;
}
```

11. hasil output external selektor
<p align="center">
	<img src="SS\External selector.jpg" alt="">
</p>