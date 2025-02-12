# 🍼 **Analisis Stunting pada Balita di Kota Baru, Bekasi** 🍼

## 🔍 **Ringkasan**
Proyek ini menganalisis **stunting** pada balita di Kota Baru, Bekasi, dengan menggunakan dua algoritma machine learning: **K-Nearest Neighbor (KNN)** dan **Naive Bayes**. Tujuannya adalah untuk memprediksi status stunting berdasarkan data seperti usia, berat badan, tinggi badan, dan lainnya. 📊

## 🚸 **Tujuan**
- 🔍 **Membandingkan kinerja KNN dan Naive Bayes**.
- 📈 **Evaluasi akurasi, presisi, recall, dan F1-score**.
- ⚖️ **Mengatasi ketidakseimbangan kelas** menggunakan SMOTE.
- 🏆 **Menentukan model terbaik untuk prediksi stunting**.

## 🧑‍👩‍👧‍👦 **Dataset**
Data diambil dari **Puskesmas Kota Baru**, terdiri dari 193 entri yang mencakup informasi seperti:
- **Usia**
- **Berat Badan**
- **Tinggi Badan**
- **Status TB/U (Pendek, Sangat Pendek, Normal)**
- **Jenis Kelamin**
- **Berat Badan Lahir** dan **Tinggi Badan Lahir**

## 🛠️ **Metodologi**

### 1. **Pra-pemrosesan Data**
- 🧮 Mengisi nilai yang hilang.
- 🧑‍💻 Normalisasi dan encoding data.
- ⚖️ **SMOTE** untuk mengatasi ketidakseimbangan kelas.

### 2. **Model Machine Learning**
- **KNN**: Klasifikasi berdasarkan tetangga terdekat. 📍
- **Naive Bayes**: Probabilistik dengan asumsi independensi antar fitur. 🔢

### 3. **Penyetelan Hyperparameter**
- 🔧 Grid search untuk optimasi model.

## 📊 **Evaluasi Model**
- **Akurasi**: Berapa banyak prediksi yang benar. ✅
- **Presisi**: Berapa banyak prediksi positif yang benar. 🏅
- **Recall**: Berapa banyak kasus positif yang terdeteksi. 🔍
- **F1-Score**: Gabungan dari presisi dan recall. ⚖️

## 🏆 **Hasil**
- **KNN** tampil lebih unggul! Pada pembagian data **60:40**, KNN mencapai **83.33% akurasi** dan **83.37% F1-score**. 🚀
- **Naive Bayes** juga bagus, tapi sedikit lebih rendah: **73.08% akurasi** dan **70.98% F1-score**. 📉

## 🎯 **Kesimpulan**
- **KNN** lebih efektif untuk klasifikasi stunting, terutama dengan data yang tidak seimbang. 🏆
- Penelitian lebih lanjut bisa menambah ukuran dataset dan melakukan optimasi lebih lanjut untuk hasil yang lebih baik. 🔮
