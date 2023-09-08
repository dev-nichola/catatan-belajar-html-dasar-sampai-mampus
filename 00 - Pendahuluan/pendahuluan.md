# Pendahuluan

HTML atau HyperText Markup Language merupakan sebuah bahasa markah untuk membuat halaman web <br>
Jadi, HTML itu adalah sebuah bahasa yang menggunakan markup atau penanda untuk membuat halaman web.<br>
Penanda atau markup ini, nanti akan kita sebut dengan Tag<br>
HTML berperan untuk menentukan struktur konten dan tampilan dari sebuah web. <br>
HTML itu seperti batu bata untuk membangun rumah. Batu bata ini dapat disusun, hingga menjadi fondasi dasar <br>
![analogi](asset/html-css-js.png)
Dalam membuat halaman web, HTML tidak sendirian. Ada bahasa lain lagi yang menjadi pelengkapnya, yakni CSS dan Javascript<br>
CSS adalah bahasa khusus yang digunakan untuk memperindah tampilan web<br>
Lalu Javascript bertugas untuk membuat halaman web menjadi hidup. Karena dengan Javascript, kita dapat menentukan fungsi-fungsi maupun efek yang akan diterapkan di website<br>

## Sejarah Singkat

HTML diciptakan oleh Sir Tim Berners-lee pada akhir tahun 1991 namun tidak dirilis secara resmi. Sir Tim Berners-lee merilis HTML versi pertama pada tahun 1993 dengan tujuan untuk berbagi informasi yang dapat dibaca dan diakses melalui web browser <br>
Pada akhir tahun 1991, Tim Berners-Lee menerbitkan dokumen yang berjudul: “HTML Tags”, Dokumen ini berisi penjelasan tentang 18 tags awal yang menjadi konsep dasar HTML<br>

## Peralatan yang dibutuhkan

- Text Editor (Direkomendasikan Vscode)
- Web Browser Untuk Membuka HTML

## Ekstensi file HTML

Setiap file HTML harus berekstensi .html, .xhtml (untuk XHTML), dan .htm saja. Jika tidak menggunakan ekstensi ini, maka ia tidak akan bisa dibaca oleh web browser<br>

## Nama Khusus Untuk Homepage

Jika kamu ingin membuat halaman untuk homepage, maka sebaiknya gunakan nama index.html. Karena ia akan otomatis dibuka saat website dikunjungi.

Contohnya, saat kamu membuka www.petanikode.com.. maka file HTML yang akan dibuka adalah index.html yang berada di server petanikode <br>

## Struktur Dasar HTML

- Bagian Deklarasi
  <!DOCTYPE html <br>
  Ini adalah tag deklarasi untuk menyatakan tipe dokumen dan versinya. Pada contoh di atas, kita menyatakan dokumen ini bertipe HTML dan versinya adalah HTML 5<br>

<b>Tag Pembukan</b>

<html lang="en">
Pada tag ini, kita memberikan atribut lang="en" untuk menyatakan kalau konten dokumen HTML ini akan menggunakan bahasa inggris <br> 
di dalam tag <html> ini, terdapat dua tag penting lagi.. yakni: tag <head> dan tag <body>. <br>

Setelah itu yang terakhir tag HTML ditutup dengan </html>

## Bagian Head

Bagian HEAD adalah bagian kepala dari HTML. Dimulai dari tag <head> dan ditutup dengan </head>. <br>

```html
      <!DOCTYPE html>
<html lang="en">
    <head>
        <title>Belajar HTML #01</title>
    </head>
    <body>
        <p>Hello World!</p>
    </body>
</html
```

Pada bagian HEAD, biasanya digunakan untuk menuliskan tag-tag yang akan dibaca oleh mesin. <br>

Seperti:

- Tag meta untuk SEO;
- Tag <title> untuk judul;
- Tempat menulis kode CSS dan Javascript;
  dan lain-lain.

## Bagian Body

Bagian BODY adalah bagian yang akan ditampilkan pada web browser. Penulisannya di mulai dari tag <body> dan ditutup dengan </body>.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Belajar HTML #01</title>
  </head>
  <body>
    <p>Hello World!</p>
  </body>
</html>
```

Di sinilah nanti kita akan banyak menuliskan konten dengan berbagai macam tag. Saat ini kita baru mengisinya dengan tag <p>. Tag <p> adalah tag yang digunakan untuk membuat paragraf. <br>

## Tag HTML
Tag adalah sebuah penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung siku ```(<...>)```
, lalu di dalamnya berisi nama tag dan kadang juga ditambahkan dengan atribut <br>
Tag selalu ditulis berpasangan. Ada tag pembuka dan ada tag penutupnya. Namun, ada juga beberapa tag yang tidak memiliki pasangan penutup. Tag penutup ditulis dengan menambahkan garis miring (/) di depan nama tag <br>
Setiap tag memiliki fungsi masing-masing. Ada yang digunakan untuk membuat judul, membuat link, membuat paragraf, heading, dan lain-lain <br>

## Element HTML
Elemen dalam HTML adalah sebuah komponen yang menyusun dokumen HTML. Elemen kadang juga disebut sebagai node, karena ia merupakan salah satu jenis node yang menyusun dokumen HTML dalam diagram HTML tree. <br>
[Element](asset/pohon-html.gif)
Pada diagram tersebut, terdapat tiga macam node.. yakni: Node elemen, Node atribut, dan Node teks <br>
Elemen dibentuk dari tag pembuka, isi tag, dan tag penutup. Kadang juga ditambahkan beberapa atribut <br>

Contoh : 
[Elementt](asset/element.png)
Pada contoh di atas, terdapat satu elemen <p> dengan atribut align="center" dan memiliki isi berupa teks, yakni Hello World!. <br>
Elemen tidak selalu berisi teks, kadan ia juga akan berisi elemen lain. Ini biasanya kita sebut dengan nested element atau elemen di dalam elemen. <br>
Elemen HTML ada banyak jenisnya. Ada elemen khusus untuk teks, ada elemen untuk multimedia, script, tabel, metadata, dll. Nanti kita akan pelajari ini secara bertahap <br>

## Atribut HTML
Atribut adalah kata kunci khusus yang berada di dalam tag pembuka. Atribut juga disebut sebagai modifier yang akan menentukan perliaku dari elemen. <br>
[atribut](asset/atribut.png)
Atribut dapat ditambahkan pada elemen manapun. Ada juga elemen yang mewajibkan menggunakan atribut seperti elemen <a>, <img>, <video>, dll. <br>
Jumlah atribut pada elemen bisa lebih dari satu. <br>

### Jenis Jenis Atribut
Tiap-tiap elemen kadang memiliki atribut khusus yang hanya bisa digunakan pada elemen tersebut. Ada juga atribut yang bersifat global dan bisa ditambahkan ke semua elemen. <br>
Berikut ini jenis-jenis atribut yang harus diketahui: <br>
- Atribut Global
- Atribut Event
- Atribut Khusus

Source : [Petani Kode](https://www.petanikode.com/html-tag-elemen-atribut/) 



