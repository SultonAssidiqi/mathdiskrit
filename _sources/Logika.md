---
title:Logika

---

### 1. HUKUM DE MORGAN'S LAW'S
Hukum De Morgan dalam teori himpunan adalah aturan yang menyatakan bahwa komplemen gabungan dua himpunan sama dengan irisan komplemen kedua himpunan tersebut. Hukum ini dapat dituliskan sebagai $$\overline(A \cup B)=\bar{A}\cap\bar{B}$$
Hukum De Morgan juga dapat dituliskan sebagai
$$\overline(A \cap B)=\bar{A}\cup\bar{B}$$

Hukum De Morgan dapat digunakan untuk menyederhanakan ekspresi dalam teori himpunan dan aljabar boolean. Hukum ini juga dapat digunakan untuk mengekspresikan ekspresi logika yang tidak mengandung suku inversi. 

Hukum De Morgan dinamakan menurut Augustus De Morgan, seorang matematikawan Inggris abad ke-19.
#### PEMBUKTIAN : 
###### $\overline(A\cup B)$
Misal:
A=[1,2,3,4]
B=[4,5,6,7]
U=[8,9,10]
Maka $A\cup B=$ [1,2,3,4,5,6,7]
Dan jika yang ditanyakan $\overline(A\cup B)=$[8,9,10]/S
###### $\bar{A}\cap\bar{B}$
Di baca bukan A irisan bukan B.
Yang dimana hasilnya tidak akan ada di
Dalam Himpunan A Dan B.
Jadi hasilnya = U
### 2. HUKUM ABSORPTION LAWS
Hukum penyerapan atau absorption law adalah identitas yang menghubungkan dua operasi biner dalam aljabar. Hukum ini muncul dalam definisi aljabar Boolean dan kisi. 
Hukum penyerapan menyatakan bahwa p ∨ ( p ∧ q ) sama dengan p, tidak peduli apa pun q. 

Dalam hukum penyerapan, variabel-variabel yang serupa dapat diserap, misalnya X. (X + Y) = X. X + XY = X. 
#### PEMBUKTIAN : 
$A\cup(A\cap B)=A$
Misal:
A=[1,2,3,4]
B=[4,5,6,7]

Kerjakan / Eliminasi yang di dalam tanda kurung terlebih dahulu
$(A\cap B)=$[4]

Kemudian kerjakan / Eliminasi yang di luar tanda kurung
Kita misalkan hasil dari $(A\cap B)=$ C
Maka $A\cup C=$[1,2,3,4,] Dimana Himpunan tersebut = Himpunan A
### 3. HUKUM COMPLEMENT LAWS
Hukum komplemen adalah salah satu sifat dari komplemen himpunan, yaitu:
##### a. Gabungan himpunan A dan komplemennya A' akan menghasilkan himpunan semesta U.
##### b. Irisan himpunan A dan komplemennya A' akan menghasilkan himpunan kosong ∅. 
Komplemen suatu himpunan adalah himpunan yang berisi semua elemen himpunan semesta, tetapi tidak ada dalam himpunan yang diberikan. 

Selain hukum komplemen, ada juga hukum De Morgan yang merupakan sepasang aturan transformasi dalam aljabar boolean dan teori himpunan. Hukum De Morgan digunakan untuk menghubungkan irisan dan gabungan himpunan melalui komplemen.
#### PEMBUKTIAN : 
$A\cup\bar A = U$
Misal:
A=[1,2,3,4]
U=[5,6,7]
[1,2,3,4] $\cup$ not[1,2,3,4] = [5,6,7]