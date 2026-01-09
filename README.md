Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow

Nama: Juandra Alghifary
NIM: 1103220165

1. Main Objective
Repositori ini dibuat untuk memperdalam pemahaman dan keterampilan praktis dalam menerapkan konsep-konsep inti Machine Learning (ML) melalui reproduksi kode dan penjelasan teoretis yang terstruktur. Proyek ini menggunakan buku "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems" (O’Reilly) sebagai referensi utama.

2. Repository Overview
Repositori ini berisi serangkaian Jupyter Notebook yang mereproduksi eksperimen dan algoritma yang dibahas dalam setiap bab buku tersebut. Setiap notebook mencakup:
Code Reproduction: Implementasi teknis menggunakan pustaka Scikit-Learn, Keras, dan TensorFlow.
Chapter Summary: Ringkasan poin-poin penting dari setiap bab.
Theoretical Explanation: Penjelasan mendalam mengenai konsep matematika dan logika di balik algoritma yang digunakan.

3. Chapter Summaries & Theoretical Insights

Part I: The Fundamentals of Machine Learning

Chapter 1: The Machine Learning Landscape
Ringkasan: Pengenalan dasar ML, klasifikasi sistem (Supervised, Unsupervised, Online vs Batch, Model-based vs Instance-based).
Teori: Menjelaskan tantangan utama ML seperti data yang tidak representatif, sampling bias, serta fenomena overfitting dan underfitting.

Chapter 2: End-to-End Machine Learning Project
Ringkasan: Panduan proyek nyata (prediksi harga rumah di California) dari pengambilan data hingga peluncuran.
Teori: Fokus pada metrik evaluasi seperti RMSE (Root Mean Square Error) dan MAE (Mean Absolute Error) serta pentingnya data cleaning dan feature scaling.

Chapter 3: Classification
Ringkasan: Melakukan klasifikasi pada dataset digit tulisan tangan (MNIST).
Teori: Penjelasan tentang Confusion Matrix, Precision, Recall, F1 Score, dan Kurva ROC untuk mengukur performa model klasifikasi.

Chapter 4: Training Models
Ringkasan: Membedah mekanisme kerja algoritma regresi dan optimasi.
Teori: Konsep Gradient Descent (Batch, Stochastic, Mini-batch) dan teknik regularisasi (Ridge, Lasso, Elastic Net) untuk mencegah overfitting.

Chapter 5: Support Vector Machines (SVM)
Ringkasan: Implementasi klasifikasi dan regresi linier serta non-linier menggunakan SVM.
Teori: Menjelaskan Kernel Trick (Polynomial, RBF) yang memungkinkan SVM menangani data non-linier dengan memetakannya ke ruang dimensi lebih tinggi.

Chapter 6: Decision Trees
Ringkasan: Pelatihan dan visualisasi pohon keputusan untuk klasifikasi dan regresi.
Teori: Logika algoritma CART, pengukuran impuritas Gini, dan entropi dalam pembagian node.

Chapter 7: Ensemble Learning and Random Forests
Ringkasan: Menggabungkan beberapa model untuk prediksi yang lebih kuat (Bagging, Boosting, Stacking).
Teori: Cara kerja Random Forests sebagai kumpulan Decision Trees dan algoritma Gradient Boosting yang memperbaiki kesalahan model sebelumnya secara sekuensial.

Chapter 8: Dimensionality Reduction
Ringkasan: Teknik untuk menyederhanakan data tanpa kehilangan informasi penting.
Teori: Principal Component Analysis (PCA) untuk mencari varians maksimum dan Manifold Learning untuk reduksi dimensi non-linier.

Chapter 9: Unsupervised Learning Techniques
Ringkasan: Teknik ML tanpa label seperti Clustering dan Anomaly Detection.
Teori: Algoritma K-Means, DBSCAN, dan Gaussian Mixture Models (GMM) untuk identifikasi pola tersembunyi dalam data.

4. Technologies Used
  Python 3.x
  Scikit-Learn (ML Fundamentals)
  TensorFlow 2.x & Keras (Deep Learning)
  Pandas & NumPy (Data Manipulation)
  Matplotlib (Visualization)

5. How to Use This Repo
Clone repositori ini.
Instal dependensi: pip install -r requirements.txt.
Jalankan Jupyter Notebook dan mulai eksplorasi dari Bab 1.
