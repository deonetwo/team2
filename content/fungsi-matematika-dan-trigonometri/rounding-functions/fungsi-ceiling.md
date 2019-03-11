# Fungsi CEILING

## Deskripsi

Fungsi ini engembalikan angka yang dibulatkan ke atas, menjauh dari nol, ke kelipatan signifikansi terdekat. Misalnya, jika Anda ingin menghindari penggunaan sen dalam harga Anda dan produk Anda dihargai $4,42, gunakan rumus =CEILING\(4.42,0.05\) untuk membulatkan harga ke atas ke nikel terdekat.

## Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
CEILING(number, significance)
```

Sintaks fungsi CEILING memiliki argumen berikut:

* **Number**    Diperlukan. Nilai yang ingin Anda bulatkan.
* **Significance**    Diperlukan. Kelipatan yang menjadi tujuan pembulatan.

## Contoh Implementasi

| **Rumus** | **Deskripsi** | **Hasil** |
| :--- | :--- | :--- |
| =CEILING\(2,5, 1\) | Membulatkan 2,5 ke kelipatan 1 yang terdekat | 3 |
| =CEILING\(-2,5, -2\) | Membulatkan -2,5 ke kelipatan -2 yang terdekat | -4 |
| =CEILING\(-2,5, 2\) | Membulatkan -2,5 ke kelipatan 2 yang terdekat | -2 |
| =CEILING\(1,5, 0,1\) | Membulatkan 1,5 ke kelipatan 0,1 yang terdekat | 1,5 |
| =CEILING\(0,234, 0,01\) | Membulatkan 0,234 ke kelipatan 0,01 yang terdekat | 0,24 |

