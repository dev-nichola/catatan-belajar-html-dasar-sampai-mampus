# Semantic

Semantic element adalah element yang memiliki arti <br>
Sebelum di HTML 5, setiap kita ingin membuat layout di html, kita biasanya hanya menggunakan div dan span saja <br>
Di HTML 5 terdapat tag tag seperti div namun lebih memiliki arti <br>
Oleh karena itu, kita di rekomendasikan menggunakan semantic tag agar kode di HTML yang kita buat lebih mudah untuk dibaca dan dimengerti <br>

## Semantic Tag

- article untuk konten artikel
- aside untuk sidebar atau konten yang berada di samping
- figure untuk konten ilustrasi, diagram, foto, dan lain lain
- figurecaption untuk keterangan tag figure
- footen untuk bagian footer
- header untuk header
- main untuk konten utama
- mark untuk bagian yang di tandai atau highlight
- nav untuk bagian navigasi link
- section untuk spesifik bagian
- detail untuk bagian detail yang bisa pengguna lihat
- summary untuk heading tag detail
- time untuk konten waktu/tanggal

### Kode : Semantic

```html
<header>
  <h1>Belajar Semantic HTML</h1>
</header>
<nav>
  <ul>
    <li><a href="#">Beranda</a></li>
    <li><a href="#article">Artikel</a></li>
    <li><a href="#">Kontak Kami</a></li>
  </ul>
</nav>

<hr/>
<h1>Bagian Artikel</h1>
<section id="article">
  <article>
    <h1>Belajar HTML</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, dicta.
    </p>
  </article>
  <article>
    <h1>Belajar HTML</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, dicta.
    </p>
  </article>
  <article>
    <h1>Belajar HTML</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, dicta.
    </p>
  </article>
</section>
<footer>
  <p>Created By Nichola Saputra <time datetime="2023">2023</time></p>
</footer>
```
