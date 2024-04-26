# Pemrograman Web 1
## HTML 
HTML, singkatan dari Hypertext Markup Language, merupakan bahasa pemrograman fundamental yang digunakan untuk menciptakan halaman situs web. Salah satu aspek penting dari HTML adalah penggunaan tag atau tanda, yang digunakan untuk menentukan struktur dan konten dari sebuah halaman web.

### Dokumen Html Sederhana
```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>Heading pertama ku</h1>
<p>paragraf kedua.</p>

</body>
</html>
```

dan kemudian hasilnya akan sebagai berikut :

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/2cba2cd4-d162-4225-836d-51aec35e7e4f)


1. Deklarasi tersebut ```<!DOCTYPE html>```mendefinisikan bahwa dokumen ini adalah dokumen HTML5

2. Elemen ```<html>```adalah elemen akar dari halaman HTML

3. Elemen tersebut ```<head>```berisi informasi meta tentang halaman HTML

4. Elemen ```<title>```menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul browser atau di tab halaman)

5. Elemen ```<body>```mendefinisikan badan dokumen, dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, hyperlink, tabel, daftar, dll.

6. Elemen ```<h1>``` mendefinisikan judul besar

7. Elemen ```<p>``` mendefinisikan paragraf

### HTML Elemen
apa itu elemen? dan apa itu tag pada elemen?  
Tag adalah penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung sudut ```<...>```.
Elemen adalah gabungan dari tag pembuka, konten, dan tag penutup yang membentuk sebuah unit dalam halaman web.

Elemen HTML ditentukan oleh tag awal, beberapa konten, dan tag akhir:

```<html>       </html>```

contoh lainnya:

```<h1> Heading </h1>​​```

```< p > Paragraf < /p >```

hasil outputnya:

![Cuplikan layar 2024-04-25 160053](https://github.com/RevanoAugustofa/Web1/assets/167878957/29b511af-82aa-47c5-850e-37a45785ee16)


### Browser web

Tujuan browser web (Chrome, Edge, Firefox, Safari) adalah untuk membaca dokumen HTML dan menampilkannya dengan benar.

Browser tidak menampilkan tag HTML, namun menggunakannya untuk menentukan cara menampilkan dokumen:

![Cuplikan layar 2024-04-25 160543](https://github.com/RevanoAugustofa/Web1/assets/167878957/dbfdcd5a-a7f9-455d-9197-59d11040b3e9)


### Struktur HTML

berikut adalah struktur dari HTML :

![Cuplikan layar 2024-04-25 160756](https://github.com/RevanoAugustofa/Web1/assets/167878957/5819e786-2d91-4308-a981-060032c65719)


### Heading

pada html terdapat heading atau bisa disebut dengan judul ditentukan dengan tag ``` <h1> </h1>``` sampai ```<h6> </h6>``` dimana semakin kecil angka maka akan semakin besar tulisan yang akan ditampilkan. Contohnya 

```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>


</body>
</html>
```

hasilnya akan seperti ini:

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/9afb72a4-88e3-4c18-b265-f38ed9d0012c)

### Paragraf

Paragraf didefinisikan dengan tag```<p>  </p> ```

```
<!DOCTYPE html>
<html>
<body>

<p>Ini paragraf.</p>
<p>ini paragraf lainnya.</p>

</body>
</html>
```

hasilnya akan seperti ini:

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/0dfd7332-f1c5-4b04-9302-fc93f8298fa2)

### Link/ Tautan

Tautan didefinikan dengan tag: ```<a>```

```
<!DOCTYPE html>
<html>
<body>

<h2>HTML Links</h2>
<p>HTML link didefinisikan dengan tag a </p>

<a href="https://www.w3schools.com">ini sebuah link</a>

</body>
</html>

```

hasilnya akan seperti ini:

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/e48ada9a-9acd-412a-87a5-9bb679d0c5d0)

### Gambar

Gambar HTML ditentukan dengan tag```<img>```. File sumber ```(src)```, teks alternatif ```(alt)```, width/ lebar, dan height/tinggi disediakan sebagai atribut.

```
<!DOCTYPE html>
<html>
<body>

<h2>HTML Images</h2>
<p>HTML gambar didefinisikan dengan tag img </p>

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYq9WB6Y_Ec5kLryZhfKNF84geLC9zbaUMzA&s" alt="google.com" width="200" height="142">

</body>
</html>
```

