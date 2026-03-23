# Practice-Library - Titanic EDA & Visualisasi

## 📌 Deskripsi Proyek
Folder ini berisi notebook latihan untuk melakukan **Exploratory Data Analysis (EDA)** dan visualisasi data dasar menggunakan library utama Python. Dataset yang digunakan adalah data penumpang kapal Titanic untuk latihan pembersihan data (*data cleaning*) dan eksplorasi fitur (*feature exploration*).

---

## 📂 Struktur Proyek
```text
Practice-Library/
├── dataset/
│   └── titanic.csv        # Dataset Titanic
├── library.ipynb          # Latihan Library dasar
└── practice.ipynb         # Latihan EDA & Visualisasi
```

---

## 🛠️ Ringkasan & Library
Notebook ini fokus pada pemahaman struktur data, distribusi fitur, dan visualisasi hubungan antar variabel.

**Library Utama:**
*   `pandas`: Analisis struktur data tabel.
*   `numpy`: Operasi matematika dan manipulasi array.
*   `matplotlib` & `seaborn`: Pembuatan grafik dasar (Countplot, Scatterplot, Heatmap Korelasi).

---

## 🚀 Cara Menjalankan
Untuk menjalankan notebook secara interaktif di **Google Colab**, ikuti langkah berikut:

1.  **Buka Google Colab**: Masuk ke [Google Colab](https://colab.research.google.com/).
2.  **Upload Notebook**: Pilih tab `Upload` dan pilih file `practice.ipynb` atau `library.ipynb`.
3.  **Upload Dataset**:
    *   Pastikan path dataset di notebook sesuai (misal: `dataset/titanic.csv`).
    *   Upload file `titanic.csv` ke session storage Colab.
4.  **Jalankan Sel**: Klik `Runtime` -> `Run all` atau jalankan sel satu per satu dari atas ke bawah.

---

## 📊 Informasi Dataset
Dataset ini berisi data penumpang dengan beberapa fitur kunci:
*   `Survived`: Status selamat (0 = Tidak, 1 = Ya).
*   `Pclass`: Kelas tiket (1 = Atas, 2 = Menengah, 3 = Ekonomi).
*   `Sex`: Jenis kelamin.
*   `Age`: Umur.
*   `Fare`: Tarif tiket.
*   `Embarked`: Pelabuhan naik (C = Cherbourg, Q = Queenstown, S = Southampton).

---
