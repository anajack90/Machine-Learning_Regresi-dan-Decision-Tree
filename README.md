Repository ini berisi dua modul eksperimen machine learning menggunakan Python dan Jupyter Notebook:
  1. Iris Flower Classification (source: 1)
     Mengimplementasikan eksperimen klasifikasi pada dataset bunga Iris menggunakan algoritma Decision Tree Classifier dari pustaka scikit-learn.
     Proyek ini mencakup tahap pra-pemrosesan data (Encoding label), pembagian data latih/uji (train-test split), pelatihan model, hingga visualisasi struktur pohon keputusan (tree plot).
  2. Linear Regression & Data Imputation Analysis (source: 2)
     Mengimplementasikan algoritma Linear Regression untuk analisis regresi sederhana dan berganda.
     Modul ini mencakup kalkulasi matriks korelasi, pelatihan model regresi, evaluasi kinerja (Mean Squared Error dan $R^2$ Score), heatmap korelasi, serta analisis variabel prediksi pada dataset kebotakan.

.
├── iris_classification.ipynb   # Eksperimen Klasifikasi Decision Tree (Source 1)
├── linear_regression.ipynb     # Eksperimen Regresi Linier (Source 2)
├── iris-flower.csv             # Dataset Bunga Iris
├── botak.csv                   # Dataset Prediksi Kebotakan
└── README.md                   # Dokumentasi Proyek

Fitur Utama
  - Pra-pemrosesan Data: Pembersihan data missing value, analisis matriks korelasi, dan pengodean variabel kategorikal menggunakan LabelEncoder.
  - Pemodelan Klasifikasi: Pelatihan model DecisionTreeClassifier untuk memprediksi spesies bunga Iris.
  - Pemodelan Regresi: Pelatihan model LinearRegression untuk memprediksi nilai kontinu beserta kalkulasi koefisien dan intersep.
  - Evaluasi Model: Pengukuran performa model regresi menggunakan Mean Squared Error (MSE) dan $R^2$ Score.
  - Visualisasi Data: Visualisasi pola pohon keputusan (Decision Tree Plot), diagram pencar (scatter plot) garis regresi, dan diagram korelasi (heatmap).

Persyaratan Sistem
Pastikan pustaka Python berikut telah terinstal sebelum menjalankan kode:
  - python >= 3.8
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

Cara Penggunaan
  1. Kloning repository berikut ke perangkat anda
       git clone <URL_REPOSITORY_ANDA>
       cd <NAMA_DIREKTORI>
  2. Instal depedensi yang dibutuhkan
       pip install numpy pandas matplotlib seaborn scikit-learn
  3. Jalankan jupyter notebook
       jupyter notebook
  4. Buka notebook yang ingin dijalankan (.ipynb) dan jalankan setiap cell secara berurutan.