hasilnya akan seperti ini:

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/34413b5f-c36a-4046-8351-308b634eafb5)

## CSS

CSS (Cascading Style Sheet) digunakan bersama dengan bahasa markup, seperti HTML dan XML, untuk membangun sebuah website yang menarik dan memiliki fungsi yang berjalan baik.
Dengan CSS, Anda bisa mengatur tampilan elemen-elemen di halaman web, seperti mengubah warna teks, mengatur posisi, dan mengatur layout.
CSS membantu memisahkan antara struktur konten (HTML) dan tampilan (CSS) pada halaman web.

CSS dapat ditambahkan ke dokumen HTML dengan 3 cara:

1. Inline - dengan menggunakan ```style```atribut di dalam elemen HTML
2. Internal - dengan menggunakan ```<style>```elemen di <head>bagian tersebut
3. Eksternal - dengan menggunakan ```<link>``` elemen untuk menautkan ke file CSS eksternal

   contoh penggunaan css inline:
 ```
   <!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;">Heading Berwarna Biru dengan css inline</h1>

<p style="color:red;">paragraf berwarna merah.</p>

</body>
</html>

 ```
![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/1d6f9103-d6a2-4daf-b58d-d9cdd8be13a9)

conoth penggunaan css internal:

```
<!DOCTYPE html>
<html>
<head>

<style>
	h1 {color: blue;}
	p  {color: red;}
</style>

</head>
<body>

<h1> heading berwarna biru menggunakan css internal</h1>
<p> paragraf berwarna merah.</p>

</body>
</html>

```
![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/7d340b45-89cf-4c2a-9d26-9a84e16f91a1)

contoh penggunaan css eksternal:

simpan file dengan format ```.html``` 
```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>hai ini heading</h1>
<p>ini paragraf.</p>

</body>
</html>

```

simpan file dengan format ```.css```
```
body{
    background-color: bisque;
}

h1{
    color: blueviolet;
}
p{
    color: rgb(0, 59, 111);
}
```
![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/50ef91e8-a51e-4662-bbc1-4fc5d64d60e2)



### Colors, Fonts dan Sizes

1. ```color``` mendefinisikan warna teks yang akan digunakan.
2. ```font-family```mendefinisikan font yang akan digunakan.
3. ```font-size```menentukan ukuran teks yang akan digunakan.
```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: lightgrey;
  font-family: verdana;
  font-size: 300%;
 

}
p  {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>hai ini heading</h1>
<p>ini juga paragraf.</p>

</body>
</html>

```

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/aa03055b-aa3f-438e-8b74-e7c7984b1f67)

### Border

```
<!DOCTYPE html>
<html>
<head>
<style>
p {
  border: 2px solid powderblue;
}
.form{
	border: 3px solid red;
}
</style>
</head>
<body>
<form class="form">
<h1>Judul</h1>


<p>Halo aku revano.</p>
<p>Halo aku revano.</p>
<p>Halo aku revano.</p>

</form>

</body>
</html>

```
![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/e6d35a18-6b14-4326-b0de-71477d21fd31)

style ```p``` untuk mengedit semua tag yang berelemenkan ```<p>```. style```.form``` digunakan untuk mengedit pada bagian ```<form>``` dan semua jenis elemen yg didalamnya

### Margin, padding dan background color

1. Margin fungsinya mengatur jarak antara satu elemen dengan elemen lainnya pada HTML
2. Padding merupakan sebutan untuk spasi atau ruang di dalam tag HTML
3. background color digunakan untuk memberikan warna pada background html
```
<!DOCTYPE html>
<html>
<head>
</head>
<style>
    .margin{
        margin: 20px;
    }
    
</style>
<body>
    <div class="margin">
        <h3 style="background-color: greenyellow; padding: 20px;">Padding 4 Sisi Sekaligus</h3>
    <h3 style="background-color: rgb(125, 4, 0); padding: 50px 100px;">Padding 2 Sisi</h3>
    </div>
    
    <h3 style="background-color: rgb(7, 163, 187); padding: 10px 100px 50px;">Padding 3 Sisi</h3>
    <h3 style="background-color: rgb(97, 156, 8); padding: 5px 50px 10px 60px;">Padding 4 Sisi berbeda</h3>

    <div>
        
    </div>
    
</body>
</html>

```

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/4a8df2fe-793a-4cdc-a6b4-1afa2ac72b2d)

