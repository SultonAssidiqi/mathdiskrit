---
title: Logika dan Pembuktian

---

# Logika Matematika

## Negasi
Negasi adalah penolakan atau kebalikan dari suatu pernyataan. Negasi dapat diterapkan pada proposisi, gagasan, nilai kebenaran, atau nilai semantik. 

| Pernyataan P | Negasi $\neg P$ | 
| -------- | -------- | 
| True    | False   | 
| False     | True   | 

## Konjungsi
Konjungsi adalah kata hubung yang digunakan dalam proposisi majemuk, yaitu kata hubung "dan" yang disimbolkan dengan "^" (huruf v terbalik). 

| Pernyataan P |Pernyataan Q|Konjungsi $P\wedge Q$ |
| -------- | -------- | -------- |
| True    | True     | True    |
| True    | False     | False    |
| False    | True     | False    |
| False    | False     | False    |
## Disjungsi
Disjungsi adalah pernyataan majemuk dalam logika matematika yang membandingkan dua objek dengan kata hubung “atau”. Disjungsi disimbolkan dengan “∨”.

| Pernyataan P |Pernyataan Q|Disjungsi $P\vee Q$ |
| -------- | -------- | -------- |
| True    | True     | True    |
| True    | False     | True    |
| False    | True     | True    |
| False    | False     | False    |
## Implikasi
Implikasi adalah pernyataan majemuk dalam logika matematika yang menunjukkan hubungan sebab dan akibat. Implikasi menggunakan kata hubung "jika... maka..." dan disimbolkan dengan karakter "→". 

| Pernyataan P |Pernyataan Q|Disjungsi $P\implies Q$ |
| -------- | -------- | -------- |
| True    | True     | True    |
| True    | False     | False   |
| False    | True     | True    |
| False    | False     | True |
## Biimplikasi
Biimplikasi adalah pernyataan majemuk dalam logika matematika yang menggunakan kata hubung "jika dan hanya jika". Notasi dari biimplikasi adalah "p ⇔ q" yang dibaca "p jika dan hanya jika q".

| Pernyataan P |Pernyataan Q|Disjungsi $P\iff Q$ |
| -------- | -------- | -------- |
| True    | True     | True    |
| True    | False     | False   |
| False    | True     | False    |
| False    | False     | True |

sumber:https://www.kompas.com/skola/read/2022/06/02/145036669/negasi-konjungsi-disjungsi-implikasi-dan-biimplikasi

Buatlah tabel kebenaran untuk~pernyataan berikut: 
$$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{-}&\text{-}&\text{-}\\\text{Т}&\text{Т}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{T}&\text{F}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{T}&\text{F}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{T}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{T}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{F}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{F}&\text{F}&\text{-}&\text{-}&\text{-}&\text{-}\end{array}$$
Answer:
$$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{F}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{F}&\text{F}&\text{}\end{array}$$