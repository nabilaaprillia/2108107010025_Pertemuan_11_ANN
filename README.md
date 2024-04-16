### 2108107010025_Pertemuan_11_ANN

Nama : Nabila Aprillia

NPM  : 2108107010025

Materi bacaan:
* https://www.megabagus.id/deep-learning-artificial-neural-networks/ (halaman 1 - 7)
* ⁠⁠https://www.megabagus.id/deep-learning-artificial-neural-networks-aplikasi (halaman 1 - 4)
  
Pahami isi dari kedua artikel tersebut dan kerjakan:
* Contoh pada artikel kedua menggunakan tensorflow pada python environment
⁠* Tugas 2 sebelumnya menggunakan SVM, kerjakan dengan menggunakan ANN pada python environment yang sama

Kumpulkan kedua tugas tersebut menggunakan repository pada github dengan nama repository: NPM_Pertemuan_11_ANN. Repository tersebut berisi:
* Dataset sebelum dipreprocessing (format csv)
⁠* Kode python yang memuat process preprocessing, training, testing dan perhitungan akurasi
⁠* File requirements.txt yang berisi library yang digunakan
* ⁠File README.md yang berisi penjelasan tentang kedua tugas yang dikerjakan beserta perbandingan akurasi SVM dan ANN

Klasifikasi_ANN
Dataset yang saya gunakan untuk bagian Klasifikasi bernama Breast cancer dataset yang berasal dari kaggle : https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset. 

Studi Kasus: Dataset ini memprediksi dan membagi kelas apakah termasuk kedalam jenis kanker bersifat ganas (kanker)/M (Maglinant) atau jinak (bukan kanker)/ B (Benign). 

Adapun library yang digunakan:
* import pandas as pd
* import numpy as np
* import seaborn as sns
* import matplotlib.pyplot as plt

editor yang saya pakai untuk mengolah dataset ini adalah menggunakan Vscode.

Regresi_ANN
Dataset yang saya gunakan untuk bagian Regresi adalah bernama energy yang berasal dari Kaggle : https://www.kaggle.com/datasets/hassanoukhouya/energycsv.

Studi kasus: Memprediksi Beban listrik yang dipakai dari September 1, 2014, hingga Desember 31, 2014

Informasi Atribut: 
1. timestamp
2. load
3. temp

## Install file requirements.txt dengan menjalankan:
pip install -r requirements.txt

## Perbandingan Hasil SVM dengan ANN
### Klasifikasi
* Pada SVM model dengan kernel RBF berhasil memprediksi akurasi sebesar 98%
* Pada ANN model dengan arsitektur yang terdiri dari beberapa layer Dense dengan aktivasi ReLU, dan satu layer output dengan aktivasi sigmoid berhasil mendapatkan akurasi sebesar 98,82%
* Akurasi keduanya tidak beda jauh

### Regresi
* Membangun model prediksi SVM dan menghasilkan prediksi dengan skor MSE : 0.7367301678686033
* Membangun model prediksi ANN yang terdiri dari beberapa layer Dense dengan aktivasi ReLU, dan satu layer output dengan aktivasi sigmoid dan menghasilkan prediksi dengan skor MSE : 0.6941
