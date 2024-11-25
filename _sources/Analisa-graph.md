---
title: Analisa-graph

---

# Graph
### Social Network Analysis (SNA)

Sistem analisis data yang berfungsi membuat data lebih terstruktur agar mudah dalam melakukan pengukuran. SNA merupakan analisis yang memiliki fungsi dalam menggambarkan bagaimana struktur sosial dan hubungan antar struktur sosial.

SNA menggambarkan struktur yang saling berhubungan, merepresentasikan individu atau sistem dalam suatu jaringan (nodes), maupun yang menggambarkan hubungan atau interaksi antar individu tersebut (edges).

Berikut adalah penjelasan tentang berbagai metrik sentralitas yang digunakan dalam analisis jaringan:

#### Degree Centrality

Degree centrality mengukur jumlah koneksi langsung (edges) yang dimiliki suatu node. Node dengan degree centrality tinggi dianggap sebagai pusat dari jaringan karena memiliki banyak hubungan langsung dengan node lainnya. Misalnya, dalam jaringan sosial, seseorang dengan banyak koneksi akan memiliki nilai degree centrality yang tinggi.
Rumusnya adalah:

$C_D(v) = \frac{\text{deg}(v)}{n - 1}$


Di mana:

- $deg(v)$ : jumlah koneksi langsung dari node v
- $n$ : total jumlah node dalam jaringan.


#### Betweenness Centrality

Betweenness centrality mengevaluasi sejauh mana sebuah node berada di antara node-node lainnya dalam jaringan. Ini didasarkan pada jumlah jalur terpendek di mana node tersebut menjadi perantara. Node dengan nilai betweenness tinggi dianggap penting karena berfungsi sebagai penghubung antar bagian jaringan, memungkinkan informasi atau sumber daya mengalir lebih efisien.
Rumusnya adalah:

$C_B(v) = \sum_{s \neq v \neq t} \frac{\sigma_{st}(v)}{\sigma_{st}}$

Penjelasan untuk simbol-simbolnya:

- 𝜎𝑠𝑡 σ st : Jumlah jalur terpendek antara node s dan t.
- 𝜎𝑠𝑡(𝑣)σ st(v): Jumlah jalur terpendek antara s dan t yang melewati node v.

#### Closeness Centrality

Closeness centrality mengukur kedekatan sebuah node terhadap semua node lainnya dalam jaringan. Ini dihitung berdasarkan jarak rata-rata dari satu node ke semua node lainnya. Node dengan nilai closeness tinggi memiliki akses lebih cepat ke seluruh jaringan karena berada di posisi strategis
Rumus :

$C_C(v_i) = \left[ \frac{1}{n-1} \sum_{j \neq i} g(v_i, v_j) \right]^{-1} = \frac{n-1}{\sum_{j \neq i} g(v_i, v_j)}$

#### Eigen Vector Centrality
Sentralitas vektor eigen adalah algoritma yang mengukur pengaruh suatu simpul dalam jaringan yang terhubung. Sentralitas vektor eigen juga disebut sebagai sentralitas eigen atau skor prestise
Rumus :

$x_i = \frac{1}{\lambda} \sum_{j=1}^n A_{ij} x_j$

Penjelasan untuk simbol-simbolnya :

- $x_i$ : Nilai eigenvector centrality dari node 𝑖.
- $\lambda$ : Nilai eigen (eigenvalue) terbesar dari matriks adjacency 𝐴.
- $A_{ij}$ : Elemen matriks adjacency, yaitu hubungan antara node 𝑖 dan 𝑗.
- $n$ : Jumlah total node dalam jaringan.

source :
- https://www.sbm.itb.ac.id/id/2023/07/20/menganalisa-data-besar-dengan-social-network-analysis-sna/ 
- https://ejurnal.stmik-budidarma.ac.id/index.php/jurikom/article/download/4053/2709





