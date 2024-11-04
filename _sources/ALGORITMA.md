---
title: ALGORITMA

---

# ALGORITMA 
NAMA :Fahrizal umam
NIM  :230411100056
KELAS:IF2D

## Defisi ALgoritma
Algoritma adalah metode atau langkah yang direncanakan secara tersusun dan berurutan untuk menyelesaikan atau memecahkan permasalahan dengan sebuah intruksi atau kegiatan

Perkembangan ilmu pengetahuan dan teknologi menjadikan manusia mampu menghasilkan karya-karya yang semakin canggih dan kompleks. Meskipun komputer dapat melakukan perhitungan dengan cepat dibandingkan manusia pada umumnya, namun komputer tidak bisa menyelesaikan masalah begitu saja tanpa diajarkan oleh manusia melalui urutan langkah-langkah (algoritma) penyelesaian yang dide?nisikan terlebih dahulu. Selain digunakan untuk pemecahan masalah menggunakan komputer, algoritma juga dapat diterapkan dalam menyelesaikan permasalahan sehari-hari yang membutuhkan sederet proses atau langkah-langkah prosedural. Agar lebih memahami apa itu algoritma mari kita pelajari pengertiannya dari beberapa sumber.

#### Referenses:
https://bdkm.unida.ac.id/artikel/pengertian-algoritma.html
### Algoritma Sequential search
Algoritma Sequential Search, atau pencarian berurutan, adalah metode yang digunakan untuk mencari elemen tertentu dalam sebuah array atau daftar dengan cara memeriksa setiap elemen satu per satu dari awal hingga akhir. Ini adalah salah satu algoritma pencarian yang paling sederhana dan paling mudah diimplementasikan.

### Cara Kerja Sequential Search
1. Inisialisasi: Mulai dengan elemen pertama dalam array.
2. Perbandingan: Bandingkan elemen yang sedang diperiksa dengan nilai yang dicari (key).
3. Temukan atau Lanjutkan:
    * Jika elemen yang sedang diperiksa sama dengan nilai yang dicari, pencarian berhasil, dan algoritma mengembalikan indeks elemen tersebut.
    * Jika tidak, lanjutkan ke elemen berikutnya dalam array.

4. Ulangi Proses: Ulangi langkah 2 dan 3 sampai elemen ditemukan atau sampai semua elemen dalam array telah diperiksa.
5. Hasil Pencarian: Jika elemen tidak ditemukan setelah memeriksa seluruh array, algoritma mengembalikan informasi bahwa elemen tersebut tidak ada dalam daftar.

### Kelebihan Sequential Search
Sederhana: Algoritma ini mudah dipahami dan diimplementasikan, karena hanya melibatkan perulangan dan perbandingan sederhana.
Tidak Memerlukan Pengurutan: Algoritma ini dapat digunakan pada array yang tidak terurut, sehingga tidak memerlukan langkah pengurutan sebelumnya.

### Kekurangan Sequential Search
Inefisien untuk Data Besar: Karena algoritma ini memeriksa setiap elemen satu per satu, waktu pencarian meningkat secara linear dengan jumlah elemen dalam array. Kompleksitas waktu adalah O(n), di mana n adalah jumlah elemen dalam array. Ini membuatnya tidak efisien untuk dataset besar.
Waktu Terburuk: Dalam kasus terburuk, algoritma ini harus memeriksa setiap elemen dalam array, yang dapat memakan waktu cukup lama jika array sangat besar.

### Contoh Penggunaan:
Misalkan kita memiliki array berikut: [3, 5, 2, 8, 6], dan kita ingin mencari angka 8.

Algoritma Sequential Search akan memeriksa elemen satu per satu:
Memeriksa 3, tidak cocok.
Memeriksa 5, tidak cocok.
Memeriksa 2, tidak cocok.
Memeriksa 8, cocok! Elemen ditemukan.
### Algoritma Binary search
Binary Search adalah algoritma pencarian yang efisien untuk menemukan posisi elemen dalam array yang sudah terurut. Algoritma ini bekerja dengan membagi array menjadi dua bagian secara berulang hingga elemen yang dicari ditemukan atau interval pencarian menjadi kosong.

