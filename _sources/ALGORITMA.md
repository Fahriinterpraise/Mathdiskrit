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
Pola	 Sequential	 Search	 akan	 membandingkan	 dari	 tiap-tiap	 unsurnya	 seraca	bergantuan	dan	berjenjang.	dari	unsur	awal	hingga	diselesaikan	di	unsur	paling	belakang.	 model	 Sequential	 Search	 yang	 sering	 dikatakan	 sebagai	 penelusuran	secara	 berjenjang	 yang	 bisa	diperuntukkan	 dalam	 proses	 penelusuran	 berkas	dalam	 bentuk	 array	 yang	 sudah	 dirapihak	 sesuah	 dengan	 urutan	 dari	 yang	sebelumnya	 tidak	 terurut	 hingga	 rapih.	 pola	 yang	 dipergunakan	 dalam	 model	penelusuran	ialah

1. Membaca	array	data.
2. Meyakinkan	data	yang	ditelusuri.
3. Mulai	 dari	 data	 awal	 sampai	 paling	 belakang,	 penelusuran	 dataakan	 di	perumpamakan	 dengan	 tiap-tiap	 unsur	 pa

Urutan	Algoritma	Sequential	Search
1. I	<-0
2. Ketemu	<-false
3. Selama	(tidak	ketemu)	dan	(I	<	N)	kerjakan	baris
4. Jika	(Data(i)	=	key)	maka	ketemu	<-true	jika	tidak	i<-i+
5. Jika	(ketemu)	maka	I	adalah	indeks	dari	da
### Algoritma Binary search
pola	 instruksi binary	 search	 ini	 bisa	 dikenal	 dengan	 nama	 lain	 dicotomic	search.	bermula	dari	membandikan	value	yang	akan	di	telusuri,x,	dengan	unsur	dibagian	tengah	array.	dimana	disaar	x	mepunyai	poin	lebih	banyak	dari	unsur	array	 ditengan,	 jadi	 tiap	 unsur	 array	 disusun	 membesar,	 maka	 penelusuran	dilakukan	pada	paruh	waktu	yang	mempunyai	poinlebih	besar	dari	x	hingga	unsur	selesai,	 dengan	 menggunakan	 cara	 yang	 mirip.	 agar	 lebih	 mudah,	 diutarakandengan	 dengan	 gambar	 kasus.	 ditemukan	 sebuah	table	 yang	 memiliki	 poin	 int	TabInt[1..n],	 yang	 sudah	 dimuat	 .,	 dan	 disusun	 membesar.	 tuliskan	 program	dengan	 menggunakan	 bantuan	 function	 yang	 jika	 ditetapkan	 poin	 x	 bernilai	integer,maka	 akan	 dicari	 apakah	harga	 x	 ada	 dalam	 TabInt	 secara	 dicotomik,	dengan	rulesberikut:perumpamaanx	dengan	velue	unsurtengah.

a.Apabila	serupaberarti	x	ditemukan	dalam	tabel.	
b.Apabilax	<,	penelusurandilakukan	pada	unsurbagian	bawah	dengan	proses	yangserupa.
c.Apabilax	>,	penelusuran	 dimulai	pada	unsur	bagian	 atas	 dengan	 cara	 yangserupa.	Penelusuran	akan	menghasilkan	sebuah	boolean	ditemukan	yang	valuetrueapabila	x	 ditemukan,	 dan	 false	apabilax	 tidakditemukan	 serta	 indeks	tempat	x	ditemukan.Penelusurandistopsetelah	valueawal	ditemukan.

Pola	instruksi ini	bekerja	dengan	cara	memilih	record	dengan	indeks	tengah	dari	tabledan	menhumpamakannya	dengan	record	yang	hendak	ditelusuri.	apabilarecord	tersebut	lebih	rendah	atau	lebih	tinggi,	maka	tabletersebut	dibagi	dua	dan	bagian	tabel	yang	bersesuaian	akan	diproses	kembali	secara	rekursif

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
