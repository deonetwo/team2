# Fungsi Database

Sebelumnya perlu diingatkan bahwa Microsoft Excel bukanlah sebuah software untuk pengolahan database. Namun tidak menutup kemungkinan bahwa excel tidak dapat digunakan untuk keperluan tersebut. Terlebih excel sendiri sudah menyediakan beberapa fungsi database khusus yang dapat digunakan untuk pengelolaan sebuah database.

Database dapat diartikan sebagai sekelompok data pada range data atau rentang sel tertentu yang saling terkait serta telah disusun sedemikian rupa dimana baris pertama berisi Label untuk masing-masing kolom yang disebut sebagai Field \(Bidang Data\) dan baris-baris berikutnya biasa disebut sebagai Record \(Rekaman Data\).

## Adapun 12 fungsi yang dikategorikan sebagai Fungsi Database Excel antara lain:

1. [DSUM](fungsi-dsum.md)
2. [DAVERAGE](fungsi-daverage.md)
3. [DMAX](fungsi-dmax.md)
4. [DMIN](fungsi-dmin.md)
5. [DCOUNT](fungsi-dcount.md)
6. [DCOUNTA](fungsi-dcounta.md)
7. [DGET](fungsi-dget.md)
8. [DPRODUCT](fungsi-dproduct.md)
9. [DSTDEV](fungsi-dstdev.md)
10. [DSTDEVP](fungsi-dstdevp.md)
11. [DVAR](fungsi-dvar.md)
12. [DVARP](fungsi-dvarp.md)

## CARA MENGGUNAKAN FUNGSI DARTABASE EXCEL

Secara umum sintak penggunaan fungsi database excel adalah sebagai berikut:

```text
NAMA_FUNGSI(Database; Field; Kriteria)
```

Tentunya yang membedakan hanyalah nama fungsi yang akan digunakan untuk mendapatkan hasil tertentu.

**Database**: Merupakan range data atau rentang sel yang membentuk sebuah daftar atau database tertentu yang akan kita agregasi hasilnya.

**Field**: Menunjukkan Field atau kolom mana yang akan di agregasi atau digunakan oleh fungsi database ini. Argumen ini bisa kita isi dengan Label atau nama field, bisa juga anda isi dengan angka tertentu yang menunjukkan nomor urut posisi field tersebut pada kolom-kolom database dari arah kiri. Misal angka 1 menunjukkan kolom atau field pertama dan angka 2 menunjukkan field atau kolom kedua dalam Database.

**Kriteria**: Adalah rentang sel atau range data lain yang berisi kriteria atau syarat tertentu yang Anda tentukan sebagai acuan agregasi dalam fungsi database. Kriteria ini setidaknya memuat 2 baris data dimana baris pertama berisi Label data yang sama persis dengan Label field pada database dan baris-baris berikutnya merupakan acuan kriteria, syarat atau kondisi tertentu yang akan kita terapkan.

