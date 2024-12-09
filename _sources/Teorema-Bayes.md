---
title: Teorema Bayes

---


### Teorema Bayes 
---> suatu formula yang menjelaskan bagaimana caranya memperbarui sebuah probabilitas dari suatu hipotesis saat kita udah menemukan suatu bukti atau petunjuk baru. Teori ini menyatakan seberapa jauh sih suatu derajat kepercayaan subjektif harus berubah secara rasional ketika ada bukti baru.

$$
P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
$$

Contoh singkat dari teorema bayes:

Misalkan kawan Anda bercerita dia bercakap-cakap akrab dengan seseorang lain di atas kereta api. Tanpa informasi tambahan, peluang dia bercakap-cakap dengan perempuan adalah 50%. Sekarang misalkan kawan Anda menyebut bahwa orang lain di atas kereta api itu berambut panjang. Dari keterangan baru ini tampaknya lebih boleh jadi kawan Anda bercakap-cakap dengan perempuan, karena orang berambut panjang biasanya wanita. Teorema Bayes dapat digunakan untuk menghitung besarnya peluang bahwa kawan Anda berbicara dengan seorang wanita, bila diketahui berapa peluang seorang wanita berambut panjang.

### Contoh Teorema Bayes: Percakapan di Kereta Api

Misalkan kita ingin menghitung peluang bahwa kawan Anda berbicara dengan seorang wanita ($P(W|L)$) jika diketahui orang tersebut memiliki rambut panjang. Dengan menggunakan Teorema Bayes:

$$
P(W|L) = \frac{P(L|W) \cdot P(W)}{P(L)}
$$

Untuk menghitung $P(L)$ (peluang seseorang berambut panjang), kita gunakan aturan probabilitas total:

$$
P(L) = P(L|W) \cdot P(W) + P(L|M) \cdot P(M)
$$

**Diketahui:**
- $P(W) = 0,5$
- $P(M) = 1 - P(W) = 0,5$
- $P(L|W) = 0,75$
- $P(L|M) = 0,3$

**Langkah 1: Hitung $P(L)$**
$$
P(L) = (P(L|W) \cdot P(W)) + (P(L|M) \cdot P(M))
$$
$$
P(L) = (0,75 \cdot 0,5) + (0,3 \cdot 0,5)
$$
$$
P(L) = 0,375 + 0,15 = 0,525
$$

**Langkah 2: Hitung $P(W|L)$**
$$
P(W|L) = \frac{P(L|W) \cdot P(W)}{P(L)}
$$
$$
P(W|L) = \frac{0,75 \cdot 0,5}{0,525}
$$
$$
P(W|L) = \frac{0,375}{0,525} \approx 0,714
$$

**Kesimpulan:**
Peluang bahwa kawan Anda berbicara dengan seorang wanita, jika diketahui orang tersebut berambut panjang, adalah sekitar **71,4%**.
