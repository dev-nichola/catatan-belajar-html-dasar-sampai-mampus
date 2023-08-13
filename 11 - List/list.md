# List
Untuk membuat daftar tulisan biasanya kita membuat list, di html kita dapat membuatnya dengan TAG list

ada dua tipe list di html yaitu undordered list dan ordered list

untuk membuat isi list tersebut dihtml menggunakan TAG li

## Unordered List
undordered list adalah list yang tidak ada penomoranya, untuk di html kita dapata membuatnya dengan tag ul

### Kode : Penggunaan ul
```html
     <ul>
        <li>List Pertama</li>
        <li>List Kedua</li>
        <li>List Ketiga</li>
    </ul>
```

## Ordered List
sementara untuk membuat list yang ada penomoranya kita menggunakan tag ol

## Kode : Penggunaan ol

```html
    <ol>
        <li>List Pertama</li>
        <li>List Kedua</li>
        <li>List Ketiga</li>
    </ol>
```

## Ordered List Lainya
kadang kadang kita tidak ingin menggunakan nomor pada list, tetapi kita bisa menggunakan angka romawi atau huruf abjad ABC

pada kasus ketika kita menggunakan daftar yang berurut (ol), kita bisa mengubah format daftarnya, defaultnya menggunakan angka (dimulai dari 1).
kita bisa menambahkan attribute type di ol dengan nilai :
- type="1" artinya daftar isi akan menggunakan angka(ini adalah defaultnya)
- type="A" artinya daftar isi akan menggunakan huruf kapital
- type="a" artinya daftar isi akan menggunakan huruf kecil
- type="I" artinya daftar isi akan menggunakan angka romawi kapital
- type="i" artinya daftar isi akan menggunakan angka romawi kecil