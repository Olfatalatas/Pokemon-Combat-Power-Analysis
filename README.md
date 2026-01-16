# 📊 Pokémon Combat Power (CP) Predictive Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)](https://scikit-learn.org/)

## 📌 Project Overview
Proyek ini adalah studi kasus **Data Science** yang bertujuan untuk memprediksi *Combat Power* (CP) Pokémon berdasarkan atribut fisiknya (HP, Attack, Defense, dll) menggunakan teknik **Analisis Regresi Linear**.

Fokus utama proyek ini bukan hanya prediksi, melainkan **Statistical Inference** (menggunakan OLS - *Ordinary Least Squares*) untuk memahami variabel mana yang memiliki korelasi paling signifikan terhadap kekuatan tempur sebuah Pokémon. Proyek ini mendemonstrasikan siklus lengkap analisis data mulai dari *Data Cleaning*, *Exploratory Data Analysis (EDA)*, hingga *Model Evaluation*.

## 🔍 Key Insights & Methodology

### 1. Exploratory Data Analysis (EDA)
Saya melakukan analisis korelasi antar variabel menggunakan **Heatmap Visualization**.
* **Temuan Utama:** Terdapat korelasi positif yang kuat antara *Evolution Stage* dan *Total Stats* terhadap CP.
* **Distribusi Data:** Menggunakan histogram untuk melihat persebaran tipe Pokémon (Legendary vs Non-Legendary).

<img width="542" height="468" alt="image" src="https://github.com/user-attachments/assets/8a32b96f-4f1c-4920-85cb-e4c6f84e9ee1" />


### 2. Statistical Modeling (OLS Regression)
Menggunakan library `statsmodels` untuk melakukan uji statistik mendalam:
* **R-squared Score:** Digunakan untuk mengukur seberapa baik model menjelaskan variansi data.
* **P-value Analysis:** Untuk menentukan signifikansi statistik dari setiap fitur (Attack, Defense, Speed).

### 3. Predictive Modeling
Membangun model **Linear Regression** menggunakan `scikit-learn` untuk memprediksi nilai CP pada data uji (Test Set).

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Statistical Analysis:** Statsmodels
* **Machine Learning:** Scikit-learn (Linear Regression, Train-Test Split)

## 📂 File Structure
* `Pokemon Analysis.ipynb`: Jupyter Notebook berisi seluruh kode analisis.
* `pokemon.csv`: Dataset yang digunakan (sumber: Kaggle/Database publik).
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
    Jalankan file `.ipynb` di Jupyter Notebook atau VS Code.

## 👤 Author
**Olfat Harits Alatas**
* **Role:** Data Scientist & AI Engineer
* **Connect:** [LinkedIn](https://www.linkedin.com/in/olfat-harits-alatas-ba626722b)

---
*Disclaimer: Data used is for educational and analytical purposes.*
