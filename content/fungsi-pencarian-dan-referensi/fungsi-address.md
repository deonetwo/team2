# Fungsi ADDRESS

## Deskripsi

Fungsi ADDRESS digunakan untuk memperoleh alamat sebuah sel dalam lembar kerja, jika diberikan nomor baris dan kolom yang ditentukan.

## Sintaks

`ADDRESS(row_num, column_num, [abs_num], [a1], [sheet_text])`

Sintaks fungsi ADDRESS memiliki argumen berikut:

* **row\_num** diperlukan untuk menentukan nomor baris yang akan digunakan dalam referensi sel.
* **column\_num** diperlukan untuk menentukan nomor kolom yang akan digunakan dalam referensi sel.
* **abs\_num** \(Opsional\) digunakan untuk menentukan tipe referensi yang akan dihasilkan.
* **a1** \(Opsional\) untuk menentukan gaya referensi A1 atau R1C1. Dalam gaya A1, kolom diberi label menurut abjad, dan baris diberi label menurut angka. Dalam gaya referensi R1C1, baik kolom maupun baris diberi label menurut angka.
* **sheet\_text** \(Opsional\) menentukan nama lembar kerja yang akan digunakan sebagai referensi eksternal.

## Contoh Implementasi

| **Rumus** | **Deskripsi** | **Hasil** |
| :--- | :--- | :--- |
| =ADDRESS\(2,3\) | Referensi absolut | $C$2 |
| =ADDRESS\(2,3,2\) | Baris absolut; kolom relatif | C$2 |
| =ADDRESS\(2,3,2,FALSE\) | Baris absolut; kolom relatif dalam gaya referensi R1C1 | R2C\[3\] |
| =ADDRESS\(2,3,1,FALSE,"\[Book1\]Sheet1"\) | Referensi absolut untuk buku kerja dan lembar kerja lainnya | '\[Book1\]Sheet1'!R2C3 |
| =ADDRESS\(2,3,1,FALSE,"EXCEL SHEET"\) | Referensi absolut untuk lembar kerja lainnya | 'EXCEL SHEET'!R2C3 |

