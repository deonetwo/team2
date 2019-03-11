# Fungsi RAND

### Deskripsi

**RAND** mengembalikan bilangan riil acak yang terdistribusi secara merata yang lebih besar atau sama dengan 0 dan kurang dari 1. Bilangan riil acak akan dikembalikan setiap kali lembar kerja dihitung.

### Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
RAND()
```

Sintaks fungsi RAND tidak memiliki argumen.

### Contoh Implementasi

| **Rumus** | **Deskripsi** | **Hasil** |
| :--- | :--- | :--- |
| =RAND\(\) | Angka acak lebih besar dari atau sama dengan 0 dan kurang dari 1 | bervariasi |
| =RAND\(\)\*100 | Angka acak lebih besar dari atau sama dengan 0 dan lebih kecil dari 100 | bervariasi |
| =INT\(RAND\(\)\*100\) | Bilangan bulat acak lebih besar dari atau sama dengan 0 dan lebih kecil dari 100 | bervariasi |
|  | **Catatan:** Saat lembar kerja dihitung ulang dengan memasukkan rumus atau data dalam sel lain, atau dengan menghitung ulang secara manual \(menekan **F9**\), sebuah angka acak baru akan dibuat untuk setiap rumus yang menggunakan fungsi RAND. |  |

