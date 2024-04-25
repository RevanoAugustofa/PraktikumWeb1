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
![image](https://github.com/RevanoAugustofa/Pemrograman-Web-1/assets/167878957/6b5aa2c5-7461-4b68-a414-a0966cc742d6)

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

![image](https://github.com/RevanoAugustofa/Pemrograman-Web-1/assets/167878957/aa73f637-9f25-4898-812c-011e2bcaa5dc)

### Browser web

Tujuan browser web (Chrome, Edge, Firefox, Safari) adalah untuk membaca dokumen HTML dan menampilkannya dengan benar.

Browser tidak menampilkan tag HTML, namun menggunakannya untuk menentukan cara menampilkan dokumen:

![image](https://github.com/RevanoAugustofa/Pemrograman-Web-1/assets/167878957/50d766e4-c44f-4e48-9c7d-7c540b26ad00)

### Struktur HTML

berikut adalah struktur dari HTML :

![image](https://github.com/RevanoAugustofa/Pemrograman-Web-1/assets/167878957/5815c769-e52c-487a-9f00-0701f4fbe7d9)

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

Paragraf didefinisikan dengan tag```<p> ```

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





## JavaScript

JavaScript adalah bahasa pemrograman yang digunakan untuk pengembangan website agar lebih dinamis dan interaktif. Website dinamis yang dimaksud berarti konten di dalamnya dapat bergerak atau mengubah apapun yang tampak di layar tanpa harus dimuat ulang secara manual. Misalnya seperti konten gambar animasi, maps, slideshow, polling, dan sebagainya.
