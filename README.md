# **Praktikum 6**
  ---------------
|Nama			|Kelas		|NIM		|
|-----			|-----		|-----		|
|Syahru	Raga Ramdhani	|TI.20.A.2	|312010354	|

# **Instruksi Praktikum**
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab6_css_framework
3. Buat file baru dokumen html
4. Buat struktur dasar dari dokumen HTML.
5. Buatlah layout web sederhana menggunakan css frameword (Twitter Bootsrtap).
6. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

# **Langkah Praktikum**
* Tambahkan pada bagian <head> dan pada bagian <body> beberapa elemen sebagai berikut untuk menginputkan bootstrap
![Gambar](/gambar/Capture1.PNG)
* Lalu tambahkan kode seperti berikut pada HTML untuk membuat layout sederhana.
```
    <!DOCTYPE html>
<html>
<head>
    <title>bootstrap</title>
    <meta name=”viewport” content=”widthdevice-width, initial-scale=1.0″>
    <link rel=”stylesheet” href=”css/bootstrap.min.css” type=”text//css”>
    <link rel=”sstylesheet” href=”css/bootstrap-responsif.min.css” type=”text/css>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <script src=”http://code.jquery.com/jquery.js”></script>
    <script src=”js/bootstrap.min.js”></script>
    <div class="header">
        <div class="jarak">
            <h2>Layout Sederhana</h2>
        </div>
    </div>
    <div class="menu">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>
    <div class="content">
        <div class="jarak">
            <!-- kiri -->
            <div class="kiri">
                <!-- blog -->
                <div class="border">
                    <div class="jarak">
                        <h3>Layout Sederhana</h3>
                        <p>Layout Sederhana [...]</p>
                        <button class="btn">Read More ..</button>
                    </div>
                </div>
                <!-- end blog -->
                <!-- blog -->
                <div class="border">
                    <div class="jarak">
                        <h3>Layout Sederhana</h3>
                        <p>Layout Sederhana [...]</p>
                        <button class="btn">Read More ..</button>
                    </div>
                </div>
                <!-- end blog -->
            </div>
            <!-- kiri -->
            <!-- kanan -->
            <div class="kanan">
                <div class="jarak">
                    <h3>CATEGORY</h3>
                    <hr/>
                    <p><a href="#" class="undecor">HTML</a></p>
                    <p><a href="#" class="undecor">CSS</a></p>
                    <p><a href="#" class="undecor">BOOTSTRAP</a></p>
                </div>
            </div>
            <!-- kanan -->
        </div>
    </div>
    <div class="footer">
        <div class="jarak">
            <p>Dibuat Pada April 2022</p>
        </div>
    </div>
</body>
</html>

``` 

* Lalu tambahkan kode seperti berikut pada CSS.
```
body{
    background:#f3f3f3;
    color:#333;
    width:100%;
    font-family:sans-serif;
    margin:0 auto;
}

.header{
    width:90%;
    margin:auto;
    height:120px;
    line-height:120px;
    background:aqua;
    color:black;
}

.menu{
    background-color:aqua; 
    height:50px; 
    line-height:50px; 
    position:relative;
    width:90%;
    margin:0 auto;
    padding:0 auto;
}

.jarak{
    padding:0 2pc;
}

.menu ul {
    list-style:none;
}

.menu ul li a {
    float:left; 
    width:70px; 
    display:block; 
    text-align:center; 
    color:black; 
    text-decoration:none; 
}

.menu ul li a:hover {
    background-color:aqua; 
    display:block;
}

.content{
    width:90%;
    margin:auto;
    height:420px;
    padding:0.1px;
    background:#fff;
    color:#333;
}

.border{
    border:2px solid aqua;
    margin-top:1pc;
    padding-bottom:1pc;
    padding-left:2pc;
    padding-right:2pc;
}

.kiri{
    width:70%;
    float:left;
    margin:auto;
    background:white;
    height:420px;
}

.kanan{
    width:30%;
    float:left;
    margin:auto;
    background:#fff;
    height:420px;
}

.undecor{
    text-decoration:none;
}


.footer{
    width:90%;
    margin:auto;
    height:40px;
    line-height:40px;
    background:aqua;
    color:black;
    margin-bottom: 1pc;
}

```

* Lalu save dan jalankan HTML pada browser, maka hasilnya akan seperti berikut.
![Gambar](/gambar/Capture2.PNG)