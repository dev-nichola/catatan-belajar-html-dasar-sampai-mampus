# Form Tag

Form Tag adalah tag dengan kata kunci form, yang digunakan sebagai bagiandari input informasi yang diberikan oleh pengguna <br>
Setiap kita ingin membuat input informasi dari pengguna, Maka kita harus buat dalam form tag <br>

### Kode : Form

```html
    <form>
      <!-- Isi Form -->
    </form>
```

## Form Attribute
Seperti tag html lainya form juga memiliki atribut, berikut adalah atribut yang penting untuk kita ketahui <br>
- name, berisi informasi nama form, nama form harus unique dalam satu file HTML, artinya tidak boleh ada nama form yang sama <br>
- action, berisi url(bisa absolute atau relative) kemana informasi di form ini akan di kirim <br>
- enctype, berisi tipe data form, defaultnya isi atributnya "application.x-www-form-urlencoded", atau jika form tersebut berfungsi untu input file maka wajib di isi dengan "multipart/form-data" jika input data berisi file <br>
- method, berisi aksi HTTP Method yang akan digunakan, jika "get" maka informasi akan di kirim sebagai query parameter di URL, jika "post" maka informasi akan dikirim di request body HTTP <br>
- target, berisikan informasi dimana hasil form ini akan di tampilkan, defaultnya adalah "_self"(di halaman yang sama), atau "blank"(membuka di halaman yang baru)<br>

### Kode : Form Attribute
```html
      <form action="form-submit.html" name="contoh" enctype="application/x-www-form-urlencoded" method="post" target="_blank">

            <!-- Isi Form -->
            
      </form>
```