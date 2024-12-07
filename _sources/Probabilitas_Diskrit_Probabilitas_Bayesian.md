---
title: Probabilitas_Diskrit_Probabilitas_Bayesian

---

# Naive Bayes
Naive Bayes adalah salah satu dari banyak model pengklasifikasi yang ada. Model ini pada dasarnya didasarkan pada Teorema Bayes dan menggunakan asumsi "naif" bahwa semua fitur bersifat independen.

X₁ (Suhu) dan X₂ (Angin). Fitur X₁ dapat mengasumsikan tiga nilai diskret (rendah, sedang, tinggi), sementara fitur X₂ dapat mengasumsikan tiga nilai diskret yang berbeda (lemah, normal, kuat). Untuk menyederhanakannya, kita akan menggunakan X₁ sebagai singkatan untuk Suhu, dan X₂ untuk Angin. Target Pantai kita akan disingkat menjadi B.

Tabel di bawah ini berisi beberapa catatan fitur X₁ , X₂ , dan target B. Yang terakhir dapat mengasumsikan nilai Boolean benar (pergi ke pantai) atau salah (jangan pergi ke pantai).

$$
\begin{array}{|c|c|c|}
\hline \text { Temperature ( } X_1 \text { ) } & \text { Wind }\left(X_2\right) & \text { Beach (B) } \\
\hline \text { low (L) } & \text { weak (W) } & \text { true (T) } \\
\text { high (H) } & \text { weak (W) } & \text { false (F) } \\
\text { medium (M) } & \text { strong (S) } & \text { false (F) } \\
\text { low (L) } & \text { normal (N) } & \text { true (T) } \\
\text { medium (M) } & \text { normal (N) } & \text { true (T) } \\
\hline
\end{array}
$$

dengan mempertimbangkan sepasang fitur baru (X₁, X₂) , menentukan target B ( benar atau salah ). Tentu saja contoh ini sangat disederhanakan, demi penjelasan. Jadi, kami akan berasumsi bahwa sepasang fitur baru tersebut belum direkam.

Secara sederhana, kita dapat mengatakan: jika suhu sedang (tidak tinggi, tidak rendah) dan angin lemah, haruskah kita pergi ke pantai atau tidak? Kita juga berasumsi bahwa kita memiliki skala sendiri untuk suhu dan angin, sehingga kita tahu persis apa arti masing-masing status tersebut.

Secara Matematika, kita mencari probabilitas tertinggi diantara dua hal berikut: probabilitas bahwa Pantai = benar , dengan asumsi bahwa Suhu = sedang & Angin = lemah ,

$$
P\left(B=\mathrm{T} \mid X_1=\mathrm{M}, X_2=\mathrm{W}\right)
$$
dan kemungkinan bahwa Pantai $=$ salah, mengingat Suhu $=$ sedang \& Angin $=$ lemah,
$$
P\left(B=\mathbf{F} \mid X_1=\mathrm{M}, X_2=\mathrm{W}\right)
$$

Mana pun yang lebih besar akan secara otomatis memberi kita jawaban atas pertanyaan tersebut. Perhatikan bahwa model ini murni berdasarkan probabilitas.

Bagaimana kemungkinan/probabilitas usia paruh baya tekanan darah sangat tinggi kemungkinan penyakit Hipertensi (H) atau Tidak (T)

$$
\begin{array}{llll}
\text { No } & \text { Usia } & \text { Tekanan Darah } & \text { Penyakit (H/T) } \\
\hline 1 & \text { Muda } & \text { Normal } & \text { T } \\
2 & \text { Muda } & \text { Tinggi } & \text { T } \\
3 & \text { Paruh baya } & \text { Normal } & \text { T } \\
4 & \text { Paruh baya } & \text { Tinggi } & \text { H } \\
5 & \text { Tua } & \text { Normal } & \text { H } \\
6 & \text { Tua } & \text { Sangat Tinggi } & \text { H } \\
7 & \text { Muda } & \text { Normal } & \text { T } \\
8 & \text { Tua } & \text { Tinggi } & \text { H }
\end{array}
$$

* Hitunglah probabilitas Hipertensi terhadap usia paruh baya tekanan darah sangat tinggi

