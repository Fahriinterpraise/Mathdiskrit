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
Big O Notation adalah notasi matematika yang digunakan untuk menggambarkan kompleksitas algoritma dalam hal waktu (kompleksitas waktu) dan ruang (kompleksitas ruang). Notasi ini memberikan cara untuk membandingkan seberapa efisien algoritma dalam hal penggunaan sumber daya saat ukuran inputnya meningkat. Big O Notation fokus pada perilaku algoritma dalam skenario terburuk dan menggambarkan pertumbuhan fungsi yang terkait dengan waktu eksekusi atau penggunaan memori.

### Komponen Big O Notation
Pertumbuhan Fungsi: Big O menggambarkan seberapa cepat waktu eksekusi atau ruang yang dibutuhkan oleh algoritma bertambah seiring bertambahnya ukuran input (n). Hal ini memungkinkan kita untuk mengabaikan konstanta dan faktor kecil, dan hanya memperhatikan aspek yang paling signifikan dari pertumbuhan.

Notasi: Dalam Big O Notation, kita biasanya menggunakan huruf "O" diikuti oleh fungsi yang menunjukkan hubungan antara ukuran input dan waktu eksekusi. Contohnya, O(n), O(log n), O(n²), dan lain-lain.

### Contoh Fungsi Big O
**O(1):** Kompleksitas konstan. Waktu eksekusi tidak tergantung pada ukuran input. Contoh: Mengakses elemen di array dengan indeks tertentu.

O(log n): Kompleksitas logaritmik. Waktu eksekusi meningkat secara logaritmik seiring bertambahnya ukuran input. Contoh: Algoritma Binary Search.

**O(n):** Kompleksitas linier. Waktu eksekusi meningkat secara langsung sebanding dengan ukuran input. Contoh: Algoritma Sequential Search.

**O(n log n):** Kompleksitas n log n. Umumnya muncul dalam algoritma pengurutan efisien seperti Merge Sort dan Quick Sort.

**O(n²):** Kompleksitas kuadratik. Waktu eksekusi meningkat dengan kuadrat dari ukuran input. Contoh: Algoritma pengurutan gelembung (Bubble Sort) dan pengurutan seleksi (Selection Sort).

**O(2^n):** Kompleksitas eksponensial. Waktu eksekusi meningkat secara eksponensial seiring bertambahnya ukuran input. Contoh: Algoritma yang menyelesaikan masalah kombinatorial seperti pencarian semua subset dari himpunan.

### Pentingnya Big O Notation
**Perbandingan Algoritma:** Dengan Big O, kita dapat membandingkan efisiensi berbagai algoritma untuk memahami mana yang lebih baik untuk digunakan dalam situasi tertentu.

**Skalabilitas:** Big O membantu dalam memahami bagaimana algoritma akan berperilaku seiring bertambahnya ukuran input, yang sangat penting dalam pengembangan perangkat lunak dan sistem besar.

**Optimisasi:** Dengan mengetahui kompleksitas suatu algoritma, kita bisa mencari cara untuk mengoptimalkan kode agar lebih efisien, baik dalam hal waktu maupun ruang.


#### refrences:
https://www.geeksforgeeks.org/analysis-algorithms-big-o-analysis/

##  Hitung Big O dari algoritma Sequential Search
### Cara Kerja Sequential Search
Algoritma Sequential Search memeriksa setiap elemen dalam array satu per satu, mulai dari elemen pertama hingga elemen terakhir, sampai elemen yang dicari ditemukan atau sampai seluruh elemen telah diperiksa.

### Analisis Kompleksitas Waktu
**Kasus Terburuk:**

* Dalam kasus terburuk, elemen yang dicari berada di akhir array atau tidak ada dalam array sama sekali. Dalam situasi ini, algoritma harus memeriksa setiap elemen.

* Jika kita memiliki array dengan n elemen, maka algoritma akan melakukan n perbandingan.

* Oleh karena itu, dalam kasus terburuk, kompleksitas waktu adalah:
$$O(n)$$

**Kasus Terbaik:**

* Dalam kasus terbaik, elemen yang dicari berada di posisi pertama dalam array.

* Dalam situasi ini, algoritma hanya perlu melakukan satu perbandingan.

* Maka kompleksitas waktu dalam kasus terbaik adalah:

$$O(1)$$

**Kasus Rata-rata:**

