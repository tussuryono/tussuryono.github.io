# HTML5

## Summary
HyperText Markup Language (HTML) merupakan suatu bahasa (Standard Markup Language) yang digunakan dalam pengembangan web, dimana versi terakhir dari HTML adalah 5.2 ([W3C](https://www.w3.org/)). HTML mendeskripsikan struktur halaman web dalam bentuk markup. HTML element merupakan bagian atau parts yang membentuk suatu halaman web, serta direpresentasikan dalam bentuk tag HTML yang antara lain bisa berupa `heading`, `paragraph`, `table`, dan lain sebagainya. Standar sederhana dalam penulisan HTML5 adalah sebagai berikut :

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Sample page</title>
  </head>
  <body>
    <h1>Sample page</h1>
    <p>This is a <a href="demo.html">simple</a> sample.</p>
    <!-- this is a comment -->
  </body>
</html>
```

Pada syntax HTML diatas dapat diterjemahkan sebagai berikut :
- `<!DOCTYPE html>` mendeklarasikan bahwa dokumen tersebut merupakan HTML5.
- `<html>` element merupakan `root element` dari halaman HTML.
- `<head>` element berisi konten yang berhubungan dengan meta information halaman HTML.
- `<title>` element memberikan informasi terkait `title` atau `judul` halaman HTML.
- `<body>` element merupakan bagian yang akan ditampilkan secara visual dalam halaman HTML.
- `<h1>` element mendefinisikan heading yang ditampilkan dalam contoh `<h1>` merupakan ukuran yang paling besar, range normal dalam sebuah halaman HTML adalah `<h1>` sampai dengan `<h6>`.
- `<p>` element berfungsi untuk mendefinisikan `paragraph`.
