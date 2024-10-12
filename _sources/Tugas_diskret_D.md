---
title: Himpunan

---



NAMA :Fahrizal umam
NIM  :230411100056
KELAS:IF2D

# PEMBUKTIAN DAN CONTOH DE MORGAN

$$
\begin{aligned}
& \overline{A \cap B}=\bar{A} \cup \bar{B} \\
& \overline{A \cup B}=\bar{A} \cap \bar{B}
\end{aligned}
$$

### Hukum De Morgan 1:
$$
\begin{aligned}
& \overline{A \cap B}=\bar{A} \cup \bar{B}
\end{aligned}
$$

Ini berarti komplemen dari irisan dua himpunan adalah sama dengan gabungan dari komplemen masing-masing himpunan.

##### Pembuktian dengan logika himpunan:
1. Misalkan $x \in \overline{A \cap B}$, ini berarti $x$ tidak berada di $A \cap B$, sehingga $x \notin A$ atau $x \notin B$.
2. Oleh karena itu, $x \in \bar{A}$ atau $x \in \bar{B}$, sehingga $x \in \bar{A} \cup \bar{B}$.
3. Sebaliknya, jika $x \in \bar{A} \cup \bar{B}$, maka $x \in \bar{A}$ atau $x \in \bar{B}$, yang berarti $x \notin A$ atau $x \notin B$.
4. Ini berarti $x \notin A \cap B$, sehingga $x \in \overline{A \cap B}$.

##### Karena kedua arah tersebut benar, maka:
$$
\begin{aligned}
& \overline{A \cap B}=\bar{A} \cup \bar{B}
\end{aligned}
$$

### Hukum De Morgan 2:

$$
\overline{A \cup B}=\bar{A} \cap \bar{B}
$$


Ini berarti komplemen dari gabungan dua himpunan adalah sama dengan irisan dari komplemen masing-masing himpunan.

Pembuktian dengan logika himpunan:
1. Misalkan $x \in \overline{A \cup B}$, ini berarti $x$ tidak berada di $A \cup B$, sehingga $x \notin A$ dan $x \notin B$.
2. Oleh karena itu, $x \in \bar{A}$ dan $x \in \bar{B}$, sehingga $x \in \bar{A} \cap \bar{B}$.
3. Sebaliknya, jika $x \in \bar{A} \cap \bar{B}$, maka $x \in \bar{A}$ dan $x \in \bar{B}$, yang berarti $x \notin A$ dan $x \notin B$.
4. Ini berarti $x \notin A \cup B$, sehingga $x \in \overline{A \cup B}$.

Karena kedua arah tersebut benar, maka:

$$
\overline{A \cup B}=\bar{A} \cap \bar{B}
$$

contoh:

Misal:
- $A=\{1,2,3\}$
- $B=\{3,4\}$
- Sernesta $U=\{1,2,3,4,5\}$

Kita akan mengecek kedua hukum De Morgan.
Contoh untuk Hukum De Morgan 1:

$$
\overline{A \cap B}=\bar{A} \cup B
$$

1. Irisan $A \cap B$ :

$$
A \cap B=\{3\}
$$

2. Komplemen $\overline{A \cap B}$ dalam semesta $U$ :

$$
\overline{A \cap B}=U-(A \cap B)=\{1,2,3,4,5\}-\{3\}=\{1,2,4,5\}
$$

3. Komplemen $\bar{A}$ dan $\bar{B}$ :
- $\bar{A}=I J-A=\{1,2,3,4,5\}-\{1,2,3\}=\{4,5\}$
- $\bar{B}=U-B=\{1,2,3,4,5\}-\{3,4\}=\{1,2,5\}$
4. Gabungan $\bar{A} \cup \bar{B}$ :

$$
\bar{A} \cup \bar{B}=\{4,5\} \cup\{1,2,5\}=\{1,2,4,5\}
$$


Kita dapat melihat balnwa