* Rata-rata, jika kita mengasumsikan elemen yang dicari dapat ditemukan di mana saja dalam array, maka kita dapat memperkirakan bahwa kita akan memeriksa sekitar setengah dari elemen.

* Maka, dalam kasus rata-rata, kompleksitas waktu adalah:

$$O(n)$$
#### Waktu kompleksitas (time complexity)
Waktu Kompleksitas (Time Complexity) adalah pengukuran seberapa efisien suatu algoritma dalam hal waktu eksekusi seiring bertambahnya ukuran input. Waktu kompleksitas memberikan gambaran tentang jumlah langkah atau operasi yang diperlukan untuk menyelesaikan algoritma berdasarkan ukuran input yang diberikan. Ini sangat penting dalam analisis algoritma untuk memahami seberapa cepat atau lambat suatu algoritma akan berfungsi ketika menghadapi data yang lebih besar.

**Komponen Waktu Kompleksitas**
* **Input Size (Ukuran Input):** Ukuran input adalah faktor utama yang memengaruhi waktu eksekusi algoritma. Ukuran ini dapat berupa jumlah elemen dalam array, panjang string, atau dimensi struktur data lainnya.

* **Operasi Dasar:** Dalam analisis waktu kompleksitas, kita sering kali fokus pada operasi dasar yang dominan dalam algoritma, seperti perbandingan, penugasan, atau akses elemen. Ini membantu menyederhanakan analisis.

**Kasus Terburuk, Terbaik, dan Rata-rata:**

* Kasus Terburuk: Menghitung waktu eksekusi maksimum yang mungkin untuk input yang tidak menguntungkan.

* Kasus Terbaik: Menghitung waktu eksekusi minimum untuk input yang paling menguntungkan.

* Kasus Rata-rata: Menghitung waktu eksekusi untuk input yang dianggap tipikal atau umum.

**Contoh Penggunaan Waktu Kompleksitas**
Misalkan kita memiliki algoritma pengurutan yang mengurutkan array dengan cara membandingkan setiap elemen dengan elemen lainnya. Jika algoritma ini memiliki waktu kompleksitas O(n²), maka jika kita memiliki 100 elemen dalam array, waktu eksekusi akan meningkat menjadi 10.000 operasi. Namun, jika kita menggunakan algoritma pengurutan dengan kompleksitas O(n log n), waktu eksekusi akan jauh lebih efisien, bahkan untuk jumlah elemen yang besar.

#### Ruang Kompleksitas (space komplexity)
Ruang Kompleksitas (Space Complexity) adalah pengukuran seberapa banyak ruang memori yang dibutuhkan oleh suatu algoritma untuk menyelesaikan tugasnya, seiring bertambahnya ukuran input. Ini mencakup semua jenis memori yang digunakan selama eksekusi algoritma, termasuk ruang untuk variabel, struktur data, dan ruang tambahan untuk rekursi.

#### Komponen Ruang Kompleksitas
* Ruang Statis: Ruang yang dibutuhkan untuk menyimpan data yang sudah didefinisikan sebelum algoritma berjalan, seperti variabel yang dideklarasikan dan struktur data yang digunakan. Ruang ini tidak tergantung pada ukuran input.

* Ruang Dinamis: Ruang yang dibutuhkan selama eksekusi algoritma, termasuk ruang untuk data yang dihasilkan secara dinamis, seperti alokasi memori untuk array atau objek baru yang dibuat saat algoritma berjalan.

* Ruang Rekursif: Jika algoritma menggunakan rekursi, ruang yang digunakan oleh setiap panggilan rekursif juga harus diperhitungkan. Setiap panggilan rekursif menambah lapisan baru ke stack memori.

**Contoh Penggunaan Ruang Kompleksitas**
Misalkan kita memiliki algoritma yang mengurutkan array dengan menggunakan array tambahan untuk menyimpan elemen yang diurutkan. Jika kita memiliki array dengan n elemen, maka ruang kompleksitas untuk algoritma ini adalah O(n), karena kita memerlukan ruang tambahan yang sebanding dengan ukuran input.

Di sisi lain, jika kita menggunakan algoritma pengurutan in-place seperti Quick Sort, ruang kompleksitasnya bisa O(log n) jika kita mempertimbangkan ruang yang digunakan oleh panggilan rekursif, atau O(1) jika kita tidak menghitung stack rekursi.


#### references Ruang Kompleksitas dan aktu kompleksitas

https://www.geeksforgeeks.org/time-complexity-and-space-complexity/
