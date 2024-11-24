---
title: DERETAN_DAN_REKURSIF

---

# Deretan_Dan_Rekursif
## Deretan
Deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu

Definisi: Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.

$$
\mathrm{N}=\{1,2,3,4, \ldots\}
$$

S misalnya $\{2,4,6,8, \ldots\}, \quad\{1 / 3,1 / 5,1 / 7, \ldots\}$ dsb

Notasi deretan: $\left\{a_n\right\}$
### Deret aritmatika
Deret dengan pola kenaikan atau penurunan tetap

Contoh: $2,5,8,11,14, \ldots$
- Rumus suku ke-n:
$$
U_n=a+(n-1) \cdot b
$$

Di mana:
- a: suku pertama
- $b$ : beda (selisih antar suku
- $n$ : nomor suku yang dicari
### Deret Geometri
Deret dengan pola kelipatan tetap.

- Contoh: 3,6,12,24,48, ...
- Rumus suku ke-n:
$$
U_n=a \cdot r^{(n-1)}
$$

Di mana:
- a: suku pertama
- r: rasio (perbandingan antar suku,
- n: nomor suku yang dicari
### Deret bilanga kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.

- Contoh: $1,4,9,16,25, \ldots$
- Rumus suku ke-n:
$$
U_n=n^2
$$
### Deret Kubik
Deret dengan pola nilai berupa kubik bilangan bulat.

- Contoh: 1,8,27,64,125, ...
- Rumus suku ke-n:
$$
U_n=n^3
$$
### Deret fibonacci
Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.

Contoh: $0,1,1,2,3,5,8, \ldots$
- Rumus suku ke-n (rekursif):
$$
F_n=F_{n-1}+F_{n-2}, F_0=0, F_1=1
$$
### Deret String
String adalah deretan berhingga karakter berbentuk
$$ a1a2a3a4…an $$
    Panjang string S adalah jumlah karakter di dalam string tersebut
     
    Contoh:  informatika adalah string dengan panjang 11 karakter
	         10100101 adalah string biner dengan panjang 8 bit

String kosong dilambangkan dengan , panjangnya = 0

### Penjumlahan deretan
  Jumlah deretan
  
  $$ am, am+1, am+2, …, an $$
  
adalah

$$ am + am+1 + am+2 + … + an $$

atau dalam notasi sumasi:

$$
\sum_{k=m}^n a_k
$$
$k$ adalah indeks summasi, $m$ adalah batas bawah indeks, $n$ adalah batas atas indeks

Contoh 2: Berapa nilai $\sum_{k=1}^5 k^2$ ?
Jawaban:
$$
\sum_{k=1}^5 k^2=1^2+2^2+3^2+4^2+5^2=1+4+9+16+25=55
$$

Contoh 3: Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0 , akibatnya:
$$
\sum_{k=1}^5 k^2=\sum_{k=0}^4(k+1)^2
$$

Contoh 4: Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya
$$
\sum_{k=1}^{100} k^2=\sum_{k=1}^{49} k^2+\sum_{k=50}^{100} k^2
$$

### Tugas pembuktian dari 3 rumus di bawah 

$$
\begin{array}{|l|l|}
\hline \text { TABLE } 2 \text { Some Useful Summation Formulae. } \\
\hline \text { Sum } & \text { Closed Form } \\
\hline \sum_{k=0}^n a r^k(r \neq 0) & \frac{a r^{n+1}-a}{r-1}, r \neq 1 \\
\sum_{k=1}^n k & \frac{n(n+1)}{2} \\
\sum_{k=1}^n k^2 & \frac{n(n+1)(2 n+1)}{6} \\
\sum_{k=1}^n k^3 & \frac{n^2(n+1)^2}{4} \\
\sum_{k=0}^{\infty} x^k,|x|<1 & \frac{1}{1-x} \\
\sum_{k=1}^{\infty} k x^{k-1},|x|<1 & \frac{1}{(1-x)^2} \\
\hline
\end{array}
$$

### jawaban

1. Rumus Jumlah Deret Geometris
$$
S_n=\frac{a r^{n+1}-a}{r-1}, \quad r \neq 1
$$

Contoh:
deret geometris $2,6,18,54, \ldots$.
Diketahui:
- $\quad a=2$ (suku pertama)
- $r=3$ (rasio)
- $n=4$ (jumlah 5 suku berarti hingga $r^4$ )

Gunakan rumus:
$$
\begin{gathered}
S_5=\frac{2\left(3^5\right)-2}{3-1} \\
S_5=\frac{2(243)-2}{2} \\
S_5=\frac{486-2}{2}=\frac{484}{2}=242
\end{gathered}
$$

Hasil: Jumlah 5 suku pertama adalah 242.

2. Rumus Jumlah Bilangan Bulat Pertama
$$
S=\frac{n(n+1)}{2}
$$

Contoh:
bilangan bulat dari 1 hingga 10.
Diketahui:
- $n=10$

Gunakan rumus:
$$
\begin{gathered}
S=\frac{10(10+1)}{2} \\
S=\frac{10 \cdot 11}{2}=\frac{110}{2}=55
\end{gathered}
$$

Hasil: Jumlah bilangan dari 1 hingga 10 adalah 55 .
Verifikasi manual:
$$
1+2+3+4+5+6+7+8+9+10=55
$$

3. Rumus Jumlah Kuadrat Bilangan Bulat Pertama
$$
S=\frac{n(n+1)(2 n+1)}{6}
$$

Contoh:
jumlah kuadrat bilangan bulat dari 1 hingga 5 .
Diketahui:
- $n=5$

Gunakan rumus:
$$
\begin{gathered}
S=\frac{5(5+1)(2(5)+1)}{6} \\
S=\frac{5(6)(11)}{6} \\
S=\frac{330}{6}=55
\end{gathered}
$$

Hasil: Jumlah kuadrat bilangan dari 1 hingga 5 adalah 55 .
Verifikasi manual:
$$
1^2+2^2+3^2+4^2+5^2=1+4+9+16+25=55
$$

### Sumasi ganda
Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.

Contoh: $\sum_{i=1}^4 \sum_{j=1}^3 i j$

Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu dilanjukan dengan sumasi terluar:
$$
\sum_{i=1}^4 \sum_{j=1}^3 i j=\sum_{i=1}^4(i+2 i+3 i)=\sum_{i=1}^4 6 i=6+12+18+24=60
$$

Contoh penggunaan: Berapa kali operasi + dilakukan di dalam algoritma di bawah ini? 

x = 0
for j = 1 to 10 do
    for k = 1 to j do
           x = x + 2
   end for
end for 

Penyelesaian:
Operasi + terdapat di dalam pernyataan $x=x+2$
Operasi ini dilakukan satu kali pada setiap pengulangan Jumlah seluruh operasi + adalah:
$$
\begin{aligned}
\mathrm{t} & =\sum_{j=1}^{10} \sum_{k=1}^j 1 \\
& =\sum_{j=1}^{10}(1+1+\ldots+1 \text { sebanyak } j \text { kali }) \\
& =\sum_{j=1}^{10} j \\
& =\frac{10(10+1)}{2}=55
\end{aligned}
$$

### rekursi
Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 

Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

### Fungsi Rekursif
Fungsi rekursif didefinisikan oleh dua bagian:
 (i)  Basis 
Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
 
 (ii)  Rekurens
Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

Contoh 6: Misalkan $f$ didefinsikan secara rekusif sbb
$$
f(n)=\left\{\begin{array}{cll}
3 & , n=0 & \text { basis } \\
2 f(n-1)+4 & , n>0 & \text { rekurens }
\end{array}\right.
$$

Tentukan nilai $\mathrm{f}(4)$ !
$$
\text { Solusi: } \begin{aligned}
& f(4)=2 f(3)+4 \\
= & 2(2 f(2)+4)+4 \\
= & 2(2(2 f(1)+4)+4)+4 \\
= & 2(2(2(2 f(0)+4)+4)+4)+4 \\
= & 2(2(2(2 \cdot 3+4)+4)+4)+4 \\
= & 2(2(2(10)+4)+4)+4 \\
= & 2(2(24)+4)+4 \\
= & 2(52)+4 \\
= & 108
\end{aligned}
$$

Cara lain menghitungnya:
$$
\begin{aligned}
& f(0)=3 \\
& f(1)=2 f(0)+4=2 \cdot 3+4=10 \\
& f(2)=2 f(1)+4=2 \cdot 10+4=24 \\
& f(3)=2 f(2)+4=2 \cdot 24+4=52 \\
& f(4)=2 f(3)+4=2 \cdot 52+4=108
\end{aligned}
$$
$$
\text { Jadi, } f(4)=108
$$