## JavaScript

JavaScript adalah bahasa pemrograman yang digunakan untuk pengembangan website agar lebih dinamis dan interaktif. Website dinamis yang dimaksud berarti konten di dalamnya dapat bergerak atau mengubah apapun yang tampak di layar tanpa harus dimuat ulang secara manual. Misalnya seperti konten gambar animasi, maps, slideshow, polling, dan sebagainya.

### Tag HTML ```<script>```

digunakan untuk mendefinisikan skrip sisi klien (JavaScript).Elemen tersebut ```<script>```berisi pernyataan skrip, atau menunjuk ke file skrip eksternal melalui srcatribut.Kegunaan umum JavaScript adalah manipulasi gambar, validasi formulir, dan perubahan konten dinamis.Untuk memilih elemen HTML, JavaScript paling sering menggunakan metode ```document.getElementById()```.

Contoh JavaScript ini menulis "Halo JavaScript!" menjadi elemen HTML dengan ```id="demo"```:

```
<!DOCTYPE html>
<html>
<body>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script> 

</body>
</html>

```

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/58a52993-21ea-4c1d-83a0-d03602dfef44)




# <i>challenge CSS 4</i> 

ketentuan:

1. Warna border adalah yellowgreen
2. Gunakan tranformasi teks uppercase pada heading
3. Paragraf utama menggunaka indentasi dan rata kanan kiri
4. Gunakan letter-spacing pada paragraf utama
5. Warna teks hyperlink adalah #008CBA
6. Pada saat link di klik maka akan membuka halaman https://elearning.pnc.ac.id/ pada Tab baru

### HTML

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/1248e376-ba3e-472d-b9ef-1567f4f37f03)

hasilnya akan seperti ini jika belum memakai css:

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/3e70234e-296b-45d3-a31e-5649a45226c1)

### CSS

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/71182ab5-3e9e-42f8-aa93-6473d88c2984)

ketika menambahkan style css maka hasilnya akan seperti berikut

![image](https://github.com/RevanoAugustofa/Web1/assets/167878957/58e755bb-fe2a-401b-a264-9712221b601f)

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS 3</title>
</head>
<style>
    div {
        border: 5px solid yellowgreen;
        margin: auto;
        width: 35%;
    }

    h2 {
        color: darkred;
        text-align: center;
        text-transform: uppercase;
    }

    .a {
        letter-spacing: 2px;
        text-indent: 15%;
        text-align: justify;
        padding-left: 2%;
        padding-right: 2%;
    }

    a {
        text-decoration: none;
        color: #008CBA;
    }
</style>
<body>
    <div>
        <h2>praktikum pemrograman web</h2>
    <p class="a">
        Praktikum Keterampilan kepada mahasiswa dalam pembuatas situs web yang dinamis dan dapat berinteraksi dengan user Materi meliputi Teknologi Web,Pemrograman situs 
        HTML, CSS, PHP, MySQL dan Visual Studio Code. <a target="_blank" href="https://elearning.pnc.ac.id/">"E-Learning"</a> link
    </p>
</div>
        <h4>Keterangan:</h4>
        <ol>
            <li>Warna border adalah <b>yellowgreen</b></li>
            <li>Gunakan tranformasi teks <b>uppercase</b> pada heading</li>
            <li>Paragraf utama menggunaka <b>indentasi</b> dan rata kanan kiri</li>
            <li>Gunakan <b>letter-spacing</b> pada paragraf utama</li>
            <li>Warna teks hyperlink adalah <b>#008CBA</b></li>
            <li>Pada saat link di klik maka akan membuka halaman <b>https://elearning.pnc.ac.id/</b> pada Tab baru</li>
        </ol>
</body>
</html>
```

```text-decoration: none;``` digunakan untuk menghapus dekorasi pada pada style ```a```.

```text-indent: 15%;```  pada style ```.a``` digunakan untuk membuat suatu kalimat atau paragraf menjorok

```letter-spacing: 2px;``` pada style```.a``` digunakan untuk memberikan jarak pada suatu kalimat atau paragraf tertentu

``` text-transform: uppercase;``` pada style ```h2``` digunakan untuk menjadikan semua huruf menjadi kapital

```border: 5px solid yellowgreen;``` pada style ```div``` digunakan untuk membuat border dengan ketebalan ```5px``` dengan warna ```yellowgreen```





