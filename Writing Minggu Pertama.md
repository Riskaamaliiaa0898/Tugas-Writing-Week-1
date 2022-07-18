# Writing Minggu Pertama

## __Unix Command Line (CLI)__
> **Unic Command Line** adalah Shell atau Terminal yang digunakan untuk menjalankan program, mengelola file komputer, dan berinteraksi dengan komputer.__Shell__ adalah program penerima perintah yang diketikkan dari keyboard, dan mengantarnya ke sistem operasi untuk dieksekusi. Sedangkan __Terminal__ adalah program yang menjadi perantara antara kita dengan shell.

berikut daftar perintah command dasar Linux :
1.	__LS__ => Menampilkan List/daftar file dan folder 
2.	__Ls-La__ => Menampilkan daftar file yang disembunyikan/hidden
3.   __Cd__ => perintah Pindah directory/berkas yang berada dalam komputer. Caranya Cd nama_file. 

    Contoh : Cd Data01

4.    __Cd__  nama_master => Pindah ke derectory master.

    Contoh : cd D: atau cd G:
5. __Cd ..__ => Kembali directory sebelumnya

6. __Clear__ => Bersihkan tampilan terminal Clear
7.	 __Touch nama_file.extensi__ => Perintah untuk membuat filebaru. 

    Contoh : Touch Data01.txt
8.	 __Cp (Copy Paste)__ => meng copy paste File. 

    Contoh : Cp nama file yang mau di copy.ekstensi   nama file baru.ekstensi

9.	 __Cp__ => Copy File ke folder. 

    contoh : Cp nama_file_yang mau dicopy.extensi nama_derectory\nama file
10.	 Cp –r => Copy file beserta isinya.

    Contoh : Cp –r nama_folder
11.	 Mv => Moving file

    Contoh : Mv nama file yang ingin dipindahkan. Ekstensi ke folder yang ingin di tuju
13.	 Rm => Hapus /Delete

    contoh : Rm nama_file yang mau dihapus.ekstensi

14.	 Rm –r => Hapus /delete folder 
   
    Contoh : Rm –r nama_folder
15.	 Apabila ingin mengHapus file lebih dari 1 beri tanda koma
    
    Contoh : Rm –r nama_folder,nama_folder,nama_folder
16.  mkdir => Membuat folder baru

    contoh : Mkdir nama_folder_baru



*Notes :*

- Jika nama file lebih dari satu kata beri tanda “ ”

- Membuat folder tanpa spasi berikan tanda _ setiap kata

    contoh : Mkdir nama_folder_baru


## __Git & GitHub__

> __Git__ adalah tools untuk melacak setiap perubahan file/folder (termasuk code yang kita buat) pada suatu proyek baik dikerjakan secara individu maupun tim serta mencatat siapa yang mengubah code tersebut  dari suatu file program.

Terdapat 3 Cara membuka git :
1. dapat menggunakan powersell kode : git –version
2. dapat menggunakan Comingfrom : git –version
3. menu terus pencarian __git bash__

4.   Configurasi git

    git config --global user.name "Petani Kode"

    git config --global user.email contoh@Petanikode.com

5.   Melihat hasil configurasi / mengecek hasil berhasil atau tidak

    git config --list
6. Selesai

langkah selanjutnya apabila git telah ter Instal, adalah :

__Repository git__ adalah direktori proyek yang ingin kita buat. _1 Repo =  1 Proyek = 1 Direktori_

 1.  git Proyek

    Git init proyek1

    git init . (apabila folder sudah ada sebelumnya)


2. git Status (mengecek status dari git kita, biasanya itu   tentang file yang belum di add atau di commit, 
  jika sudah aman harusnya message yang keluar " nothing to commit, working tree clean ")
3. git add. (menambahkan seluruh file)
4.   git commited ( meng acc , mengcommit tentang penambahan checkpoint)

    git commit -m "pesan yang mengdeskripsikan apa yang kita lakukan"