Cara Kerja:
Inisialisasi: Tentukan indeks awal (low) dan indeks akhir (high) dari array.
Iterasi:
Hitung indeks tengah (mid) dari array.
Bandingkan elemen di indeks tengah dengan elemen yang dicari (key).
Jika elemen tengah sama dengan key, pencarian selesai.
Jika key lebih kecil dari elemen tengah, ulangi pencarian pada bagian kiri.
Jika key lebih besar, ulangi pada bagian kanan.
Ulangi hingga elemen ditemukan atau interval pencarian menjadi kosong.
Keuntungan:
Waktu Eksekusi: O(log n), sehingga lebih cepat dibandingkan pencarian linier (O(n)) pada array besar.

### Contoh:
Jika kita memiliki array terurut [2, 3, 5, 7, 11, 13, 17] dan ingin mencari angka 11, binary search akan:

Memeriksa elemen tengah (7), tidak cocok.
Melihat ke kanan (pencarian berikutnya pada [11, 13, 17]), memeriksa elemen tengah (13), tidak cocok.
Kembali ke kiri (pencarian berikutnya pada [11]), menemukan 11.
Dengan cara ini, binary search memungkinkan pencarian yang cepat dan efisien dalam data yang terurut.

#### references binary search and sequential search:
http://klik.ulm.ac.id/index.php/klik/article/view/519/pdf

### mengapa binary search lebih cepat dari pada sequential search
binary search karena dengan cara ini kita mengecek separuh dari data yang ada, jika tidak ditemukan maka kita mengecek kembali separuh data yang lain dengan kompleksitas O( log N ), sedangkan sequential search mengecek satu per satu dari seluruh data yang ada sehingga kompleksitasnya menjadi O(N).


## Pseudocode adalah...
Istilah Pseudocode berasal dari gabungan kata pseudo yang berarti imitasi, palsu, menyerupai, atau mirip, dengan kata code yang artinya sebuah kode pemrograman. Pseudocode yaitu kode yang mirip dengan kode pemrograman yang sesungguhnya. Pseudocode adalah sebuah deskripsi atau ringkasan tingkat tinggi dari algoritma pemrograman komputer dengan konvensi struktural. Dengan menuliskan kode semu tersebut, seseorang dapat menuliskan algoritma untuk dapat dibaca oleh manusia, tetapi tidak ditunjukkan kepada mesin atau robot. Pseudocode merupakan cara penulisan algoritma yang menyerupai bahasa pemrograman tingkat tinggi.

#### References:
https://www.kompas.com/skola/read/2023/10/18/060000469/mengenal-pseudocode-
## Big O algoritma
Big-O , yang biasa disebut sebagai " Orde ", adalah cara untuk menyatakan batas atas kompleksitas waktu suatu algoritma, karena ia menganalisis situasi terburuk dari algoritma tersebut. Ia memberikan batas atas waktu yang dibutuhkan oleh suatu algoritma dalam hal ukuran input. Ia dilambangkan sebagai O(f(n)) , di mana f(n) adalah fungsi yang merepresentasikan jumlah operasi (langkah) yang dilakukan suatu algoritma untuk memecahkan masalah berukuran n .

#### refrences:
https://www.geeksforgeeks.org/analysis-algorithms-big-o-analysis/

##  Hitung Big O dari algoritma Sequential Search
#### Waktu kompleksitas (time complexity)
Umumnya, selalu ada lebih dari satu cara untuk menyelesaikan masalah dalam ilmu komputer dengan algoritma yang berbeda. Oleh karena itu, sangat diperlukan untuk menggunakan suatu metode guna membandingkan solusi-solusi tersebut guna menilai mana yang lebih optimal. Metode tersebut harus:

Terlepas dari mesin dan konfigurasinya, di mana algoritma tersebut berjalan.
Menunjukkan korelasi langsung dengan jumlah masukan.
Dapat membedakan dua algoritma dengan jelas tanpa ambiguitas.

#### Ruang Kompleksitas (space komplexity)
Kompleksitas waktu suatu algoritma mengukur jumlah waktu yang dibutuhkan oleh suatu algoritma untuk berjalan sebagai fungsi dari panjang input. Perhatikan bahwa waktu untuk berjalan adalah fungsi dari panjang input dan bukan waktu eksekusi aktual dari mesin tempat algoritma tersebut berjalan.
Algoritma yang valid membutuhkan waktu yang terbatas untuk dieksekusi. Waktu yang dibutuhkan oleh algoritma untuk menyelesaikan masalah yang diberikan disebut kompleksitas waktu  algoritma. Kompleksitas waktu merupakan ukuran yang sangat berguna dalam analisis algoritma.

#### references Ruang Kompleksitas dan aktu kompleksitas

https://www.geeksforgeeks.org/time-complexity-and-space-complexity/
