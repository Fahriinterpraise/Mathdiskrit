---
title: BOOLEAN

---

# ALJABAR_BOOLEAN
Boolean adalah istilah yang berasal dari nama matematikawan dan logikawan George Boole, yang dikenal karena kontribusinya dalam logika dan aljabar. Dalam konteks ilmu komputer dan matematika, Boolean merujuk pada jenis data atau logika yang memiliki dua nilai:

Benar (True): Biasanya dilambangkan dengan angka 1.
Salah (False): Biasanya dilambangkan dengan angka 0.
## Operasi NOT
Operasi NOT (juga disebut negasi) adalah operasi yang membalikkan nilai input. Jika input adalah 1, maka output adalah 0, dan sebaliknya. Ini adalah operasi satu variabel dengan simbol "$\lnot$".

## Operasi AND
Operasi AND menghasilkan output 1 hanya jika kedua operandnya adalah 1. Dalam aljabar Boolean, operasi ini diwakili dengan tanda "$\land$".

## Operasi OR
Operasi OR menghasilkan output 1 jika salah satu atau kedua operandnya adalah 1. Operasi ini diwakili dengan tanda "$\lor$".

## Operasi XOR
XOR (Exclusive OR) adalah operasi yang menghasilkan output 1 hanya jika salah satu operand adalah 1, tetapi tidak keduanya. Ini diwakili dengan tanda "$\oplus$".

% Tabel Kebenaran NOT
| A | NOT A ($\lnot$ A) |
|---|------------|
| 0 | 1          |
| 1 | 0          |


% Tabel Kebenaran AND
| A | B | A AND B (A $\land$ B) |
|---|---|------------------|
| 0 | 0 | 0               |
| 0 | 1 | 0               |
| 1 | 0 | 0               |
| 1 | 1 | 1               |


% Tabel Kebenaran OR
| A | B | A OR B (A $\lor$ B) |
|---|---|-----------------|
| 0 | 0 | 0              |
| 0 | 1 | 1              |
| 1 | 0 | 1              |
| 1 | 1 | 1              |


% Tabel Kebenaran XOR
| A | B | A XOR B (A $\oplus$ B) |
|---|---|------------------|
| 0 | 0 | 0               |
| 0 | 1 | 1               |
| 1 | 0 | 1               |
| 1 | 1 | 0               |


## % Tabel Kebenaran Gerbang Logika
% Gerbang NOT
| A | Output |
|---|--------|
| 0 | 1      |
| 1 | 0      |


% Gerbang AND
| A | B | Output |
|---|---|--------|
| 0 | 0 | 0      |
| 0 | 1 | 0      |
| 1 | 0 | 0      |
| 1 | 1 | 1      |


% Gerbang OR
| A | B | Output |
|---|---|--------|
| 0 | 0 | 0      |
| 0 | 1 | 1      |
| 1 | 0 | 1      |
| 1 | 1 | 1      |


% Gerbang XOR
| A | B | Output |
|---|---|--------|
| 0 | 0 | 0      |
| 0 | 1 | 1      |
| 1 | 0 | 1      |
| 1 | 1 | 0      |

### Ringkasan
AND: Benar jika kedua operand benar.
OR: Benar jika salah satu atau kedua operand benar.
NOT: Membalik nilai operand.
XOR: Benar jika hanya salah satu operand yang benar.

### REFERENCES 
https://www.dicoding.com/blog/gerbang-logika-dan-tabel-kebenaran/
