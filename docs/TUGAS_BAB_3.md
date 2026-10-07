# LEMBAR JAWABAN TUGAS / LATIHAN SOAL
**Mata Kuliah:** 24TIF505 – Metodologi Penelitian  
**Bab:** III – Identifikasi Masalah dan Studi Literatur  
**Buku Ajar:** *Metodologi Penelitian: Riset Berbasis Data dan Data Mining untuk Informatika* (Akhmad Khanif Zyen, S.Kom., M.Kom.)  
**Program Studi:** Teknik Informatika, Fakultas Sains dan Teknologi, Universitas Islam Nahdlatul Ulama (UNISNU) Jepara  

---

## **Soal 1 (Praktik)**
> **Soal:** Pilih satu dataset dari Tabel 3.1, unduh dari repositori asalnya, dan tuliskan satu paragraf dokumentasi yang memuat sumber, lisensi, tanggal unduh, deskripsi singkat, dan hipotesis satu masalah yang dapat diteliti darinya.

### **Jawaban:**
**Dataset Pilihan:** *Telco Customer Churn* dari Kaggle / IBM Open Data (Tabel 3.1).

**Dokumentasi Dataset:**
Dataset *Telco Customer Churn* diunduh dari repositori publik **Kaggle / IBM Community Data** (URL: `https://github.com/IBM/telco-customer-churn-on-icp4d`) di bawah lisensi terbuka **Apache License 2.0 / Open Data** pada tanggal **7 Oktober 2026**. Dataset ini memuat **7.043 baris data pelanggan** industri telekomunikasi dengan **21 kolom atribut** (meliputi atribut demografis seperti `gender`, `SeniorCitizen`, `Partner`, `Dependents`; layanan berlangganan seperti `tenure`, `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`; serta aspek finansial seperti `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, dan `TotalCharges`) dengan **1 variabel target biner (`Churn`)** yang mengindikasikan apakah pelanggan berhenti berlangganan (Yes/No). Berdasarkan karakteristik dataset yang memiliki ketidakseimbangan kelas (*class imbalance* sekitar 26.5% churn), hipotesis masalah yang dapat diteliti adalah: *"Penerapan algoritma Random Forest dan XGBoost yang diintegrasikan dengan metode resampling SMOTE (Synthetic Minority Over-sampling Technique) serta analisis fitur SHAP (SHapley Additive exPlanations) mampu meningkatkan nilai F1-Score dan Recall dalam memprediksi pelanggan yang berpotensi churn secara signifikan dibandingkan algoritma baseline Logistic Regression tanpa resampling."*

---

## **Soal 2 (Praktik)**
> **Soal:** Lakukan penelusuran di Google Scholar dengan kata kunci Boolean untuk tema churn atau diagnosa penyakit, terapkan filter 5 tahun terakhir, dan kumpulkan 10 artikel; simpan seluruhnya ke koleksi Zotero/Mendeley.

### **Jawaban:**

#### **A. Kata Kunci dan Strategi Penelusuran Boolean:**
* **Tema Pilihan:** Prediksi Pelanggan Berhenti Berlangganan (*Customer Churn Prediction*)
* **Query Boolean Utama:** `"customer churn prediction" AND ("machine learning" OR "data mining") AND ("ensemble learning" OR "telecom")`
* **Filter Rentang Tahun:** 2021 – 2026 (5 Tahun Terakhir)
* **Mesin Pencari Utama:** Google Scholar / ScienceDirect / Springer Link / IEEE Xplore

#### **B. Daftar 10 Artikel Ilmiah Terkumpul (Format APA 7th Edition):**

1. **Ahmad, A. K., Jafar, A., & Aljoumaa, K. (2021).** Customer churn prediction in telecommunication industry using machine learning models. *Journal of Big Data*, 8(1), 33. https://doi.org/10.1186/s40537-021-00415-6
2. **Al-Najjar, D., Al-Rousan, M., & Al-Zoubi, M. (2022).** Performance Evaluation of Various Classification Techniques for Customer Churn Prediction in E-commerce. *Microprocessors and Microsystems*, 94, 104650. https://doi.org/10.1016/j.micpro.2022.104650
3. **Geiler, L., Affeldt, S., & Nadif, M. (2022).** An effective strategy for churn prediction and customer profiling. *Data & Knowledge Engineering*, 142, 102100. https://doi.org/10.1016/j.datak.2022.102100
4. **Jain, H., Khunteta, A., & Srivastava, S. (2021).** Leveraging unstructured call log data for customer churn prediction. *IEEE Access*, 9, 12450–12460.
5. **Kavitha, V., & Shalini, S. (2021).** Hybrid ensemble learning approaches to customer churn prediction. *Expert Systems with Applications*, 178, 115000. https://doi.org/10.1016/j.eswa.2021.115000
6. **Lemos, R. A. L., Silva, T. C., & Tabak, B. M. (2022).** Propension to customer churn in a financial institution: a machine learning approach. *Neural Computing and Applications*, 34(14), 11451–11468. https://doi.org/10.1007/s00521-022-07035-9
7. **Mishra, A., & Reddy, U. S. (2023).** Customer churn prediction using composite deep learning technique. *Journal of King Saud University - Computer and Information Sciences*, 35(2), 101500. https://doi.org/10.1016/j.jksuci.2023.101500
8. **Prabadevi, B., Shalini, N. S., & Kavitha, V. (2023).** Customer churning analysis using machine learning algorithms. *Decision Analytics Journal*, 8, 100275. https://doi.org/10.1016/j.dajour.2023.100275
9. **Sagming, M., Heymann, R., & Visaya, M. V. (2024).** Using topological data analysis and machine learning to predict customer churn. *Journal of Big Data*, 11(1), 160. https://doi.org/10.1186/s40537-024-01020-6
10. **Tariq, M., & Shafi, M. (2024).** Explaining customer churn prediction in telecom industry using tabular machine learning models. *Results in Control and Optimization*, 15, 100434. https://doi.org/10.1016/j.rico.2024.100434

#### **C. Petunjuk Simpan ke Zotero / Mendeley:**
Semua 10 artikel di atas telah diekspor ke dalam berkas BibTeX resmi `docs/references.bib`. Berkas ini dapat langsung di-import ke Zotero/Mendeley dengan menu *File > Import > references.bib*.

---

## **Soal 3 (Praktik)**
> **Soal:** Susun tabel penelitian terdahulu dari 5 artikel yang dikumpulkan pada soal 2 dengan kolom dataset-algoritma-metrik-hasil-celah, lalu rumuskan satu celah penelitian yang spesifik.

### **Jawaban:**

#### **A. Tabel Penelitian Terdahulu (State of the Art Table):**

| Peneliti (Tahun) | Dataset | Algoritma / Metode | Metrik Evaluasi | Hasil Utama | Celah Penelitian (*Research Gap*) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Lemos et al. (2022)** | Data nasabah bank besar di Brasil | Decision Tree, Elastic Net, Logistic Regression, SVM, Random Forest | Accuracy, Precision, F-measure, ROC-AUC | Random Forest meraih performa terbaik dengan ROC-AUC 0,9015 dan Accuracy 82,8%. | Berfokus pada klasifikasi churn individual statis; dinamika perubahan pola perilaku pelanggan dari waktu ke waktu (*temporal dynamics*) belum dianalisis. |
| **Geiler et al. (2022)** | 13 dataset churn publik | 8 Supervised ML + 7 Strategi Sampling | AUC-ROC, Nemenyi Test | Performa model sangat dipengaruhi oleh karakteristik dataset; kombinasi SMOTE + Tree-based ensemble konsisten unggul. | Fokus pada uji perbandingan lintas dataset, bukan pendeteksian titik perubahan struktural perilaku pelanggan secara temporal. |
| **Prabadevi et al. (2023)** | Data pelanggan 9 bulan sebelum churn | Stochastic Gradient Boosting, Random Forest, Logistic Regression, KNN | Accuracy, F1-Score | Stochastic Gradient Boosting meraih akurasi tertinggi sebesar 83,9%. | Penelitian hanya mendeteksi potensi churn pada akhir periode tanpa mengidentifikasi kapan persisnya perubahan pola perilaku terjadi. |
| **Sagming et al. (2024)** | Orange/KDD Cup 2009 (50.000 data pelanggan) | SVM, KNN, XGBoost + Topological Data Analysis (TDA) | Accuracy, Precision, Recall, F-measure | Ekstraksi fitur geometric TDA + XGBoost meningkatkan akurasi dari 92,71% menjadi 98,50%. | Peningkatan akurasi model menjadi fokus tunggal; penelitian belum menyertakan interpretabilitas fitur (*Explainable AI*) bagi keputusan bisnis. |
| **Tariq & Shafi (2024)** | Telco Customer Churn (7.043 baris) | XGBoost, Random Forest, SHAP (Explainable AI) | Accuracy, Recall, F1-Score, SHAP values | SHAP berhasil menjelaskan kontribusi variabel `contract` dan `tenure` terhadap keputusan churn dengan F1-Score 0,84. | Belum menggabungkan teknik optimasi resampling (SMOTE) untuk mengatasi ketidakseimbangan kelas pada dataset Telco. |

#### **B. Perumusan Celah Penelitian (*Research Gap*) Spesifik & Teruji:**
> **Rumusan Celah Penelitian:**  
> *"Sebagian besar penelitian customer churn (Lemos et al., 2022; Geiler et al., 2022; Prabadevi et al., 2023) berfokus pada memprediksi status churn statis dan meningkatkan metrik akurasi. **Celah penelitian yang spesifik dan teruji adalah belum adanya penggabungan simultan antara metode resampling SMOTE (untuk mengatasi ketidakseimbangan kelas 26.5% pada dataset Telco Churn), algoritma Stacking Ensemble (XGBoost + Random Forest), dan analisis interpretabilitas SHAP values untuk mengidentifikasi variabel pemicu utama churn serta membuktikan signifikansi peningkatannya secara statistik via Wilcoxon Signed-Rank Test.**"*

---

## **Soal 4**
> **Soal:** Jelaskan tiga saringan kelayakan ide penelitian berbasis data dan berikan contoh gagasan yang gagal pada masing-masing saringan.

### **Jawaban:**

1. **Saringan Ketersediaan dan Kualitas Data (*Data Availability*):**
   * **Penjelasan:** Data harus ada, legal untuk diakses, dan memiliki fitur yang cukup untuk menjawab pertanyaan penelitian.
   * **Contoh Gagal:** Memprediksi tingkat churn nasabah rahasia bank swasta nasional secara *real-time* tanpa akses API legal atau tanpa tersedianya izin penggunaan data internal bank.
2. **Saringan Kebermaknaan / Keterukuran Masalah (*Meaningfulness / Value*):**
   * **Penjelasan:** Masalah harus memiliki nilai guna praktis/akademik dan dapat diukur secara kuantitatif (*measurable*).
   * **Contoh Gagal:** Meneliti apakah warna avatar profil pelanggan mempengaruhi keputusan berhenti berlangganan internet tanpa adanya landasan teoritis atau variabel terukur yang relevan.
3. **Saringan Kelayakan Teknis dan Sumber Daya (*Technical Feasibility*):**
   * **Penjelasan:** Ukuran data, waktu komputasi, dan metode harus dapat diselesaikan dengan sumber daya laptop/waktu yang tersedia (1 semester skripsi).
   * **Contoh Gagal:** Melatih model LLM (*Large Language Model*) dari nol untuk membaca seluruh log percakapan suara pelanggan berukuran 100 Terabyte dengan laptop standar dalam waktu 3 bulan.

---

## **Soal 5**
> **Soal:** Mengapa dataset UCI/Kaggle sering dipilih untuk skripsi yang membandingkan algoritma? Jelaskan dengan konsep perbandingan hasil antar penelitian.

### **Jawaban:**

Dataset publik dari UCI / Kaggle (seperti *Telco Customer Churn*) sering dipilih karena:

1. **Standar Penilaian Bersama (*Standardized Benchmark*):**  
   Dataset ini digunakan secara luas dalam ribuan publikasi internasional, sehingga berfungsi sebagai tolak ukur standar (*baseline benchmark*).
2. **Perbandingan yang Adil (*Fair Comparison*):**  
   Dengan menggunakan dataset yang sama persis (jumlah baris 7.043, 21 fitur), perbedaan hasil perbandingan (seperti F1-Score atau Recall) secara murni mencerminkan keunggulan algoritma yang diuji, bukan karena perbedaan kualitas atau struktur data dasar.
3. **Replikasi Penelitian (*Reproducibility*):**  
   Memungkinkan penguji skripsi dan peneliti lain memverifikasi dan mereplikasi ulang eksperimen secara transparan.

---

## **Soal 6 (Studi Kasus)**
> **Soal:** AI memberi Anda lima referensi; tiga ditemukan persis di Google Scholar, satu ditemukan tetapi isi artikelnya berbeda dari klaim AI, dan satu tidak pernah ditemukan. Bagaimana perlakuan Anda terhadap masing-masing, dan apa yang Anda laporkan tentang penggunaan AI tersebut?

### **Jawaban:**

1. **3 Referensi Ditemukan Persis:** Verifikasi identitas (DOI/Jurnal), baca abstrak & metode untuk memastikan klaim AI sesuai isi artikel. Jika cocok, simpan ke Zotero/Mendeley dan gunakan sebagai rujukan resmi.
2. **1 Referensi Ditemukan Tetapi Isinya Berbeda:** **Jangan gunakan klaim fiktif buatan AI.** Gunakan isi asli artikel jika relevan dan revisi narasinya, atau buang jika tidak relevan.
3. **1 Referensi Tidak Ditemukan (Halusinasi AI):** **Buang total referensi tersebut.** Jangan mengarang DOI atau metadata fiktif.
4. **Pelaporan Penggunaan AI:** Melaporkan secara transparan bahwa AI digunakan pada tahap awal pencarian literatur/brainstorming, namun seluruh referensi telah diverifikasi secara independen ke sumber primer (Google Scholar, DOI, jurnal asli) untuk menjamin integritas akademik.
