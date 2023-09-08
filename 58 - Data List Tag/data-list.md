# Data List Tag

Saat melakukan pencarian di Google misalnya, kita sering melihat rekomendasi berupa autocomplete kata-kata yang ingin kita cari<br>
Saat kita membuat input type text, kita bisa menambahkan sumber data yang bisa dijadikan sebagai rekomendasi input valuenya, juga autocompletenya<br>
kita bisa menggunakan datalist tag,nah di dalam datalist tag kita bisa gunakan option tag dimana tag ini akan berisi nilai / pilihan autocompletenya <br>
Untuk menghubungkan dari input type text ke datalist, kita bisa menggunakan atribut list yang mengacu ke id datalist <br>

### Kode : Data List Tag

```html
<form>
  <label for="hobby">Hobby : </label>
  <input type="text" name="hobby" id="hobby" list="hobbies" />
  <button type="submit">Simpan</button>

  <datalist id="hobbies">
    <option value="coding">Coding</option>
    <option value="gaming">Gaming</option>
    <option value="reading">Reading<option>
  </datalist>
</form>
```

<b>Penjelasan : <b><br>
kita membuat tag data list yang idnya hobbies <br>
kemudian kita hubungkan dengan menambahkan atribut `list` pada tag `input`
