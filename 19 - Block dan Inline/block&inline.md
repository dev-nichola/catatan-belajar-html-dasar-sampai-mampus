# Block dan Inline
Di dalam html semua element memiliki nilai display, tergantung dari jenis element yang digunakan
Secara garis besar ada dua nilai untuk display, yang pertama namanya block block dan yang kedua adalah inline inline

## Block
Element yang memiliki nilai display block selalu di mulai dengna baris baru atau istilahnya enter,
Web browser secara otomatis menambahkan jarak / margin sebelum dan setelah element.
Dan element dengan nilai display block, selalu mengambil ukuran penuh yang tersedia, yang artinya dia akan meregang dari kiri ke kanan secara otomatis.
Contoh tag yang menggunakan nilai block adalah : 
h1-h6, header,body, ul, li, ol,table, form,dan lain lain

## Inline
Sedangkan dalam display inline, element tidak dimulai dengan baris baru, Selain itu dalam display inline, element hanya menggunakan ukuran seperlunya saja 
Contoh tag yang menggunakan display inline : 
a, b, i, em, button, strong, input, dll

## Div
Div adalah salah satu tag di HTML yang memiliki nilai display block, Div biasanta digunakan sebagai container atau wadah untuk beberapa elemen HTML, misal ada bagian menu,content,footer, header dan lain-lain.
Biasanya itu semua dibungkus dalam Div

### Kode Div
```html
    <h1>Belajar Div</h1>
    <div id="menu" style="background-color: yellow;">
        <ul>
            <li>Beranda</li>
            <li>Artikel</li>
            <li>Media Sosial</li>
        </ul>
    </div>

    <div id="content" style="background-color: pink;">
            <h1>Judul Halaman</h1>
            <p>Isi Halaman</p>
    </div>
```