🏥 Diabetes Prediction Model - Machine Learning

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Focus-Machine%20Learning-green?style=for-the-badge)](https://en.wikipedia.org/wiki/Machine_learning)

📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun model prediktif yang dapat menentukan apakah seorang pasien menderita diabetes berdasarkan data medis tertentu (seperti glukosa, tekanan darah, BMI, dll). Proyek ini merupakan bagian dari portofolio saya dalam mendalami Supervised Learning.

📊 Dataset
Dataset yang digunakan berisi informasi medis pasien, termasuk:
- Fitur: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age.
- Target:`Outcome` (0: Tidak Diabetes, 1: Diabetes).
🛠️ Tech Stack & Library
- Bahasa:Python
- Libraries:- `Pandas` (Data Manipulation)
  - `Matplotlib` (Data Visualization)
  - `Scikit-Learn` (Machine Learning Framework)

📈 Alur Kerja (Workflow)
1. Exploratory Data Analysis (EDA):Mengecek korelasi antar variabel menggunakan matriks visualisasi.
2. Data Preprocessing:Membersihkan data dan menangani nilai yang tidak konsisten.
3. Data Splitting:Membagi data menjadi 70% Training set dan 30% Testing set dengan teknik `stratify` untuk menjaga distribusi target.
4. Model Building:Menggunakan algoritma klasifikasi untuk melatih data.

📝 Hasil Analisis
Model ini mampu memberikan gambaran distribusi data pasien yang terkena diabetes dan yang tidak, serta memberikan wawasan tentang faktor medis mana yang paling berpengaruh (korelasi tinggi) terhadap risiko diabetes.

Proyek ini dikembangkan sebagai bentuk validasi keahlian saya yang tersertifikasi oleh Udemy (Machine Learning with Python).
