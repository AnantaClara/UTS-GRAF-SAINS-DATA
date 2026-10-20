# UTS Graf Sains Data

Implementasi analisis graf dan sistem rekomendasi menggunakan dataset **RetailRocket**, Python, dan Neo4j untuk memenuhi tugas Ujian Tengah Semester mata kuliah Graf Sains Data.

## Dataset
Dataset asli: https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset

Data asli (events.csv) digunakan pada tahap impor dan filtering, kemudian dibagi menjadi dua periode:
- **P1 (Training):** 1–15 Agustus 2015.
- **P2 (Testing):** 16–31 Agustus 2015.

## Metode
Analisis meliputi pembentukan Vector Space Modelling (VSM) User–Item dan Item–User, perhitungan Cosine Similarity, serta implementasi sistem rekomendasi menggunakan User-Based KNN dengan K = 5.

Evaluasi rekomendasi dilakukan menggunakan metrik Hit@5 dan NDCG@5.

## Dokumentasi
Kode dan hasil pengerjaan tersedia dalam `031_UTS GSD.ipynb`, sedangkan penjelasan metode, hasil analisis, dan visualisasi disajikan dalam `031_LAPORAN UTS GSD.pdf`.

Dependensi yang diperlukan tercantum dalam `requirements.txt`.