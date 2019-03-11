# Fungsi INDIRECT

## Deskripsi

Fungsi INDIRECT digunakan untuk mengembalikan referensi yang ditentukan oleh string teks. Referensi langsung dievaluasi untuk menampilkan isinya.

## Sintaks

```text
INDIRECT(ref_text, [a1])
```

Sintaks fungsi INDIRECT memiliki argumen ini:

* **ref\_text**  diperlukan untuk sebuah referensi ke sel yang berisi referensi gaya A1, referensi gaya R1C1, nama yang ditetapkan sebagai referensi, atau referensi ke sel sebagai string teks.  
* **a1**  Opsional. Sebuah nilai logika yang menentukan jenis referensi apa yang terdapat di dalam ref\_text.
  * Jika a1 TRUE atau dikosongkan, maka ref\_text diterjemahkan sebagai referensi gaya A1.
  * Jika a1 FALSE atau dikosongkan, maka ref\_text diterjemahkan sebagai referensi gaya R1C1.

## Contoh Implementasi

![](https://github.com/deonetwo/team2/tree/12f5c2a0859ce47fd98fbf7b7380f6a3c0df0755/.gitbook/assets/gambar%20%281%29.png)

