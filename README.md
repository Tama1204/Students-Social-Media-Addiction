# Students-Social-Media-Addiction
Proyek ini bertujuan untuk menganalisis tingkat kecanduan media sosial pada mahasiswa dengan pendekatan kuantitatif. Data dikumpulkan melalui kuesioner, lalu dianalisis menggunakan Google Colab untuk mendapatkan wawasan terkait frekuensi penggunaan, dampak akademik, dan faktor-faktor pemicu kecanduan.
**Deskripsi Proyek**
Proyek ini merupakan analisis data mengenai tingkat kecanduan media sosial di kalangan mahasiswa. Dataset yang digunakan berisi catatan anonim tentang perilaku mahasiswa dalam menggunakan media sosial serta dampaknya terhadap kehidupan sehari-hari, seperti performa akademik, tidur, dan kesehatan mental.

Kami menggunakan pendekatan data science termasuk eksplorasi data, visualisasi, serta model machine learning menggunakan Random Forest Regressor untuk memprediksi tingkat kecanduan.

**Isi Repositori**
presentasi.pdf            :File presentasi akhir yang merangkum seluruh hasil analisis
data_students.csv         :Dataset hasil survei mahasiswa
students_addiction.ipynb  :Notebook analisis menggunakan Python di Google Colab
link_colab.txt            :Link menuju notebook Google Colab online
README.md                 :Dokumentasi proyek ini

**Variabel Utama dalam Dataset**
- Student_ID, Age, Gender, Academic_Level, Country
- Avg_Daily_Usage_Hours : Rata-rata waktu harian menggunakan media sosial
- Most_Used_Platform, Affects_Academic_Performance
- Sleep_Hours_Per_Night, Mental_Health_Score, Relationship_Status
- Conflicts_Over_Social_Media, Addicted_Score

**Tujuan Analisis**
1. Menggali pola penggunaan media sosial mahasiswa berdasarkan demografi dan kebiasaan
2. Menilai dampak penggunaan media sosial terhadap:
   - Performa akademik
   - Kesehatan mental
   - Jam tidur
   - Konflik sosial
3. Memprediksi skor kecanduan media sosial (Addicted_Score) menggunakan machine learning

**Hasil Model Machine Learning**
- Algoritma : Random Forest Regressor
  R² Score : 0.99 (Model sangat akurat)
- MAE & RMSE rendah : Prediksi sangat dekat dengan nilai aktual
- Fitur paling berpengaruh : Avg_Daily_Usage_Hours, Conflicts_Over_Social_Media, Mental_Health_Score, Sleep_Hours_Per_Night

Link Google Colab
(https://colab.research.google.com/drive/1tvefF74AZTeOBlWChNidiQr2qG9wABDT?usp=sharing)
