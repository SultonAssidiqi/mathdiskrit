---
title: Deretan-dan-reduksi

---

# Deret dan Reduksi

## Deret
Deret adalah penjumlahan suku-suku dari suatu barisan. Misalnya, terdapat barisan U1, U2, U3, U4, …, Un, maka deret itu adalah U1 + U2 + U3 + U4 +…, Un. Oh iya, “U” itu artinya suku ya. Kalau Un berarti suku ke-n.

**Penjumlahan Deretan**
Jumlah deretan tertentu dapat dinyatakan dalam bentuk:

$S = \sum_{i=m}^n a_i$

Keterangan:

- $i$: indeks penjumlahan
- $m$: batas bawah
- $n$: batas atas

**Contoh Soal**

$\sum_{i=1}^{4} i = 1 + 2 + 3 + 4 = 10$


### Contoh Deret
**1. Deret Aritmatika**

Deret Aritmetika adalah jumlah suku ke-n pertama pada barisan aritmatika.

Misalnya, di suatu barisan memiliki suku pertama, yaitu 1. Suku pertama barisan aritmetika disimbolkan dengan U1 atau a. Lalu, di suku kedua (U2), yaitu 4. Suku ketiga (U3), yaitu 7, suku keempat (U4), yaitu 10, dan seterusnya. Berarti, barisan ini memiliki beda, yaitu 3 pada setiap sukunya.

**Rumus**

**$U_n = a + (n - 1)b$**

- U20 = 1 + (20 – 1)2
- U20 = 1 + (19.2)
- U20 = 1 + 38 = 39

($a$ : suku pertama, $b$ : beda atau selisih antar suku, $n$ : nomor suku yang dicari)

Jadi, suku ke-20 barisan aritmetika tersebut adalah 39.

**2. Deret Geometri**

Deret Geometri adalah yang bentuknya seperti barisan geometri, tetapi ditulis dalam bentuk penjumlahan. Rasio pada deret geometri tersebut disimbolkan dengan r. Contoh sederhana dari deret geometri adalah: 1 + 4 + 16 + 64 + 256,….
Contoh lain dari deret geometri adalah:

- S1 = U1 (jumlah 1 suku pertama)
- S2 = U1 + U2 (jumlah 2 suku pertama)
- S3 = U1 + U2 + U3 (jumlah 3 suku pertama)
- S4 = U1 + U2 + U3 + U4 (jumlah 4 suku pertama) dan seterusnya.

**Rumus**

**$U_n = a \cdot r^{n-1}$**

768 = 3 . 2^(n-1)
$2^{n-1}$ = $\frac{768}{3}$ ---> 256 ---> $2^8$
n-1 = 8
n = 8 + 1 = 9

**3. Deret Fibonacci**

Deret Fibonacci didefinisikan secara rekursif (berulang). Misalkan dalam beberapa pola barisan bilangan dengan dua suku pertama  F1 = 0 dan F2 = 1.
Suku selanjutnya dirumuskan secara rekursif sebagai berikut.

$F_{n+1} = F_{n-1} + F_n$

Berikut ini akan dijelaskan mengenai rumus Fibonacci.

**Contoh Soal**

4, 7, 11, 18, 29, . . .

Tentukan tiga suku selanjutnya dari barisan di atas.

- Suku ke-4 = 18
- Suku ke-5 = 29
- Suku ke-6 = 18 + 29 = 47
- Suku ke-7 = 29 + 47 = 76
- Suku ke-8 = 47 + 76 = 123

Tiga suku berikutnya yaitu 47, 76, dan 123.


## Rekursif

Rekursif terjadi ketika suatu objek atau fungsi didefinisikan menggunakan dirinya sendiri. Proses ini disebut rekursi.
Fungsi rekursif terdiri dari:
- Basis: Nilai awal yang terdefinisi secara eksplisit.
- Rekurens: Kaidah yang mendefinisikan fungsi berdasarkan nilai sebelumnya.

Contoh:
Misalkan $f(n)$ didefinisikan secara rekursif:

$f(n) =\begin{cases} 
1, & \text{jika } n = 0 \\
f(n-1) + 2, & \text{jika } n > 0
\end{cases}$

Untuk $n$ = 3

$\begin{align*}
f(3) & = f(2) + 2 \\
     & = (f(1) + 2) + 2 \\
     & = ((f(0) + 2) + 2) + 2 \\
     & = 1 + 2 + 2 + 2 \\
     & = 7
\end{align*}$

**Latihan**

1. Definisi $a_n$
  secara Rekursif
Jika $a$ adalah bilangan ril tak-nol dan $n$ adalah bilangan bulat tidak-negatif, maka $a_n$ didefinisikan sebagai berikut:

$a_n =\begin{cases} 
1, & \text{jika } n = 0 \\
a \cdot a_{n-1}, & \text{jika } n > 0
\end{cases}$


2. Definisi $a⋅b$ secara Rekursif
Jika $a$ dan $b$ adalah bilangan bulat positif, maka 
$a⋅b$ didefinisikan sebagai berikut:

$a \cdot b =\begin{cases} 
a, & \text{jika } b = 1 \\
a + (a \cdot (b-1)), & \text{jika } b > 1
\end{cases}$