$$
\overline{A \cap B}=\bar{A} \cup \bar{B}=\{1,2,4,5\}
$$

### Contoh untuk Hukum De Morgan 2:

$$
\overline{A \cup B}=\bar{A} \cap B
$$

1. Gabungan $A \cup B$ :

$$
A \cup B=\{1,2,3,4\}
$$

2. Komplemen $\overline{A \cup B}$ dalam semesta $U$ :

$$
\overline{A \cup B}=U-(A \cup B)=\{1,2,3,4,5\}-\{1,2,3,4\}=\{5\}
$$

3. Komplemen $\bar{A}$ dan $B$ :
- $A=\{4,5\}$
- $B=\{1,2,5\}$
4. Irisan $A \cap B$ :

$$
A \cap B=\{4,5\} \cap\{1,2,5\}=\{5\}
$$


Kita dapat melihat balows

$$
\overline{A \cup B}=\bar{A} \cap \bar{B}=\{5\}
$$


Jadi. Hukum De Morgan 2 juga terbukti benar dalam cantoh ini.

# PEMBUKTIAN DAN CONTOH ABSORPSION LAWS

$$
\begin{aligned}
& A \cup(A \cap B)=A \\
& A \cap(A \cup B)=A
\end{aligned}
$$



### Hukum Absorpsi 1:

$$
A \cup(A \cap B)=A
$$


Penjelasan:

Gabungan antara himpunan $A$ dan irisan $A$ dengan $B$ akan selalu menghasilkan himpunan $A$ kembali.

Pembulttian:
1. Bukti bahwa sisi kiri merupakan subset dari sisi kanan (C):
- Ambil sembarang elemen $x \in A \cup(A \cap B)$.
- Maka, $x \in A$ atau $x \in A \cap B$.
- Jika $x \in A$, maka jelas $x \in A$
- Jika $x \in A \cap B$, maka $x \in A$ dan $x \in B$, sehingga $x \in A$.
- Oleh karena itu, dalam ketha kasus, $x \in A$.
- Jadi $A \cup(A \cap B) \subseteq A$.
2. Bukti bahwa sisi kanan merupakan subset dari sisi kiri (2):
- Ambil sembarang elemen $x \in A$.
- Karena $x \in A$, maka $x \in A \cup(A \cap B)$ karena $x \in A)$
- $\quad \operatorname{ardi} A \subseteq A \cup(A \cap B)$.
3. Kesimpular:
- Karena $A \cup(A \cap B) \subseteq A$ dan $A \subseteq A \cup(A \cap B)$, maka:

$$
A \cup(A \cap B)=A
$$

### Hukum Absorpsi 2:

$$
A \cap(A \cup B)=A
$$


Penjelasan:
Irisan antara himpunan $A$ dan gabungan $A$ dengan $B$ akan selalu menghasilkan himpunan $A$ kembali.

Pembultian:
1. Bukti bahwa sisi kiri merupakan subset dari sisi kanan ( $G$ ):
- Ambil sembarang elemen $x \in A \cap(A \cup B)$.
- Maka, $x \in A$ dan $x \in A \cup B$.
- Karena $x \in A$, maka $x \in A$.
- Jadi $A \cap(A \cup B) \subseteq A$.
2. Bukti bahwa sisi kanan merupakan subset dari sisi kiri (2):
- Ambil sembarang elemen $x \in A$.
- Karena $x \in A$, maka $x \in A \cup B$ (karena $x \in A$ atas $x \in B$ ).
- Mala $x \in A$ dan $x \in A \cup B$, sehingga $x \in A \cap(A \cup B)$.
- Jadi $A \subseteq A \cap(A \cup B)$.
3. Kesimpulan:
- Karena $A \cap(A \cup B) \subseteq A \operatorname{dan} A \subseteq A \cap(A \cup B)$, makax $A \cap(A \cup B)=A$

