<!DOCTYPE html>

```
<html>

<head>

<tittle> ini adalah judul </tittle>

</head>

<body>

<p> pilihan hanya 2, tempe dan tahu</p>

<p>kesuksesan itu seperti banyak nya tempe</p>

<p>tidak ada yang tahu</p>

</body>

</html>
```

- Tag <!DOCTYPE HTML> memberitahukan web browser bahwa dokumen HTML adalah versi 5
- Tag pembuka`<html>`  menandai awal sebuah dokumen HTML  sampai dengan tag menutup `</html>'
- Tag pembuka `<head>` berisi informasi tentang halaman HTML sampai dengan tag penutup `</head>` biasanya dalam tag head terdapat tag `<title>` untuk memberikan informasi judul halaman HTML
- Adapun tag yang berada di antara tag pembuka `<body>` sampai dengan tag penutup `</body>` akan tampil di web browser.

![[hasil program tempe.jpg]]

# ANATOMY ELEMEN HTML
 ## **INI ADALAH PROGRAM**
 <!DOCTYPE html>

```
<html>

<head>

<tittle> </tittle>

</head>

<body>

<p> untuk mendapatkan info lebih lanjut klik link di bawah ini</p>

<a href="//www.instagram.com/buaya.storee/"> link buaya store</a>

</body>

</html>
```


## Hasil
![[h.link instagram.png]]
## Penjelasan program


Anatomi elemen HTML merujuk pada struktur dasar atau komponen-komponen yang membentuk suatu elemen dalam HTML. Anatomi ini mencakup beberapa elemen utama seperti tag pembuka, tag penutup, atribut tag, isi/konten tag, dan tag dasar.

Elemen adalah suatu kesatuan dari sebuah tag yang dimulai dari tag pembuka hingga ke tag penutup Elemen HTML secara garis besar terdiri atas tiga bagian yaitu tag pembuka konten/isi. 

![lagi](lagi.jpg)

- tag `<a` adalah elemen dasar untuk membuat link di HTML dan termasuk di tag pembuka
- herf= adalah nama atribut yang menghubungkan antara halaman web.
- `https://www.instagram.com/buaya.stoore` adalanh nilai atribut yang digunakan untuk mengakses subuah link. Isi konten itu untuk masuk ke URL/link yang sudah kiita buat di atrbut `href` yaitu klik link.
# Tag Pembuka `(<tag>)`/Tag Penutup (`</tag>`)
- Tag pembuka adalah bagian dari sebuah elemen HTML yang menandakan dimulainya elemen tersebut.
- Biasanya terdiri dari nama elemen yang dibungkus oleh tanda kurung sudut (< dan >).
- Contoh: <`body`>, <`p`>, <`table>`, <`a`>, dll
- Beberapa tag pembuka mungkin juga memiliki atribut yang digunakan untuk menambahkan informasi tambahan tentang elemen tersebut.
- Contoh: <`img src="gambar.jpg" alt="Gambar"`>, di mana src dan alt adalah atribut.

## Sedangkan Tag Penutup
- Tag pembuka dan penutup memberikan struktur yang jelas dalam dokumen HTML, memungkinkan browser untuk memahami bagaimana elemen-elemen tersebut diatur dan ditampilkan.
- Mereka memungkinkan Anda untuk menentukan hierarki elemen dalam dokumen HTML dengan benar.
- Kesalahan dalam penempatan atau penulisan tag pembuka dan penutup dapat mengakibatkan masalah dalam rendering halaman web oleh browser.

>[!faq] contoh program : Tag pembuka
><`body`>
  <`p`>Ini adalah Paragraf<`/p`>
<`/body`>
## Hasil web:
![[h.teks pembuka.png]]
### Kesimpulan
jadi dari analisis di atas ada beberapa poin atau kesimpulan yang dapat kita ambil seperti berikut:
1. **Membentuk Struktur Dokumen:**  
    Tag pembuka dan penutup digunakan untuk menandai awal dan akhir dari sebuah elemen HTML, membentuk struktur hierarkis dokumen.
2. **Memberikan Konteks:**
    Tag pembuka memberi konteks tentang jenis elemen yang sedang dibuka, sementara tag penutup menunjukkan akhir dari elemen tersebut.
3. **Kesalahan Dapat Menyebabkan Masalah:** 
     Kesalahan dalam penulisan tag pembuka dan penutup bisa mengakibatkan masalah dalam rendering halaman web dan mempersulit pemeliharaan dan pemahaman kode HTML.
