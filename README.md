# Nama : Felix Amon Sitinjak
# NIM : 312410063
# Kelas : TI.24.A1

**1.Membuat dokumen HTML file lab3_list.html**

<img width="959" height="500" alt="image" src="https://github.com/user-attachments/assets/335c04e3-b073-4719-b3f6-7219bbbf6761" />

**Code**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan - List</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>

    <!-- Ordered List -->
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol type="A" start="D">
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>

    <!-- Unordered List -->
    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
        </ul>
    </section>

    <!-- Description List -->
    <section id="desc-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Industri</dd>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Lingkungan</dd>
            <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntansi</dd>
            <dd>Manajemen</dd>
            <dd>Bisnis Digital</dd>
        </dl>
    </section>
</body>
</html>
```

**Penjelasan**
# Praktikum Web - Lab 3: Membuat List di HTML

## Deskripsi
Project ini merupakan latihan pada Lab 3 mata kuliah Pemrograman Web yang berfokus pada pembuatan berbagai jenis **list (daftar) di HTML.  
File utama: `lab3_list.html`

---

## Tujuan Pembelajaran
- Memahami perbedaan antara Ordered List Unordered List, dan Description List.  
- Mampu mengimplementasikan atribut tambahan seperti `type` dan `start` pada tag `<ol>` dan `<ul>`.  
- Menyusun data secara terstruktur menggunakan elemen list dalam halaman web.

**2.Membuat dokumen HTML file lab3_tabel.html**

<img width="958" height="494" alt="image" src="https://github.com/user-attachments/assets/5774288a-82ee-4697-a7bf-843e4c77bcf2" />

**Code**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan - Table</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>

    <table border="1" cellpadding="6" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

**Penjelasan**
# Praktikum Web - Lab 3: List dan Table HTML

## Deskripsi
Repository ini berisi hasil praktikum Pemrograman Web (Lab 3) yang berfokus pada pembuatan List (Daftar) dan Table (Tabel) menggunakan HTML5.  
Tujuan dari praktikum ini adalah memahami cara menampilkan data dalam bentuk daftar terstruktur dan tabel dengan berbagai atribut HTML.

**3.Membuat dokumen HTML file lab3_form.html**

<img width="959" height="491" alt="image" src="https://github.com/user-attachments/assets/5a744d59-4f3e-4a90-acd7-ccfb6f23dcff" />

**Code**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan - Form</title>
    <style>
        form p > label {
            display: inline-block;
            width: 100px;
        }
        form input[type="text"], form textarea, select {
            border: 1px solid #197a43;
        }
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>

    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L">
                <label for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P">
                <label for="jk_p">Perempuan</label>
            </p>
            <p><input type="submit" value="Simpan"></p>
        </fieldset>
    </form>
</body>
</html>
```

**Penjelasan**
# Praktikum Web - Lab 3: HTML Lanjutan (List, Table, dan Form)

## Deskripsi
Repository ini berisi hasil praktikum Lab 3 - HTML Lanjutan pada mata kuliah Pemrograman Web.  
Tujuan utama dari praktikum ini adalah memahami dan mengimplementasikan berbagai elemen HTML dasar dan lanjutan, meliputi:
- Pembuatan List (daftar terurut, tidak terurut, dan deskripsi)
- Pembuatan Table (tabel data)
- Pembuatan Form (formulir input data pengguna)

**1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.**

<img width="958" height="500" alt="image" src="https://github.com/user-attachments/assets/eb8eba71-12b6-4510-b612-381484af6f66" />

**Code**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Pendaftaran</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        form p > label {
            display: inline-block;
            width: 120px;
        }
        form input[type="text"], form textarea, select {
            border: 1px solid #197a43;
            padding: 5px;
        }
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background-color: #145a32;
        }
    </style>
</head>
<body>
    <header>
        <h1>Form Pendaftaran</h1>
    </header>

    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Mahasiswa</legend>
            
            <!-- Input Nama -->
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama" required>
            </p>

            <!-- Dropdown (Select) -->
            <p>
                <label for="jurusan">Jurusan</label>
                <select id="jurusan" name="jurusan">
                    <option value="">-- Pilih Jurusan --</option>
                    <option value="ar">Arsitektur</option>
                    <option value="ts">Teknik Sipil</option>
                    <option value="ie">Teknik Industri</option>
                    <option value="ti">Teknik Informatika</option>
                    <option value="tl">Teknik Lingkungan</option>
                    <option value="tp">Teknologi Hasil Pertanian</option>
                    <option value="mm">Manajemen</option>
                    <option value="bd">Bisnis Digital</option>
                    <option value="kn">Kewirausahaan</option>
                    <option value="es">Ekonomi Syariah</option>
                    <option value="ai">Akutansi</option>
                    <option value="pgsd">Pendidikan Guru Sekolah Dasar</option>
                    <option value="pgpaud">Pendidikan Guru Pendidikan Anak Usia Dini</option>
                    <option value="bkpi">Bimbingan Dan Konseling Pendidikan Islam</option>
                    <option value="hm">Hukum</option>
                </select>
            </p>

            <!-- Listbox Multiple Selection -->
            <p>
                <label for="hobi">Hobi</label>
                <select id="hobi" name="hobi[]" multiple size="4">
                    <option value="membaca">Membaca</option>
                    <option value="olahraga">Olahraga</option>
                    <option value="musik">Musik</option>
                    <option value="gaming">Gaming</option>
                    <option value="traveling">Traveling</option>
                </select>
            </p>

            <!-- Tombol Submit -->
            <p>
                <input type="submit" value="Kirim Data">
            </p>
        </fieldset>
    </form>
</body>
</html>
```

**Penjelasan**
# Praktikum Web - Lab 3: Form Pendaftaran Mahasiswa

## Deskripsi
Repository ini berisi tugas Lab 3 HTML Lanjutan pada mata kuliah Pemrograman Web.  
Pada tugas ini, dibuat sebuah formulir pendaftaran mahasiswa menggunakan elemen-elemen HTML, seperti:
- Input teks
- Dropdown (select)
- Listbox dengan multiple selection
- Tombol submit
