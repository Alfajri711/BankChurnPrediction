# 🔍 Analisis Pengguna yang Berhenti Menggunakan Layanan Bank  

Proyek ini bertujuan untuk memprediksi apakah nasabah bank akan berhenti menggunakan layanan mereka (churn) dengan menganalisis data demografi dan perilaku. Dengan menggunakan berbagai model machine learning, kami mengevaluasi performa prediksi untuk mengidentifikasi model terbaik.  

---

## 📂 Dataset  
**Sumber Data**: `SC_HW1_bank_data.csv`  
Dataset ini berisi informasi:  
- **Demografi**: Usia, jenis kelamin, lokasi.  
- **Perilaku**: Jumlah produk yang dimiliki, kepemilikan kartu kredit, dan lainnya.  
- **Target**: Kolom `Exited` (1 = Berhenti menggunakan layanan, 0 = Tetap menggunakan layanan).  

---

## 🛠️ Pemodelan dan Evaluasi  
Kami membangun model prediksi menggunakan tiga algoritma:  
1. **Logistic Regression**  
2. **K-Nearest Neighbors (KNN)**  
3. **Random Forest**  

**Metode Evaluasi**:  
- Akurasi  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 🏆 Hasil  
Dari evaluasi, **Random Forest** memberikan hasil terbaik dengan:  
- **Akurasi**: Tinggi  
- **Recall**: Optimal dalam mendeteksi nasabah yang berhenti.  
- **F1-Score**: Seimbang antara Precision dan Recall.  

---

## 💻 Teknologi yang Digunakan  
- **Python**: Untuk pengolahan data dan pemodelan.  
- **Scikit-learn**: Membangun dan mengevaluasi model machine learning.  
- **Pandas**: Manipulasi data.  
- **Matplotlib & Seaborn**: Visualisasi data.  
