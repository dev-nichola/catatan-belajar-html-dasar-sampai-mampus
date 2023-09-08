# Input Telephone

Input type tel bisa digunakan untuk input informasi telepon <br>
Namun berbeda dengan input email atau number: aturan di input tel harus kita tentukan sendiri, hal ini karena format telepon di tiap negara berbeda beda<br>
Kita bisa menggunakan aturan format nomor telepon menggunakan attribut yang namanya <b>pattern</b>, dimana isinya harus berisi Regular Expression<br>

### Contoh : Kode Reguler Expression

```
(62)[0-9]{5,20}
```

Maksudnya Adalah :

- (62) : Adalah awal angka yang harus memenuhi
- [0-9] : Adalah range angkanya yaitu minimal 0 dan maksimal 9
- {5,20} : Adalah jumlah angkanya yaitu minimal 5 dan maksimal 20

### Kode : Input Telephone

```html
<form>
  <label for="telepon">Telepon</label>
  <input
    type="tel"
    name="telepon"
    id="telepon"
    pattern="(62)[0-9]{5,20}"
  /><br />
  <input type="submit" value="Simpan" />
</form>
```
