# Fungsi CEILING

### Deskripsi

Fungsi ini engembalikan angka yang dibulatkan ke atas, menjauh dari nol, ke kelipatan signifikansi terdekat. Misalnya, jika Anda ingin menghindari penggunaan sen dalam harga Anda dan produk Anda dihargai $4,42, gunakan rumus =CEILING\(4.42,0.05\) untuk membulatkan harga ke atas ke nikel terdekat.

### Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
CEILING(number, significance)
```

Sintaks fungsi CEILING memiliki argumen berikut:

* **Number**    Diperlukan. Nilai yang ingin Anda bulatkan.
* **Significance**    Diperlukan. Kelipatan yang menjadi tujuan pembulatan.

### Contoh Implementasi

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Rumus</b>
      </th>
      <th style="text-align:left"><b>Deskripsi</b>
      </th>
      <th style="text-align:left">
        <p></p>
        <p><b>Hasil</b>
        </p>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">=CEILING(2,5, 1)</td>
      <td style="text-align:left">Membulatkan 2,5 ke kelipatan 1 yang terdekat</td>
      <td style="text-align:left">3</td>
    </tr>
    <tr>
      <td style="text-align:left">=CEILING(-2,5, -2)</td>
      <td style="text-align:left">Membulatkan -2,5 ke kelipatan -2 yang terdekat</td>
      <td style="text-align:left">-4</td>
    </tr>
    <tr>
      <td style="text-align:left">=CEILING(-2,5, 2)</td>
      <td style="text-align:left">Membulatkan -2,5 ke kelipatan 2 yang terdekat</td>
      <td style="text-align:left">-2</td>
    </tr>
    <tr>
      <td style="text-align:left">=CEILING(1,5, 0,1)</td>
      <td style="text-align:left">Membulatkan 1,5 ke kelipatan 0,1 yang terdekat</td>
      <td style="text-align:left">1,5</td>
    </tr>
    <tr>
      <td style="text-align:left">=CEILING(0,234, 0,01)</td>
      <td style="text-align:left">Membulatkan 0,234 ke kelipatan 0,01 yang terdekat</td>
      <td style="text-align:left">0,24</td>
    </tr>
  </tbody>
</table>

