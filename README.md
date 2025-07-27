#  Analisis Kesehatan Mental & Prediksi Berbasis AI

##  Ringkasan Proyek (Project Overview)

Proyek ini bertujuan untuk menganalisis kondisi kesehatan mental berdasarkan data survei nyata yang tersedia di Kaggle. Dengan menggabungkan **Exploratory Data Analysis (EDA)** dan **model prediksi berbasis Artificial Intelligence (AI)**, proyek ini mencoba menemukan pola, hubungan, dan wawasan penting yang berkaitan dengan kesehatan mental individu.

Selain itu, model AI diterapkan untuk membantu memprediksi kemungkinan seseorang mengalami gangguan mental berdasarkan berbagai faktor seperti gaya hidup, pekerjaan, dan kondisi sosial.



## 📂 Link Dataset Mentah (Raw Dataset)

Dataset yang digunakan berasal dari Kaggle, dengan tautan sebagai berikut:  
🔗 (https://www.kaggle.com/code/imtkaggleteam/mental-health-eda-prediction/input)

Beberapa file utama:
- `1-mental_prevalence.csv`
- `4-mental_prevalence.csv`
- `6-depressive-symptoms-across-us-population.csv`
- `7-mental-illnesses.csv`

Dataset ini berisi hasil survei tentang berbagai aspek psikologis seperti kecemasan, depresi, durasi tidur, tingkat stres, serta informasi demografis.



##  Temuan & Insight (Insight & Findings)

Berikut beberapa temuan penting hasil dari proses EDA:

1. **Kelompok Usia Rentan**  
   Usia 18–30 tahun menunjukkan tingkat tertinggi dalam kasus kecemasan dan depresi.

2. **Pengaruh Gender terhadap Kesehatan Mental**  
   Responden perempuan dan non-biner melaporkan tingkat stres dan tekanan mental yang lebih tinggi dibandingkan laki-laki.

3. **Tidur & Aktivitas Fisik**  
   Waktu tidur yang kurang dan kurangnya aktivitas fisik berkorelasi kuat dengan kondisi kesehatan mental yang buruk.

4. **Stres di Tempat Kerja**  
   Tekanan kerja dan kurangnya dukungan mental dari tempat kerja menjadi penyebab utama gangguan psikologis.

5. **Potensi Prediksi AI**  
   Model Linear Regression menunjukkan hasil awal yang menjanjikan dalam memprediksi skor kesehatan mental dari variabel gaya hidup.



## 🤖 Penjelasan Dukungan AI (AI Support Explanation)

Dalam proyek ini, AI digunakan untuk membantu proses analisis dan prediksi kondisi kesehatan mental. Model yang digunakan:

- **Jenis Model:** Regresi Linier (Linear Regression)
- **Tujuan:** Memprediksi skor kesehatan mental berdasarkan input seperti jumlah jam tidur, tingkat stres, umur, dan aktivitas harian.
- **Manfaat AI:** Dapat membantu mengidentifikasi individu yang berpotensi mengalami gangguan mental secara dini sehingga dapat dilakukan intervensi atau dukungan lebih cepat.

 Rencana ke depan:
- Menggunakan model machine learning lain seperti Random Forest atau XGBoost
- Membangun model klasifikasi (contoh: memprediksi apakah seseorang mengalami depresi atau tidak)
- Mengembangkan dashboard interaktif berbasis web untuk visualisasi dan prediksi



## 🧰 Tools & Library yang Digunakan

- Bahasa Pemrograman: Python
- Library:
  - `pandas`, `numpy` – untuk manipulasi data
  - `matplotlib`, `seaborn`, `plotly` – untuk visualisasi data
  - `scikit-learn` – untuk machine learning dan evaluasi model
