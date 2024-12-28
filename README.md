# 🔍 **Analisis Pengguna yang Berhenti Menggunakan Layanan Bank**  
Proyek ini bertujuan untuk memprediksi apakah nasabah bank akan berhenti menggunakan layanan mereka (churn) dengan menganalisis data demografi dan perilaku. Dengan menggunakan algoritma machine learning, kami mengevaluasi performa model untuk mengidentifikasi pendekatan terbaik dalam memahami pola churn nasabah.  

---

## 📂 **Dataset**  
Sumber Data: `SC_HW1_bank_data.csv`  

Dataset ini mencakup:  
- **Demografi**: Lokasi (Geography), jenis kelamin (Gender), usia (Age).  
- **Perilaku**: Jumlah produk yang dimiliki (NumOfProducts), saldo (Balance), kepemilikan kartu kredit (HasCrCard), status keanggotaan aktif (IsActiveMember), dan estimasi pendapatan (EstimatedSalary).  
- **Target**: Kolom `Exited` (1 = Berhenti menggunakan layanan, 0 = Tetap menggunakan layanan).  

**Langkah Persiapan Data**:  
- Menghapus kolom yang tidak relevan untuk analisis.  
- Melakukan encoding atribut kategorikal (seperti Geography dan Gender) menggunakan teknik one-hot encoding.  

---

## 🛠️ **Pemodelan dan Evaluasi**  
Kami menggunakan tiga algoritma berikut untuk memprediksi churn:  
1. **Logistic Regression**  
2. **K-Nearest Neighbors (KNN)**  
3. **Random Forest**  

**Metrik Evaluasi**:  
- Akurasi  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

**Langkah-Langkah**:  
1. **Persiapan Dataset**: Memilih fitur relevan seperti lokasi, usia, saldo, dan lainnya.  
2. **One-Hot Encoding**: Mengubah data kategorikal menjadi numerik untuk digunakan dalam model.  
3. **Pelatihan Model**: Membangun model dengan algoritma yang disebutkan.  
4. **Evaluasi Model**: Menggunakan metrik untuk membandingkan performa ketiga model.  

---

## 🏆 **Hasil**  
- **Model Terbaik**: Random Forest  
  - **Akurasi**: Tinggi  
  - **Recall**: Optimal dalam mendeteksi nasabah yang berhenti menggunakan layanan.  
  - **F1-Score**: Memberikan keseimbangan antara Precision dan Recall.  

---

## 💻 **Teknologi yang Digunakan**  
- **Python**: Untuk pengolahan data dan pemodelan.  
- **Scikit-learn**: Digunakan untuk membangun dan mengevaluasi model machine learning.  
- **Pandas**: Manipulasi dan analisis data.  
- **Matplotlib & Seaborn**: Visualisasi distribusi data dan hasil evaluasi model. 
