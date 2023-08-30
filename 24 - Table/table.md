# Table

Saat membuat halaman web biasanya kita sering membuat table <br>
di HTML, kita juga bisa membuat table <br>
ada banyak sekali tag yang di gunakan untuk membuat table <br>

- tag table, digunakan untuk membuat table itu sendiri
- tag tr untuk membuat row / baris
- tag th untuk membuat kolom header
- tag td untuk membuat kolom isi table
- tag caption untuk keterangan table (ini sih tidak wajib)
- tag thead untuk grup header table
- tag tbody untuk grup isi table
- tag tfoot untuk footer table

### Kode : Table

```html
<table style="border: 1px solid black">
  <thead>
    <tr>
      <th>Nama Depan</th>
      <th>Nama Belakang</th>
      <th>Nilai</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nichola</td>
      <td>Saputra</td>
      <td>80</td>
    </tr>
    <tr>
      <td>Budi</td>
      <td>Nugraha</td>
      <td>80</td>
    </tr>
  </tbody>
  <tfoot>
    <td></td>
    <td>Total</td>
    <td>160</td>
  </tfoot>
</table>
```

## Column Group

kadang jika kita ingin memberi style untuk kolom, jika di lakukan satu satu maka akan menyulitkan <br>
kita bisa menggunakan tag colgroup untuk membuat group kolom, dan tag col untuk tiap kolomnya <br>
Jika kita ingin menambahkan style ke lebih dari satu kolom dengan style yang sama, kita bisa gunakan atribut span=jumlah pada tag kolom<br>

### Kode : Column Group

```html
<table style="border: 1px solid black;">
  <colgroup>
    <col span="2" style="background-color: yellow;" />
    <!-- Arti kode tersebut adalah hanya warna kuning pada kolom kesatu dan kedua -->
    <col style="background-color: aqua;" />
    <!-- Artinya kolom setelah 2 tersebut berwarna aqua -->
  </colgroup>
  <thead>
    <tr>
      <th>Nama Depan</th>
      <th>Nama Belakang</th>
      <th>Nilai</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nichola</td>
      <td>Saputra</td>
      <td>80</td>
    </tr>
  </tbody>
</table>
```

## Column Span Dan Row Span

Saat kita membuat table, kadang kita ingin menggabungkan beberapa kolom atau beberapa baris, sehingga terlihat menjadi satu kolom <br>
Pada kasus itu, kita bisa menggunakan atribut colspan untuk menggabungkan beberapa kolom dalam satu baris yang sama <br>
Atau menggunakan atribut rowspan untuk menggabungkan beberapa kolom di baris yang berbeda <br>
kalau pernah belajar Microsoft Excel ini sama saja seperti menggunakan merge cell

### Kode : Columnspan

```html
<table style="border: 1px solid black;">
  <thead>
    <colgroup>
      <col span="2" style="background-color: rgb(199, 199, 247);" />
      <col style="background-color: yellow;" />
    </colgroup>
    <tr>
      <th colspan="2">Nama</th>
      <th>Nilai</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nichola</td>
      <td>Saputra</td>
      <td>80</td>
    </tr>
  </tbody>
</table>
```

column span artinya dia akan di merge dengan baris yang ada di sampingnya

### Kode : RowSpan

```html
<table style="border: 1px solid black;">
  <thead>
    <colgroup>
      <col span="3" style="background-color: aqua;" />
    </colgroup>
    <tr>
      <th colspan="2">Nama</th>
      <th>Jumlah Kalori</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">Nama</td>
      <td>Nichola</td>
      <td>800kkl</td>
    </tr>
    <tr>
      <td>Budi</td>
      <td>500kkl</td>
    </tr>
  </tbody>
</table>
```

rowspan artinya dia akan di merge dengan baris yang ada di bawahnya
