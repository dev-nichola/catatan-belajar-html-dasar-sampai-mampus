# Input File

Input dengan type file, digunakan untuk meng-upload / mengunggah berkas file dari kompuer kita <br>
Saat kita membuat input dengan typenya adalah file, maka agar form mengirim berkas file, kita harus gunakan method post kalau menggunakan get nanti data akan dikirim lewat query parameter, dan juga enctype=multipart/form-data <br>
multipart itu artinya kalau ada data binary(data file), kalau tidak disebutkan dengan multipart/form data maka data file tersebut tidak akan dikirimkan <br>

### Kode : Input File

```html
<form action="receive.html" enctype="multipart/form-data" method="post">
  <label for="file">Upload File</label> <br />
  <br />
  <input type="file" name="file" id="file" /> <br />
  <br />
  <input type="submit" value="Simpan" />
</form>
```
