# Field Set Tag

Tag fieldset digunakan untuk membungkus / grouping beberapa input sehingga mudah untuk dimengerti ketika dilihan oleh pengguna <br>
menggunakan fieldset tag sangat baik ketika misal input data sangat banya, dan kita ingin melakukan grouping input data yang sesuai <br>
Contoh ketika registrasi, dibutuhkan identitas, alamat dan lain lain, kita bisa grouping sesuai input datanya <br>

## Legend Tag

Selain itu saat kita menggunaakn fieldset tag, biasanya kita akan menambahkan informasi berupa deskripsi group<br>
Untuk menambahkan informasi itu, kita bisa menggunakan legend tag <br>

### Kode : Field Set Tag

```html
<form>
  <fieldset>
    <legend>Identitas</legend>
    <label for="nama">Nama : </label>
    <input type="text" name="nama" id="nama" />

    <label for="email">Email : </label>
    <input type="email" name="email" id="email" />

    <label for="telepon">Telepon : </label>
    <input type="telepon" name="telepon" id="telepon" />
  </fieldset>

  <fieldset>
    <legend>Alamat</legend>
    <label for="jalan">Jalan : </label>
    <input type="text" name="jalan" id="jalan" />

    <label for="kota">Kota : </label>
    <input type="text" name="kota" id="kota" />

    <label for="provinsi">Provisinsi</label>
    <input type="text" name="provinsi" id="provisinsi" />
  </fieldset>

  <button type="submit">Simpan</button>
</form>
```
