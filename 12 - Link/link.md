# Link
Saat membuat Web, biasanya kita akan membuat banyak sekali halaman HTML, namun untuk berpindah dari satu halaman ke halaman lainya kita biasanya jarang melakukanya dengan manual dengan cara mengetikkanya di search bar Web Browser.
HTML memiliki fitur link yang dimana kita dapat berpindah ke halaman lainya
Link tidak harus berbentuk text, link juga bisa dalam bentuk gambar

## Tag a
untuk membuat link di html, kita bisa menggunakan tag a
Isi konten tag a adalah isi dari tampilan Link, bisa teks atau yang lainya, 
tag a memiliki attribute href, yang berisi lokasi tujuan Link tersebut. 
tag a juga memiliki attribute target, yang digunakan sebagai target jendela Web Browser.
kita bisa menggunakan nilai : 
- target="self" artinya halaman akan di tampilkan di halaman yang sama. ini adalah bawaan default.
- target="blank" artinya halaman akan di tampilkan di jendela baru di browser
tag a juga memiliki attribute title, untuk menuliskan judul yang keluar ketka mouse berada di atas Link tersebut.

### Kode : Link
```html 
    <h1>Belajar Link</h1>
    <ul>
        <li><a href="https://facebook.com/" target="_blank">Facebook</a></li>
        <li><a href="https://youtube.com/" target="_blank" title="Youtube">Youtube</a></li>
        <li><a href="https://google.com" target="_blank">Google</a></li>
    </ul>
```

## Absolute URL 
Saaat kita menulis halaman tujuan dari href di Link, kita bisa menggunakan absolute URL
absolue URL merupakan alamat lengkap sebuah tujuan link
dalam absolute link URL, kita wajib menuliskan seluruh detail domain dan halaman yang dituju, misal : 
- https://youtube.com/
- https://facebook.com/
- https://google.com/
kelebihan menggunakan absolute URL adalah, kita bisa membuat Link menuju domain yang berbeda dengan website yang kita buat

tapi ya seringnya kita membuat url di domain kita sendiri maka kita perlu yang namanya relative url

## Relative URL
Relative url adalah lokasi href dimana tetap menggunakan domain website saat ini.
Relative URL memiliki dua format, bisa diawali dengan /, atau tidak diawali dengan /
Misal sekarang kita berada di halaman http://127.0.0.1/link/index.html, lalu kita memliki link sebagai berikut: 
- hello.html artinya akan menuju ke http://127.0.0.1/link/hello-html
- hello.html artinya akan menuju ke http://127.0.0.1/hello.html
- nichola/hello.html artinya akan menuju ke http:127.0.0.1/link/nichola/hello.html

Saranya adalah kalau kita ingin membuat relative URL selalu menggunakana / di depanya

### Kode : Relative URL
```html
<h1>Relative URL</h1>
    <ul>
        <li><a href="link/hello.html">hello.html</a></li>
        <li><a href="link/nichola/index.html">index.html</a></li>
        <li><a href="/03 - Heading/heading/heading.html">heading.html</a></li>
    </ul>
```
## Bookmark
Pada kasus halaman web yang sangat panjang, ada bagusnya kita menggunakan Bookmark. 
Bookmark adalah link yang bisa digunakan untuk menampilkan HTML, element dengan id tertentu.
Bookmark menggunakan # pada href, misal jika kita menggunakan index.html#nichola, artinya ketika membuka halaman index.html maka Web Browser akan otomatis menampilkan pada posisi HTML element dengan id nichola.
jika kita ingin membuat link di halaman html itu sendiri, kita bisa langsung buat link dengan href langsung berisi #bookmark nya.

### Kode : Bookmark di Halaman Sendiri
```html
<h2>Daftar Isi</h2>
    <ul>
        <li><a href="#judul1">Judul 1</a></li>
        <li><a href="#judul2">Judul 2</a></li>
        <li><a href="#judul3">Judul 3</a></li>
    </ul>

    <h2 id="judul1">Judul 1</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis quod facilis natus suscipit expedita unde eveniet eaque soluta voluptate asperiores at et laborum deleniti, laudantium maiores nemo quidem? Voluptatem odio eaque modi labore? Culpa eaque facilis alias sed molestiae veritatis asperiores consequuntur magnam explicabo, ducimus animi pariatur officiis voluptate aut. Labore rem dolorum quam eaque? Ratione, alias ipsam, perferendis non unde, perspiciatis labore reiciendis aliquid culpa praesentium quos molestias illum aliquam blanditiis sed corrupti pariatur nostrum repellat qui sequi ipsum facilis. Laboriosam, est, possimus optio id temporibus nam eveniet praesentium omnis ex quasi vero dolorum itaque corrupti nemo suscipit iste!</p>

    <h2 id="judul2">Judul 2</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis quod facilis natus suscipit expedita unde eveniet eaque soluta voluptate asperiores at et laborum deleniti, laudantium maiores nemo quidem? Voluptatem odio eaque modi labore? Culpa eaque facilis alias sed molestiae veritatis asperiores consequuntur magnam explicabo, ducimus animi pariatur officiis voluptate aut. Labore rem dolorum quam eaque? Ratione, alias ipsam, perferendis non unde, perspiciatis labore reiciendis aliquid culpa praesentium quos molestias illum aliquam blanditiis sed corrupti pariatur nostrum repellat qui sequi ipsum facilis. Laboriosam, est, possimus optio id temporibus nam eveniet praesentium omnis ex quasi vero dolorum itaque corrupti nemo suscipit iste!</p>

    <h2 id="judul3">Judul 3</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis quod facilis natus suscipit expedita unde eveniet eaque soluta voluptate asperiores at et laborum deleniti, laudantium maiores nemo quidem? Voluptatem odio eaque modi labore? Culpa eaque facilis alias sed molestiae veritatis asperiores consequuntur magnam explicabo, ducimus animi pariatur officiis voluptate aut. Labore rem dolorum quam eaque? Ratione, alias ipsam, perferendis non unde, perspiciatis labore reiciendis aliquid culpa praesentium quos molestias illum aliquam blanditiis sed corrupti pariatur nostrum repellat qui sequi ipsum facilis. Laboriosam, est, possimus optio id temporibus nam eveniet praesentium omnis ex quasi vero dolorum itaque corrupti nemo suscipit iste!</p>
```

### Kode : Bookmark ke Halaman Lain
```html
     <h1>Daftar Isi</h1>
    <ul>
        <li><a href="bookmark.html#judul1"></a>Judul 1</li>
        <li><a href="bookmark.html#judul2"></a>Judul 2</li>
        <li><a href="bookmark.html#judul3">Judul 3</a></li>
    </ul>
```