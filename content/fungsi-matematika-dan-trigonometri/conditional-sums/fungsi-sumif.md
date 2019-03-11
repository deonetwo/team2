# Fungsi SUMIF

### Deskripsi

Anda dapat menggunakan fungsi **SUMIF** untuk menjumlahkan nilai dalam satu rentang yang memenuhi kriteria yang Anda tentukan. Sebagai contoh, di dalam kolom yang berisi angka, Anda hanya ingin menjumlahkan nilai-nilai yang lebih besar dari 5. Anda bisa menggunakan rumus berikut:**=SUMIF\(B2:B25,”&gt;5”\)**

### Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
SUMIF(range, criteria, [sum_range])
```

Sintaks fungsi **SUMIF** memiliki argumen berikut:

* **rentang**   Diperlukan. Rentang sel yang akan Anda evaluasi menurut kriteria. Sel di setiap rentang harus merupakan angka atau nama, array, atau referensi yang berisi angka. Sel kosong atau nilai teks diabaikan. Rentang yang dipilih dapat berisi tanggal dalam format Excel standar \(contoh di bawah\).
* **kriteria**   Diperlukan. Kriteria dalam bentuk angka, ekspresi, referensi sel, teks, atau fungsi yang menentukan sel mana yang akan ditambahkan. Misalnya, kriteria dapat diekspresikan sebagai 32, "&gt;32", B5, "32", "apples", atau TODAY\(\).

{% hint style="warning" %}
 **Penting:** Kriteria teks atau kriteria apa pun yang mencakup simbol logika atau matematika harus disertakan dalam tanda kutip ganda \(**"**\). Jika kriteria adalah numerik, tanda kutip ganda tidak diperlukan.
{% endhint %}

* **sum\_range**   Opsional. Sel aktual untuk ditambahkan, jika Anda ingin menambahkan sel yang lain dari yang sudah ditentukan dalam argumen**rentang**. Jika argumen **sum\_range** dihilangkan, Excel menambahkan sel yang ditentukan dalam argumen **range** \(sel yang sama di mana kriteria diterapkan\).
* Anda bisa menggunakan karakter wildcard—tanda tanya \(**?**\) dan tanda bintang \(**\***\)—sebagai argumen **kriteria**. Tanda tanya cocok dengan semua karakter tunggal; tanda bintang cocok dengan semua urutan karakter. Jika Anda ingin menemukan tanda tanya atau tanda bintang, ketikkan tilde \(**~**\) sebelum karakter.

### Contoh Implementasi

| **Nilai Properti** | **Komisi** | **Data** |
| :--- | :--- | :--- |
| $100.000 | $7.000 | $250.000 |
| $200.000 | $14.000 |  |
| $300.000 | $21.000 |  |
| $400.000 | $28.000 |  |

| **Rumus** | **Deskripsi** | **Hasil** |
| :--- | :--- | :--- |
| =SUMIF\(A2:A5,"&gt;160000",B2:B5\) | Jumlah komisi untuk nilai properti di atas $160.000. | $63.000 |
| =SUMIF\(A2:A5,"&gt;160000"\) | Jumlah nilai properti di atas $160.000. | $900.000 |
| =SUMIF\(A2:A5,300000,B2:B5\) | Jumlah komisi untuk nilai properti yang sama dengan $300.000. | $21.000 |
| =SUMIF\(A2:A5,"&gt;" & C2,B2:B5\) | Jumlah komisi untuk nilai properti lebih besar dari nilai di C2. | $49.000 |

