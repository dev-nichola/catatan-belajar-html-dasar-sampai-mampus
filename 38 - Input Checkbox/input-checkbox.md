# Input Checkbox
Checkbox adalah input dengan tipe ceklis, dimana kita bisa menceklis atau tidak menceklis input tersebut <br>
Biasanya checkbox digunakan untuk menerima input lebih dari satu, namun inputnya sudah disesuaikan <br>

### Kode : Input Checkbox
```html
      <form>
            Hobby : <br>
            <input type="checkbox" name="hobby" id="coding" value="Coding">
            <label for="coding">Coding</label> <br>
            
            <input type="checkbox" name="hobby" id="gaming" value="Gaming">
            <label for="gaming">Gaming<label><br>
            
            <input type="checkbox" name="hobby" id="reading" value="Reading">
            <label for="gaming">Reading<label><br> 
      </form>
```

Kalau checkbox itu biasanya keteranganya yang di belakang checkboxnya tetapi juga tergantung kebutuhanya.<br>

Kemudian yang jadi pertanyaan kenapa namenya sama?. semua dalam hal ini "hobby", jadi anggap adalah satu kesatuan jadi artinya satu input name dengan nama "hobby" bisa lebih satu nilai atau multiple, <br>
kalau idnya harus berbeda atau unique karena satu input hanya mewakili satu id saja, kalau ada dua input dengan id yang sama maka akan dianggap satu.

### Kode : Input Checkbox Dengan Submit
```html
<form>
            Hobby : <br>
            <input type="checkbox" name="hobby" id="coding" value="Coding">
            <label for="coding">Coding</label> <br>
            
            <input type="checkbox" name="hobby" id="gaming" value="Gaming">
            <label for="gaming">Gaming<label><br>
            
            <input type="checkbox" name="hobby" id="reading" value="Reading">
            <label for="gaming">Reading<label><br>
                  
            <input type="submit" value="Simpan">
      </form>
```