* Hitunglah probabilitas Tidak  Hipertensi terhadap usia paruh baya tekanan darah sangat tinggi

  $$
    P(H|\text{Paruh Baya, Sangat Tinggi}) = 
    \begin{array}{c}
        \displaystyle P(\text{Paruh Baya, Sangat Tinggi}|H) \cdot P(H) \\ 
        \hline 
        \displaystyle P(\text{Paruh Baya, Sangat Tinggi})
    \end{array}
    $$
    
    
     $$
    P(T|\text{Paruh Baya, Sangat Tinggi}) = 
    \begin{array}{c}
        \displaystyle P(\text{Paruh Baya, Sangat Tinggi}|T) \cdot P(T) \\ 
        \hline 
        \displaystyle P(\text{Paruh Baya, Sangat Tinggi})
    \end{array}
    $$
Hitung Probabilitas Prior:
* P(H): Proporsi data dengan penyakit H
* P(T): Proporsi data dengan penyakit T

Hitung Likelihood:

* (Paruh Baya,Sangat Tinggi∣H): Kemungkinan bahwa seseorang yang memiliki 
𝐻 H berusia "paruh baya" dengan tekanan darah "sangat tinggi".

* P(Paruh Baya,Sangat Tinggi∣ T): Kemungkinan bahwa seseorang yang tidak memiliki 𝐻
H (atau 𝑇) berusia "paruh baya" dengan tekanan darah "sangat tinggi".

Hitung Evidence:

* P(Paruh Baya,Sangat Tinggi): Proporsi keseluruhan data yang memiliki usia "paruh baya" dan tekanan darah "sangat tinggi".

Prior Probabilities:
* Total data 𝑛=8
* $$ \begin{array}
    \item Data (H = 4), sehingga (P(H) = \frac{4}{8} = 0.5).\end{array}$$
    
 $$ \begin{array}  
    \item Data (T = 4), sehingga (P(T) = \frac{4}{8} = 0.5).
\end{array}$$

Likelihoods:
* Dari tabel, tidak ada data eksplisit untuk "paruh baya" dengan tekanan darah "sangat tinggi". Namun, kita bisa menggunakan asumsi atau interpolasi berdasarkan pola data yang tersedia. Jika tidak ada pengamatan, probabilitas dapat dianggap nol.

Evidence:
* Jika tidak ada pengamatan eksplisit untuk kombinasi "paruh baya" dan "sangat tinggi", maka 
P(Paruh Baya,Sangat Tinggi)=0, yang membuat perhitungan probabilitas menjadi tak terdefinisi.




# Teorema Bayes
Teorema Bayes memberi tahu kita cara menghitung probabilitas bersyarat dari suatu kejadian berdasarkan pengetahuan sebelumnya tentang kejadian tersebut. Dengan kata lain, Teorema Bayes memungkinkan kita menghitung probabilitas posterior berdasarkan probabilitas sebelumnya 

$$P(E|C) = \frac{P(C|E) \cdot P(E)}{P(C)}$$

Dalam persamaan ini, kita memiliki empat istilah berikut:

*1. P(E|C): Probabilitas kondisi E diberikan bahwa C terjadi.

Ini adalah probabilitas dari peristiwa E yang terjadi, dengan informasi bahwa peristiwa C sudah terjadi. Dalam istilah lain, ini disebut posterior probability atau probabilitas posterior. Ini adalah apa yang kita coba untuk hitung atau pelajari.

2. P(C|E): Probabilitas kondisi C diberikan bahwa E terjadi.

Ini adalah probabilitas dari peristiwa C terjadi dengan asumsi bahwa peristiwa E sudah terjadi. Ini disebut likelihood atau kemungkinan, karena menunjukkan seberapa besar kemungkinan data (peristiwa C) terjadi jika kita sudah tahu bahwa peristiwa E sudah terjadi.

3. P(E): Prior probability dari peristiwa E.

Ini adalah probabilitas dari peristiwa E terjadi tanpa memperhitungkan informasi dari C. Ini disebut prior probability karena ini adalah pengetahuan kita sebelumnya (sebelum memperhitungkan data atau informasi baru).

4. P(C ): Probabilitas dari peristiwa C.

Ini adalah probabilitas bahwa peristiwa C terjadi secara keseluruhan, tanpa memperhatikan apakah peristiwa E terjadi atau tidak. Ini disebut normalizing constant atau konstanta normalisasi, yang bertujuan untuk memastikan bahwa total probabilitas P(E|C) adalah angka yang valid (antara 0 dan 1).

### references
https://tvovalentin.medium.com/the-math-behind-a-discrete-naive-bayes-classifier-abdc86e1cbf3