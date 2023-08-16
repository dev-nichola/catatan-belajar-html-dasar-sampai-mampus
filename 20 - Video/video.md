# Video
Selain gambar, HTML juga mendukung untuk menampilkan vide di halaman web yang sudah kita buat,
Namun perlu di perhatikan, tidak semua jenisa video bisa di jalankan oleh Web Browser
biasanya format video yang banyak digunakan adalah mp4, webm atau ogg
untuk menampilkan video, kita bisa menggunakan tag video

## Attribute Video
tag video itu memliki banyak atribute seperti contohnya : 
- widht : untuk mengatur lebar video 
- hegith : untuk ukuran tinggi video
- controls : untuk menampilkan kontrol video
- autoplay : agarvideo otomatis berjalan
sama seperti picture untuk menampilan video kita bisa menggunakan tag source dan sifatnya sama dengan picture kita bisa menambahkan beberapa source

### Kode : Video
```html
    <h1>Belajar Video</h1>
    <video width="1280px" height="720px" controls autoplay>
        <source src="../asset/video.mp4">
    </video>
```