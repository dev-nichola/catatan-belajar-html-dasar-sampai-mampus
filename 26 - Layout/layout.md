# Layout
Salah satu kegunaan ketika menggunakan Semantic Element adalah, mudah membuat layout <br>
Hal ini karena kita bisa tau bagian bagian tag nya yang memiliki arti <br>
Misal kita gunakan kode pada catatan semantic HTML

Kode : Layout 
```html
      <!DOCTYPE html>
<html lang="en">
<head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Semantic | HTML</title>
</head>
<body>
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

      <hr>
      <h1>Bagian Artikel</h1>
      <section id="article">
            <article>
                  <h1>Belajar HTML</h1>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, dicta.</p>
            </article>
            <article>
                  <h1>Belajar HTML</h1>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, dicta.</p>
            </article>
            <article>
                  <h1>Belajar HTML</h1>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, dicta.</p>
            </article>
      </section>
      <footer>
            <p>Created By Nichola Saputra <time datetime="2023">2023</time></p>
      </footer>
</body>
</html>
```

### Kode : CSS Layout
```css
      header {
      background-color: gray;
      padding: 30px;
      text-align: center;
      font-size: 35px;
      color: whitesmoke;
}

article {
      padding: 20px;
      width: 100%;
      background-color: #f1f1f1;
}

footer {
      background-color: gray;
      padding: 10px;
      text-align: center;
      color: white;
}

nav {
      background-color: yellow;
      padding: 20px;
}

nav ul {
      list-style-type: none;
      padding: 10px;
      align-items: center;
}

nav li {
      float: center;
}

nav li a {
      display: block;
      text-align: center;
      padding: 16px;
      text-decoration: none;
}

nav li a:hover {
      background-color: orange;
}
```