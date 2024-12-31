# Prediksi Risiko Gagal Jantung dengan Machine Learning
## Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi risiko gagal jantung pada individu menggunakan algoritma machine learning. Dengan memanfaatkan algoritma XGBoost, LightGBM, dan CatBoost, kami membandingkan performa model untuk memilih algoritma terbaik dalam memprediksi risiko penyakit gagal jantung.

Penyakit gagal jantung adalah salah satu penyebab kematian tertinggi di dunia, sehingga solusi prediktif berbasis data seperti ini diharapkan dapat membantu pengambilan keputusan medis yang lebih baik.

## Fitur Utama
- Prediksi risiko gagal jantung berbasis dataset kesehatan.
- Perbandingan performa model XGBoost, LightGBM, dan CatBoost.
- Analisis metrik evaluasi untuk menentukan model terbaik.

## Dataset
Dataset yang digunakan berisi informasi kesehatan individu yang relevan dengan gagal jantung, seperti:
- Usia
- Tekanan darah
- Kadar kolesterol
- Kondisi kesehatan lainnya
Dataset diambil dari sumber [https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction].

## Algoritma yang Digunakan
1. XGBoost (Extreme Gradient Boosting): Algoritma berbasis decision tree yang sangat efisien untuk dataset besar.
2. LightGBM (Light Gradient Boosting Machine): Algoritma boosting yang fokus pada efisiensi dan kecepatan.
3. CatBoost (Categorical Boosting): Algoritma yang dirancang untuk menangani data kategorikal dengan baik.

## Metrik Evaluasi
Model dievaluasi menggunakan metrik:

- Akurasi
- Precision
- Recall
- F1-Score
- ROC-AUC
