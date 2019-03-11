# Fungsi BASE

### Deskripsi

Fungsi BASE digunakan untuk mengonversi angka menjadi representasi teks beserta bilangan pokoknya \(basis\) entah itu binary, hexadecimal, ataupun oktal dan yang lainnya.

### Sintaks Dasar

Pada umumnya fungsi ini memiliki sintaks dasar sebagai berikut.

```text
BASE(Number, Radix [Min_length])
```

Sintaks fungsi BASE memiliki argumen berikut.

* **Number**    Diperlukan. Bilangan yang ingin Anda konversi. Harus berupa bilangan bulat yang lebih besar dari atau sama dengan 0 dan kurang dari 2^53.
* **Radix**    Diperlukan. Bilangan pokok basis yang merupakan hasil konversi bilangan. Harus berupa bilangan bulat yang lebih besar dari atau sama dengan 2 dan kurang dari atau sama dengan 36.
* **Min\_length**    Opsional. Panjang minimum string yang dikembalikan. Harus berupa bilangan bulat yang lebih besar dari atau sama dengan 0.

### Contoh Implementasi

| **Rumus** | **Deskripsi** | **Hasil** |
| :--- | :--- | :--- |
| =BASE\(7,2\) | Mengonversi angka desimal 7 ke basis 2 \(biner\). Hasilnya adalah 111. | 1:11 |
| =BASE\(100,16\) | Mengonversi angka desimal 100 ke basis 16 \(heksadesimal\). Hasilnya adalah 64. | 6,4 |
| =BASE\(15,2,10\) | Mengonversi angka desimal 15 ke basis 2 \(biner\), dengan panjang minimum 10. Hasilnya adalah 0000001111, yang merupakan 1111 dengan 6 nol di depannya agar string memiliki panjang 10 karakter. | 0000001111 |



