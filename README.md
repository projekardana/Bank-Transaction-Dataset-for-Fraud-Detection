# 💳 Bank Transaction Dataset for Fraud Detection

Proyek ini bertujuan untuk membangun model Machine Learning yang mampu mendeteksi aktivitas transaksi penipuan (fraud) secara otomatis berdasarkan data historis. Deteksi dini terhadap transaksi mencurigakan sangat penting bagi industri perbankan dalam meminimalisir risiko kerugian finansial dan menjaga kepercayaan pelanggan.

---

## 📌 Latar Belakang

Seiring dengan meningkatnya volume transaksi digital, kasus penipuan finansial juga mengalami peningkatan. Banyaknya data yang tidak seimbang (transaksi sah jauh lebih banyak daripada transaksi penipuan) menjadi tantangan utama dalam membangun model prediktif. Oleh karena itu, proyek ini tidak hanya berfokus pada akurasi model, tetapi juga pada penanganan data imbalance dan pemilihan metrik evaluasi yang tepat seperti Recall. 

---

## 🔧 Tools & Teknologi

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🧪 Proses & Metodologi

1. **Exploratory Data Analysis (EDA)**  
   - Menelusuri distribusi kelas, pola transaksi, dan deteksi outlier.

2. **Data Preprocessing**  
   - Normalisasi, encoding, dan penanganan missing values.

3. **Modeling**  
   - Penggunaan algoritma klasifikasi: Logistic Regression, Random Forest, XGBoost.
   - Hyperparameter tuning dengan GridSearchCV.

4. **Evaluasi Model**  
   - Metrik: Accuracy, Precision, Recall, F1-Score, ROC-AUC.
   - Confusion matrix dan feature importance analysis.

5. **Model Deployment (Opsional)**  
   - Model disimpan sebagai file `.h5` untuk integrasi lebih lanjut.

---

## 📊 Hasil & Insight

- Model XGBoost memberikan performa terbaik dengan **Recall** yang tinggi pada kelas minoritas (fraud).
- Fitur tertentu seperti `transaction_amount`, `account_age`, dan `transaction_time` menjadi indikator penting dalam mendeteksi penipuan.

---

## 📎 Dataset

Dataset bersumber dari [**Kaggle** / sumber lainnya] (sertakan link jika publik), dan telah melalui proses anonymisasi dan pembersihan agar dapat digunakan untuk penelitian dan pengembangan model.

Link Dataset : https://www.kaggle.com/api/v1/datasets/download/valakhorasani/bank-transaction-dataset-for-fraud-detection

----

## 🚀 Cara Menjalankan

1. Clone repositori ini
   ```bash
   git clone https://github.com/projekardana/Bank-Transaction-Dataset-for-Fraud-Detection.git
   cd fraud-detection-project
   ```

---

## 📎 Contact

Proyek ini dikembangkan untuk keperluan pembelajaran dan eksplorasi data analitik sekaligus dalam memperkuat
portofolio di bidang Data Science

Silakan hubungi saya jika ada keperluan :

- Email: mdendiardana@gmail.com
- LinkedIn: linkedin.com/in/mdendiardana
- GitHub: github.com/projekardana