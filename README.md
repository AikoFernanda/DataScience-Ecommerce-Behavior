# Analisis Perilaku & Segmentasi Pelanggan E-Commerce

Proyek ini adalah implementasi *Data Science* menggunakan bahasa pemrograman **Julia** untuk menganalisis dan mengelompokkan perilaku pelanggan pada sebuah platform e-commerce. Proyek ini disusun untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah Data Science.

## 🎯 Tujuan Proyek
1. **Data Cleaning:** Membersihkan data kotor, menangani *missing values*, menghapus duplikat, dan menyaring *outliers*.
2. **Exploratory Data Analysis (EDA):** Menggali *insight* statistik terkait perilaku pengunjung (pengaruh diskon, preferensi perangkat, dll).
3. **Dimensionality Reduction:** Menerapkan Aljabar Linear melalui algoritma **PCA (Principal Component Analysis)** untuk menyederhanakan dimensi data.
4. **Customer Segmentation:** Menerapkan algoritma **K-Means Clustering** untuk membagi pelanggan ke dalam beberapa kelompok yang memiliki karakteristik serupa.

## 🛠️ Teknologi yang Digunakan
* **Bahasa Pemrograman:** Julia v1.12
* **Environment:** Jupyter Notebook (via VS Code)
* **Libraries Utama:** * `DataFrames.jl` & `CSV.jl` (Manipulasi Data)
  * `Statistics.jl` (Analisis Deskriptif)
  * `MultivariateStats.jl` (PCA)
  * `Clustering.jl` (K-Means)
  * `Plots.jl` (Visualisasi Data)

## 🗂️ Struktur Repositori
```text
.
├── data/
│   ├── df_raw.csv                # Dataset asli (Kaggle)
│   ├── df_clean.csv              # Data bersih (Setelah melewati data cleaning)
│
├── notebooks/
│   └── customer_segmentation_analysis.ipynb         # Source code utama (Data Cleaning hingga Clustering)
├── .gitignore
└── README.md