5. git log adalah revisi yang sudah dilakukan dan dapat melihat catatan log dari revisi - revisi tersebut dengan menggunakan perintah berikut ini : ___git log__

    Melihat log dari berbagai sisi.
    - Melihat log menggunakan nomor version/commit
    - Melihat log file tertentu
    - Melihat log berdasarkan author

6. Perintah _git checkout_ mengembalikan file dalam kondisi sebelumnya, tapi bersifat sementara.__Misalnya : git checkout "nomer commit"__
7. Perintah _git reset_ akan mengembalikan file ke kondisi sebelumnya, kemudian menghapus catatan sejarah commit beikutnya.__Misalnya : git reset --soft "nomer commit"__
8. Perintah _git revert_ mengembalikan file dengan tidak menghapus sejarah commit. __Misalnya : git revert "nomer commit"__

## __HTML Dasar__

HTML adalah kerangka untuk membuat halaman web. 
 <img src="image/HTML-and-CSS-2-Custom.jpg" width="400">

File HTML tersusun sebabagi kesatuan dari sebuah tingkatan itu ibarat seperti pohon keluarga. 
Di dalam HTML terdapat "head" and "body", di dalam "head" terdapat _title dan meta_ dan "body" terdapat _h1,p,img,video,audio dll_.


Ada tools utama yang harus dipersiapkan untuk membuat HTML adalah __Visual Code Studio__ 

> Visual Code Studio merupakan paket all in one. Kamu bisa menggunakan ini untuk bahasa pemrograman apapun.

#### Kode HTML Dasar
1.  _Title tag_ adalah judul dari sebuah halaman atau website
2. _Heading_ adalah judul dari sub judul. heading itu h1 sampai h6
3. _paragraf_ adalah tulisan setiap paragraf kodenya __P__
4. _bold_ huruf tebal kodenya __B__
5. _italic text_ huruf miring __i__
6.    contoh html element, cara menge tag link 

    <a href="https://classroom.google.com/u/0/w/NTI1NTczMzc2NzU1/t/all"> Clasroom Kind Knucker </a>)
7.    menge tag image 

    <img src="nama-file.jpg" width="100">
8. HTML Atribut adalah properties dari sebuah HTML Element. _(id, src, href)_
9. _div dan span_ - Tidak memberi tahu apa pun tentang kontennya.
10. _form, table, dan article_ - Mendefinisikan isinya dengan jelas.
11. border="1" (memberikan garis terhadap table)

### __Cara Membuat HTML__

    <!DOCTYPE html>
    <html>
     <head>
        <title>Profil Saya</title>
     </head>
     <body>
        <div>
            <h1> Hallo Ini Profil Saya</h1>
            <p>Saya saat ini sedang mengikuti pembelajaran Coding Bootcamp Amman Mineral banch 3 </p>
        </div>
        <div>
            <ul>
                <li>Nama: Riska Amalia</li>
                <li>TTL: Sumbawa Besar, 02 Agustus 1998</li>
                <li>Umur: 23 Tahun</li>
                <li>Pendidikan: Universitas Samawa</li>
                <li>Alamat: Sumbawa Besar,NTB</li>
            </ul>
        </div>
        <div>Foto Saya</div>
        <img src="image/IMG-20220716-WA0002.jpg" width="100">
     </body>
     <body>
    <div>
        <video controls>
        <source src="https://youtu.be/Yk0HxRQnV78" type="vidoe/mp4">
        </video>
    </div>
     </body>
     <body>
        <!--Cara Membuat Table--> <!-memberi penjelasan dari line code dan comment tersebut tidak bisa di eksekusi->
        <h4>TABLE KELUARGA</h4>
        <table border="1">
            <thead>
                <tr>
                    <td>
                        <b>No</b>
                    </td>
                    <td>
                        <b>Nama</b>
                    </td>
                    <td>
                        <b>Jenis Kelamin</b>
                    </td>
                    <td>
                        <b>Golongan Darah</b>
                    </td>
                    <td>
                        <b>Umur</b>
                    </td>
                </tr>
            </thead>
            <tbody>
                <td>1</td>
                <td>Riska Amalia</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>23 tahun</td>
            </tbody>
            <tbody>
                <td>2</td>
                <td>Dwie Wahyu</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>28 tahun</td>
            </tbody>
            <tbody>
                <td>3</td>
                <td>Nurhayati</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>58 tahun</td>
            </tbody>
            <tbody>
                <td>4</td>
                <td>Yulistia Alwasifah</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>21 tahun</td>
            </tbody>
            <tbody>
                <td>5</td>
                <td>M. AlteZZa Abgani</td>
                <td>Laki-Laki</td>
                <td>Gol O</td>
                <td>2 tahun</td>
            </tbody>
        </table>
     </body>
     <!--Membuat Formulir-->
     <body>
      <h2>HTML Form</h2>
      <form>
        <label for="text">First name:</label><br>
        <input type="text" id="text" ><br>
        <label for="namber">Umur:</label><br>
        <input type="namber" id="namber"><br><br>
        <input type="submit" value="Submit">
      </form> 
       <p>Jika Anda mengklik tombol "Kirim", data formulir akan dikirim </p>   
     </body>
     </html>
    


