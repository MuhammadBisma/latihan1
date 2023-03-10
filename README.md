# PEMOGRAMAAN WEB

Muhammad Bisma Putra H (312010443)

Teknik Informatika - UNIVERSITAS PELITA BANGSA
______________________________________________

## MEMBUAT BOX ELEMENT

Pertama, disini saya akan membuat sebuah dokumen dasar Htmlnya terlebih dahulu, sebelum nantinya akan saya tambahkan kode untuk membuat sebuah Box Element.

![tambah_gamabar](/img/1.png)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Element</title>
</head>
<body>
    <header>
        <h1>Box Element</h1>
    </header>
</body>
</html>    
```

Setelah membuat dasarnya seperti diatas, selanjutnya tambahkan sebuah kode untuk membuat Box Element dengan tag div seperti dibawah ini:


![tambah_gambar](/img/2.png)

Dengan menggunakan kode berikut:

```html
<section>
    <div class="div1">Div 1</div>
    <div class="div2">Div 2</div>
    <div class="div3">Div 3</div>
</section>
```

Berikut kodingan css nya:

```css
<style>
    div {
        float:left;
        padding: 10px;
    }
    .div1 {
        background: rgb(237, 160, 176);
    }
    .div2 {
        background: rgb(210, 100, 135);
    }
    .div3 {
        background: rgb(170, 54, 100);
    }
</style>
```

## MEMBUAT LAYOUT SEDERHANA

Untuk dapat membuat sebuah Layout Sederhana, langkah awal yang perlu dilakuan ialah membuat sebuah sebuah folder baru yang kemudian didalamnya terdapat sebuah file baru berbasis html dan juga css.

![tambah_gambar](/img/3.png)

Berikut kode yang saya gunakan untuk membuat folder baru tersebut yang nantinya akan nampak seperti gambar diatas.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="container">
        <header>
            <h1>Layout Sederhana</h1>
        </header>
        <nav>
            <a href="home.html" class="active">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </nav>
        <section id="hero"></section>
        <section id="wrapper">
            <section id="main"></section>
            <aside id="sidebar"></aside>
        </section>
        <footer>
            <p>&copy; 2023 - Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

berikut kodingan css nya: 

```css
/* import google font */
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap');

/* Reset CSS */
* {
    margin: 0;
    padding: 0;
}
body {
    line-height:1;
    font-size:100%;
    font-family:'Open Sans', sans-serif;
    color:#8c2d2d;
}
#container {
    width: 980px;
    margin: 0 auto;
    box-shadow: 0 0 1em #ac3331;
}
    
/* header */
header {
    padding: 20px;
}
header h1 {
    margin: 20px 10px;
    color: #842626;
}
```