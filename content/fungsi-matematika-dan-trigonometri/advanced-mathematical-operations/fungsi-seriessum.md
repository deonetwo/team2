# Fungsi SERIESSUM

### Deskripsi

Fungsi ini mengembalikan jumlah deret pangkat berdasarkan rumus:

![Persamaan yang dikembalikan SERIESSUM](https://support.content.office.net/id-id/media/dbf8edd3-a26e-4b89-8f32-32595657c89b.gif)

### Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
SERIESSUM(x, n, m, coefficients)
```

Sintaks fungsi SERIESSUM memiliki argumen berikut:

* **X**    Diperlukan. Nilai input deret pangkat.
* **N**    Diperlukan. Pangkat awal yang ingin Anda terapkan untuk menaikkan x.
* **M**    Diperlukan. Langkah untuk meningkatkan n untuk setiap item dalam deret.
* **Coefficients**    Diperlukan. Sekumpulan koefisien di mana setiap pangkat dari x yang berurutan dilipatkan. Jumlah nilai dalam koefisien menentukan jumlah item di deret pangkat. Sebagai contoh, jika ada tiga nilai di koefisien, maka ada tiga item di deret pangkat.

### Contoh Implementasi

| **Koefisien sebagai angka** | **Koefisien sebagai rumus** |
| :--- | :--- |
| 0,785398163 | =PI\(\)/4 |
| 1 | 1 |
| -0,5 | =-1/FACT\(2\) |
| 0,041666667 | =1/FACT\(4\) |
| -0,001388889 | =-1/FACT\(6\) |

| **Rumus** | **Deskripsi \(Hasil\)** | **Hasil** |
| :--- | :--- | :--- |
| =SERIESSUM\(A3,0,2,A4:A7\) | Perkiraan untuk kosinus radian Pi/4, atau 45 derajat \(0,707103\) | 0,707103 |

