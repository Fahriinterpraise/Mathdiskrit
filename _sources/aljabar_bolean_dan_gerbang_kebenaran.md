---
title: aljabar bolean dan gerbang kebenaran

---

### Aljabar boolean
Aljabar Boolean adalah sistem matematika yang digunakan untuk operasi logika dengan dua nilai kebenaran, yaitu benar (1) dan salah (0). Aljabar Boolean sangat penting dalam desain sirkuit digital dan komputer karena mendasari logika biner yang digunakan dalam komputasi. Beberapa operasi dasar dalam aljabar Boolean adalah:

Operasi Dasar Aljabar Boolean:

1. NOT (-): Operasi negasi yang membalik nilai kebenaran.
2. AND (∧): Operasi logika yang hanya benar jika kedua operandnya benar.


Tabel kebenaran AND:

\begin{array}{c|c|c}
   A & B & A \land B \\
   \hline
   0 & 0 & 0 \\
   0 & 1 & 0 \\
   1 & 0 & 0 \\
   1 & 1 & 1 \\
   \end{array}

3. OR (∨): Operasi logika yang benar jika salah satu atau kedua operandnya benar.
Tabel kebenaran OR:

\begin{array}{c|c|c}
   A & B & A \lor B \\
   \hline
   0 & 0 & 0 \\
   0 & 1 & 1 \\
   1 & 0 & 1 \\
   1 & 1 & 1 \\
   \end{array}

4. XOR (<->): Operasi OR eksklusif yang hanya benar jika salah satu operand benar, tetapi tidak keduanya.
Tabel kebenaran XOR:



\begin{array}{c|c|c}
   A & B & A \oplus B \\
   \hline
   0 & 0 & 0 \\
   0 & 1 & 1 \\
   1 & 0 & 1 \\
   1 & 1 & 0 \\
   \end{array}

### Gerbang Logika

Gerbang logika adalah implementasi fisik dari operasi aljabar Boolean dalam sirkuit digital. Setiap gerbang logika menerima input biner (0 atau 1) dan menghasilkan output berdasarkan aturan logika tertentu.

1. Gerbang NOT (Inverter):

   Fungsi: Membalik nilai input.

   Simbol: Segitiga dengan lingkaran kecil di      ujungnya.

   Jika input = 1, maka output = 0, dan            sebaliknya.



2. Gerbang AND:

    Fungsi: Menghasilkan output 1 jika semua       inputnya 1.

    Simbol: Bentuk setengah lingkaran dengan       dua input dan satu output.

    Tabel kebenaran sama seperti operasi AND.



3. Gerbang OR:

    Fungsi: Menghasilkan output 1 jika salah       satu atau lebih inputnya 1.

    Simbol: Bentuk seperti panah dengan dua         input dan satu output.

    Tabel kebenaran sama seperti operasi OR.



4. Gerbang XOR:

Fungsi: Menghasilkan output 1 jika salah satu inputnya benar, tetapi tidak keduanya.

Simbol: Seperti gerbang OR tetapi dengan garis tambahan di depan.

Tabel kebenaran sama seperti operasi XOR.




Penggunaan Aljabar Boolean dan Gerbang Logika

Sirkuit digital seperti komputer, kalkulator, dan perangkat elektronik lainnya menggunakan kombinasi gerbang logika untuk memproses informasi biner (0 dan 1).

Desain rangkaian digital menggunakan gerbang logika untuk membuat perangkat yang mampu melakukan operasi aritmatika, pengambilan keputusan, kontrol logis, dan lainnya.


Contoh Sederhana:

Jika kita memiliki dua input  dan , dengan aljabar Boolean kita bisa menulis ekspresi:

yang menunjukkan bagaimana aljabar Boolean digunakan untuk menyederhanakan logika. Gerbang logika kemudian dapat digunakan untuk mengimplementasikan ekspresi ini dalam bentuk rangkaian.