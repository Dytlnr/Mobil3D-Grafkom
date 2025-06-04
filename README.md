# 🚀 Proyek 3D: [Nama Objek] - [Nama Kamu / NIM]

## 🎯 Deskripsi
Proyek ini memodelkan sebuah objek 3D yaitu *[Nama Objek, misalnya Roket Mainan]* yang dibangun dari beberapa bentuk dasar (primitive).

## 🧱 Komposisi Objek
| Bagian          | Bentuk Dasar | Transformasi        |
|-----------------|--------------|---------------------|
| Kepala Roket    | Kerucut      | Translasi, Rotasi   |
| Badan Roket     | Silinder     | Skala, Translasi    |
| Sayap           | Balok/Kubus  | Translasi, Rotasi   |
| Roda/Donat      | Torus        | Skala, Translasi    |

## 🔧 Teknologi
- Python 3 + Pyodide
- Plotly 3D (via Scatter3d / Mesh3d)
- HTML + JS dasar

## ▶ Cara Menjalankan
1. Buka index.html langsung di browser.
2. Pastikan ada koneksi internet untuk load Pyodide & Plotly.
3. Visualisasi akan langsung tampil.

## 🧠 Catatan Teknis
- Setiap objek ditransformasi dengan fungsi translate(), rotate(), scale().
- Objek disusun dalam *scene graph* sederhana (list of objects).