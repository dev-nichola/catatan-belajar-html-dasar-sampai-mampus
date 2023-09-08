# Select Tag

Select tag adalah alternatid lain seperti input type radio <br>
Saat menggunakan input type radio, jika opsi pilihan terlalu banyak, maka tampilan akan sangat panjang <br>
Select tag menawarkan solusi sederhana, dimana input akan seperti type text, namun kita bisa memilih opsi pilihan seperti radio type <br>

### Kode :: Select Tag

```html
<form>
  <label for="game">Game : </label>
  <select name="game" id="game">
    <option value="Genshin Impact" selected>Genshin Impact</option>
    <option value="Pubg">Pubg</option>
    <option value="Mobile Legends">Mobile Legends</option>
  </select>
  <button type="submit">Simpan</button>
</form>
```

Jadi mirip radio button tetapi tampilanya seperti `<input type="text">` biasanya

## Multiple

Salah satu kelebihan dibanding radio type, di dalam select tag, jika misal kita bisa memilih beberapa opsi pilihan seperti checkbox (maksudnya yang tampil itu lebih dari satu), kita bisa gunakan atribut multiple <br>
Untuk menentukan seberapa banyak data yang ditampilkan ketika menggunakan mode multiple, kita bisa gunakan atribut `size` <br>

### Kode : Multiple Select

```html
<form>
  <label for="game">Game : </label>
  <select name="game" id="game" multiple size="2">
    <option value="Genshin Impact" selected>Genshin Impact</option>
    <option value="Pubg">Pubg</option>
    <option value="Mobile Legends">Mobile Legends</option>
  </select>
  <button type="submit">Simpan</button>
</form>
```

Jadi dengan multiple kita bisa select lebih dari <b>Satu</b>

## Option Group Tag

Saat pilihan sangat banyak, kadang ada baiknya kita buat option dalam grup <br>
Hal ini akan membuat pengguna lebih mudah ketika melakukan pemilihan <br>
Kita bisa bungkus option dalam grup menggunakan optgroup tag <br>
Dan untuk menambahkan deskripsi gup, kita bisa gunakan atribut label<br>

### Kode : Option Group Tag

```html
<form>
  <label for="hobby">Hobby </label>
  <select name="hobby" id="hobby">
    <optgroup label="Coding">
      <option value="java">Java</option>
      <option value="javascript">JavaScript</option>
      <option value="php">PHP</option>
    </optgroup>
    <optgroup label="Gaming">
      <option value="genshin">Genshin Impact</option>
      <option value="zelda">Zelda</option>
      <option value="pokemon">Pokemon</option>
    </optgroup>
    <optgroup label="Sport">
      <option value="soccer">Soccer</option>
      <option value="badminton">Badminton</option>
      <option value="basket">Basket</option>
    </optgroup>
  </select>
  <button type="submit">Simpan</button>
</form>
```
