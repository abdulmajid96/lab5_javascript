# Praktikum 5: Javascript
# Mata Kuliah Pemrograman WEB
```
Nama  : Abdul Majid
NIM   : 311810693
Kelas : TI.19.C.1
Universitas Pelita Bangsa
```
## Persiapan
Membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Mengenal JavaScript</title>
  </head>
  <body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write and console.log</h3>
    <script type="text/javascript">
      document.write("Hello World");
      console.log("Hello World");
    </script>
  </body>
</html>
```
![1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/1.PNG)

## JavaScript Dasar
1. Pemakaian Alert sebagai property window.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>alert box</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
        window.alert("Ini merupakan pesan untuk anda");
      //-->
    </script>
  </body>
</html>
```
![2.1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/2.1.PNG)

2. Pemakaian Method dalam objek.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>skrip javascript</title>
  </head>
  <body>
    percobaan memakai javascript:<br>
    <script type="text/javascript">
      <!--
        document.write("Selamat mencoba Javascript<br>");
        document.write("Semoga sukses!");
      //-->
    </script>
  </body>
</html>
```
![2.2](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/2.2.PNG)

3. Pemakaian prompt
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Pemasukan Data</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
        var nama = prompt("Siapa nama anda?", "Masukan nama anda");
        document.write("Hai," + nama);
      //-->
    </script>
  </body>
</html>
```
![2.3.1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/2.3.1.PNG)
![2.3.2](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/2.3.2.PNG)

4. Pembuatan fungsi dan cara pemanggilannya.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Contoh program javascript</title>
    <script type="text/javascript">
      function pesan(){
        alert ("Memanggil javascript lewat body onload")
      }
    </script>
  </head>
  <body onload=pesan()>
  </body>
</html>
```
![2.4](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/2.4.PNG)

## Dasar Pemrograman di JavaScript
1. Operasi dasar aritmatika.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Contoh program javascript</title>
    <script type="text/javascript">
      function test (val1, val2)
      {
        document.write("<br>"+"pekalian : val1*val2 "+"<br>")
        document.write(val1*val2)
        document.write("<br>"+"pembagian : val1/val2 "+"<br>")
        document.write(val1/val2)
        document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
        document.write(val1+val2)
        document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
        document.write(val1-val2)
        document.write("<br>"+"modulus : val1%val2 "+"<br>")
        document.write(val1%val2)
      }
    </script>
  </head>
  <body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
  </body>
</html>
```
![3.1.1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/3.1.1.PNG)
![3.1.2](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/3.1.2.PNG)

2. Seleksi kondisi (if..else)
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>contoh if-else</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >= 60)
        hasil = "Lulus";
        else
        hasil = "Tidak Lulus";
        document.write("Hasil: "+ hasil);
      //-->
    </script>
  </body>
</html>
```
![3.2.1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/3.2.1.PNG)
![3.2.2](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/3.2.2.PNG)
