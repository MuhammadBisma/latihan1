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

```html
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