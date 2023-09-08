# Label Tag

Saat kita membuat caption untuk input, direkomendasikan menggunakan Label dibanding menggunakan tag seperti span, p ataupun div <br>
Label tag bisa dikaitkan dengan input (bisa terhubung), sehingga ketika kita mengklik tulisan pada Label dan secara otomatis akan berpindah ke Input <br>
Selain itu, saat mengaktifkan Screen Reader, ketika kita mengklik Input, secara otomatis Label yang terasosiasi dengan Input Tersebut akan dibaca Oleh Screen Reader <br>
Label memiliki attribute "for" yang digunakan untuk menentukan <b>INPUT dengan ID</b> yang dipilih untuk diasosiasikan.

### Kode : Label Tag

```html
<form name="registrasi" action="form-submit.html" method="post">
  <label for="nama" id="nama" name="nama">Nama</label>
  <input type="text" name="nama" id="nama" />

  <label for="email" name="email" id="email">Email</label>
  <input type="text" name="email" id="email" />

  <label for="text" name="telephone" id="telephone">Telephone</label>
  <input type="text" name="telephone" id="telephone" />
</form>
```
