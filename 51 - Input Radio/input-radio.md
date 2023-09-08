# Input Radio

Input type radio merupakan input untuk informasi piliha <br>
Pada checkbox, kita bisa memilih lebih dari satu checkbox walaupun menggunakan name yang sama <br>
Sedangkan pada radio, kita hanya bisa memilih salah satu saja radio pada input name yang sama <br>
Input ini cocok untuk input data pilihan ganda misalnya <br>

### Kode : Input Radio

```html
<form>
  <p>Budi memiliki uang 10.000, dibelikan coklat 5.000, sisa uangya adalah</p>
  <input type="radio" name="jawaban" id="jawaban1" value="A" />
  <label for="jawaban1">4.500</label> <br />
  <input type="radio" name="jawaban" id="jawaban2" value="B" />
  <label for="jawaban2">5.000</label> <br />
  <input type="radio" name="jawaban" id="jawaban3" value="C" />
  <label for="jawaban3">5.500</label> <br />
  <input type="radio" name="jawaban" id="jawaban4" value="D" />
  <label for="jawaban4">6.000</label> <br />
  <input type="submit" value="Simpan" />
</form>
```
