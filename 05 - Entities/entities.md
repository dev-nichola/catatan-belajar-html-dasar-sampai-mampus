# Entities

## Reserved Characters

Beberapa karakter sudah dipesan oleh HTML, sehingga kita tidak bisa gukana pada tulisan teks biasa, contoh karakter <,/ atau > nanti takunya akan di anggap tag HTML

oleh karena itu, jika kita memaksakan menuliskan karakter tersebut di teks paragraf misal, secara otomatis halaman HTML akan eror atau tidak sesuai yang seperti kita mau

### Kode : HTML Reserved Characters

```html
    <html>
        <body>
            <h1>Belajar<HTML>><h1>
        <body>
    <html>
```
Jadi itu lah Reserved Characters atau karakter yang sudah di pesan dalam html 

## Entities
Karakter yang sudah dipesan itu namanya, HTML Entity
ada banyak sekali HTML Entity, dan di rekomendasikan menggukana simbol Entity nya, ketika kita ingin menggunakan karakter tersebut, Tapi sebenarnya tidak wajib, kita bisa menggunakan karakter asli, namun lebih aman jika menggunakan simbol entity nya.

### Contoh Entity

| Entity        | Karakter      |
| ------------- | ------------- |
| &num;	            | #  |
| &commat;	  | @  |

Selengkapnya bisa di lihat disini (https://oinam.github.io/entities/)

jadi kita bisa menggunakan karakter karakter yang sudah di pesan oleh html dengan menggunakan entity