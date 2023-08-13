# Computer Code
Sebagai programmer kita kadang ksering membuat web artikel tentang kode program.
pada kasus ini ketika kita membuat kode program di HTML menggunakan paragraf maka akan menyulitkan, karena semua enter dan spasi akandi normalkan oleh html.
terkadang kita ingin menampilkan kodenya apa adanya

## Tag Pre
Untuk menampilkan tulisan di dalam html apa adanya kita bisa menggunakan tag pre. namun perlu di ingat kode html tetap tidak akan di tampilkan jadi kita harus tetap menggunakan HTML Entities

### Kode : Compuster Code
```html
 <h1>Belajar Kode PHP</h1>
    <pre>
        $usia = 1;

        echo "nama saya nichola" . $usia;

        vardump($usia);
    </pre>
```

setiap spasi dan enter akan di eksekusi dalam tag pre tersebut.