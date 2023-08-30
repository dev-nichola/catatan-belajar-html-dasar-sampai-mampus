# Responsive

Kita tau bahwa ukuran layar komputer itu berbeda beda <br>
Saat ini, web tidak hanya bisa diakses oleh komputer saja, bisa juga menggunakan smartphone tablet bahkan smart tv <br>
Artinya ukuran layarnya pasti berbeda beda <br>
Web Sekarang biasanya selalu implementasi responsive, agar tidak membuat banyak jenis web dengan layar yang berbeda beda <br>

## Viewport

Jadi sebelumnya di html 5, kita melakukan setting `html <meta name="viewport" content="width=device-width, initial-scale=1.0">` dengan initial-scale=1.0 <br>
Hal itu dilakukan agar ketika aweb diakses di mobile, ukuran web kita bisa mengikuti ukuran devicenya <br>
tiap handphone walaupun ukuran layarnya misal 6inch tapi secara pixel bisa berbeda, oleh karena itu ketika kita buat website dengan ukuran 100px misalnya, di handphone dengan kepadatan pixel yang besar, bisa jadi ukurannya sangat kecil, dan pada handphone dengan kepadatan pixel rendah, bisa sangat besar<br>
maka dari itu viewport bisa mengubahnya dengan mapping atau memetakan secara otomatis

## Responsive Element Size

Saat kita membuat web kadang kadang kita menentukan ukuran element, misal gambar, table, div dan lain-lain <br>
jika ingin responsive kita bisa menggunakan % sebagai ukuran elemennya, misal ketika kita gunakan nilai 100% artinya ukuran 100% dari <b>viewport</b> atau yang tampil di Web Browser, ketika kita mengubah ukuran Web Browser, secara otomatis element akan ikut berubah ukuranya

### Kode : Responsive Size

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive | HTML</title>
  </head>
  <body>
    <h1>Belajar Responsive</h1>
    <p>Belajar Responsive</p>
    <img
      src="img/image.jpg"
      alt="Nichola Saputra"
      style="width: 100%; height: auto;"
    />
  </body>
</html>
```

## Responsive Text Size

Responsive dengan % hanya bisa dilakukan di element contohnya seperti hanya bisa dilakukan di gambar, div dan lain lain <br>
Bagaimana jika pada kasusk teks misalnya?, kadang kita ingin membesarkan teks secara otomatis pada layar besar dan mengecilkan pada layar yang kecil <br>
pada kasus seperti ini kita bisa menggunakan unit vm(viewport width) untuk ukuran font <br>

### Kode : Responsive Text Size

```html
<h1 style="font-size: 5vw;">Belajar Text Responsive</h1>
<p style="font-size: 3vw;">Belajar Text Responsive</p>
```
## Media Query
Pada kasus seperti gambar, mungkin ketika layar terlalu besar dan ukuran gambar kecil, secara otomatis gambar akan pecah, oleh karena itu pada kasus seperti ini kita akan menyedikaan beberapa ukuran gambar <br>
dan untuk melakukanya kita bisa menggunakan CSS Media Query
