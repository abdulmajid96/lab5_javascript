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

3. Penggunaan operator switch untuk seleksi kondisi.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Contoh program javascript</title>
    <script type="text/javascript">
      function test ()
      {
        val1=window.prompt("input nilai (1-5):")
        switch (val1)
        {
          case "1":
            document.write("Bilangan satu")
            break
          case "2":
            document.write("Bilangan dua")
            break
          case "3":
            document.write("Bilangan tiga")
            break
          case "4":
            document.write("Bilangan empat")
            break
          case "5":
            document.write("Bilangan lima")
            break
          default:
            document.write("Bilangan lainnya")
        }
      }
    </script>
  </head>
  <body>
    <input type="button" name="button1" value="switch" onclick=test()>
  </body>
</html>
```
![3.3.1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/3.3.1.PNG)
![3.3.2](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/3.3.2.PNG)
![3.3.3](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/3.3.3.PNG)

## Pembuatan Form
1. Form Input.
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Form input</title>
    <script type="text/javascript">
      function test()
      {
        var val1=document.kirim.T1.value
        if (val1%2==0)
          document.kirim.T2.value="Bilangan genap"
        else
          document.kirim.T2.value="Bilangan ganjil"
      }
    </script>
  </head>
  <body>
    <form method="POST" name="kirim">
      <p>BIL <input type="text" name="T1" size="20">MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
      <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
  </body>
</html>
```
![4.1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/4.1.PNG)

2. Form Button.
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>objek document</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
      function ubahWarnaLB(warna){
        document.bgColor = warna;
      }
      function ubahWarnaLD(warna){
        document.fgColor = warna;
      }
      //-->
    </script>
    <h1>tes</h1>
    <form>
      <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
      <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
      <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
      <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script type="text/javascript">
      <!--
      document.write("Dimodifikasi terakhir pada " + document.lastModified);
      //-->
    </script>
  </body>
</html>
```
![4.2.1](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/4.2.1.PNG)
![4.2.2](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/4.2.2.PNG)
![4.2.3](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/4.2.3.PNG)
![4.2.4](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/4.2.4.PNG)

## HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis.
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Daftar Menu</title>
    <script type="text/javascript">
      function hitung(ele){
        var total = document.getElementById('total').value;
            total = (total ? parseInt(total) : 0);
        var harga = 0;

        if (ele.checked) {
            harga = ele.value;
            total += parseInt(harga);
        }else {
            harga = ele.value;
            if (total > 0)
                total -= parseInt(harga);
        }
        document.getElementById('total').value = total;
      }
    </script>
  </head>
  <body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"/>Ayam Goreng Rp. 5.000</label><br/>
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"/>Tempe Goreng Rp. 500</label><br/>
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"/>Telur Dadar Rp. 2.2500</label><br/>
    <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
  </body>
</html>
```
![5](https://github.com/abdulmajid96/lab5_javascript/blob/main/SS/5.PNG)

## Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form.

## Jawab
1. Berikut adalah script untuk melakukan validasi isian form, sebagai contoh saya membuat validasi untuk form login.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Validasi Isian Form</title>
    <script type="text/javascript">
      function validasi() {
        var nama = document.getElementById("nama").value;
        var email = document.getElementById("email").value;
        var alamat = document.getElementById("alamat").value;
        if (nama != "" && email!="" && alamat !="") {
          return true;
        }else{
          alert('Anda harus mengisi data dengan lengkap !');
        }
      }
      </script>
    </head>
    <body>
      <h2>Validasi Isian Form</h2>
      <div class="login">
        <form action="#" method="POST" onSubmit="validasi()">
          <div>
            <label>Nama Lengkap:</label>
            <input type="text" name="nama" id="nama" />
          </div>
          <div>
            <label>Email:</label>
            <input type="email" name="email" id="email" />
          </div>
          <div>
            <label>Alamat:</label>
            <textarea cols="40" rows="5" name="alamat" id="alamat"></textarea>
          </div>
          <div>
            <input type="submit" value="Daftar" class="tombol">
          </div>
        </form>
      </div>
    </body>
</html>
```
