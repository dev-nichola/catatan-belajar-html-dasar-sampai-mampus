# Input Color
Input type color adalah type untuk menerima input warna <br>
Warna di HTML akan ditulis dalam bentuk HEX Code <br>
Contohnya bisa kita lihat daftar hex codenya di : https://www.color.hex.com <br>

[!Color Hex](asset/color-hex.png) <br>

Pertanyaanya ialah kalau kita diminta memasukan nilai HEX Codenya itu akan sangat sulit, dikarenakan kita tidak mungkin hafal.<br>
Untungnya HTML punya Input Type <b>color<b>

### Kode : Input Color
```html
      <form>
            <label for="color">Warna</label>
            <input type="color" id="color" value="#ffffff">
            <input type="submit" value="Simpan">
      </form>
```