# Fungsi MATCH

### Deskripsi

Fungsi MATCH mencari item yang ditentukan dalam rentang sel, kemudian mengembalikan posisi relatif item tersebut dalam rentang.

### Sintaks 

```text
MATCH(lookup_value, lookup_array, [match_type])
```

Sintaks fungsi MATCH memiliki argumen berikut:

* **lookup\_value** diperlukan memasukan nilai yang ingin anda cocookan.  Argumen lookup\_value bisa berupa nilai \(angka, teks, atau nilai logika\) atau referensi sel ke angka, teks atau nilai logis.
* **lookup\_array** diperlukan untuk rentang sel yang dicari.
* **match\_type** Opsional bilangan 1, 0, atau -1.Nilai default untuk argumen ini adalah 1.
  * 1 menemukan nilai terbesar yang lebih kecil dari atau sama dengan lookup\_value. Nilai dalam argumen lookup\_array harus disusun dalam urutan ascending
  * 0  menemukan nilai pertama yang sama persis dengan lookup\_value.
  * -1  menemukan nilai terkecil yang lebih besar dari atau sama dengan lookup\_value.Nilai dalam argumen lookup\_array harus disusun dalam urutan descending

### Contoh Implementasi

![](../../.gitbook/assets/gambar%20%285%29.png)

Tekan CTRL+SHIFT+ENTER ketika Anda selesai, bukan dengan menekan ENTER dengan sendirinya.

