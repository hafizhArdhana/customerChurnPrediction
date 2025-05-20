# 📊 Customer Churn Prediction

Proyek ini bertujuan untuk memprediksi apakah pelanggan layanan telekomunikasi akan berhenti berlangganan (*churn*) menggunakan **Decision Tree Classifier**.

## 📁 Dataset
- 7043 data pelanggan, 21 fitur
- Fitur mencakup data demografis, jenis layanan, biaya bulanan, dan durasi berlangganan
- Target: `Churn` (Yes/No)

## 🔧 Proses
- **Data Cleaning**: Menghapus karakter aneh, handle missing values, dan duplikasi
- **EDA**: Distribusi fitur, korelasi, dan analisis fitur penting
- **Preprocessing**: Encoding data kategorikal, scaling, train-test split
- **Modeling**: Decision Tree Classifier + evaluasi (Akurasi, F1-score, Confusion Matrix)
- **Visualisasi**: Struktur decision tree untuk interpretasi hasil

## 📈 Insight
- Pelanggan dengan kontrak bulanan, tagihan tinggi, dan masa langganan pendek cenderung churn

## 🧰 Tools
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## 🚀 Rencana Lanjutan
- Bandingkan dengan model lain (Random Forest, XGBoost)
- Cross-validation & tuning hyperparameter
- Deploy model (opsional)

---