### __Hasil Pembuatan HTML__


<!DOCTYPE html>
<html>
    <head>
        <title>Profil Saya</title>
    </head>
    <body>
        <div>
            <h1> Hallo Ini Profil Saya</h1>
            <p>Saya saat ini sedang mengikuti pembelajaran Coding Bootcamp Amman Mineral banch 3 </p>
        </div>
        <div>
            <ul>
                <li>Nama: Riska Amalia</li>
                <li>TTL: Sumbawa Besar, 02 Agustus 1998</li>
                <li>Umur: 23 Tahun</li>
                <li>Pendidikan: Universitas Samawa</li>
                <li>Alamat: Sumbawa Besar,NTB</li>
            </ul>
        </div>
        <div>Foto Saya</div>
        <img src="image/IMG-20220716-WA0002.jpg" width="100">
    </body>
    <body>
    <div>
        <video controls>
        <source src="https://youtu.be/Yk0HxRQnV78" type="vidoe/mp4">
        </video>
    </div>
    </body>
    <body>
        <!--Cara Membuat Table--> <!-memberi penjelasan dari line code dan comment tersebut tidak bisa di eksekusi->
        <h4>TABLE KELUARGA</h4>
        <table border="1">
            <thead>
                <tr>
                    <td>
                        <b>No</b>
                    </td>
                    <td>
                        <b>Nama</b>
                    </td>
                    <td>
                        <b>Jenis Kelamin</b>
                    </td>
                    <td>
                        <b>Golongan Darah</b>
                    </td>
                    <td>
                        <b>Umur</b>
                    </td>
                </tr>
            </thead>
            <tbody>
                <td>1</td>
                <td>Riska Amalia</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>23 tahun</td>
            </tbody>
            <tbody>
                <td>2</td>
                <td>Dwie Wahyu</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>28 tahun</td>
            </tbody>
            <tbody>
                <td>3</td>
                <td>Nurhayati</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>58 tahun</td>
            </tbody>
            <tbody>
                <td>4</td>
                <td>Yulistia Alwasifah</td>
                <td>Perempuan</td>
                <td>Gol O</td>
                <td>21 tahun</td>
            </tbody>
            <tbody>
                <td>5</td>
                <td>M. AlteZZa Abgani</td>
                <td>Laki-Laki</td>
                <td>Gol O</td>
                <td>2 tahun</td>
            </tbody>
        </table>
    </body>
    <!--Membuat Formulir-->
    <body>
    <h2>HTML Form</h2>
    <form>
        <label for="text">First name:</label><br>
        <input type="text" id="text" ><br>
        <label for="namber">Umur:</label><br>
        <input type="namber" id="namber"><br><br>
        <input type="submit" value="Submit">
    </form> 
    <p>Jika Anda mengklik tombol "Kirim", data formulir akan dikirim </p>   
    </body>
