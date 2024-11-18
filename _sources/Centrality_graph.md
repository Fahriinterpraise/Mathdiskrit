---
title: Centrality_graph

---

# Centrality graph
## Social Network Analysis 
merupakan bidang kajian yang mengekplorasitentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. Relasi dalam analisis jaringan sosial dapat diproses dalam bentuk perhitungan yang disebut centrality dalam sebuah jaringan sosial sesuai dengan posisi masing-masing aktor di dalam struktur jaringan tersebut

Tidak semua node dalam jaringan adalah penting  (aktor)
Mencari node yang paling penting dalam suatu jaringan
Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network .Dibagi menjadi empat jenis, 
* degree centrality, 
* betweeness centrality, 
* closeness centrality 
* eigenvector centrality

## Degree Centrality
Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.
Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut
Lebih besar derajatnya (degree), maka lebih penting node itu dalam suatu jaringan 
Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan 

Degree Centrality

$C_D\left(v_i\right)=d_i=\sum_i A_{i j}$

Normalisasi  Degree Centrality:

$C_D^{\prime}\left(v_i\right)=d_i /(n-1)$
## Closeness Centrality
Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.

Average Distance:

$D_{\text {avg }}\left(v_i\right)=\frac{1}{n-1} \sum_{j \neq i}^n g\left(v_i, v_j\right)$

Closeness Centrality 

$C_C\left(v_i\right)=\left[\frac{1}{n-1} \sum_{j \neq i}^n g\left(v_i, v_j\right)\right]^{-1}=\frac{n-1}{\sum_{j \neq i}^n g\left(v_i, v_0\right)}$

## Betweenness Centrality
Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi 

Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan

Ukuran ini juga dapat digunakan untuk mengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas

* Menghitung jumlah lintasan terpendek yang melewati suatu node
* Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi
* Betweenness Centrality

$C_B\left(v_i\right)=\sum_{v_s \neq v_i \neq v_t \in V, s<t} \frac{\sigma_{s t}\left(v_i\right)}{\sigma_{s t}}$

$\sigma_{s t}$ Jumlah lintasan terpendek antara  s dan t

$\sigma_{s t}\left(v_i\right)$ Jumlah lintasan terpendek antara s dan t yang melewati vi

## eigenvector centrality
adalah ukuran yang lebih canggih dalam analisis jaringan dibandingkan degree centrality. Ini mengukur pengaruh suatu simpul (node) dalam jaringan, dengan mempertimbangkan bahwa tidak semua koneksi memiliki bobot yang sama. Dalam konteks ini, simpul yang terhubung ke simpul-simpul lain yang juga berpengaruh akan memiliki eigenvector centrality yang lebih tinggi.

### referemces:
https://en.wikipedia.org/wiki/Centrality