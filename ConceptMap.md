Nama : Naila Ratu Dianti
NIM : 20123019

## Concept Map
```mermaid
graph TB
  A["Proyek Data Sains Titanic"]

  A -- Mencakup --> B1["Data Eksplorasi"]
  A -- Mencakup --> B2["Pembersihan Data"]
  A -- Dilakukan --> B3["Pemodelan Data"]
  A -- Menghasilkan --> B4["Evaluasi"]
  A --> B5["Implementasi"]

  B1 --> C1["Statistika Deskriptif"]
  B1 --> C2["Visualisasi"]

  B2 --> C3["Mengatasi Nilai Hilang"]
  B2 --> C4["Encoding Data Kategorikal"]
  B2 --> C5["Normalisasi"]

  B3 -- Menerapkan --> C6["Logistic Regression"]
  B3 -- Menerapkan --> C7["Random Forest"]
  B3 -- Menerapkan --> C8["SVM"]
  B3 -- Menerapkan --> C9["KNN"]

  B4 --> C10["Akurasi"]
  B4 --> C11["Hasil Klasifikasi"]
  B4 --> C12["Perbandingan Model"]

  B5 --> C13["Kesimpulan"]
