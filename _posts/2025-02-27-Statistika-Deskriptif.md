---
title: "Apa itu Statistika Deskriptif?"
date: 2025-02-07 10:00:00 +0800
categories: [Statistika]
tags: [Statistika]
---

Statistika Deskriptif adalah cabang dari statistika yang berfokus pada pengumpulan, penyajian, dan analisis data tanpa melakukan generalisasi atau inferensi terhadap populasi yang lebih besar. Statistika ini bertujuan untuk menggambarkan atau meringkas data dengan cara yang mudah dipahami, seperti menggunakan tabel, grafik, atau ukuran pemusatan dan penyebaran data.

Ada 3 jenis Ukuran Pemusatan Data dalam Statistika Deskriptif yaitu :

1. **Mean** 

    > *Mean adalah nilai rata-rata dari sekumpulan data yang diperoleh dengan menjumlahkan semua nilai data lalu dibagi dengan jumlah data.*

    Namun, terdapat 3 jenis rata-rata juga yaitu :

    * Aritmatika Mean (Rata-rata Aritmatika)<br>
        Mean ini merupakan salah satu jenis rata-rata yang paling sering digunakan, dengan cara menjumlahkan semua data seluruh data lalu membaginya dengan seberapa banyak data (jumlah data).

        ![Rumus](https://latex.codecogs.com/png.latex?\color{White}\bar{X}=\frac{\sum X_i}{n})

    * Geometric Mean (Rata-rata Geometrik)<br>
        Mean ini digunakan untuk menghitung rata-rata pertumbuhan atau perubahan yang bersifat multiplikatif, seperti suku bunga atau pertumbuhan penduduk.

        ![Rumus](https://latex.codecogs.com/png.latex?\color{White} \text{GM} = \left( \prod X_i \right)^{\frac{1}{n}})

    * Harmonic Mean (Rata-rata Harmonik)<br>
        Digunakan dalam kasus kecepatan rata-rata atau perbandingan.

        ![Rumus](https://latex.codecogs.com/png.latex?\color{White} \text{HM} = \frac{n}{\sum \frac{1}{X_i}})

2. **Median**

    > *Median adalah nilai tengah dari sekumpulan data yang telah diurutkan dari yang terkecil ke terbesar. Jika jumlah data ganjil, median adalah nilai tengah. Jika jumlah data genap, median adalah rata-rata dari dua nilai tengah.*

    Untuk mendapatkan hasil median dari data ganjil, dengan mencari nilai tengahnya. Sedangkan data genap, dengan mencari dua nilai tengah, lalu bagi rata-ratanya menggunakan rumus di bawah ini.

    ![Rumus](https://latex.codecogs.com/png.latex?\color{White} \text{Median} = \frac{x_1 + x_2}{2})

3. **Modus**

    > *Modus adalah nilai yang paling sering muncul dalam sekumpulan data.*

    *Contoh:*<br>
    Data: 2,3,3,5,7,7,7,82, 3, 3, 5, 7, 7, 7, 82,3,3,5,7,7,7,8

    Modus = 7 (karena muncul paling banyak)

    Jika ada dua nilai yang sering muncul, disebut bimodal, dan jika lebih dari dua, disebut multimodal.

---

<span style="font-size: 40px; font-weight: bold;">V</span>ariasi dan standar deviasi membantu memahami seberapa “tersebar” data dari rata-rata. Semakin kecil standar deviasi, semakin konsisten data tersebut. Sedangkan, Semakin besar standar deviasi, semakin bervariasi dan tidak terprediksi data tersebut.

Berikut merupakan penjelasan mengenai variasi dan standar deviasi.

1. **Variasi**
    > *Variasi mengukur seberapa jauh data tersebar dari rata-rata (mean). Semakin besar nilai variansi, semakin besar penyebaran data.*

     * **Variansi untuk Populasi** 

        ![Rumus](https://latex.codecogs.com/png.latex?\color{White} \sigma^2 = \frac{\sum (X_i - \mu)^2}{N})
     * **Variansi untuk Sampel**

        ![Rumus](https://latex.codecogs.com/png.latex?\color{White} s^2 = \frac{\sum (X_i - \bar{X})^2}{n-1})
        
        **Keterangan:**  
        - ![Xi](https://latex.codecogs.com/png.latex?\color{White}X_i) = nilai individu dalam data  
        - ![Mu](https://latex.codecogs.com/png.latex?\color{White}\mu) = mean populasi  
        - ![Xbar](https://latex.codecogs.com/png.latex?\color{White}\bar{X}) = mean sampel  
        - ![N](https://latex.codecogs.com/png.latex?\color{White}N) = jumlah data populasi  
        - ![n](https://latex.codecogs.com/png.latex?\color{White}n) = jumlah data sampel  

2. **Standar Deviasi**
    > *Standar deviasi adalah akar kuadrat dari variansi, yang menunjukkan seberapa jauh data menyebar dari rata-rata dalam unit yang sama dengan data aslinya.*

    - **Standar Deviasi untuk Populasi**  
        
        ![Rumus](https://latex.codecogs.com/png.latex?\color{White} \sigma = \sqrt{\sigma^2})  

    - **Standar Deviasi untuk Sampel**  
        
        ![Rumus](https://latex.codecogs.com/png.latex?\color{White} s = \sqrt{s^2})  

---
### Kesimpulan
Statistika deskriptif membantu dalam menganalisis dan menyajikan data melalui ukuran pemusatan seperti mean, median, dan modus, serta ukuran penyebaran seperti variansi dan standar deviasi. Mean digunakan untuk menghitung rata-rata, median untuk menentukan nilai tengah, dan modus untuk menemukan nilai yang paling sering muncul. Sementara itu, variansi dan standar deviasi mengukur seberapa tersebar data dari rata-rata, di mana standar deviasi yang kecil menunjukkan data lebih konsisten, sedangkan standar deviasi yang besar menunjukkan data lebih bervariasi. Dengan memahami konsep ini, kita dapat menginterpretasikan data dengan lebih akurat dan mengambil keputusan berdasarkan pola yang ada. 📊✨










