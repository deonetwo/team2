# FUNGSI MAXIFS

## Pengertian Fungsi **MAXIFS**

**Fungsi MAXIFS** mengembalikan nilai maksimal di antara sel yang ditentukan oleh kumpulan persyaratan atau kriteria tertentu.

## Sintaks Fungsi **MAXIFS**  pada Excel

{% code-tabs %}
{% code-tabs-item title="Sintaks Fungsi MAXIFS" %}
```text
=MAXIFS(max_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Sintaks atau cara penulisan fungsi excel **MAXIFS** di atas memiliki argumen berikut :

| **Argumen** | Deskripsi |
| :--- | :--- |
| **rentang\_maks**  \(diperlukan\) | Rentang sel aktual tempat nilai maksimum akan ditentukan. |
| **rentang\_kriteria1** \(diperlukan\) | Adalah kumpulan sel yang akan dievaluasi dengan kriteria. |
| **kriteria1**  \(diperlukan\) | Adalah kriteria dalam bentuk angka, ekspresi, atau teks yang menentukan sel mana yang akan dievaluasi sebagai kondisi maksimum. Kumpulan kriteria yang sama dapat digunakan dengan fungsi MINIFS, SUMIFS, dan AVERAGEIFS. |
| **criteria\_range2,**  **criteria2, …**\(opsional\) | Rentang tambahan dan kriteria yang terkait. Anda bisa memasukkan hingga 126 pasang rentang/kriteria. |

