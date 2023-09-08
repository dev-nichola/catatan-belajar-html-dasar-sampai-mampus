# Input Hidden

Di HTML, terdapat fitur input type Hidden.<br>
Input type hidden artinya input datanya tidak terlihat oleh pengguna Web <br>
Biasanya input hidden memang tidak dimaksudkan untuk di input oleh pengguna, biasanya pada kasus kasus tertentu input data hidden digunakan untuk informasi yang dibuat secara otomatis oleh web kita, dan atau dilihan oleh pengguna<br>
Misal saat mengubah nama pengguna, kita mungkin harus tahu user_id dari pengguna namun kita tidak mau user_id bisa diubah oleh pengguna, kita bisa menggunakan input type hidden untuk user_idnya

### Kode : Input Hidden

```html
<form>
  <input type="hidden" name="user_id" value="nichola" />
  <label for="nama">Nama</label> <br />
  <input type="text" name="nama" id="nama" /> <br />
  <input type="submit" value="Simpan" />
</form>
```
