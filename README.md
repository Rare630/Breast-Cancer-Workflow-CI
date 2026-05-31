Breast Cancer Classification with MLflow

Deskripsi Proyek

Proyek ini bertujuan untuk membangun model machine learning untuk mengklasifikasikan kanker payudara berdasarkan fitur-fitur hasil pemeriksaan medis menggunakan dataset Breast Cancer Wisconsin.

Dataset

Dataset yang digunakan adalah Breast Cancer Wisconsin Dataset yang tersedia pada library scikit-learn. Dataset telah melalui tahap preprocessing yang meliputi:

Pemisahan fitur dan target
Pembagian data train dan test
Standardisasi fitur menggunakan StandardScaler

Dataset hasil preprocessing disimpan dalam file:

breast_cancer_preprocessed.csv

Model

Model yang digunakan adalah Random Forest Classifier dengan parameter:

n_estimators = 100
random_state = 42

Evaluasi

Hasil evaluasi model menunjukkan akurasi sebesar:

0.945054945054945

MLflow

Eksperimen model dilacak menggunakan MLflow Tracking. Informasi yang tersimpan meliputi:

Parameter model
Metrics
Artifacts
Model hasil training

Struktur Folder

modelling.py
breast_cancer_preprocessed.csv
model.pkl
requirements.txt
README.md
screenshot_dashboard.jpg
screenshot_artifact.jpg
