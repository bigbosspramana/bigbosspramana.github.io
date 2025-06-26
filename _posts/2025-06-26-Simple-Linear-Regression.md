---
title: "Simple Linear Regression"
date: 2025-06-26 10:30:00 +0800
categories: 
  - Statistika
  - Regresi
tags: [Statistika, Regresi Linier, Prediksi]
---

# 📉 Simple Linear Regression

## Pengertian
Regresi linier sederhana digunakan untuk memodelkan hubungan linear antara satu variabel independen (X) dan satu variabel dependen (Y).

### Persamaan Umum:
**Y = a + bX + e**  
- a: intercept  
- b: koefisien regresi  
- e: error

### Tujuan:
- Memprediksi nilai Y berdasarkan X
- Menjelaskan seberapa besar pengaruh X terhadap Y

### Evaluasi Model:
- **R² (koefisien determinasi):** Proporsi variasi Y yang dijelaskan oleh X
- **Uji t:** Signifikansi koefisien regresi
- **Uji F:** Signifikansi model secara keseluruhan

---

## 🧠 Komponen dalam Persamaan Regresi

Persamaan regresi sederhana:  
**Y = a + bX + e**

- **Y (dependent variable):** Nilai yang diprediksi  
- **X (independent variable):** Nilai yang digunakan untuk memprediksi  
- **a (intercept):** Titik potong garis regresi pada sumbu Y  
- **b (slope/gradien):** Perubahan rata-rata Y untuk setiap satu unit perubahan X  
- **e (error/residual):** Selisih antara nilai aktual dan prediksi model

---

## 📋 Asumsi Regresi Linier Sederhana

1. **Linearitas:** Hubungan antara X dan Y harus linier  
2. **Independensi:** Residual (error) bersifat independen  
3. **Homoskedastisitas:** Variansi residual harus konstan di seluruh rentang nilai X  
4. **Normalitas:** Residual mengikuti distribusi normal

> Jika asumsi-asumsi ini dilanggar, hasil prediksi bisa bias atau tidak valid.

---

## 📌 Interpretasi Koefisien Regresi

- **Intercept (a):** Nilai rata-rata Y saat X = 0  
- **Slope (b):** Perubahan rata-rata Y untuk setiap kenaikan 1 unit pada X  
  - Jika b > 0: hubungan positif  
  - Jika b < 0: hubungan negatif  
  - Jika b ≈ 0: hampir tidak ada hubungan

---

## 📊 Evaluasi Tambahan Model

Selain **R²**, uji t, dan uji F, kamu bisa juga mengevaluasi dengan:

- **RMSE (Root Mean Square Error):** Ukuran kesalahan rata-rata prediksi  
- **MAE (Mean Absolute Error):** Rata-rata selisih mutlak antara nilai aktual dan prediksi  
- **Adjusted R²:** Mengoreksi R² untuk jumlah variabel (penting saat beralih ke regresi berganda)

---

## 🧪 Contoh Kasus

**Kasus:**  
Seorang guru ingin memprediksi nilai ujian matematika (Y) berdasarkan jumlah jam belajar siswa (X).

Hasil analisis menunjukkan:
- Persamaan: Y = 50 + 5X  
- Interpretasi: Setiap tambahan 1 jam belajar meningkatkan nilai ujian rata-rata sebesar 5 poin

---

## 📈 Visualisasi

1. **Scatter Plot dengan Garis Regresi**
   - Titik data dan garis prediksi ditampilkan dalam grafik
   - Memudahkan melihat pola hubungan dan outlier

2. **Plot Residual**
   - Menilai apakah asumsi homoskedastisitas dan normalitas residual terpenuhi
