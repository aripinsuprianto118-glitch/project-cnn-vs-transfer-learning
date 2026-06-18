# project-cnn-vs-transfer-learning

# Project: CNN vs Transfer Learning untuk Klasifikasi Citra

Oleh: Aripin suprianto

## Deskripsi
Repositori ini berisi eksperimen untuk membandingkan performa model Convolutional Neural Network (CNN) yang dibangun dari dasar (from scratch) dengan pendekatan Transfer Learning menggunakan pretrained model. 

- Eksperimen 1:CNN from Scratch menggunakan dataset CIFAR-10.
- Eksperimen 2: Transfer Learning (MobileNetV2 - Feature Extraction) menggunakan dataset Cats vs Dogs.

## Struktur Repository
- `notebook/`: Berisi source code Jupyter Notebook (`cnn_vs_transfer_learning.ipynb`).
- `report/`: Berisi laporan akhir eksperimen dan analisis berformat PDF.
- `dataset/`: (Dataset diunduh langsung via script atau menggunakan dataset dari internet).
- `requirements.txt`: Daftar pustaka Python yang dibutuhkan.

## Cara Menjalankan
1. Clone repositori ini ke komputer lokal .
2. Install dependensi dengan menjalankan `pip install -r requirements.txt`.
3. Buka dan jalankan seluruh cell di dalam `notebook/cnn_vs_transfer_learning.ipynb`.
