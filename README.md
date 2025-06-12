# 🧠 Brain Tumor Detection using CNN

Proyek ini bertujuan untuk membangun sistem deteksi tumor otak berbasis citra MRI menggunakan Convolutional Neural Network (CNN). Dataset yang digunakan terdiri dari gambar MRI yang telah dikategorikan menjadi tumor dan non-tumor.

## 🚀 Teknologi yang Digunakan

- Python  
- TensorFlow / Keras  
- OpenCV (untuk preprocessing gambar)  
- Google Colab (untuk training)  
- CNN (untuk klasifikasi gambar)  

## 🏗️ Arsitektur Model

Model CNN terdiri dari:  
- Conv2D layer (ReLU + MaxPooling)  
- Flatten layer  
- Fully Connected (Dense) layer  
- Output layer dengan aktivasi sigmoid untuk klasifikasi biner  

## ⚙️ Cara Kerja Sistem

1. Gambar MRI dimuat dan diresize ke dimensi tetap (224x224 piksel).  
2. Gambar diproses melalui jaringan CNN.  
3. Model memprediksi apakah gambar mengandung tumor atau tidak.  
4. Output ditampilkan beserta label prediksi.  

## 📊 Hasil dan Visualisasi

- Akurasi training: sekitar 97%  
- Akurasi testing: sekitar 94%  
- Contoh output deteksi:  
  ![contoh gambar](path/to/sample_result.png)  

## 📂 Struktur Repository

brain-tumor-detection/
```
│
├── brain_tumor_classification.ipynb # Notebook dengan kode dan dokumentasi
├── tumor_otak.h5 # Model hasil training
├── README.md # Dokumentasi proyek
└── requirements.txt # Daftar library (opsional)
```
