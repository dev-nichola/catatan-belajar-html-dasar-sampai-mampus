#Picture
Selain untuk menampilkan gambar menggunakan tag img di HTML, kita bisa menggunakan picture untuk menampilkan gambar
Salah satu keuntungan menggunakan tag picture adalah, kita bisa menggunakan beberapa lokasi gambar, dan bisa diatur sesuai dengan ukuran layar.

## Picture Content
tag img adalah void element, sedangkan tag picture itu bukan, di dalam tag picture kita bisa menambahkan tag source yang berisi lokasi gambar dan tag img sebagai default gambar ketika semua kondisi tag soruce tidak terpenuhi

### Kode : Picture
```html
    <h2>Belajar Picture</h2>
    <picture>
        <source media="(max-widht: 500px)" srcset="img/image.jpg">
        <source media="(max-widht: 1000px)" srcset="img/image100.jpg">
    </picture>
```
## Media Query 
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
