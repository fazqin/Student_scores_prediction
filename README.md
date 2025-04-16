# 🎓 Student Score Prediction

Proyek ini dibuat sebagai bagian dari mini project Machine Learning Bootcamp.  
Tujuannya adalah untuk memprediksi skor ujian siswa berdasarkan jumlah jam belajar menggunakan algoritma regresi.


## 📌 Dataset
Dataset yang digunakan hanya memiliki dua fitur:
- `Hours` : jumlah jam belajar
- `Scores`: nilai ujian

---

## 🔍 Proses Pengerjaan

1. **Exploratory Data Analysis (EDA)**
   - Melihat distribusi data dan korelasi antara fitur.
   - Visualisasi scatter plot, histogram, dan korelasi.

2. **Feature Engineering**
   - Mengecek data duplikat
   - Menangani missing value (tidak ditemukan)
   - Deteksi outlier (tidak signifikan)

3. **Modeling**
   Menggunakan dua algoritma regresi:
   - Linear Regression
   - Decision Tree Regressor

4. **Evaluasi Model**
   Metrik evaluasi yang digunakan:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

---

## 📊 Hasil Evaluasi

| Model                  | MAE   | MSE   | RMSE   | R² Score |
|------------------------|-------|-------|--------|----------|
| Linear Regression      | 3.92  |18.94  | 4.35   | 0.9678   |
| Decision Tree Regressor| 5.40  |31.70  |  5.63  | 0.9461   |

> Model dengan performa terbaik adalah: **[Linear Resgression]**

---

## 🚀 Kesimpulan

Model terbaik menunjukkan performa lebih akurat dalam memprediksi skor berdasarkan jam belajar.  
Walau dataset sangat sederhana, ini jadi latihan dasar yang bagus untuk memahami regression modelling & evaluasi metrik.

---

## 🧠 Tech Stack
- Python
- Pandas, Seaborn, Matplotlib
- Scikit-learn
- Google Colab

---

## 📁 Cara Menjalankan
Buka file `Student_Score_Prediction.ipynb` di Google Colab atau Jupyter Notebook, lalu jalankan sel-sel secara berurutan.

---

## ✍️ Created by
Nama: Faza Qinthoro  
Bootcamp: Machine Learning Bootcamp Dibimbing.id

---

## 🔗 License
This project is open source and available under the [MIT License](LICENSE).
