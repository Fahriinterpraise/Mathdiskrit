---
title: UAS

---

# UAS
NAMA :FAHRIZAL UMAM
NIM :23041110056

## SOAL 1

$$\begin{array}{c|c|c|c|cc}P&Q&R&\  S&(P\to\ Q)\to (R \to \  S)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{F}&\text{F}&\text{}\\\text{Т}&\text{Т}&\text{F}&\text{F}&\text{T}&\text{}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{T}&\text{}\\\text{T}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}\\\text{F}&\text{T}&\text{T}&\text{F}&\text{F}&\text{}\\\text{F}&\text{T}&\text{F}&\text{F}&\text{T}&\text{}\\\text{F}&\text{F}&\text{T}&\text{T}&\text{T}&\text{}\\\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}&\end{array}$$

## SOAL 2
![GRAF](https://hackmd.io/_uploads/SJUHrfEEkg.jpg)


## HITUNG CLOSENES CENTRALITY = G
Kedekatan Sentralitas (Simpul G):
Rumus:
$$
C_C(v)=\frac{N-1}{\sum_{u \neq v} d(v, u)}
$$
1. Identifikasi simpul dalam grafik:
- Sederhana: $A, B, C, D, E , F, G$
- Total simpul $N=7$.
2. Hitung jarak terpendek dari G ke simpulan lainnya:
- $(G, A)=2$
- $(G, B)=1$
- $(G, C)=1$
- $(G, D)=1$
- $(G, E)=1$
- $(G, F)=2$
3. Jumlah jarak total:
$$
\sum_{u \neq G} d(G, u)=2+1+1+1+1+2=8
$$
4. Substitusi ke rumus sentralitas kedekatan:
$$
C_C(G)=\frac{N-1}{\sum_{u \neq G} d(G, u)}=\frac{7-1}{8}=\frac{6}{8}=0.75
$$

## BEETWENES CENTRALITY = F

Langkah 1: Identifikasi simpul dalam graf
Simpul dalam graf adalah:
$$
\{A, B, C, D, E, F, G\}
$$

Langkah 2: jalur terpendek untuk semua pasangan simpul $(s, t)$


Contoh pasangan:
1. $(A, B)$
2. $(A, C)$
3. $(A, D)$, dan seterusnya.

Jalur yang relevan untuk simpul $F$ :
 simpul $F$ mungkin berada di jalur terpendek.
- $\quad(A, D)$ : Jalur terpendek adalah $A \rightarrow G \rightarrow D . F$ tidak terlibat.
- $\quad(A, E)$ : Jalur terpendek adalah $A \rightarrow G \rightarrow E . F$ tidak terlibat.
- $(A, F)$ : Jalur terpendek adalah $A \rightarrow G \rightarrow E \rightarrow F$. $F$ terlibat.
- $\quad(B, F)$ : Jalur terpendek adalah $B \rightarrow G \rightarrow E \rightarrow F$. $F$ terlibat.
- $(C, F)$ : Jalur terpendek adalah $C \rightarrow G \rightarrow E \rightarrow F$. $F$ terlibat.

Langkah 3: Hitung kontribusi $F$ untuk setiap pasangan

- Pasangan $(A, F)$ :
- Total jalur terpendek $=1$ (hanya $A \rightarrow G \rightarrow E \rightarrow F$ ).
- Jalur melalui $F=1$.
- Kontribusi $=1 / 1=1$.
- Pasangan $(B, F)$ :
- Total jalur terpendek $=1$ (hanya $B \rightarrow G \rightarrow E \rightarrow F$ ).
- Jalur melalui $F=1$.
- Kontribusi $=1 / 1=1$.
- Pasangan $(C, F)$ :
- Total jalur terpendek $=1$ (hanya $C \rightarrow G \rightarrow E \rightarrow F$ ).
- Jalur melalui $F=1$.
- Kontribusi $=1 / 1=1$.

Langkah 4: Jumlahkan kontribusi untuk semua pasangan
$$
C_B(F)=1+1+1=3
$$

Langkah 5: Normalisasi 
$$
C_B^{\prime}(F)=\frac{C_B(F)}{(n-1)(n-2) / 2}
$$

Dengan $n=7$, maka:
$$
C_B^{\prime}(F)=\frac{3}{(7-1)(7-2) / 2}=\frac{3}{15}=0.2
$$