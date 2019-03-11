# Fungsi ROMAN

## Deskripsi

Fungsi ini digunakan untuk mengonversi angka Arab ke Romawi, sebagai teks.

## Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
ROMAN(number, [form])
```

Sintaks fungsi ROMAN memiliki argumen berikut:

* **Number**    Diperlukan. Angka Arab yang ingin Anda konversikan.
* **Formulir**    Opsional. Angka yang menentukan tipe angka Romawi yang Anda inginkan. Gaya angka Romawi beragam dari Klasik sampai Sederhana, menjadi lebih singkat seiring nilai dari formulir meningkat. Lihat contoh berikut ROMAN\(499,0\) di bawah.

| **Formulir** | **Tipe** |
| :--- | :--- |
| 0 atau dihilangkan | Klasik. |
| 1 | Lebih singkat. Lihat contoh di bawah ini. |
| 2 | Lebih singkat. Lihat contoh di bawah ini. |
| 3 | Lebih singkat. Lihat contoh di bawah ini. |
| 4 | Sederhana. |
| TRUE | Klasik. |
| FALSE | Sederhana. |

## Contoh Implementasi

| **Rumus** | **Deskripsi \(Hasil\)** | **Hasil** |
| :--- | :--- | :--- |
| =ROMAN\(499,0\) | Gaya angka Romawi Klasik untuk 499 \(CDXCIX\) | CDXCIX |
| =ROMAN\(499,1\) | Versi lebih singkat untuk 499 \(LDVLIV\) | LDVLIV |
| =ROMAN\(499,2\) | Versi lebih singkat untuk 499 \(XDIX\) | XDIX |
| =ROMAN\(499,3\) | Versi lebih singkat untuk 499 \(VDIV\) | VDIV |
| =ROMAN\(499,4\) | Versi sederhana untuk 499 \(ID\) | ID |