# Atribut Tag
   Elemen dalam HTML dapat memiliki atribut atribut memberikan informasi tambahan tentang suatu elemen informasi ini bisa berupa instruksi untuk memberi warna dan teks, menggatur besar huruf dan teks. setiap atribut memiliki pasangan nama dan nilai (value), dan ditulis dengan `nama"nilai"`, Value/nilai diapit dengan tanda kutip, boleh menggunakan tanda kutip satu ( ' ) atau dua ( " ).

- **Nama Atribut:** 
    Setiap atribut memiliki nama yang unik yang menentukan jenis informasi tambahan yang diberikan kepada elemen HTML.
- **Nilai Atribut:** 
    Atribut biasanya memiliki nilai yang terkait dengannya. Nilai ini dapat berupa teks atau nilai tertentu yang memberikan informasi lebih lanjut atau mengontrol perilaku elemen.
- **Penggunaan Atribut**:
    Atribut ditambahkan ke dalam tag pembuka elemen HTML dan diberi nilai jika diperlukan. Contohnya adalah <tagnama atribut1="nilai1" atribut2="nilai2">konten<`/tagnama`>.
- **Peran dalam Perilaku dan Tampilan**: 
    Atribut dapat digunakan untuk mengatur berbagai aspek perilaku dan tampilan elemen, seperti warna, ukuran, layout, dan lain-lain.

> [!note]- Dan ada beberapa contoh atribut yang ada di html
> - **Atribut Global** 
> dalam HTML adalah atribut yang dapat digunakan pada hampir semua elemen HTML. Mereka memberikan informasi tambahan atau mengontrol perilaku elemen di seluruh dokumen Berikut adalah Contohnya: 
> 1. <`Div class`>
> Class (class): Menentukan satu atau lebih kelas untuk elemen, memungkinkan penerapan gaya CSS tertentu.
> 2. <`p id>`>
> ID (id): Memberikan identitas unik pada elemen tertentu.
> 3. <`p style`>
> Style (style): Menentukan aturan gaya CSS secara langsung untuk elemen tertentu.  
> 4. <`a href="#" title`>
> Title (title): Memberikan teks bantuan yang muncul saat mouse mengarah ke elemen.
> - **Atribut Spesifik**
>Atribut spesifik dalam HTML adalah atribut yang terkait dengan jenis elemen tertentu dan memberikan fungsi atau perilaku yang khusus untuk elemen tersebut. Berikut adalah Contohnya: 
>1. <`img src`> 
>Src (src): Digunakan pada elemen seperti <`img`>, <`video`>, dan <`audio`> untuk menentukan lokasi sumber konten yang akan ditampilkan.
>2. <`a href`>
>Href (href): Digunakan pada elemen <`a`> untuk menentukan URL tujuan tautan.

>[!faq] Contoh program <`a href`>
><`a href="//www.instagram.com/buaya.storee/"`> link buaya store<`/a`>
## Hasil
![[h.Atribut tag.png]]

### Kesimpulan
jadi dari analisis di atas ada beberapa poin atau kesimpulan yang dapat kita ambil seperti berikut:
1. **Kontrol dan Fungsionalitas**: 
     Atribut tag memberikan kontrol dan fungsionalitas tambahan kepada elemen-elemen HTML, memungkinkan pengembang web untuk menyesuaikan tampilan dan perilaku elemen sesuai kebutuhan.
2. **Atribut Global dan Atribut Spesifik**: 
    Ada dua jenis atribut: atribut global, yang dapat digunakan pada hampir semua elemen HTML, dan atribut spesifik, yang terkait dengan jenis elemen tertentu dan memberikan fungsionalitas khusus.
3. Penggunaan Bersama dengan Nilai: 
    Atribut tag sering digunakan bersama dengan nilai untuk mengontrol perilaku atau tampilan elemen. Nilai-nilai ini memberikan informasi tambahan tentang elemen atau mengatur perilaku mereka.
# Konten/isi Tag 

   Objek yang dikenai perintah oleh tag, letaknya berada di antara tag pembuka dan tag penutup biasanya apa yang dituliskan diantara tag pembuka dan tag penutup akan ditampilkan pada halaman website dan mempresentasikan hasil dari penggunaan tag beserta atributnya.

   Sebagai contoh, tag yang ada digambar akan menampilkan tulisan Klik Google yang dimana teks tersebut jika di klik akan mengarahkan kita ke nilai atribut href yaitu url google `(https://www.intagram.com/buaya.stoore)`. 
>[!faq] Contoh program konten tag
>    <`h3`>Bingung mau top up diamond di mana?<`/h3`>
<`p`>klik link di bawah ini anda akan mendapatkan diskon hingga 10%<`/p`>
<`a href="//www.instagram.com/buaya.storee/"`> link buaya store<`/a`>

### Hasil
![[h.Atribut tag.png]]

## Kesimpulan
Jadi kesimpulan yang saya dapat dari penjelasan di atas adalah fungsi dari konten isi tag dapat berupa teks, seperti paragraf, judul, atau teks biasa. ini membantu bagian utama dari konten html.
# Tag Dasar
   Tag dasar dalam HTML adalah elemen-elemen yang membentuk struktur dasar dari sebuah dokumen HTML. Tag-tag ini digunakan untuk menentukan bagaimana konten dalam dokumen tersebut akan ditampilkan di dalam browser. Berikut adalah beberapa penjelasan tentang tag dasar HTML:

1. **<`!DOCTYPE html`>**:
    Mendefinisikan tipe dokumen HTML yang digunakan, dalam hal ini HTML versi terbaru HTML versi 5.
2. **<`html`>**:
    Menandai awal dan akhir dari sebuah dokumen HTML. Semua elemen HTML harus berada di dalam tag ini.
3. **<`head`>**:
    Berisi informasi meta-data tentang dokumen HTML, seperti judul halaman, stylesheet, skrip JavaScript, dan meta tag untuk SEO.
4. **<`title`>**: 
    Menetapkan judul atau nama halaman yang akan ditampilkan di bilah judul browser.
5. **<`body`>*: 
    Berisi konten yang akan ditampilkan di jendela browser, seperti teks, gambar, tautan, formulir, dan elemen-elemen lainnya.
6. Elemen Teks: 
    Seperti <`h1>`, <`h2`>, <`p`>, <`span`>, dan lainnya, digunakan untuk menampilkan teks dengan berbagai tingkat kepentingan dan format.
7. Elemen Gambar:
    Seperti <img>, digunakan untuk menampilkan gambar di dalam halaman web.
8. Elemen Tautan: 
    Seperti <`a`>, digunakan untuk membuat tautan atau hyperlink ke halaman web lain, dokumen, atau alamat email.
9. Elemen Daftar: 
    Seperti <`ul`>, <`ol`>, dan <`li`>, digunakan untuk membuat daftar item, baik berurut maupun tidak berurut.
10. Elemen Formulir:
    Seperti <`form`>, <`input`>, <`textarea`>, dan lainnya,  digunakan untuk mengumpulkan data dari pengguna.
11. Elemen Divisi: 
    <`div`> digunakan untuk mengelompokkan dan menata konten secara visual atau untuk membuat layout halaman yang lebih kompleks.
12. Elemen Semantik: 
    Seperti <`header`>, <`footer`>, <`nav`>, <`section`>, dan lainnya, digunakan untuk memberikan struktur semantik pada halaman web dan memperbaiki aksesibilitas

## Kesimpulan
Kesimpulan tentang tag dasar dalam HTML:

1. *<!DOCTYPE html>*: Mendefinisikan tipe dokumen HTML yang digunakan, dalam hal ini HTML versi terbaru.

2. *<`html`>*: Menandai awal dan akhir dari sebuah dokumen HTML. Semua elemen HTML harus berada di dalam tag ini.

3. *<`head`>*: Berisi informasi meta-data tentang dokumen HTML, seperti judul halaman, stylesheet, skrip JavaScript, dan meta tag untuk SEO.

4. *<`title`>*: Menetapkan judul atau nama halaman yang akan ditampilkan di bilah judul browser.

5. *<`body`>*: Berisi konten yang akan ditampilkan di jendela browser, seperti teks, gambar, tautan, formulir, dan elemen-elemen lainnya.

6. *Elemen Teks*: Seperti <`h1`>, <`h2`>, <`p>`, <`span`>, dan lainnya, digunakan untuk menampilkan teks dengan berbagai tingkat kepentingan dan format.

7. *Elemen Gambar*: Seperti <img>, digunakan untuk menampilkan gambar di dalam halaman web.

8. *Elemen Tautan*: Seperti <`a`>, digunakan untuk membuat tautan atau hyperlink ke halaman web lain, dokumen, atau alamat email.

9. *Elemen Daftar*: Seperti <`ul`>, <`ol`>, dan <`li`>, digunakan untuk membuat daftar item, baik berurut maupun tidak berurut.

10. *Elemen Formulir*: Seperti <`form`>, <`input`>, <`textarea`>, dan lainnya, digunakan untuk mengumpulkan data dari pengguna.

11. *Elemen Divisi*: <`div`> digunakan untuk mengelompokkan dan menata konten secara visual atau untuk membuat layout halaman yang lebih kompleks.

12. *Elemen Semantik*: Seperti <`header`>, <`footer`>, <`nav`>, <`section`>, dan lainnya, digunakan untuk memberikan struktur semantik pada halaman web dan memperbaiki aksesibilitas.

Tag-tag dasar ini membentuk dasar dari sebuah dokumen HTML dan digunakan untuk membuat struktur dan tata letak halaman web. Dengan pemahaman yang baik tentang penggunaan dan fungsionalitas masing-masing tag, Anda dapat membuat halaman web yang terstruktur, mudah dimengerti, dan dapat diakses dengan baik oleh pengguna dan mesin pencari.
# Heading
   
   Heading atau judul dalam HTML digunakan untuk menandai tingkatan kepentingan dari teks judul pada halaman web. HTML menyediakan enam tingkat heading, mulai dari `<h1>` (heading level 1) sebagai tingkat judul paling tinggi hingga `<h6>` sebagai tingkat judul paling rendah.
   
- Contoh penggunaan heading dalam HTML:   

1. `<h1>`  Heading Level 1

   Digunakan untuk judul utama atau judul halaman

2. `<h2>`  Heading Level 2

   Digunakan untuk judul subseksi atau subbagian.

3.  `<h3>`  Heading Level 3

   Digunakan untuk judul subbagian yang lebih dalam

4.  `<h4>`  Heading Level 4

   Digunakan untuk judul yang lebih spesifik atau terkait dengan subbagian.

5.  `<h5>`  Heading Level 5

   Digunakan untuk judul yang lebih rinci atau terkait dengan judul tingkat kepentingan lebih tinggi.

6.  `<h6>`  Heading Level 6

   Digunakan untuk judul tingkat kepentingan terendah dalam sebuah dokumen.

>[!faq] Contoh Program Heading

```
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
      <body>
        <h1>Judul Utama</h1>
        <h2>Sub judul</h2>
        <h3>Contoh ke 3</h3>
         <h4>Contoh ke 4</h4>
          <h5>Contoh ke 5</h5>
           <h6>Contoh ke 6</h6>
      </body>
  
  </head>
</html>
```
## Hasil dari web
![[h.heading.png]]

## Kesimpulan
Kesimpulan tentang penggunaan heading dalam HTML:
1. **Pentingnya Hierarki**: 
    Heading digunakan untuk memberikan hierarki judul dalam dokumen HTML. Semakin tinggi tingkat heading, semakin besar tingkat kepentingan judul tersebut.
2. **Struktur dan Navigasi**:
    Dengan menggunakan heading dengan benar, halaman web dapat memiliki struktur yang jelas dan memudahkan navigasi bagi pengguna.
3. **Pengaturan Tata Letak**: 
    Heading dapat digunakan untuk memberikan tata letak visual pada halaman web, membuatnya lebih menarik dan mudah dipahami.
4. Satu <`h1`> per Halaman: 
    Direkomendasikan untuk hanya menggunakan satu <`h1`> per halaman sebagai judul utama, dan tingkat heading yang lebih tinggi digunakan untuk judul-judul utama subbagian.
# PARAGRAF
Paragraf dalam HTML ditandai dengan tag <`p`>. Tag ini digunakan untuk menandai blok teks yang membentuk sebuah paragraf. Berikut adalah beberapa poin penting tentang penggunaan paragraf di HTML:

1. *<`p`> (Paragraf)*:
   - Digunakan untuk menandai awal dan akhir dari sebuah paragraf teks dalam dokumen HTML.
   - Menambahkan jarak sebelum dan sesudah teks yang ditandai dengan tag <`p`>.
   - Membantu dalam memberikan struktur dan keterbacaan yang baik pada dokumen HTML.

2. *<`b`> (Bold)*:
   - Digunakan untuk membuat teks menjadi tebal (bold).
   - Secara tradisional digunakan untuk memberikan penekanan visual pada teks tertentu.

3. *<`u`> (Underline)*:
   - Digunakan untuk membuat teks menjadi bergaris bawah (underline).
   - Biasanya digunakan untuk memberikan penekanan visual atau menandai teks sebagai tautan (link).

4. *<`i`> (Italic)*:
   - Digunakan untuk membuat teks menjadi miring (italic).
   - Digunakan untuk memberikan penekanan visual yang berbeda atau menunjukkan istilah dalam bahasa asing.

5. *<`br`> (Line Break)*:
   - Digunakan untuk membuat jeda baris di dalam teks.
   - Teks setelah tag <br> akan ditampilkan di baris baru, tanpa menunggu akhir dari paragraf atau elemen lainnya.

6. *<`hr` (Horizontal Rule)*:
   - Digunakan untuk membuat garis horizontal yang memisahkan konten dalam halaman.
   - Garis horizontal ini sering digunakan untuk memisahkan bagian-bagian dalam halaman web, seperti antara judul dan konten, atau antara bagian-bagian berbeda dalam konten.

>[!faq] Contoh Program Paragraf
```
<!DOCTYPE html>
<html>
   </head>
   <body>
     <title>ini adalah judul</title>
     <p>paragraf:Digunakan untuk membuat paragraf teks.</p>
     <b>Bold: menggunakan teks tebal</b>
     <br> -line Break:di gunakan untuk memasukkan pemisah baris (line break).</br>
     <u>underline: menggunakan garis bawah pada teks</u>
     <br></br>
     <i>- italic: menggunakan teks miring</i>
     <hr>-Horizontal rule: membuat garis horizontal untuk memisahkan konten.</hr>
   </body>
</html>
```

## Hasil dari web
![[h.paragraf.png]]

## Kesimpulan
Kesimpulan tentang penggunaan tag teks dalam HTML:

1. *<`p`> (Paragraf)*:
   - Digunakan untuk menandai awal dan akhir dari sebuah paragraf teks dalam dokumen HTML, memberikan struktur yang terorganisir pada konten.
   
2. *<`b`> (Bold)*:
   - Digunakan untuk membuat teks menjadi tebal (bold), menyoroti teks yang penting atau membedakan teks tertentu dari yang lain.
   
3. *<`u`> (Underline)*:
   - Digunakan untuk membuat teks menjadi bergaris bawah (underline), sering digunakan untuk menandai tautan atau memberikan penekanan tambahan pada teks.
   
4. *<`i`> (Italic)*:
   - Digunakan untuk membuat teks menjadi miring (italic), biasanya digunakan untuk menunjukkan kata-kata dalam bahasa asing, judul buku, atau istilah teknis.
   
5. *<`br`> (Line Break)*:
   - Digunakan untuk membuat jeda baris di dalam teks, memungkinkan untuk menampilkan teks berikutnya di baris baru tanpa menunggu akhir dari paragraf atau elemen lainnya.
   
6. *<`hr`> (Horizontal Rule)*:
   - Digunakan untuk membuat garis horizontal yang memisahkan konten dalam halaman, seperti antara bagian-bagian berbeda atau untuk memberikan visual pemisah.

# Tag Align
Atribut align digunakan untuk mengatur perataan teks pada halaman HTML  Elemen <`p`> dapat menggunakan nilai atribut align"left", akan menghasilkan paragraf dengan perataan teks disebelah kiri Nilai atribut align="right", akan menghasilkan paragraf dengan perataan teks sebelah kanan nilai atribut Align="center" ,Akan menghasilkan paragraf dengan perataan teks di tengah dan nilai atribut align="justify" ,akan menghasilkan paragraf dengan perataan teks pada kiri dan sisi kanan

<`h3`>  belajar Menggunakan Elemen Tag HTML.P <`/h3`>
<`p align ="left"`> 
    Lorem ipsum dolor sit amet,  consectetur  adipisicing elit. officiis ut   iure quit
<`/p`>
<`p align="right">
     Lorem ipsum dolor sit amet, consectetur adipisicing elit. officiis ut iure quit 
<`/p`>
<`p align"center">
     Lorem ipsum dolor sit amet, consectetur adipisicing elit. officiis ut iure quit 
<`/p>
<`p align="justify"
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. officiis ut iure quit 
<`/p`>

## Hasil
![[h.align.png]]
# Komentar
Html juga mempunyai tag khusus untuk komentar. Untuk membuat komentar di Html
Kita menggunakan awalan "<!-- " dan penutup --> .

```
<!DOCTYPE html>

<html>

    <body>

        <!-- Ini komentar, tidak akan tampil di browser -->

<p>Ini bukan komentar, dan akan tampil di browser</p>

    </body>

</html>
```

![siapa](siapa.jpg)

# List
List adalah fungsi HTML yang digunakan untuk menampilkan daftar dari sesuatu dalam HTML. tag list terdiri dari 2 jenis "<"ol> ordered list (berurutan) dan "<"ul> nordered list (tidak berurutan) ordered list akan tampilkan dengan angka atau huruf sedangkan unordered list dengan bulatan atau kotak ataupun simbol lainnya.

## Program List
```<!DOCTYPE html>

<html>

<body>

<h1>Cara membuat kopi </b1>

    <p> bahan-bahan </p>

    <ul>

        <li>2std kopi bubuk</li>

        <li>2std gula pasir</li>

        <LI> Air panas secukupnya</LI>

    </ul>

    <p>Langkah-Langkah</p>

    <ol>

    <li>Masukkan bubuk kopi dan gula kedalam cangkir</li>

    <li>,Seduh dengan air panas mendidih</li>

    <li>Aduk dan siap dihidangkan</li>

    </ol>

</body>

</html>
```

## Hasil dari web Browser
![gambar](gambarr.jpg)

# Link
Link dapat ditemukan di lampir semua halaman web Link/tautan memungkinkan sebuah teks yang ketika di klik akan pindah ke halaman lainnya HTML menggunakan Tag ''<a"> untuk keperluan ini. Link di tulis dengan "<a"> yang merupakan singkatan dari ancher (jaringan).

>[!faq]- setiap tag ''<a"> setidaknya atribut href di mana href berisi alamat yang di tuju. href adalah singkatan dari hypertext refences.

 Atribut penting lainnya dari tag "<a"> atribut target menentukan tempat untuk membuka dokumen yang  di tautkan. Atribut target memiliki beberapa nilai salah satunya _blank yang berfungsi untuk membuka tautan di tab baru.

## Program Link
```
```
```
<!DOCTYPE html>

<html>

  <head>

    <title>judul halaman</title>

  </head>

  <body>

    <h3>Menggunakan tag anchor</h3>

    <a href="https://www.istagram.com/reyhanz_aja" target="_blank"> klik disini untuk ke buat</a><br>

   <a

   href="file://D:/folder%20html/dasar.html"> klik disini untuk kehalaman lain yang saya buat</a>

  </body>

</html>
```

### Hasil dari Web Browser
![frhan](frhann.jpg)

# Multimedia
Gambar 
Dalam html g ambar didefinisikan dengan tag <img> adalah tag kosong hanya berisi atribut saja dan tidak memiliki penutup.

>[!faq]- catatan
>Atribut <`src> setidaknya ada dalam tag ini untuk menentukan url (alamat web) dari gambar yang ingin di tampil kan

Atribut alt menyediakan teks alternatif untuk gambar jika pengguna karena beberapa alasan tidak dapat melihat nya (karena koneksi lambat kesalahan pada atribut src, jika web browser telah di setting untuk di tampilkan gambar)
  
  Dalam tag <img> terdapat juga atribut width dan height untuk mengatur ukuran gambar pada versi HTML5 standar satuan ukuran gambar adalah alt
  
- misalnya dalam folder root terdapat file gambar bernama logo.png untuk menampilkan gambar tersebut kita hanya perlu mengisi nama gambar beserta jenis ekstensi file gambar ke dalam atribut src    contoh src="logo.png"
- untuk menampilkan gambar dari internet carilah link gambar yang akan di tampilkan lalu memasukkan dalam atribut src contohnya https://namasitus.com/gambar.jpg
## Program menampilkan gambar

```<!DOCTYPE html>

<html>

    <head>

        <title>program web</title>

    </head>

    <body>

        <img src="siapa.jpg" alt="siapa.jpg"width="600" height="300">

    </body>

</html>
```

## Hasil dari Web Browser
![rehan](ASET/REHAN.jpg)

Berikut adalah letak gambar yang dimuat website diatas:
![[simpan gambar.png]]


# Multimedia video
dalam HTML, video didefinisikan dengan tag <`video>`, tag <`video>` adalah tag yang digunakan untuk memasukkan video kedalam web, di tag <`video>` terdapat tag khusus yang dimana tag ini tidak memiliki tag penutup yaitu <`source>` yang Digunakan untuk menyediakan beberapa sumber video dan memberi browser pilihan format yang sesuai.

Dalam tag <`video>` terdapat juga atribut   controls yang digunakan untuk Menambahkan kontrol pemutaran standar seperti play, pause, dan volume, dan juga di tag <`video>` ada atribut width dan height yang digunakan untuk mengatur ukuran video, pada versi HTML 5 standar satuan ukuran video adalah pixel, dan juga di dalam nya juga terdapat atribut type yang di gunakan untuk menentukan tipe MIME (Multipurpose Internet Mail Extensions) dari file video yang disematkan.

misalnya dalam folder root terdapat file video bernama video.mp4. untuk menampilkan video tersebut kita hanya perlu mengisi nama video beserta jenis ekstensi file video didalam tag <`source>` dan didalamnya atribut src terus juga didalam tag <source> kita beri juga didalamnya atribut type untuk menetukan tipe MIME(Multipurpose Internet Mail Extensions) di file video yang di sematkan.

## kode program video

```<!DOCTYPE html>

<html>

    <head>

        <title>program web</title>

    </head>

    <body>

        <video src="./goal.mkv"controls loop width="600"></video>

  

    </body>

</html
```

## Hasil dari web browser
![hprusak](ASET/hprusak.jpg)

Berikut adalah letak gambar yang dimuat website diatas:
![[video web.png]]
# Multimedia audio
Seperti yang telah dibahas sebelumnya bahwasanya tag <`audio`> merupakan bagian fitur HTML5 untuk menampilkan audio asli di halaman web tanpa memerlukan flash sebagaimana pada HTML versi 4. yang penting untuk diatur pada tag ini adalah Atribut <`src`> yang berfungsi untuk mengidentifikasi sumber media. selain itu terdapat pada Atribut <`controls`> agar pengguna dapat menukar dan menjadi  medua.

>[!faq]- contoh program
`audio src="audio.wav" controls>
   browser anda tidak  mendukung elemen <`audio>.
   <`/audio>

konten berupa teks"browser anda tidak mendukung elemen `<`elemen`> pada tag <`video>". pada tag <`video`> akan di tampilkan jika browser tidak mendukung elemen tersebut sehingga sebenarnya bagian ini dapat dihilangkan.

## Hasil dari web browser
![[Pemrograman WEB 2/h audiio.png]]

Berikut adalah letak gambar yang dimuat website diatas:
![[simpan web.png]]
# Halaman web lain
 Elemen `<iframe>` dapat digunaka untuk menampilkan halaman website lain dalam suatu website. akan menampilkan dokumen HTML lain dalam subuah website. mudahnya. bisa dibilang website dalam website.

💡 CONTOH penggunaannya seperti ini. jika kita mempunyai website sekolah, lalu di website tersebut ingin menampilkan alamat dalam google maps sekolah, agar memudahkan pengunjung website, kita bisa langsung tampilkan saja halaman sekolah yang ada di google maps.

Dalam tag `<frame>` ada beberapa Atribut yang penting seperti :

### `<src>`, untuk mencari sumber halaman HTML atau web yang akan ditampilkan di dalam frame
### `<width>` dan `<height>` untuk mengatur ukuran panjang dan lebar dari frame.

>[!faq] Contoh Program
```
<!DOCTYPE html>

<html>

    <head>

        <title>program web</title>

    </head>

    <body>

        <iframe src="https://www.smkn7makassar.sch.id/" width="360" height="360"></iframe>

    </body>
</html
```

## Hasil
![[h.web.png]]
# Table
Tabel dalam HTML didefinisikan dengan tag <`table`>
- setiap baris tabel didefinisikan dengan <`tr`>.
- Header (judul) tabel didefinisikan dengan tag <`th`>. secara defaul Header tabel memiliki teks tabel dan berada di tengah.
- data tabel/sel didefinisikan dengan tag <`th`> karena  sel merupakan  bagian terkecil dari tabel maka dari itu tag ini selalu berada di dalam tag <`tr`>

  CONTOH :
```
 HTML
  <table> border="1">
  <tr>
  <th>nama</th>
  <th>Asal institusi</th>
  </tr>
  <tr>
  <td>ibrahim Mallombasang</td>
  ```

💡 Perhatikan bahwa pada tag <`table`> terdapat sebuah Atribut  <`border`>. Atribut    <`border`> Digunakan untuk memberikan nilai garis tapi dari tabel nilai ini dalam ukuran pixel <`border="1"`>, berarti kita mengistruksikan kepada web browser bahwa tabel tersebut akan memiliki garis tapi sebesar 1 pixel .  jika tidak di tambahkan. secara defaul tabel tidak memiliki garis tapi.

selain itu terdapat pula beberapa atribut tabel yang penting untuk diketahui yaitu:
### <`rowspan`>
  merupakan atribut HTML yang berfungsi untuk menggabungkan  beberapa baris (ke bawah
### <`colspan`> 
atau colum span merupakan atribut HTML yang berfungsi untuk menggabungkan beberapa kolom (ke samping).
### <`widh`> 
berfungsi untuk mengatur lebar tabel yang nilainya didefinisikan dalam satuan pixel secara defaul.
### <`height`>
berfungsi untuk mengatur tinggi tabel yang nilainya  didefinisikan dalam satuan pixel secara defaul.
### <`align`> 
berfungsi untuk mengatur perataan teks pada tabel. nilai atribut yang dapat  di berikan yaitu <`left`> Untuk perataan teks ke kiri, <`right`> Untuk perataan teks ke kanan, dan <`center`> untuk perataan teks ke tenggah.
## Contoh:
```
<!DOCTYPE html>

<html>

    <head>

        <title>tabel web</title>

    </head>

    <body>

        <table border="1">

            <tr>

             <th>nama</th>

              <th>asal institusi</th>

             </tr>

  

             <tr>

                <td>ibrahimm mallombasang</td>

                <td>Universitas Negeri Makassar</td>

             </tr>

             <tr>

                <td>Conrado Alain Sharon</td>

                <td>SMKN 7 MAKASSAR</td>

            </tr>

        </table>

    </body>

</html>
```
## Hasil
![[hasil program tabel.jpg]]

## Penjelasan tentang program di atas
Program di atas menghasilkan sebuah halaman web yang menampilkan sebuah tabel sederhana dengan dua baris dan dua kolom. Berikut adalah penjelasan tentang hasil yang dihasilkan dari program tersebut:

1. Tabel: Tabel yang memiliki border dengan tebal 1.
2. Baris Header:
   - Terdapat satu baris untuk header.
   - Baris tersebut memiliki dua kolom: "nama" dan "asal institusi".
3. Baris Data:
   - Ada dua baris data.
   - Setiap baris memiliki dua kolom.
   - Kolom pertama berisi nama orang.
   - Kolom kedua berisi asal institusi orang tersebut.
4. Data yang ditampilkan:
   - Baris pertama: Nama "ibrahimm mallombasang" berasal dari "Universitas Negeri Makassar".
   - Baris kedua: Nama "Conrado Alain Sharon" berasal dari "SMKN 7 MAKASSAR".
5. Tabel ditutup dengan tag <`/table`> di akhir.



## Contoh 2:
```
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=>, initial-scale=1.0">

    <title>Document</title>

</head>

<body>

    <table border="1">

        <tr>

        <th rowspan="2">Nama</th>

      <th colspan="2">Asal institusi</th>

    </tr>

    <tr>

        <th width="100">Sekolah</th>

        <th width="100">Kampus</th>

    </tr>

    <tr>

        <td>ibrahim mallombasang</td>

        <td>Sman 14 Makassar</td>

        <td>Universitas Negeri Makassar</td>

    </tr>

<tr>

    <td>conrado Alain Sharon</td>

    <td rowspan="2">SMKN 7 MAKASSAR</td>

    <td align="center" rowspan="2"> </TD>

</tr>

<tr>

    <td>Resky Awalya</td>

</tr>

<tr>

    <td>Muzhawir Amri</td>

    <td>SMAN 1 Palu</td>

    <td>STMIK Dipanegara</td>

</tr>

    </table>

</body>

</html>

```

### Hasil:
![[h.tabell.png]]

## Penjelasan tentang gambar di atas
Program di atas menghasilkan sebuah halaman web yang menampilkan sebuah tabel dengan beberapa baris dan kolom. Berikut adalah penjelasan tentang hasil yang dihasilkan dari program tersebut:

1. Tabel: Tabel yang memiliki border dengan tebal 1.
2. Baris Header:
   - Terdapat dua baris untuk header.
   - Baris pertama memiliki satu kolom yang digabungkan menggunakan atribut rowspan dengan nilai 2, dan berisi teks "Nama".
   - Baris kedua memiliki dua kolom yang digabungkan menggunakan atribut colspan dengan nilai 2, dan berisi teks "Asal institusi" yang terbagi menjadi dua bagian: "Sekolah" dan "Kampus".
3. Baris Data:
   - Ada tiga baris data.
   - Setiap baris memiliki tiga kolom.
   - Kolom pertama berisi nama-nama orang.
   - Kolom kedua berisi asal sekolah.
   - Kolom ketiga berisi asal kampus.
4. Beberapa baris memiliki kolom yang digabungkan:
   - Baris kedua, kolom "Asal institusi - Sekolah" digabungkan menggunakan atribut rowspan dengan nilai 2.
   - Baris ketiga, kolom "Asal institusi - Kampus" tidak memiliki data, tetapi masih ada dalam tabel.
5. Tabel ditutup dengan tag <`/table`> di akhir.

💡 Perhatikan pada Konten elemen <`td`> yang berisi RESKY AWALYA ,hanya terdapat satu elemen <`td`> di sana. Hal ini di karenakan konten elemen <`td`> sebelumnya yaitu SMKN 7 MAKASSAR dan - pada data Condrado Alain Sharon Mengandung Atribut <`rowspan`> dengan  nilai 2 yang sacara otomatis mengisi data di bawahnya yakni data  RESKY AWALYA. Nilai 2 menunjukkan bahwa ada dua baris yang di gabungkan menjadi satu

Konsep ini juga dengan apa yang terjadi pada <`th rowspan="2">Nama</th> dan <`th colspan="2"`> Asal Intitusi<`/th`>. 

# From
Elemen <`from`> HTML Digunakan untuk mendefinisikan from yang digunakan untuk mengumpulkan inputan dari pengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata.

>[!faq] Dengan kata lain tag <`from`> merepresentasikan sebuah "formulir" di mana satu formulir bisa memiliiki banyak kolom isian.

From HTML berisikan elemen-elemen from lainnya. Elemen <`from`> digunakan untuk menampung macam-macam elemen yang berkaitan dengan sebuah from, seperti, text fields, chackbox, radio button, tombol sumbit, dan banyak lagi yang dapat di edit kemudian ditulis untuk dikirim pada sebuah server untuk selanjutnya diproses guna mendapatkan informasi tertentu dari suatu untuk user.

umumnya, sebuah website selalu memiliki fitur from, contoh paling umum yang sering kita temui adalah seperti from login, form sign up, form komentar di suatu blog/media

### Input
Elemen <`input`> adalah elemen from yang paling penting. elemen <`input`> dapat ditampilkan daalam beberapa cara. terngantung pada nilai atribut type yang di gunakan berikut adalah beberapa contoh nilai atribut type:
### text 
digunakan untuk mengambil isian berupa teks. contohnya seperti nama. contohnya ialah seperti berikut:

   <`label for="nama-lengkap"><b>Nama:</b></label><br`>   
   <`input type="text" id="nama-lengkap" name="nama_lengkap" placeholder="Masukkan passssword"`>

Hasil Program:
![[img.1.png]]
                
### password  
digunakan untuk mengambil isian berupa kata sandi atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua kerakter yang diketikkan ke dalam kerakter bulat. contohnya ialah seperti berikut:

   <`label for="password"><b>Password:</b></label><br`>

   <`input type="password" id="password" name="password" placeholder="Masukkan passssword"`>
                
Hasil Program:
![[img.2.png]]
### rasio 
digunakan sebagian kolom isian bertipe pilihan yang menawarkan  beberapa opsi  kepada user namun  tetapi hanya satu opsi saja yang boleh di pilih.  contohnya seperti jenis kelamin atau agama.
>[!faq] perlu di perhatikan bahwa untuk penggunaan tipe radio yang berkategori set pilihan yang sama mengharuskan nilai name -nya juga sama. 

 Opsi  default dapat dilakukan dengan menambahkan atribut <`hecket`> pada elemen opsi dijadikan sebagai opsi default. contohnya ialah seperti berikut:

                <b>Jenis Kelamin: </b><br>

                <input id="lk" type="radio" name="jenis_kelamin" checked>

                <label for="lk">Laki-Laki</label>

                <input id="pr" type="radio" name="jenis_kelamin">

                <label for="pr">Perempuan</label>

Hasil Program:
![[img.3.png]]

### <`checkbox`>
digunakan untuk memberikan *daftar pilihan dalam satu set opsi* . User dapat memilih satu atau bahkan  *lebih dari satu pilihan* pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu radio yang hanya memungkinkan user untuk memilih satu pilihan saja. Contoh penggunaan <`checkbox`> seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai dan yang Semisalnya. contohnya ialah seperti berikut:
  >[!faq] perlu diperhatikan bahwa untuk penggunaan tipe <`checkbox`> yang berkategori set pilihan yang sama mengharuskan nilai name -nya juga sama.

                <b>Kemampuan Berbahasa Asing:*</b><br>

                <input type="checkbox" id="inggris" name="bahasa_asing">

                <label for="inggris">Inggris</label>

                <input type="checkbox" id="arab" name="bahasa_asing">

                <label for="arab">,Arab</label>

  

                <input type="checkbox" id="jepang" name="bahasa_asing">

                <label for="Jepang">Jepang</label>

            </div>

Hasil Program:
![[img.4.png]]
### number 
digunakan untuk membatasi isian user hanya pada karakter *numerik* saja. Browser akan menambahkan dua buah tombol atas dan bawah untuk mengubah angka isian. 
Beberapa atribut untuk tipe Number:
### min - 
menentukan angka minimal
### max - 
menentukan angka maksimal
### step - 
menentukan kelipatan (nilai yang tidak sesuai kelipatan tidak bisa di-input, dan default dari atribut ini adalah 1)
### date 
digunakan untuk menberikan isian berupa *tanggal*. Atribut min dan max dapat pula difungsikan pada tipe ini untuk mengatur tanggal minimal dan tanggal maksimal yang diinginkan. Nilai min dan max tersebut ditulis dengan format: YYYY-MM-dd . 

 file digunakan untuk memungkinkan pengguna memuat *file*. Atribut accept juga dapat disisipkan pada tipe ini dengan maksud untuk mengatur file apa saja yang boleh di-upload. Beberapa contoh value dari atribut accept yaitu:
### accept="image/png/,image/jpg, image/jpeg" -
untuk file gambar seperti png, jpg, atau jpeg
### accept=".pdf" - 
untuk file pdf
### accept=".doc, .docx" -
untuk file doc atau docx
### accept=".ppt, .pptx" - 
untuk file ppt atau pptx
### submit 
ditampilkan dalam *bentuk tombol untuk mengirim data* pada <`form`> yang menjadi pembungkus nya. Atribut value digunakan untuk mengisi teks yang ingin ditampilkan pada tombol. 
### reset 
berguna untuk *mengembalikan state(keadaan)atau data dari suatu form ke nilai awalnya*. Jika nilai awal sebuah input adalah kosong, maka ketika direset ia akan kembali kosong. Tapi jika nilai awalnya sudah terisi sesuatu, maka ketika direset datanya akan kembali seperti yang sudah diset sebelumnya. 
### Button 
berguna untuk membuat *inputan berupa sebuah tombol* . Tombol ini nantinya bisa difungsikan sesuai dengan keinginan dari pengembang web

### *Label*
Elemen <`label`> memiliki fungsi khusus untuk melabeli sebuah kolom inputan. Ketika screen reader membaca konten halaman HTML, lalu menemukan sebuah inputan, ia akan membaca label yang bersangkutan. 
Fungsi lain dari tag <`label`> adalah ketika kita mengklik label, maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya. Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah <`label`> dan <`input`> dengan atribut for untuk label, dan atribut id pada <`input`> dengan nilai untuk kedua atribut tersebut mesti sama persis.

### Select
Elemen <`select`> berguna dalam mendefinisikan sebuah tombol dropdown yang dimana user dapat memilih salah satu dari banyak pilihan.

>[!faq] Elemen <`select`> nantinya berperan sebagai kontainer atau pembungkus dari elemen <`option`> yang berperan sebagai daftar pilihan atau opsi. 

 Elemen <`select`> hampir mirip fungsinya dengan <`input type ="radio"`> akan tetapi baiknya elemen <`select`> digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan <`input type ="radio"`> lebih baiknya untuk digunakan jika user diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.
 
Penting untuk diketahui bahwasanya opsi yang aktif secara default adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara default dengan menambahkan atribut selected pada suatu <`option`> yang ingin dijadikan sebagai opsi default contohnya ialah seperti berikut:

                <label for="opsi-agama"><b>Agama:</b></label><br>

                <select id="opsi-agama" name="agama" required>

                <option disabled>---Pilih Agama----</option>

                <option value="islam">Islam</option>

                <option value="kristen">Kristen</option>

                <option value="katolik">Katolik</option>

                <option value="hindu">Hindu</option>

                <option value="buddha">Buddha</option>

                <option value="atheis" disabled>Atheis</option>

                </select>


Hasil Program:
![[img.5.png]]

### Text Area
Elemen <`textarea`> berguna untuk mengambil inputan user berupa teks yang dapat memuat lebih dari satu baris. Jika dibandingkan dengan elemen <`input`> teks biasa, elemen <`textarea`> memiliki ukuran tinggi yang lebih besar. Element <`textarea`> bisa diisi lebih dari satu baris dengan menekan enter.

Atribut yang dapat digunakan untuk mengatur kuran dari textarea yaitu rows untuk jumlah baris, sedangkan atribut cols untuk lebarnya.

### Button
Elemen <`button`> yang berada di dalam sebuah form akan otomatis dianggap sama fungsinya seperti <`input type="submit"`>. Jika ingin membuat tombol biasa yang tidak men-submit <`form`> dapat dilakukan dengan menambahkan atribut type="`button`".

## Contoh :
```
<!DOCTYPE html>

<html>

    <head>

        <title>formulir</title>

    </head>

    <body>

        <h1>formulir pendaftaran</h1>

        <form action="">

            <div>

                <label for="nama-lengkap"><b>Nama:</b></label><br>

                <input type="text" id="nama-lengkap" name="nama_lengkap" placeholder="Masukkan passssword">

  

            </div>

            <div>

                <label for="password"><b>Password:</b></label><br>

                <input type="password" id="password" name="password" placeholder="Masukkan passssword">

            </div>

            <div>

                <b>Jenis Kelamin: </b><br>

                <input id="lk" type="radio" name="jenis_kelamin" checked>

                <label for="lk">Laki-Laki</label>

                <input id="pr" type="radio" name="jenis_kelamin">

                <label for="pr">Perempuan</label>

            </div>

            <div>

                <label for="isian-usia"><b>Usia:</b></label><br>

                <input type="number" id="isian-usia" name="usia" min="17" max="25" value="19">

            </div>

            <div>

                <label for="tgl-ijazah:"><b>Tanggal ijazah:</b></label><br>

                <input type="date" id="tgl-ijazah" name="tgl-ijazah" min="2021-01-0\1" value="2">

            </div>

            <div>

                <label for="opsi-agama"><b>Agama:</b></label><br>

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

  

                <label for="alamat"><b>Alamat:</b></label> <br>

                <textarea id="alamat" name="alamat" cols="25" rows="5" placeholder="Harap masukan alamat"></textarea>

            </div>

            <div>

                <b>Kemampuan Berbahasa Asing:*</b><br>

                <input type="checkbox" id="inggris" name="bahasa_asing">

                <label for="inggris">Inggris</label>

                <input type="checkbox" id="arab" name="bahasa_asing">

                <label for="arab">,Arab</label>

  

                <input type="checkbox" id="jepang" name="bahasa_asing">

                <label for="Jepang">Jepang</label>

            </div>

            <br>

            <input type="submit" value="Kirim">

            <input type="reset" value="Batal">

            <i>*opsional (tidak wajib diisi)</i>

        </form>

    </body>

</html>
```
### Hasil 
![[hasil program formulir.png]]

## Penjelasan tentang gambar
Program di atas menghasilkan sebuah halaman web yang menampilkan formulir pendaftaran dengan beberapa field yang dapat diisi oleh pengguna. Berikut adalah hasil yang dihasilkan dari program tersebut:

1. Judul: "formulir pendaftaran".
2. Formulir dengan beberapa input field:
   - Nama lengkap: Input teks untuk nama lengkap pengguna.
   - Password: Input password untuk password pengguna.
   - Jenis kelamin: Radio button untuk memilih jenis kelamin (laki-laki atau perempuan).
   - Usia: Input number untuk mengisi usia pengguna dengan rentang 17 hingga 25.
   - Tanggal ijazah: Input tanggal untuk tanggal ijazah dengan nilai default tanggal 2.
   - Agama: Dropdown pilihan agama dengan opsi Islam, Kristen, Katolik, Hindu, Buddha, dan Atheis (yang dinonaktifkan).
   - Alamat: Input teks area untuk alamat pengguna.
   - Kemampuan berbahasa asing: Checkbox untuk memilih kemampuan berbahasa asing (Inggris, Arab, dan Jepang).
3. Tombol:
   - Kirim: Tombol submit untuk mengirimkan formulir.
   - Batal: Tombol reset untuk menghapus inputan pada formulir.
4. Catatan opsional di bawah tombol "Kirim".

>[!faq] Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:
### name -
digunakan sebagai nama variabel yang akan diproses oleh web server (contoh menggunakan PHP)
### required - 
digunakan untuk memastikan bahwa pengguna harus memasukkan nilai pada input tersebut sebelum dapat melakukan proses submit formulir
### placeholder - 
menuliskan teks pada elemen input. Placeholder sangat bermanfaat untuk memberikan teks bantuan kepada user untuk inputan form yang kompleks
### value - 
menentukan nilai awal dari sebuah elemen input
### disabled - 
digunakan untuk menonaktifkan inputan pada elemen yang diberi atribut ini

### *Bagaimana Cara Memproses Form?*

Ketika sebuah <`form`> disubmit, baik menggunakan elemen <`button`> mau pun <`input type="submit"`>, browser akan mengirimkan data tersebut kepada URL yang didefinisikan pada atribut action di dalam tag form.

Ada pun jika atribut action tidak didefinisikan, maka browser akan menggunakan URL sekarang sebagai tujuan pengiriman data.

Contoh:

html
**<form** action=**"/proses-pendaftaran"****>
  ...
**<`/form`>**


Pada contoh di atas, ketika form di-submit, browser akan mengirimkan data yang ada  menuju URL /proses-pendaftaran.

*Apa yang terjadi pada URL /proses-pendaftaran?*

Pada URL tersebut terdapat sebuah aplikasi/program yang berjalan di server (bukan di browser). Tugas dari program tersebut adalah mengelola data yang dikirim seperti misalnya menyimpan data tersebut ke dalam sebuah database.

Bahasa yang umum digunakan di dalam server adalah python, nodejs, PHP, dan lain sebagainya.

Untuk mendapatkan gambaran lebih jelas, sebenarnya akan dijelaskan pada modul selanjutnya yang berkaitan dengan materi PHP atau juga bisa dengan membaca tutorial berikut : 

# Tabel Bulan
## Sturktur
Program HTML di atas memiliki struktur dasar yang terdiri dari:

1. *Deklarasi DOCTYPE*: <!DOCTYPE html> mendefinisikan jenis dokumen HTML yang digunakan, dalam hal ini HTML5.

2. *Elemen <`html`>*: Menandai awal dan akhir dari dokumen HTML.

3. *Elemen <`head`>*: Berisi informasi meta-data tentang dokumen HTML, seperti judul halaman yang ditentukan oleh tag <`title`>.

4. *Elemen <`title`>*: Menetapkan judul atau nama halaman yang akan ditampilkan di bilah judul browser.

5. *Elemen <`body`>*: Berisi konten yang akan ditampilkan di jendela browser, seperti teks, gambar, dan elemen-elemen HTML lainnya.

6. *Elemen <`p`>*: Menandai awal dan akhir dari sebuah paragraf yang berisi teks "Buatlah kode program untuk tabel dibawah ini".

7. *Elemen <`table`>*: Membuat sebuah tabel untuk menampilkan data.

8. *Elemen-elemen <`tr`> dan <`td`>*: Digunakan untuk mendefinisikan baris dan sel-sel di dalam tabel. Sel-sel ini berisi data seperti nama hari dan nama bulan.

9. *Atribut colspan dan rowspan*: Digunakan untuk menggabungkan sel-sel dalam tabel, baik secara horizontal maupun vertikal.

## Analisi
1. Deklarasi DOCTYPE: <!DOCTYPE html>: Menandakan bahwa dokumen merupakan dokumen HTML5.
2. Tag HTML: <`html`>: Menandakan awal dari dokumen HTML.
3. Tag Head: <`head`>: Berisi informasi tambahan tentang dokumen HTML, seperti judul dan metadata. Di dalamnya terdapat tag <`title`> yang memberi judul halaman
4. Tag Body: <`body`>: Berisi konten yang akan ditampilkan di halaman web.
5. Tag Tabel: <`table`>: Mendefinisikan sebuah tabel di dalam dokumen HTML. Atribut border="1" menetapkan ketebalan garis batas tabel.
6.  Baris Tabel (Tag TR): <`tr`>: Mendefinisikan sebuah baris dalam tabel.
7. Sel Tabel (Tag TD): <`td`>: Mendefinisikan sebuah sel dalam tabel. Isinya adalah teks yang akan ditampilkan. Atribut colspan digunakan untuk menggabungkan sel horizontal, sedangkan atribut rowspan digunakan untuk menggabungkan sel secara vertikal. Pada baris pertama, sel "Nama hari" dan "Nama bulan" memiliki colspan="2" yang artinya mereka akan mengambil dua kolom secara horizontal.
8. Atribut Width dan Bgcolor: Atribut width digunakan untuk menetapkan lebar sel, sedangkan atribut bgcolor digunakan untuk menetapkan warna latar belakang sel.
9. Tag Baris Kosong: <`tr`>: Membuat baris kosong di dalam tabel.
10. Penutup Tag: Setiap tag dibuka harus ditutup. Misalnya <`/td`>, <`/tr`>, <`/table`>, dst.
## Contoh
Berikut adalah contoh kode program HTML Yang sama:
```
<!DOCTYPE html>
<html>
    <head>
        <title>tes 2</title>
    </head>
    <body>
        <p>Buatlah kode program untuk tabel dibawah ini</p>
        <table border="1">
            <tr>
                <td colspan="2" style="background-color: yellow;">Nama Hari</td>
                <td colspan="2" style="background-color: yellow;">Nama Bulan</td>
            </tr>
            <tr>
                <td style="width: 100px;">senin</td>
                <td>selasa</td>
                <td>april</td>
                <td rowspan="2">juni</td>
            </tr>
            <tr>
                <td>rabu</td>
                <td>kamis</td>
                <td>mei</td>
            </tr>
        </table>
    </body>
</html>

```
## Hasil 
![[h.Bulan.png]]

## Kesimpulan
- Program membuat sebuah tabel dengan dua baris dan empat kolom.
- Kolom pertama menampilkan nama-nama hari (Senin, Rabu, Selasa, Kamis) dan kolom kedua menampilkan nama-nama bulan (April, Mei, Juni).
- Nama hari dan bulan ditampilkan di atas tabel dengan latar belakang warna merah.
- Sel "Juni" memiliki atribut rowspan="2" yang menyebabkan sel tersebut menempati dua baris secara vertikal.
- Terdapat kesalahan pada baris terakhir di mana atribut pada tag <`td`> tidak valid (td="2"), yang seharusnya dihapus atau diperbaiki
- Program ini merupakan contoh sederhana penggunaan elemen-elemen dasar HTML untuk membuat sebuah tabel sederhana dengan menggunakan atribut-atribut seperti colspan, rowspan, width, dan bgcolor.

# Tabel Nama
## Analisis
1. *Deklarasi DOCTYPE*: <!DOCTYPE html> mendefinisikan jenis dokumen HTML yang digunakan, dalam hal ini HTML5.

2. *Elemen <`html`>*: Menandai awal dan akhir dari dokumen HTML.

3. *Elemen <`head`>*: Berisi informasi meta-data tentang dokumen HTML, seperti judul halaman yang ditentukan oleh tag <`title`>.

4. *Elemen <`title`>*: Menetapkan judul atau nama halaman yang akan ditampilkan di bilah judul browser.

5. *Elemen <`body`>*: Berisi konten yang akan ditampilkan di jendela browser.

6. *Elemen <`table`>*: Membuat sebuah tabel untuk menampilkan data.

7. *Elemen-elemen <`tr`> dan <`td`>*: Digunakan untuk mendefinisikan baris dan sel-sel di dalam tabel. Sel-sel ini berisi data seperti nama, sekolah, dan universitas.

8. *Atribut border, height, bgcolor, rowspan, width, dan align*: Digunakan untuk mengatur berbagai properti dari tabel dan sel-selnya, seperti tinggi, lebar, warna latar belakang, penggabungan sel secara vertikal (rowspan), dan penyejajaran teks.
## Struktur
1. *Deklarasi DOCTYPE*: <!DOCTYPE html> mendefinisikan jenis dokumen HTML yang digunakan, yaitu HTML5.

2. *Elemen <`html`>*: Menandai awal dan akhir dari dokumen HTML.

3. *Elemen <`head`>*: Berisi informasi meta-data tentang dokumen HTML, dalam hal ini hanya terdapat tag <`title`> untuk menetapkan judul halaman.

4. *Elemen <`title`>*: Menetapkan judul atau nama halaman yang akan ditampilkan di bilah judul browser.

5. *Elemen <`body`>*: Berisi konten yang akan ditampilkan di jendela browser.

6. *Elemen <`table`>*: Membuat sebuah tabel untuk menampilkan data.

7. *Elemen-elemen <`tr`> dan <`td`>*: Digunakan untuk mendefinisikan baris dan sel-sel di dalam tabel. Dalam hal ini, terdapat dua baris dan tiga kolom.
   - Baris pertama (<`tr`>):
      - Tiga sel berisi teks "ibrahim mallombasang", "SMAN 14 MAKASSAR", dan "UNIVERSITAS NEGERI MAKASSAR".
      - Pengaturan tinggi sel pertama dengan atribut height="10px".
   - Baris kedua (<`tr`>):
      - Sel pertama berwarna merah (bgcolor="red") dan berisi teks "conrado".
      - Sel kedua (<`td rowspan="2" width="100PX"`>) menggabungkan dua baris dan memiliki lebar sebesar 100 piksel.
      - Sel ketiga (`<td rowspan="2" align="center">-</td>`) menggabungkan dua baris dan berisi tanda hubung ("-").
      - Sel keempat (<`td align="center">Reaky awalya</td>`) berada di baris kedua dan berada di tengah secara horizontal.
## Contoh
```
<!DOCTYPE html>

<html>

    <head>

        <title> tes </title>

    </head>

    <body>

        <table border="1">

            <tr>

                <td height="10px">ibrahim mallombasang</td>

                <td>SMAN 14 MAKASSAR</td>

                <td>UNIVERSITAS NEGERI MAKASSAR</td>

            </tr>

            <tr>

                <td bgcolor="red"> conrado</td>

                <td rowspan="2" width="100PX"> SMKN7 MAKASSAR</td>

                <td rowspan="2" align="center">-</td>

            </tr>

            <tr>

                <td align="center">Reaky awalya</td>

            </tr>

        </table>

    </body>

</html>

```
### Hasil
![[h.nama 1.png]]
## Kesimpulan
 Kesimpulan dari program HTML di atas adalah sebagai berikut:

1. Program ini merupakan sebuah halaman web sederhana yang menggunakan tag <`table`> untuk membuat sebuah tabel.

2. Tabel tersebut terdiri dari dua baris dan tiga kolom, yang berisi informasi tentang beberapa orang beserta sekolah dan universitas mereka.

3. Setiap baris tabel diwakili oleh elemen <`tr`> (table row), sedangkan setiap sel diwakili oleh elemen <`td`> (table data).

4. Pada baris pertama tabel, setiap sel berisi informasi tentang nama orang, nama sekolah, dan nama universitas. Sel pertama memiliki tinggi sebesar 10 piksel.

5. Pada baris kedua tabel, sel pertama memiliki warna latar belakang merah dan berisi teks "conrado". Sel kedua dan ketiga menggabungkan dua baris menggunakan atribut rowspan, dan sel ketiga berisi tanda hubung ("-") yang ditengah secara horizontal.

6. Beberapa sel juga memiliki atribut tambahan seperti width, bgcolor, align, dan height untuk mengatur tampilan dan tata letak konten di dalam tabel.

Dengan demikian, program ini menghasilkan tabel yang menyajikan informasi dengan tampilan yang terorganisir dan terstruktur.

