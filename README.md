# Practical Statistics for Data Scientists
 
Repositori ini berisi reproduksi kode dan penjelasan teoritis mendalam untuk setiap bab dari buku Practical Statistics for Data Scientists karangan Peter Bruce, Andrew Bruce, dan Peter Gedeck. Proyek ini disusun sebagai pemenuhan Tugas 4 Enrichment for Machine Learning and Deep Learning Classes untuk Tugas Individu. Seluruh kode ditulis menggunakan bahasa pemrograman Python dan disajikan dalam format Jupyter Notebook beserta penjelasan teoritisnya secara terstruktur.
 
---
 
## Identifikasi
 
| Field | Detail |
|-------|--------|
| Nama | Najwa Bilqis Al Khalidah |
| NIM | 101032300186 |
| Kelas | TK-46-GAB |
| Mata Kuliah | Machine Learning |
| Referensi | Introduction to Machine Learning with Python -- Andreas C. Muller & Sarah Guido (O'Reilly) |
 
---
 
## Deskripsi Proyek
 
Tugas ini merupakan bagian dari enrichment course Machine Learning dan Deep Learning.
Tujuannya adalah memperdalam pemahaman dan keterampilan praktis dalam
mengimplementasikan konsep-konsep inti Machine Learning melalui reproduksi kode
dan penjelasan teori terstruktur.
 
Setiap notebook mencakup:
- Penjelasan teori konsep yang dibahas (dalam Bahasa Indonesia)
- Reproduksi dan adaptasi kode dari buku referensi
- Visualisasi hasil eksperimen
- Ringkasan dan panduan praktis di akhir setiap chapter
 
---
 
## Struktur Repository
 
```
PracticalStatisticsforDataScientists/
|
|-- Chapter_01_Exploratory_Data_Analysis.ipynb
|-- Chapter_02_Data_and_Sampling_Distributions.ipynb
|-- Chapter_03_Statistical_Experiments_and_Significance_Testing.ipynb
|-- Chapter_04_Regression_and_Prediction.ipynb
|-- Chapter_05_Classification.ipynb
|-- Chapter_06_Statistical_Machine_Learning.ipynb
|-- Chapter_07_Unsupervised_Learning.ipynb
|-- README.md
```
 
---
 
## Deskripsi Setiap Chapter
 
* **Chapter 1: Exploratory Data Analysis**
Bab ini membahas tahapan awal dalam analisis data, termasuk estimasi lokasi seperti nilai tengah dan nilai rata rata, estimasi variabilitas seperti standar deviasi, eksplorasi distribusi data dengan visualisasi, analisis data kategorikal, hingga pengenalan korelasi antar variabel numerik.

* **Chapter 2: Data and Sampling Distributions**
Bab ini berfokus pada pentingnya desain pengambilan sampel, bias seleksi, distribusi sampling, dan Teorema Limit Pusat. Konsep lanjutan seperti metode bootstrap untuk pengambilan sampel ulang, interval kepercayaan, dan berbagai jenis distribusi spesifik seperti Binomial dan Poisson juga dijelaskan secara komprehensif.

* **Chapter 3: Statistical Experiments and Significance Testing**
Bab ini mengulas cara merancang eksperimen statistik yang valid melalui pengujian perbandingan kelompok, uji hipotesis, dan metode uji permutasi. Evaluasi signifikansi dijelaskan menggunakan Nilai Probabilitas, Uji T, Analisis Varians untuk banyak kelompok, dan Uji Chi Square untuk data kategorikal.

* **Chapter 4: Regression and Prediction**
Bab ini menjabarkan regresi sebagai alat prediksi dasar. Dimulai dari regresi linear sederhana, regresi linear berganda, penanganan variabel faktor dengan pengkodean kategori, hingga pemahaman tentang masalah multikolinearitas. Evaluasi asumsi regresi melalui analisis residual dan pengenalan regresi polinomial juga dibahas secara mendalam.

* **Chapter 5: Classification**
Bab ini berfokus pada prediksi kategori atau kelas. Algoritma dasar seperti Naive Bayes, Analisis Diskriminan, dan Regresi Logistik dieksplorasi beserta cara mengevaluasi kinerjanya menggunakan matriks konfusi dan kurva probabilitas. Strategi penanganan data tidak seimbang turut disertakan beserta contoh simulasinya.

* **Chapter 6: Statistical Machine Learning**
Bab ini menjembatani statistik klasik dengan konsep modern. Fokus utamanya adalah pada algoritma yang mampu menangani pola non linear, mulai dari K Nearest Neighbors, Pohon Keputusan, hingga teknik ensemble tingkat lanjut seperti Random Forest dan Gradient Boosting.

* **Chapter 7: Unsupervised Learning**
Bab terakhir ini membahas teknik penggalian pola pada data tanpa label target. Analisis Komponen Utama diperkenalkan untuk reduksi dimensi, diikuti oleh berbagai teknik pengelompokan seperti K Means Clustering, Hierarchical Clustering, dan Gaussian Mixture Models untuk menangani distribusi data yang lebih kompleks.
 
 
---
 
## Cara Menjalankan
 
### Persyaratan Sistem
Untuk menjalankan seluruh file notebook di dalam repositori ini, pastikan sistem Anda telah terpasang pustaka Python berikut:
* numpy
* pandas
* matplotlib
* seaborn
* scipy
* scikit learn
* statsmodels

### Menjalankan Notebook
 
```bash
git clone https://github.com/njwbilll/Tugas-4_Practical-Statistics-for-Data-Scientists-O-Reilly_Najwa-Bilqis-Al-Khalidah.git
cd Tugas-4_Practical-Statistics-for-Data-Scientists-O-Reilly_Najwa-Bilqis-Al-Khalidah
jupyter notebook
```
 
Kemudian buka notebook sesuai urutan chapter (01 hingga 08) di browser.
 
### Urutan yang Disarankan
 
Notebook dirancang untuk dibaca secara berurutan karena konsep dari
chapter sebelumnya sering digunakan di chapter berikutnya.
 
```
01 Exploratory Data Analysis
   |
   v
02 Data and Sampling Distributions
   |
   v
03 Statistical Experiments and Significance Testing
   |
   v
04 Regression and Prediction
   |
   v
05 Classification
   |
   v
06 Statistical Machine Learning
   |
   v
07 Unsupervised Learning
```
