---
title: "Analisis Data: Optimalkan Biaya & Tingkatkan Profit di Industri Logistik"
dateString: Des 2024
draft: false
tags: ["Pyhton", "Machine Learning", "Jupyter Notebook", "Looker Studio"]
showToc: true
weight: 200
cover:
    image: "projects/analisis_penjualan/dashboard.png"
--- 

### Link 
- 🔗 [Github](https://github.com/Alfianri-Manihuruk/Analisis-Data-Optimalkan-Biaya-Tingkatkan-Profit-di-Industri-Logistik)
- 🔗 [Looker Studio](https://lookerstudio.google.com/reporting/462415dd-194d-411c-9a1e-a3d378a9892d)


### Latar Belakang

Di era digital, data menjadi aset tak ternilai bagi perusahaan untuk mengambil keputusan strategis. 
Di industri penerbangan, analisis data tidak hanya membantu meningkatkan pengalaman pelanggan, tetapi
juga menjadi kunci untuk mengoptimalkan biaya operasional dan memaksimalkan profitabilitas.

### Exploratory Data Analysis (EDA)
#### Eksplorasi pada kolom numerik

1. Distribusi Data
  - Beberapa fitur memiliki distribusi yang tidak normal (skewed), terutama COST_RATIO dan PROFIT, yang cenderung condong ke kanan (positively skewed).
  - COLLY dan WEIGHT juga menunjukkan adanya beberapa nilai ekstrem yang mungkin perlu diteliti lebih lanjut (mungkin outlier).

2. Korelasi Antara Variabel
  - TOTAL_COST berkorelasi sangat tinggi dengan COST_A, COST_B, dan COST_C, yang berarti biaya total sangat dipengaruhi oleh biaya individu ini. Hal ini masuk akal karena TOTAL_COST merupakan jumlah dari biaya-biaya tersebut.
  - PRICE berkorelasi positif dengan REVENUE dan PROFIT, menunjukkan bahwa semakin tinggi harga tiket, semakin besar potensi pendapatan dan keuntungan maskapai.
  - MARGIN berkorelasi negatif dengan COST_RATIO, artinya semakin tinggi rasio biaya terhadap pendapatan, semakin kecil margin keuntungan maskapai. Ini bisa menjadi faktor penting dalam strategi pricing maskapai.

3. Potensi Perbaikan Model & Bisnis
  - Analisis Profitabilitas: Maskapai bisa fokus pada harga tiket yang optimal untuk memaksimalkan profit sambil mempertahankan volume penumpang.
  - Efisiensi Biaya: Mengurangi COST_RATIO bisa membantu meningkatkan margin keuntungan, misalnya dengan mengoptimalkan operasional pesawat atau mengurangi biaya bahan bakar.
  - Outlier Handling: Jika ada nilai ekstrem pada kolom seperti WEIGHT atau PROFIT, sebaiknya dilakukan analisis lebih lanjut apakah ini kesalahan data atau memang kejadian yang jarang terjadi.

#### Eksplorasi pada kolom kategorikal
1.  Dominasi Maskapai & Rute Populer
  - Citilink dan Lion Air mendominasi dalam jumlah penerbangan, menunjukkan mereka sebagai pilihan utama.
  - Makassar dan Banjarmasin adalah tujuan paling sering dikunjungi, kemungkinan besar karena tingginya mobilitas bisnis atau kebutuhan logistik.

2. Distribusi Layanan
  - Door to Door (DTD) jauh lebih populer dibandingkan Port to Port (PTP).
  - Hal ini bisa menunjukkan bahwa pelanggan lebih memilih layanan yang lebih lengkap daripada sekadar pengiriman antar bandara.

3. Keberangkatan dari Kota Besar
  - Jakarta dan Surabaya menjadi pusat keberangkatan utama, yang wajar karena merupakan pusat ekonomi Indonesia.




