# Input Submit
Saat kita membuat form, kita bisa menambahkan tombol yang bisa digunakan untuk mengirim data yang diinputkan di dalam form, atau disebut Submit <br>
Tombol Submit, bisa kita buat menggunakan Input dengan type Submit <br>

### Kode : Input Submit
```html
      <form name="registrasi">
            <label for="nama" id="nama" name="nama">Nama</label> <br>
            <input type="text" name="nama" id="nama"> <br>

            <label for="email" name="email" id="email">Email</label> <br>
            <input type="text" name="email" id="email"> <br>

            <label for="text" name="telephone" id="telephone">Telephone</label> <br>
            <input type="text" name="telephone" id="telephone"> <br>

            <input type="submit" value="Registrasi">
      </form>
```

Dengan contoh di atas kita menambahkan sebuah input dalam bentuk tombol dengan type submit dan menambahkan value "Registrasi" <br>
Defaultnya kalau kita tidak menambahkan actionya artinya form tersebut akan dikirimkan ke halamanya sendiri dan akan terlihat di query parameternya atau URL Browsernya<br>

Note : Jangan bingung dengan %20 hal tersebut adalah encoded character yang hasilya adalah @
