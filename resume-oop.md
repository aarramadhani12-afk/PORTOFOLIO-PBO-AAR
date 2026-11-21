# RESUME MATERI PYTHON OOP

Materi ini membahas penerapan konsep Pemrograman Berorientasi Objek (OOP) menggunakan Python melalui program percakapan antara Aar dan Naseh dengan tema makan ayam gecek di belakang UNTIRTA.

## 1. Class dan Object

Class adalah cetakan atau rancangan untuk membuat object. Sedangkan object merupakan hasil dari class yang dibuat.

Pada program ini terdapat class `Teman` yang digunakan untuk membuat dua object, yaitu `teman1` dan `teman2`. Object pertama berisi data Aar, sedangkan object kedua berisi data Naseh.

## 2. Attributes

Attribute adalah variabel yang digunakan untuk menyimpan data di dalam class atau object.

Pada program ini terdapat beberapa atribut:

- `nama` untuk menyimpan nama teman.
- `makanan` untuk menyimpan pilihan makanan.
- `lokasi` untuk menyimpan tempat makan.

Atribut tersebut digunakan untuk menyimpan informasi masing-masing object.

## 3. Class Attribute

Class attribute adalah atribut yang dibuat langsung di dalam class dan dapat digunakan oleh object yang dibuat dari class tersebut.

Pada program ini terdapat atribut:

`lokasi = "belakang UNTIRTA"`

Atribut tersebut digunakan sebagai informasi lokasi makan bersama antara Aar dan Naseh.

## 4. Instance Attribute

Instance attribute adalah atribut yang dimiliki oleh masing-masing object dan dapat memiliki nilai yang berbeda.

Pada program ini terdapat:

- `self.nama = nama`
- `self.makanan = makanan`

Contohnya, object `teman1` memiliki nama Aar dan makanan ayam gecek biasa, sedangkan `teman2` memiliki nama Naseh dan makanan ayam gecek sambal pedas.

## 5. Methods

Method adalah fungsi yang dibuat di dalam class untuk menjalankan suatu aktivitas.

Pada program ini terdapat beberapa method:

- `perkenalan()` untuk memperkenalkan diri.
- `menyapa()` untuk menyapa teman.
- `membahas_lokasi()` untuk membahas tempat makan.
- `membahas_makanan()` untuk membahas pilihan makanan.

Method tersebut digunakan untuk membuat percakapan antara Aar dan Naseh.

## 6. Parameter Self

`self` adalah parameter khusus yang digunakan untuk mengakses data milik object yang sedang menjalankan method.

Contohnya, `self.nama` digunakan untuk mengambil nama teman, sedangkan `self.makanan` digunakan untuk mengambil pilihan makanan masing-masing object.

## 7. Constructor

Constructor adalah method khusus bernama `__init__()` yang dijalankan secara otomatis ketika object dibuat.

Pada program ini:

`def __init__(self, nama, makanan):`

Constructor digunakan untuk memberikan nama dan pilihan makanan kepada setiap object.

## 8. Method dengan Parameters

Parameter adalah data tambahan yang dapat diterima oleh method ketika dipanggil.

Pada program ini contohnya:

- `menyapa(self, nama_teman)`
- `membahas_lokasi(self, nama_teman)`
- `membahas_makanan(self, nama_teman, makanan_teman)`

Parameter tersebut membantu Aar dan Naseh saling bertukar informasi dalam percakapan.

## 9. Naming Conventions

Naming conventions adalah aturan penulisan nama dalam program agar kode lebih mudah dibaca dan dipahami.

Penerapannya pada program ini:

- **Class:** menggunakan PascalCase, contohnya `Teman`.
- **Method:** menggunakan snake_case, contohnya `perkenalan()` dan `membahas_lokasi()`.
- **Attribute:** menggunakan snake_case, contohnya `nama`, `makanan`, dan `lokasi`.

## Kesimpulan

Melalui program percakapan Aar dan Naseh, saya dapat memahami penerapan konsep dasar Python OOP. Program ini menggunakan class, object, attribute, method, constructor, parameter, dan self. Dengan konsep tersebut, program percakapan sederhana dapat dibuat lebih teratur dan mudah dipahami.

---

**Identitas Mahasiswa**

Nama: Aar Ramadhani  
NIM: 14022500114  
Kelas: 3-B Sistem Informasi  
Mata Kuliah: Pemrograman Berorientasi Objek  
Bahasa Pemrograman: Python
