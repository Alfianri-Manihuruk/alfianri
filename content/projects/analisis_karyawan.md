---
title: "Analisis Data Karyawan: Demografi, Metrik Pekerjaan, dan Indikator Keluar Kerja"
dateString: Des 2024
draft: false
tags: ["Pyhton", "Jupyter Notebook"]
showToc: true
weight: 203
cover:
    image: "projects/analisis_karyawan/data_karyawan.png"
--- 

### Link 
- 🔗 [Github](https://github.com/Alfianri-Manihuruk/Analisis-Data-Karyawan/blob/main/analisis_karyawan.ipynb)


### Latar Belakang
    Analisis ini bertujuan untuk mengeksplorasi dataset karyawan yang mencakup atribut demografis, metrik terkait pekerjaan, dan status attrition. Fokus utamanya adalah melakukan Exploratory Data Analysis (EDA) untuk memahami karakteristik data, mengidentifikasi pola, serta menemukan insight yang relevan.

### Langkah-Langkah Analisis

1.  Import Data dan Library
    -  Dataset diambil dari Google Drive menggunakan Pandas.
    - Library yang digunakan: NumPy, Pandas, Matplotlib, dan Seaborn untuk    visualisasi.

2. Pembersihan Data 

    Kolom yang tidak relevan dihapus: EmployeeNumber, Over18, dan StandardHours.
   
    - EmployeeNumber: Hanya identifier unik.

    - Over18: Semua karyawan sudah di atas 18 tahun.

    - StandardHours: Nilainya konstan untuk semua karyawan.

3. EDA Univariat untuk Kolom Numerik

    - Visualisasi: Histogram dan boxplot untuk setiap kolom numerik.

    - Statistik Deskriptif: Mean, standar deviasi, min, kuartil (Q1, Q2, Q3), dan max.

    - Identifikasi Outlier:

        1. Menghitung Interquartile Range (IQR).

        2. Menentukan batas upper whisker (Q3 + 1.5×IQR) dan lower whisker (Q1 – 1.5×IQR).

        3. Outlier didefinisikan sebagai nilai di luar batas tersebut.



###  Kesimpulan

- Dataset karyawan ini relatif bersih dengan sedikit noise (tidak ada outlier).

- Usia karyawan terdistribusi normal, menunjukkan keberagaman generasi dalam perusahaan.

- Penghapusan kolom yang tidak relevan membantu memfokuskan analisis pada fitur yang lebih informatif.

Analisis ini menjadi dasar untuk eksplorasi lebih lanjut, seperti memprediksi attrition atau mengidentifikasi faktor yang memengaruhi kepuasan kerja karyawan. Untuk lebih hasil analisis lebih lengkap silahkan kunjungi link github di atas.

