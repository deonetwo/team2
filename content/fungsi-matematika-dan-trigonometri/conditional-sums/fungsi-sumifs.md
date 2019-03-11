# Fungsi SUMIFS

## Deskripsi

Fungsi SUMIFS, salah satu dari [fungsi matematika dan trigonometri](https://support.office.com/id-id/article/fungsi-matematika-dan-trigonometri-referensi-ee158fd6-33be-42c9-9ae5-d635c3ae8c16), menambahkan semua argumennya yang memenuhi beberapa kriteria. Sebagai contoh, gunakan SUMIFS untuk menjumlahkan jumlah pengecer di negara yang \(1\) berada dalam satu kode pos dan \(2\) yang labanya melebihi nilai dolar tertentu. Seperti pada video di link berikut [https://www.microsoft.com/id-id/videoplayer/embed/RWflBa?pid=ocpVideo0-innerdiv-oneplayer&postJsllMsg=true&maskLevel=20&market=id-id](https://www.microsoft.com/id-id/videoplayer/embed/RWflBa?pid=ocpVideo0-innerdiv-oneplayer&postJsllMsg=true&maskLevel=20&market=id-id)

## Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
SUMIFS(sum_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)
```

Fungsi SUMIFS memeiliki argumen sebagai berikut.

| **Nama argumen** | **Deskripsi** |
| :--- | :--- |


| **Sum\_range** \(diperlukan\) | Rentang sel untuk dijumlahkan. |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Criteria_range1</b> (diperlukan)</th>
      <th style="text-align:left">
        <p>Rentang yang diuji menggunakan <b>Criteria1</b>.</p>
        <p><b>Criteria_range1</b> dan <b>Criteria1</b> mengatur pasangan pencarian saat
          suatu rentang ditelusuri untuk kriteria tertentu. Setelah item dalam rentang
          ditemukan, nilai item yang berhubungan dalam <b>Sum_range</b> akan ditambahkan.</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>| **Criteria1** \(diperlukan\) | Kriteria yang menentukan sel mana dalam **Criteria\_range1** yang akan ditambahkan. Misalnya, kriteria bisa dimasukkan sebagai **32**, **"&gt;32"**, **B4**, **"apel"**, atau **"32"**. |
| :--- | :--- |


| **Criteria\_range2, criteria2, …** \(opsional\) | Rentang tambahan dan kriteria yang terkait. Anda bisa memasukkan hingga 127 pasang rentang/kriteria. |
| :--- | :--- |


| **Rumus** | **Deskripsi** | **Hasil** |
| :--- | :--- | :--- |
| =BASE\(7,2\) | Mengonversi angka desimal 7 ke basis 2 \(biner\). Hasilnya adalah 111. | 1:11 |
| =BASE\(100,16\) | Mengonversi angka desimal 100 ke basis 16 \(heksadesimal\). Hasilnya adalah 64. | 6,4 |
| =BASE\(15,2,10\) | Mengonversi angka desimal 15 ke basis 2 \(biner\), dengan panjang minimum 10. Hasilnya adalah 0000001111, yang merupakan 1111 dengan 6 nol di depannya agar string memiliki panjang 10 karakter. | 0000001111 |

| **Kuantitas Terjual** | **Produk** | **Penjual** |
| :--- | :--- | :--- |
| 5 | Apel | Tom |
| 4 | Apel | Sarah |
| 15 | Artichoke | Tom |
| 3 | Artichoke | Sarah |
| 22 | Pisang | Tom |
| 12 | Pisang | Sarah |
| 10 | Wortel | Tom |
| 33 | Wortel | Sarah |
| **Rumus** | **Deskripsi** | **Hasil** |
| =SUMIFS\(A2:A9, B2:B9, "=A\*", C2:C9, "Tom"\) | Menambahkan jumlah produk yang dimulai dengan **A** dan yang dijual oleh **Tom**. Menggunakan karakter wildcard \* di **kriteria1**, **"= A \*"** untuk mencari cocok produk nama di **Criterial\_range1** B2: B9, dan mencari nama **"Tom"**di C2: C9 **Criterial\_range2** . Itu lalu menambahkan angka di A2: A9 **Sum\_range** yang memenuhi kondisi kedua. | 20 |
| =SUMIFS\(A2:A9, B2:B9, "&lt;&gt;Pisang", C2:C9, "Tom"\) | Menambahkan jumlah produk yang bukan pisang dan dijual oleh Tom. Rumus mengecualikan pisang dengan menggunakan **&lt;&gt;** di **Criteria1**, **"&lt;&gt;Pisang"**, cari nama **"Tom"** dalam **Criterial\_range2** C2:C9. Kemudian menambahkan angka dalam **Sum\_range** A2:A9 yang memenuhi kedua kondisi. | 30 |

