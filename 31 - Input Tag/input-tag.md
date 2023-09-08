# Input Tag
Form tag itu hanya deklarasinya saja bahwa kita akan membuat form berisi input data <br>
Sedangkan untuk detail input data apa yang di perlukan, kita menggunakan tag input <br>
Input tag menggunakan kata kunci "input"

## Input Attribute 
HTML Form mendukung banyak sekali jenis input, dan untuk mengatur jenis input, kita harus mengubahnya menggunakan attribute, Ada beberapa attribute yang perlu kita ketahui di input <br>
- name, digunakan untuk memebri nama input, nama input harus unique dalam form yang sama, artinya tidak boleh sama, kalau tidak unique maka akan di anggap satu input yang sama<br>
- type, digunakan untuk memeilih jenis input <br>
- value, digunakan untuk mengubah nilai degault dari input<br>
- disabled, digunkan untuk menjadikan input tidak aktif <br>
- readonly, digunakan untuk menjadikan input tidak bisa di ubah <br>
- required, digunakan untuk menandai bahwa input wajib di isi <br>
- placeholder, digunakan untuk menjadikan input ada karakternya tetapi tidak ada nilainya

### Kode : Input
```html
<form action="form-submit.html" name="contoh" enctype="application/x-www-form-urlencoded" method="post" target="_blank">

            Pencarian : <br>
            <input type="text" name="pencarian"> <br>

      </form>

```