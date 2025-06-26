---
title: "Correlation Analysis"
date: 2025-06-26 10:20:00 +0800
categories: 
  - Statistika
  - Korelasi
tags: [Statistika, Korelasi, Correlation]
---

# 🔗 Correlation Analysis

## Apa itu Korelasi?
Korelasi mengukur hubungan linear antara dua variabel.

### Jenis Korelasi:
- **Pearson:** Untuk data interval/rasio dan normal
- **Spearman:** Untuk data ordinal atau tidak normal

### Interpretasi Nilai Korelasi (r):
| Nilai r     | Interpretasi            |
|-------------|-------------------------|
| 0.00–0.19   | Sangat lemah            |
| 0.20–0.39   | Lemah                   |
| 0.40–0.59   | Sedang                  |
| 0.60–0.79   | Kuat                    |
| 0.80–1.00   | Sangat kuat             |

> ⚠️ Korelasi ≠ kausalitas. Hubungan tidak berarti sebab-akibat.

---

## 🧠 Tujuan Analisis Korelasi
Analisis korelasi bertujuan untuk:
- Mengetahui **arah hubungan** antara dua variabel (positif atau negatif)
- Menilai **kekuatan hubungan** antara dua variabel
- Menjadi dasar untuk **analisis lanjutan**, seperti regresi linier

---

## 🔀 Arah Korelasi

| Jenis Korelasi     | Penjelasan                                                                 |
|--------------------|----------------------------------------------------------------------------|
| Korelasi Positif   | Jika nilai X meningkat, maka Y juga meningkat (arah hubungan searah)      |
| Korelasi Negatif   | Jika nilai X meningkat, maka Y menurun (arah hubungan berlawanan)         |
| Tidak Berkorelasi  | Tidak ada pola hubungan antara X dan Y                                    |

---

## 🧪 Cara Mengukur Korelasi

1. **Pearson Correlation Coefficient (r)**
   - Mengukur hubungan linear antara dua variabel numerik
   - Nilainya antara -1 dan +1
   - Cocok untuk data kuantitatif yang berdistribusi normal

2. **Spearman Rank Correlation**
   - Berdasarkan peringkat, bukan nilai asli
   - Tidak mengasumsikan distribusi data
   - Cocok untuk data ordinal atau data tidak normal

---

## 📊 Contoh Nyata Penggunaan Korelasi

- **Pendidikan dan Pendapatan:** Apakah tingkat pendidikan seseorang berhubungan dengan penghasilan?
- **Tinggi dan Berat Badan:** Apakah orang yang lebih tinggi cenderung memiliki berat badan lebih besar?
- **Waktu Belajar dan Nilai Ujian:** Apakah semakin lama belajar, nilai ujian meningkat?

---

## 🧭 Visualisasi Korelasi

Untuk memahami korelasi secara visual, kamu bisa menggunakan:

- **Scatter Plot (Diagram Sebar):**  
  Menunjukkan titik-titik data dua variabel. Pola naik ke kanan = korelasi positif, turun ke kanan = negatif.

- **Heatmap Korelasi:**  
  Menampilkan matriks korelasi antar variabel dalam dataset. Warna lebih terang/tua menggambarkan kekuatan korelasi.

---

## ⚠️ Kesalahan Umum dalam Interpretasi

- **Korelasi ≠ Kausalitas:**  
  Hanya karena dua variabel berkorelasi, bukan berarti yang satu menyebabkan yang lain. Bisa jadi ada variabel ketiga yang memengaruhi keduanya.

- **Outlier:**  
  Nilai ekstrem bisa memengaruhi koefisien korelasi secara signifikan, apalagi dalam Pearson correlation.
