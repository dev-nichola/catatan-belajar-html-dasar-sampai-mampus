#Image
Image / Gambar bisa digunakan untuk memperindah tampilan website yang kita buat
Html mendukung untuk menampilkan gambar dengan tag img
Hampir semua format gambar di dukung oleh web browser, bisa ditampilkan di halaman web HTML

## Image Attribut
tag img adalah void element jadi tidak memilik konten
Terdapat beberapa atribut yang bisa kita gunakan dalam tag img

Attribute src yang digunakan untuk menentukan lokasi gambar yang mau di tampilkan bisa menggunakan Absolute URL atau Relative URL

Attribute ALT yang digunakan sebagai representasi text atau tulisan untuk gambar, jadi semisal gambar tidak terload maka yang akan ditampilkan adalah text atribut alt tersebut. ini biasanya digunakan oleh search engine (cth: google image) untuk melakukan pembacaan kepada gambar kita

### Kode : Image
```html
 <h1>Belajar Image</h1>
    <img src="img/image.jpg" alt="Belajar-IMG">
```

## Image Size
jadi secara bawaan default, ukuran gambar itu akan selalu ditampilkan dengan ukuran aslinya kadang kadang kita ingin mengubah ukuran gambarnya, untuk melakukan ini kita membutuhkan bantuan css, untuk mengubahnya kita bisa menggunakanan attribute css yang berupa widht untuk mengatur lebarnya dan heigh untuk mengatur tingginya, 
untuk mengaturnya kita bisa menggunakan satuan px (pixel), atau % untuk persentasi dari ukuran aslinya

### Kode : Image Size
```html
     <h1>Image Size</h1>
    <img src="../img/image.jpg" alt="Image-Size" style="width: 50%; width: 40px;">
```

Ingat! saat kita menggunakan pixel ketika ukuranya tidak ideal maka gambarnya bisa gepeng / tidak sesuai seperti yang kita inginkan