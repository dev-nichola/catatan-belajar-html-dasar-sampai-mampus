# Input Date Time

Jika untuk input tanggal bisa menggunakan type date, jika kita butuh samapi ke menit, kita bisa menggunakan Input Date Time, yaitu menggunakan type menggunankan <b>datetime-local</b> <br>
Format value untuk Date Time adalah yyyy-mm-ddThh:mm <br>
Dimana tanggal dan waktu dipisahkan oleh karakter <b>T</b> <br>
hh adalah jam dalam format 2 digit <br>
mm adalah menit dalam format 2 digit <br>
Untuk membatasi minimal dan maksimal waktu yang dipilih kita bisa gunakan min dan max <br>

### Kode : Input Date Time
```html
<form>
  <label for="jam_masuk">Jam Masuk</label>
  <input type="datetime-local" name="jam_masuk" id="jam_masuk" />
  <input type="submit" value="Submit" />
</form>
```
