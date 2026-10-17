
# Jawaban Praktikum Web101: Halaman Profil Kampus
Nama: Misbahul Palah
NIM: 10224026

## Bagian 1: Pemanasan

1. Anatomi aturan CSS

   Pada aturan `nav a.active:hover { color: red; }`:
   - Selector: `nav a.active:hover`
   - Deklarasi: `color: red;`
   - Property: `color`
   - Value: `red`
   - Pseudo-class: `:hover`

2. Perbedaan elemen block dan inline

   Elemen block secara default dimulai pada baris baru dan menggunakan lebar yang tersedia. Contohnya `<p>`, `<li>`, dan `<h2>`.

   Elemen inline secara default berada dalam alur teks yang sama dan hanya menggunakan ruang sesuai kontennya. Contohnya `<span>`, `<a>`, dan `<strong>`.

3. Selector `.box p { color: green; }`

   Paragraf A dan B akan berwarna hijau karena keduanya merupakan elemen `<p>` yang berada di dalam elemen dengan class `box`. Paragraf C tidak memenuhi selector tersebut apabila elemen itu memiliki class `box` sendiri, tetapi tidak berada di dalam elemen `.box`.

4. Urutan specificity CSS

   Jika terdapat aturan `h1`, `.heading`, dan `#title` yang semuanya mengatur warna elemen yang sama, selector `#title` memiliki specificity paling tinggi. Oleh karena itu, warna yang diterapkan adalah warna dari aturan `#title`, selama tidak ada aturan lain dengan prioritas lebih tinggi.

5. Kesalahan struktur HTML

   Pada kode `<p>Hello <strong>world</p></strong>`, tag ditutup tidak sesuai urutan pembukaan. Tag `<strong>` harus ditutup sebelum tag `</p>`.

   Perbaikan:
   `<p>Hello <strong>world</strong></p>`

## Bagian 3: Prediksi Selector Golf

P1. Selector yang lebih spesifik dapat mengalahkan selector yang kurang spesifik ketika keduanya mengatur properti yang sama dan tidak ada faktor cascade lain yang mengubah hasilnya.

P2. Selector dengan ID memiliki specificity lebih tinggi daripada selector class dan selector elemen.

Setelah diuji (hasil sebenarnya):
Isi berdasarkan hasil pengujian seluruh tantangan Selector Golf di browser.

## Bagian 4: Box Model

Q1 (content-box):

Pada `box-sizing: content-box`, nilai width hanya menghitung lebar konten. Padding dan border ditambahkan di luar lebar tersebut sehingga ukuran total elemen menjadi lebih besar.

Q2 (border-box):

Pada `box-sizing: border-box`, nilai width sudah mencakup konten, padding, dan border. Karena itu, ukuran total elemen lebih mudah dikendalikan.

Pengecekan DevTools:

Gunakan Developer Tools pada browser, pilih elemen yang diperiksa, lalu buka bagian Computed atau Box Model. Periksa nilai content, padding, border, dan margin.

## Bagian 5: Tabel Debug

| # | Baris | Bug | Perbaikan | Cara menemukannya |
|---|-------|-----|-----------|-------------------|
| 1 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 2 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 3 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 4 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 5 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 6 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 7 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 8 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |
| 9 | Periksa kode sumber | Belum diidentifikasi | Perbaiki sesuai hasil pemeriksaan | Membaca kode |

## Bagian 6: Tabel Code Review

| # | Baris | Masalah | Mengapa penting | Perbaikan saya |
|---|-------|---------|-----------------|----------------|
| 1 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |
| 2 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |
| 3 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |
| 4 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |
| 5 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |
| 6 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |
| 7 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |
| 8 | Periksa kode rekan | Belum diidentifikasi | Perlu diperiksa berdasarkan kode | Sesuaikan dengan temuan |

### Refleksi

1. Saya belajar bahwa penulisan HTML yang semantik membuat struktur halaman lebih jelas dan mudah dipahami.

2. Saya belajar bahwa specificity, cascade, dan box model memengaruhi hasil tampilan halaman web.

3. Saya akan memeriksa struktur HTML, aturan CSS, dan hasil tampilan di browser secara bertahap ketika menemukan kesalahan.

## Bagian 7: Exit Ticket

1. Hal yang paling saya pahami dari praktikum ini adalah penggunaan HTML semantik dan CSS untuk membangun halaman web.

2. Hal yang masih perlu saya latih adalah memahami specificity CSS, memeriksa box model, dan menemukan kesalahan kode secara sistematis.

3. Langkah berikutnya adalah memvalidasi HTML, menguji tampilan di browser, memperbaiki kesalahan, dan memastikan seluruh file praktikum tersimpan dengan benar.