</html>

## __CSS Dasar__
>__CSS Dasar (layer presentation)__ adalah bahasa yang digunakan untuk mendesain, mempercantik, memberikan warna atau baju,memposisikan text terhadap halaman website.

3 cara menggunakan CSS
-    Inline Styles => menyematkan code csspada elemen apapun di dalam body HTML dengan menggunakan atribut _style_.


    <P style="color: red">Masuk</button>

-    Internal Styles => CSS yang diletakkan pada bagian head suatu halaman HTML

    <head>
    <styles> isi dengan Content seperti padding,margin,bacground,color ataupun font</styles>
    </head>
    
-    Eksternal Styles => Membuat file tersendiri yang berekstensi dengan css. eksternal css dapat digunakan lebih dari 1 kali. Kemudian file tersebut di hubungkan ke dalam halaman HTML menggunakan tag _link_. 

    contoh Eksternal styles
    <link href="styles.css" type="text/css" rel="stylesheet"/>

    contoh Eksternal dari alamat website
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"type="text/css" rel="stylesheet"/>


Struktur CSS

    . elementHTML {
        property : value;
        }

-    tanda (.) => (selector khusus untuk properti class)
-    tampa . => (seluruh text html p diambil/dipanggil di css)
-    code # => (untuk div)
-    id => (hanya ada 1 element sifat priority)
-    class => ( bisa lebih dari 1) text html

    Contoh 1: 
    <h1 class="Font-12"></h1>   value dari h1 adalah __Font-12__

    Contoh 2:
    <p id="test" class="Test2"></p> 
    
    value atribut id = Test 
    value atribut class = Test 2


-    CSS- Tag Name (menggunakan secara lgsung dan bersifat global)

    h1 {color:blueviolet;}

    berarti seluruh h1 akan berubah warna menjadi blueviolet

