---
title: Aljabar Boolean & Gerbang Logika

---

aljabar boolean dan gerbang logika
Aljabar Boolean dan gerbang logika adalah konsep dasar dalam teknik komputer dan elektronika yang digunakan untuk analisis dan desain rangkaian digital. Berikut adalah penjelasan singkat tentang keduanya:

### Aljabar Boolean
Aljabar Boolean adalah sistem aljabar yang digunakan untuk mengoperasikan nilai logika (true/false atau 1/0). Konsep utamanya mencakup operasi dasar berikut:

1. **AND (∧)**: Hasilnya benar (1) jika kedua operand juga benar. 
   - Contoh: A ∧ B = 1 hanya jika A = 1 dan B = 1.

2. **OR (∨)**: Hasilnya benar jika salah satu atau kedua operand benar. 
   - Contoh: A ∨ B = 1 jika A = 1, B = 1, atau keduanya.

3. **NOT (¬)**: Operasi ini membalik nilai logika. 
   - Contoh: ¬A = 1 jika A = 0, dan ¬A = 0 jika A = 1.

4. **XOR (⊕)**: Hasilnya benar jika satu operand benar dan yang lainnya salah. 
   - Contoh: A ⊕ B = 1 jika A dan B berbeda.

5. **NAND dan NOR**: Operasi ini adalah negasi dari AND dan OR. 
   - NAND: A NAND B = 1 jika A ∧ B = 0.
   - NOR: A NOR B = 1 jika A ∨ B = 0.

### Gerbang Logika
Gerbang logika adalah komponen dasar dalam rangkaian digital yang melakukan operasi logika berdasarkan aljabar Boolean. Berikut adalah beberapa jenis gerbang logika yang umum digunakan:

1. **Gerbang AND**: Menghasilkan output tinggi (1) hanya jika semua input tinggi.
   - Simbol: A ● B
   - Tabel Kebenaran:
     ```
     A | B | Output
     0 | 0 |  0
     0 | 1 |  0
     1 | 0 |  0
     1 | 1 |  1
     ```

2. **Gerbang OR**: Menghasilkan output tinggi jika salah satu atau kedua input tinggi.
   - Simbol: A + B
   - Tabel Kebenaran:
     ```
     A | B | Output
     0 | 0 |  0
     0 | 1 |  1
     1 | 0 |  1
     1 | 1 |  1
     ```

3. **Gerbang NOT**: Menghasilkan output yang merupakan kebalikan dari input.
   - Simbol: ¬A
   - Tabel Kebenaran:
     ```
     A | Output
     0 |  1
     1 |  0
     ```

4. **Gerbang NAND**: Menghasilkan output rendah (0) hanya jika semua input tinggi.
   - Simbol: (A ● B)'
   - Tabel Kebenaran:
     ```
     A | B | Output
     0 | 0 |  1
     0 | 1 |  1
     1 | 0 |  1
     1 | 1 |  0
     ```

5. **Gerbang NOR**: Menghasilkan output tinggi hanya jika semua input rendah.
   - Simbol: (A + B)'
   - Tabel Kebenaran:
     ```
     A | B | Output
     0 | 0 |  1
     0 | 1 |  0
     1 | 0 |  0
     1 | 1 |  0
     ```

### Kesimpulan
Aljabar Boolean dan gerbang logika adalah dasar dari sistem digital dan rangkaian logika. Mereka digunakan dalam desain komputer, perangkat keras, dan berbagai aplikasi elektronik lainnya. Jika Anda memiliki pertanyaan lebih lanjut atau ingin mendalami topik tertentu, silakan beri tahu!

referensi:
https://www.gramedia.com/literasi/gerbang-logika/
https://inovasi.ac.id/wiki/prinsip-gerbang-logika/