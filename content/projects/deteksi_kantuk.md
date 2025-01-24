---
title: "Driver Drowsiness Detection Using Convolution Neural Networks(CNN)"
description: "Can computers really understand the human face?"
dateString: Jun 2024
draft: false
tags: ["DeepLearning", "AI", "Python", "TensorFlow"]
showToc: false
weight: 202
cover:
    image: "projects/deteksi_kantuk/hasil_prediksi.png"
--- 

## Link
- [**🔗Github**](https://github.com/Alfianri-Manihuruk/TA)

- [**🔗Dokumen**](https://repo.itera.ac.id/depan/submission/SB2406060109)


## Abstrak
Kecelakaan lalu lintas yang diakibatkan oleh kelalaian manusia, seperti mengantuk
saat mengemudi, menjadi masalah serius. Karena peristiwa ini melibatkan kendaraan lain atau pengemudi lain di jalan raya. Kelalaian manusia seperti kantuk dapat
menyebabkan kecelakaan yang merugikan secara materi dan non materi. Banyak
pengendara yang mengabaikan rasa kantuk, mereka tetap memaksakan dirinya untuk mengemudi padahal sudah seharusnya untuk beristirahat. Penelitian ini mengusulkan deteksi kantuk pengemudi berbasis Convolutional Neural Network (CNN)
untuk mendeteksi kantuk. Digunakan parameter Eye Aspect Ratio (EAR) dan Mouth Aspect Ratio (MAR) untuk menentukan kelasya. Terdapat tiga kelas yang dilatih
menggunakan CNN untuk mengidentifikasi pola pengendara, seperti ’mengantuk
dan menguap’, ’mengantuk tidak menguap’ dan ’menguap tidak mengantuk’. Ketiga kelas tersebut merupakan kombinasi antara parameter EAR & MAR. Hasil penelitian menunjukkan bahwa model ini mampu mendeteksi kantuk dengan akurasi
tinggi. Pada penelitian ini didapatkan hasil terbaik yaitu dengan penggunaan parameter learning rate sebesar 0,0001, activation ReLU dan Optimizer SGD. Dengan
performansi model untuk akurasi, precision, recall, dan F1-Score masing-masing
sebesar 91.76%, 91.76%, 92.94%, dan 91.62%.

## Tools
Penelitian ini memanfaatkan perangkat lunak berikut:
- Windows 11 x64
- Python 3.11.4
- Tensorflow 2.9.1
- Conda 22.9.0
- Dlib 19.22.1
- Open CV 4.8.1
- Google Colaboratory

## Data
Data yang dimanfaatkan dalam penelitian ini termasuk dalam kategori data sekunder dengan format video (avi). Sumber data ini berasal dari **YAWDD: YAWNING DETECTION DATASET**

## Flowchart

![Flowchart](https://alfianri-manihuruk.github.io/alfianri/projects/deteksi_kantuk/fowchart.png)


## Hasil
Dapat dilihat akurasi dan loss stabil di semua fold, semakin tinggi nilai epoch akurasi semakin meningkat dan akurasi di atas 90%. Begitu juga dengan nilai loss semakin tinggi epoch semakin mengecil nilai loss yang dihasilkan dan mendekati nilai nol. Hal ini menunjukkan bahwa model mampu belajar dari data dan tidak
hanya menghafal data pelatihan. Ini berarti model memiliki kinerja baik pada data baru yang tidak dilihat saat pelatihan.

![Flowchart](https://alfianri-manihuruk.github.io/alfianri/projects/deteksi_kantuk/akurasi_plotfix.png)


Begitu juga untuk nilai sepeti akurasi, precison, recall dan f1-score rata-rata diatas angka 90%, seperti di
tunjukkan pada gambar dibawah ini.
![Flowchart](https://alfianri-manihuruk.github.io/alfianri/projects/deteksi_kantuk/peforma_cv2.png)




## Evaluasi
Dapat dilihat dari hasil evaluasi menggunakan confusion matrix. Nilai akurasi dan
metriks yang dihasilkan tidak berbeda jauh dengan pengujian yang dilakukan sebelumnya.
![Flowchart](https://alfianri-manihuruk.github.io/alfianri/projects/deteksi_kantuk/confusion_matrix.png)


