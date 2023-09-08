# Input Week

Input type week digunakan untuk menerima input minggu dalam satu tahun <br>
Total minggu dalam satu tahun berkisar antara 52 - 53, artinya itu adalah maksimal nilai week dalam satu tahun <br>
Format penulisan week bisa menggunakan yyyy-Www <br>
yyyy adalah tahun dalam 4 digit <br>
ww adalah minggu dalam 2 digit <br>
Untuk membatasi minimal dan maksimal minggu yang dipilih, kita bisa gunakan atribut min dan max <br>

### Kode : Input Week

```html
<form>
  <label for="waktu-mulai">Waktu Mulai : </label> <br />
  <input type="week" name="waktu-mulai" id="waktu_mulai" value="2023-W01" />
  <br />

  <label for="waktu-selesai">Waktu Selesai : </label> <br />
  <input type="week" name="waktu-selesai" id="waktu-selesai" value="2023-W52" />
  <br />
  <input type="submit" value="Simpan" /> <br />
</form>
```
