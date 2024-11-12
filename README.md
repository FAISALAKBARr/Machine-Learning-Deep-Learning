# Machine-Learning-Deep-Learning
Repository ini berisi source code mengenai penugasan kelompok pada Assignment 2 - Machine Learning &amp; Deep Learning. Program ini adalah bagian dari tugas Machine Learning dan Deep Learning yang berfokus pada 4 kasus yang berbeda. Antara lain:
1. Case 1 (02-Kelompok F-1.ipynb):"Classification with Supervised Machine Learning Models"
Memprediksi churn status pelanggan bank menggunakan model klasifikasi seperti Random Forest, Logistic Regression, dan K-Nearest Neighbors (KNN).
Dataset diproses melalui penghapusan kolom yang tidak relevan dan encoding kategori untuk fitur-fitur tertentu. Setelah itu, data dibagi menjadi data latih dan uji dengan menggunakan train_test_split, dan fitur-fitur dinormalisasi. Model kemudian dilatih dengan GridSearchCV untuk tuning hyperparameter dan dievaluasi menggunakan akurasi dan matriks kebingungan.

2. Case 2 (02-Kelompok F-2.ipynb):"Data Segmentation with KMeans Clustering"
Melakukan segmentasi data menggunakan metode clustering KMeans. Dataset diimpor dan diproses dengan metode Elbow untuk menemukan jumlah cluster yang optimal. KMeans diterapkan pada data dengan jumlah cluster terbaik, dan hasil clustering divisualisasikan menggunakan Seaborn.

3. Case 3 (02-Kelompok F-3.ipynb):"Regression with Multilayer Perceptron (MLP)"
Memprediksi harga rumah menggunakan model neural network dengan dua input yang berbeda. Dataset harga rumah California digunakan, dan data dibagi menjadi set latih, validasi, dan uji. Fitur distandarisasi dan dinormalisasi sebelum digunakan dalam model MLP. Data kemudian dipecah menjadi dua set fitur yang tumpang tindih untuk menciptakan dua input pada model MLP. Model ini dilatih untuk menghasilkan output berupa prediksi harga rumah.

4. Case 4 (02-Kelompok F-4.ipynb):"Multilayer Perceptron dengan Pytorch""
Proyek ini adalah tugas untuk klasifikasi transaksi fraud menggunakan Multilayer Perceptron (MLP) yang dilatih dengan PyTorch. Dataset yang digunakan adalah Credit Card Fraud 2023, dan terdapat penggunaan GPU untuk mempercepat pemrosesan, baik untuk manipulasi data maupun training model. Dataset diambil dari file zip dataset_case_04.zip yang kemudian di-unzip. Penggunaan read_csv dari pandas (untuk CPU) dan cudf (untuk GPU) mengizinkan pembandingan performa antara pemrosesan di CPU dan GPU. Hyperparameters (seperti epochs, num_layers, num_neurons, learning_rate) adalah nilai yang ditentukan oleh pengguna untuk membangun model.

Program ini bertujuan untuk membandingkan performa model dan memilih model terbaik yang sesuai untuk tiap tugas dengan cara mengevaluasi akurasi, precision, recall, F1-score, dan skor siluet.