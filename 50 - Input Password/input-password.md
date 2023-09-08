# Input Password

Input type password adalah input untuk informasi teks, sama seperti input type text namun pada input type password karakternya akan di masking (tidak ditampilkan) <br>
Input type password sangat cocok untuk input teks yang rahasia, sehingga tidak bisa diintip oleh orang lain <br>

### Kode : Input Password

```html
<form action="receive.html" method="post">
  <label for="email">Email</label>
  <input type="email" name="email" id="email" />
  <label for="password" id="password">Password</label>
  <input type="password" name="password" id="password" />
</form>
```

Khusus untuk password disarankan methodnya menggunakan "POST" walaupun bisa menggunakan "GET" juga namun kalau get akan tampil lewat Query Parameter jadi sangat disayangkan jika menggunakan input type password menggunakan method "GET" (Kelihatan Di URL)