#### Contoh untuk Hukum Absorpsi 1:
Misalkan:
- $A=\{1,2,3\}$
- $B=\{3,4,5\}$
1. Inisan $A \cap B$ :

$$
A \cap B=\{3\}
$$

2. Gabungan $A \cup(A \cap B)$ :

$$
A \cup(A \cap B)=\{1,2,3\} \cup\{3\}=\{1,2,3\}=A
$$


Jadi, hukum ahsarpsi pertarna terbulti benar ctalam cantah ini.

#### Contoh untuk Hukum Absorpsi 2:
Dengan himpunan yang sama
1. Gabungan $A \cup B$ :

$$
A \cup B=\{1,2,3,4,5\}
$$

2. Irisan $A \cap(A \cup B)$ :

$$
A \cap(A \cup B)=\{1,2,3\} \cap\{1,2,3,4,5\}=\{1,2,3\}=A
$$


Jadi, hukum absarpsi kedua juga terbukti benar dalam contoh ini.

#  PEMBUKTIAN DAN CONTOH COMPLEMENT LAWS
$$
\begin{aligned}
& A \cup \bar{A}=U \\
& A \cap \bar{A}=\emptyset
\end{aligned}
$$

Pembuktian Hukum Komplemen
### Pembuktian Hukum Komplemen 1:
$A \cup \bar{A}=U$
- Misalkan $x \in A \cup \bar{A}$, artinya $x$ ada di $A$ atau di $\bar{A}$. Karena $\bar{A}$ adalah komplemen dari $A$, semua elemen di luar $A$ ada di $\bar{A}$. Maka, setiap elemen $x$ di semesta $U$ pasti berada di $A$ atau $\bar{A}$. Oleh karena itu, $x$ pasti ada di $U$.
- Sebaliknya, setiap elemen $x$ di semesta $U$ pasti berada di $A$ atau $\bar{A}$, karena $\bar{A}$ adalah komplemen dari $A$.

Karena kedua arah benar, maka:

$$
A \cup \bar{A}=U
$$


### Pembuktian Hukum Komplemen 2:

$$
A \cap \bar{A}=\emptyset
$$

- Misalkan $x \in A \cap \bar{A}$, artinya $x$ ada di $A$ dan di $\bar{A}$. Ini tidak mungkin, karena $\bar{A}$ adalah komplemen dari $A$, yang berarti bahwa setiap elemen di $A$ tidak ada di $\bar{A}$, dan sebaliknya. Maka, tidak ada elemen yang bisa berada di $A$ dan $\bar{A}$ secara bersamaan. Oleh karena itu, $A \cap$ $\bar{A}$ adalah himpunan kosong ( $\emptyset$ ).
- Sebaliknya, jika $x \in \emptyset$, maka jelas $x$ tidak bisa berada di $A \cap \bar{A}$.

Karena kedua arah benar, maka:

$$
A \cap \bar{A}=\emptyset
$$

Contoh Hukum Komplemen
Misalikar:
- $A=\{1,2,3\}$
- Semesta $U=\{1,2,3,4,5\}$

Maka, kamplemen dari $A$ adalah:

$$
\bar{A}=U-A=\{4,5\}
$$


### Contoh untuk Hukum Komplemen 1:

$$
A \cup \bar{A}=U
$$

1. Gabungan $A \cup A$ :

$$
A \cup A=\{1,2,3\} \cup\{4,5\}=\{1,2,3,4,5\}=U
$$


Jadi kita mendapatkan:

$$
A \cup \bar{A}=U=\{1,2,3,4,5\}
$$


Hukum Komplemen 1 terbukti benar.
### Contah untuk Hukum Komplemen 2:

$$
A \cap \bar{A}=0
$$

1. Irisan $A \cap \bar{A}:$

$$
A \cap \bar{A}=\{1,2,3\} \cap\{4,5\}=0
$$


Jadi kita mendapotkan:

$$
A \cap A=\emptyset
$$


Hukum Komplemen 2 terbukti benar.