# FUNGSI MINIFS

### Pengertian Fungsi **MINIFS**

**Fungsi MINIFS** mengembalikan nilai minimal di antara sel yang ditentukan oleh kumpulan persyaratan atau kriteria tertentu.

### Sintaks Fungsi **MINIFS**  pada Excel

{% code-tabs %}
{% code-tabs-item title="Sintaks Fungsi MINIFS" %}
```text
=MINIFS(min_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Sintaks atau cara penulisan fungsi excel **MAXIFS** di atas memiliki argumen berikut :

| **Argumen** | Deskripsi |
| :--- | :--- |
| **rentang\_maks**  \(diperlukan\) | Rentang sel aktual tempat nilai minimum akan ditentukan. |
| **rentang\_kriteria1** \(diperlukan\) | Adalah kumpulan sel yang akan dievaluasi dengan kriteria. |
| **kriteria1**  \(diperlukan\) | Adalah kriteria dalam bentuk angka, ekspresi, atau teks yang menentukan sel mana yang akan dievaluasi sebagai kondisi minimum. Kumpulan kriteria yang sama dapat digunakan dengan fungsi MAXIFS, SUMIFS, dan AVERAGEIFS. |
| **criteria\_range2,**  **criteria2, …**\(opsional\) | Rentang tambahan dan kriteria yang terkait. Anda bisa memasukkan hingga 126 pasang rentang/kriteria. |



