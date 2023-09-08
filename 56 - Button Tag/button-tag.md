# Button Tag

Button tag adalah tag yang bisa kita gunakan untuk membuat tombol <br>
lalu apa bedanya dengan input type button<br>
Karena button tag memiliki content di dalam tagnya, jadi kita bisa dengan bebas menambahkan isi dari button, misal text atau gambar <br>
Jadi menggunakan button tag akan lebih flexibel dibanding menggunakan input type button <br>
Button juga memiliki attribute type, yang bisa kita gunakan untuk mengubah jenis tipe button, dari mulai button(biasa), reset dan submit <br>
Selain itu secara semantic lebih bagus karena lebih merepresentasikan <br>

### Kode : Button Tag

```html
<form>
  <label for="name">Nama : </label>
  <input type="text" /> <br />
  <button type="button">
    <img
      src="https://interactive-examples.mdn.mozilla.net/media/examples/login-button.png"
    />
  </button>
  <button type="reset">Reset</button>
  <button type="submit">Submit</button>
</form>
```
