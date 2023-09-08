# Input Date

Input type date, adalah jenis input untuk menerima informasi berupa tanggal, tanggal yang dimaksud adalah kombinasi dari tahun, bulan dan tanggalnya <br>
jikalau kita ingin mengubah nilai value di input type date, kita bisa menggunakan format
`yyyy-mm-dd` <br>

- yyyy adalah tahun dalam 4 digit
- mm adalah bulan 2 digit
- dd adalah tanggal dalam 2 digit
  Untuk membatasi minimal dan maksimal tanggal yang dipilih, kita bisa gunakan attribute min dan max

### Kode : Input Date

```html
<form>
  <label for="join_date">Tanggal Masuk</label><br />
  <input type="date" name="join_date" id="join_date" /> <br>
  <input type="submit" value="Simpan">
</form>
```

### Kode : Input Date Dengan Atribut

```html
<form>
  <label for="join_date">Tanggal Masuk</label><br />
  <input type="date" name="join_date" id="join_date" />
</form>
```
