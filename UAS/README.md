Machine Learning UAS – Telkom University

Repositori ini berisi implementasi **end-to-end pipeline Deep Learning** untuk Ujian Akhir Semester. Masing-masing proyek difokuskan pada jenis model dan dataset yang berbeda sesuai spesifikasi tugas.

Deskripsi Setiap Proyek

1. Regression MLP – Predict Continuous Outcomes
- **Dataset**: `RegresiUTSTelkom.csv`
- **Model**: Multilayer Perceptron (MLP) untuk regresi
- **Task**:
  - Pembersihan dan transformasi data
  - Feature engineering
  - Membangun arsitektur MLP (dropout, batchnorm, dll)
  - Evaluasi menggunakan RMSE, MAE, R²
  - Visualisasi hasil prediksi vs aktual

2. Classification MLP – Predict Discrete Categories
- **Dataset**: `KlasifikasiUTS.csv`
- **Model**: MLP untuk klasifikasi kategori
- **Task**:
  - Preprocessing dan encoding
  - Arsitektur MLP untuk klasifikasi
  - Evaluasi menggunakan Accuracy, Precision, Recall, F1, AUC-ROC
  - Confusion matrix dan analisis model

3. CNN – Image Classification (Fish Dataset)
- **Dataset**: Folder `FishImgDataset/` (train, val, test berisi gambar berbagai jenis ikan)
- **Model**: Convolutional Neural Network (CNN)
- **Task**:
  - Pengolahan gambar (augmentasi, normalisasi)
  - Arsitektur CNN custom / transfer learning
  - Evaluasi: Accuracy, Precision, Recall, F1, AUC-ROC
  - Visualisasi confusion matrix
  - Analisis hasil klasifikasi dan solusi perbaikan


