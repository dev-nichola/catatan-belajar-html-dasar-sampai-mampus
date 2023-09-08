# Form Action
Seperti yang di materi sebelumnya di bahas, untuk mengirim data di form, kita harus tentukan kemana semua input data yang akan dikirim menggunakan attribute "action" pada form <br>
Kita juga bisa menentukan jenis method, baik "get" atau "post" ketika mengirim input data <br>
memang defaultnya method adalah "get" <br>
kalau methodnya dirubah ke method "post" biasanya bentukan adalah <b>HTTP Request Body</b>, makanya biasanya untuk data data yang sensitif biasanya kebanyakan akan dikirimkan dengan method "post"

### Kode : Form Action
```html
      <form name="registrasi" action="receive.html" method="post" target="_parent">
            <label for="nama" id="nama" name="nama">Nama</label> <br>
            <input type="text" name="nama" id="nama"> <br>

            <label for="email" name="email" id="email">Email</label> <br>
            <input type="text" name="email" id="email"> <br>

            <label for="text" name="telephone" id="telephone">Telephone</label> <br>
            <input type="text" name="telephone" id="telephone"> <br>

            <input type="submit" value="Registrasi">
      </form>
```

## Memproses Input
Untuk memproses input, kita harus menggunakan teknologi berbasis server di Web Server <br>
HTML adalah halaman web yang ditampilkan di client(Web Browser), Sehingga HTML tidak bisa digunakan untuk memproses input data dari form<br>
Untuk memproses datanya kita harus menggunakan teknologi berbasis server, misal contoh PHP, Node JS DLL.

Jadi intinya HTML tidak bisa memproses datanya, jadi HTML hanya bisa membuat FORM INPUTNYA untuk bisa memprosesnya kita bisa menggunakan PHP, Node JS DLL