---
title: BOOLEAN

---

# ALJABAR_BOOLEAN
## Operasi NOT
Operasi NOT (juga disebut negasi) adalah operasi yang membalikkan nilai input. Jika input adalah 1, maka output adalah 0, dan sebaliknya. Ini adalah operasi satu variabel.

## Operasi AND
Operasi AND menghasilkan output 1 hanya jika kedua operandnya adalah 1. Dalam aljabar Boolean, operasi ini diwakili dengan tanda "".

## Operasi OR
Operasi OR menghasilkan output 1 jika salah satu atau kedua operandnya adalah 1. Operasi ini diwakili dengan tanda "".

## Operasi XOR
XOR (Exclusive OR) adalah operasi yang menghasilkan output 1 hanya jika salah satu operand adalah 1, tetapi tidak keduanya. Ini diwakili dengan tanda "".

% Tabel Kebenaran NOT
\[
\begin{array}{c|c}
A & \neg A \\
\hline
0 & 1 \\
1 & 0 \\
\end{array}
\]

% Tabel Kebenaran AND
\[
\begin{array}{c|c|c}
A & B & A \land B \\
\hline
0 & 0 & 0 \\
0 & 1 & 0 \\
1 & 0 & 0 \\
1 & 1 & 1 \\
\end{array}
\]

% Tabel Kebenaran OR
\[
\begin{array}{c|c|c}
A & B & A \lor B \\
\hline
0 & 0 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 1 \\
\end{array}
\]

% Tabel Kebenaran XOR
\[
\begin{array}{c|c|c}
A & B & A \oplus B \\
\hline
0 & 0 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0 \\
\end{array}
\]

## % Tabel Kebenaran Gerbang Logika

% Gerbang NOT
\[
\begin{array}{c|c}
A & \text{Output} \\
\hline
0 & 1 \\
1 & 0 \\
\end{array}
\]

% Gerbang AND
\[
\begin{array}{c|c|c}
A & B & \text{Output} \\
\hline
0 & 0 & 0 \\
0 & 1 & 0 \\
1 & 0 & 0 \\
1 & 1 & 1 \\
\end{array}
\]

% Gerbang OR
\[
\begin{array}{c|c|c}
A & B & \text{Output} \\
\hline
0 & 0 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 1 \\
\end{array}
\]

% Gerbang XOR
\[
\begin{array}{c|c|c}
A & B & \text{Output} \\
\hline
0 & 0 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0 \\
\end{array}
\]
