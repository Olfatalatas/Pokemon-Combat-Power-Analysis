# 📊 Pokémon Total Stats Predictive Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)](https://pandas.pydata.org/)
[![Statsmodels](https://img.shields.io/badge/Statsmodels-Statistical%20Modeling-orange.svg)](https://www.statsmodels.org/)

## 📌 Project Overview
Proyek ini adalah studi kasus **Data Science** yang bertujuan untuk membedah hubungan antara atribut fisik Pokémon (*HP, Attack, Defense, Sp. Atk, Sp. Def, Speed*) dengan kekuatan keseluruhannya (**Total Stats**).

Menggunakan metode **OLS (Ordinary Least Squares) Regression**, proyek ini membuktikan secara statistik bagaimana setiap atribut berkontribusi terhadap nilai total. Analisis ini mencakup pembersihan data (*renaming columns*), eksplorasi korelasi (*heatmap*), dan validasi hipotesis.

## 🔍 Key Methodology & Insights

### 1. Data Preprocessing
Dataset asli memiliki penamaan kolom yang mengandung spasi dan karakter khusus (contoh: `Sp. Atk`).
* **Action:** Melakukan *renaming* kolom menjadi format yang aman untuk pemrograman (`Sp_Atk`, `Sp_Def`) agar kompatibel dengan formula regresi Statsmodels.
* **Target Variable:** Menggunakan kolom `Total` sebagai variabel dependen (Y).

### 2. Exploratory Data Analysis (EDA)
Menggunakan **Correlation Heatmap** untuk memvisualisasikan hubungan antar variabel.
* **Temuan:** Semua variabel statistik individu memiliki korelasi positif yang kuat terhadap `Total`.

### 3. Statistical Modeling (OLS Results)
Model regresi menunjukkan hasil yang sangat menarik:
* **R-squared Score:** **1.000** (Perfect Fit).
* **Interpretasi:** Nilai ini mengonfirmasi secara matematis bahwa variabel `Total` pada dataset Pokémon adalah hasil penjumlahan linear sempurna dari keenam statistik dasarnya, tanpa ada koefisien tersembunyi atau *error term* yang signifikan.
* **P-value:** 0.000 (Semua variabel signifikan secara statistik).

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Statistical Analysis:** Statsmodels (OLS Regression)
* **Machine Learning:** Scikit-learn

## 📂 File Structure
* `Pokemon Analysis.ipynb`: Jupyter Notebook berisi kode lengkap (Preprocessing, EDA, OLS).
* `Pokemon.csv`: Dataset standar yang digunakan (sumber: Kaggle).
* `README.md`: Dokumentasi proyek.

## 🚀 How to Run
1.  **Clone Repository**
    ```bash
    git clone [https://github.com/Olfatalatas/Pokemon-Combat-Power-Analysis.git](https://github.com/Olfatalatas/Pokemon-Combat-Power-Analysis.git)
    ```
2.  **Install Libraries**
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn statsmodels
    ```
3.  **Run Notebook**
    Jalankan file `.ipynb` di Jupyter Notebook atau VS Code. Pastikan file `Pokemon.csv` berada di folder yang sama.

## 👤 Author
**Olfat Harits Alatas**
* **Role:** Data Scientist & AI Engineer
* **Connect:** [LinkedIn](https://www.linkedin.com/in/olfat-harits-alatas-ba626722b)

---
*Disclaimer: This project uses a standard Pokémon dataset for educational and analytical demonstration purposes.*