-    CSS- Class Name (HTML yang memiliki class yang sama, akan mempunyai styling yang sama)
 
    .title {color: brown;

    .header-style-1 {
    font-size: 40px;
    font-family: Arial, Helvetica, sans-serif;
- CSS-Multiple class (menggunakan lebih dari 1 class element html)
-   CSS- id name (bersifat unik artinya hanya ada 1 nama ID pada 1 element HTML.Gunakan (#namaID) saat memanggil element ID HTML pada CSS)
  
- Chaining Selector (jika ada 3 element html 
nested elemen ( pohon keluarga, ketika ada sesuatu prest memiliki class anak2nya akan mengikuti)
-    Nested Element (Konsep CSS sama dengan HTML yaitu setiap element memiliki parent dan child.)

    .parent{
    text-align: center;
    }

- !importent css ( dampaknya kita memaksa bahwa harus menjalankan styles secara prioritas atau di khususkan)
- multiper selector (membuat code lebih efisien dan tidak repetitive (melakukan hal yang sama berulang-ulang).
)
 
Cara Membuat CSS

1.   Background-image 

     untuk masuk ke sebuah folder => __href='../css.styles'__

2.   Background-Color
    
    body {
    background-color: color pilihan;}
3.   font- size

    h1 {
        font- size : 6 px;
    }
4.   font-color

    p {
        color:red;
    }
5.    Nested Element

    .parent{
    text-align: center;
    }

__Box System__ (seluruh text html berbentuk kotak)
- border => garis box
- margin=> jarak luar
- padding=> jarak dalam kontent
- bisa menuliskan seluruhnya dengan menyesuaikan arah jarum jam
    
     contoh :

      sub-header { 
        border : 1px solid: black;
        margin: 20 px atau 20px 10px 15px 20px
        padding: 25px}

baground-image
untuk masuk ke sebuah folder href='./css.styles'

CTRL + Spasi (untuk melihat file)

## __Cara Membuat CSS__
    DOCTYPE html>
    <html>
        <head>
            <!--Internal Style-->
                <style>
                    .bootcamp {color :blue;}
                </style>
        <title>Profil Saya</title>

        <!--Eksternal style-->
        <!--dapat memanggil file css lebih dari 1-->

        <link href="styles.css" type="text/css" rel="stylesheet"/>

        </head>

        <body>
            <!--Inline Style-->
            <div>
                <h1 style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;"> Hallo Ini Profil Saya</h1>
                <p style="color:rgb(248, 148, 17);">Saya saat ini sedang mengikuti pembelajaran Coding Bootcamp Amman Mineral banch 3 </p>
                <p class="bootcamp">Saya Sangat Senang</p>
            </div>
            <div>
                <h1 class="title header-style-1">Biodata Diri</h1>
                <p class="parent">Selamat Datang</p>
                <ul>
                    <li>Nama: Riska Amalia</li>
                    <li>TTL: Sumbawa Besar, 02 Agustus 1998</li>
                    <li>Umur: 23 Tahun</li>
                    <li>Pendidikan: Universitas Samawa</li>
                    <li>Alamat: Sumbawa Besar,NTB</li>
                </ul>
            </div>
        </body>
    </html>

__Hasil CSS__
<!DOCTYPE html>
<html>
    <head>
        <!--Internal Style-->
        <style>
            .bootcamp {
                color :blue;
            }
        </style>
        <title>Profil Saya</title>
        <!--Eksternal style-->
        <!--dapat memanggil file css lebih dari 1-->
        </head>
    <body>
        <!--Inline Style-->
        <div>
            <h1 style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;"> Hallo Ini Profil Saya</h1>
            <p style="color:rgb(248, 148, 17);">Saya saat ini sedang mengikuti pembelajaran Coding Bootcamp Amman Mineral banch 3 </p>
            <p class="bootcamp">Saya Sangat Senang</p>
        </div>
        <div>
            <h1 class="title header-style-1">Biodata Diri</h1>
            <p class="parent">Selamat Datang</p>
            <ul>
                <li>Nama: Riska Amalia</li>
                <li>TTL: Sumbawa Besar, 02 Agustus 1998</li>
                <li>Umur: 23 Tahun</li>
                <li>Pendidikan: Universitas Samawa</li>
                <li>Alamat: Sumbawa Besar,NTB</li>
            </ul>
        </div>
    </body>
</html>

## Flexbox

> __Flexbox__ adalah cara untuk mengatur layout atau mengatur tata letak. Flexbox memiliki kemampuan untuk menyesuaikan layout secara otomatis.

Contoh HTML

        <body>
            <div class="container">
                <div class ="item"> item 1 </div>
                <div class ="item"> item 2 </div>
                <div class ="item"> item 3 </div>
                <div class ="item"> item 4 </div>
                <div class ="item"> item 5 </div>
                <div class ="item"> item 6 </div>
            </div>
        </body>

Contoh CSS

    .container {
        border: 1px solid: black
        display: flex;}

    .item{
        border: 1px solid:black;
        width: 200px;
        height: 200px;
        baground-color: orange;
    }


## Algoritma & Pseudocode
> __Algoritma__ adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. Kualitas dari Algoritma antara lain:
- Input dan output harus didefinisikan terlebih dahulu dengan tepat
- Setiap step harus benar-benar clear dan tidak ambigu
- Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman tertentu. Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.

### Contoh algoritma Sederhana

Kondisi Hujan
1. Apakah hujan?
2. Jika tidak hujan, kamu tidak perlu bawa payung
3. Jika hujan, segera cari payung
4. Ketika payung sudah ketemu, bawa payungnya
5. Jika payung tidak ketemu pastikan apakah masih hujan dan akan kembali berputar ke poin 2 dan 3

kondidi jam ke menit dan detik

buatlah algoritma dalam bentuk pseudocode untuk menghitung konversi dari jam dan menit dalam satuan detik! 
1. adapun nilai 1 jam = 3600 detik,  
3. 1 menit=60 detik. 
2. sehingga rumus untuk konversi dari jam dan menit kedalam satuan detik adalah detik=(jam*3600> + (jam*60)







             













