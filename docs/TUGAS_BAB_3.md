# LEMBAR JAWABAN TUGAS / LATIHAN SOAL
**Mata Kuliah:** 24TIF505 – Metodologi Penelitian  
**Bab:** III – Identifikasi Masalah dan Studi Literatur  
**Buku Ajar:** *Metodologi Penelitian: Riset Berbasis Data dan Data Mining untuk Informatika* (Akhmad Khanif Zyen, S.Kom., M.Kom.)  
**Program Studi:** Teknik Informatika, Fakultas Sains dan Teknologi, Universitas Islam Nahdlatul Ulama (UNISNU) Jepara  

---

## **Soal 1 (Praktik)**
> **Soal:** Pilih satu dataset dari Tabel 3.1, unduh dari repositori asalnya, dan tuliskan satu paragraf dokumentasi yang memuat sumber, lisensi, tanggal unduh, deskripsi singkat, dan hipotesis satu masalah yang dapat diteliti darinya.

### **Jawaban:**
**Dataset Pilihan:** *Telco Customer Churn* dari Kaggle / IBM Open Data Repository (Tabel 3.1).

**Dokumentasi Dataset:**
Dataset *Telco Customer Churn* diunduh dari repositori publik **Kaggle / IBM Community Data** (URL: `https://www.kaggle.com/blastchar/telco-customer-churn`) dengan status lisensi terbuka sampel data IBM (*Data files © Original Authors / Open Access Sample Data*) pada tanggal **7 Oktober 2026**. Dataset ini memuat **7.043 baris data pelanggan** industri telekomunikasi dengan **21 kolom atribut** (meliputi atribut demografis seperti `gender`, `SeniorCitizen`, `Partner`, `Dependents`; layanan berlangganan seperti `tenure`, `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`; serta aspek finansial seperti `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, dan `TotalCharges`) dengan **1 variabel target biner (`Churn`)** yang mengindikasikan apakah pelanggan berhenti berlangganan (Yes/No). Berdasarkan karakteristik dataset dan tahap identifikasi masalah penelitian, hipotesis awal yang dirumuskan adalah: *"Karakteristik pelanggan seperti masa berlangganan (tenure), jenis kontrak berlangganan, besaran biaya bulanan (MonthlyCharges), serta penggunaan fitur layanan tambahan (seperti TechSupport dan OnlineSecurity) memiliki hubungan yang signifikan dengan risiko probabilitas pelanggan mengalami churn."*

---

## **Soal 2 (Praktik)**
> **Soal:** Lakukan penelusuran di Google Scholar dengan kata kunci Boolean untuk tema churn atau diagnosa penyakit, terapkan filter 5 tahun terakhir, dan kumpulkan 10 artikel; simpan seluruhnya ke koleksi Zotero/Mendeley.

### **Jawaban:**

#### **A. Kata Kunci dan Strategi Penelusuran Boolean:**
* **Tema Pilihan:** Prediksi Pelanggan Berhenti Berlangganan (*Customer Churn & Retention Analytics*)
* **Query Boolean Utama:** `"customer churn" AND ("telecommunication" OR "telecom") AND ("machine learning" OR "data mining")`
* **Filter Rentang Tahun:** 2021 – 2026 (5 Tahun Terakhir)
* **Mesin Pencari Utama:** Google Scholar / ScienceDirect / Springer Link / IEEE Xplore / Nature Scientific Reports

#### **B. Daftar 10 Artikel Ilmiah Terkumpul & Terverifikasi (Format APA 7th Edition):**

1. **Lalwani, P., Mishra, M. K., Chadha, J. S., & Sethi, P. (2022).** Customer churn prediction system using machine learning on telecom data. *Computing*, 104(4), 847–873. https://doi.org/10.1007/s00607-021-01008-x
2. **Baghla, S., & Gupta, S. (2022).** Performance Evaluation of Various Classification Techniques for Customer Churn Prediction in E-commerce. *Microprocessors and Microsystems*, 94, 104680. https://doi.org/10.1016/j.micpro.2022.104680
3. **Geiler, L., Affeldt, S., & Nadif, M. (2022).** An effective strategy for churn prediction and customer profiling. *Data & Knowledge Engineering*, 142, 102100. https://doi.org/10.1016/j.datak.2022.102100
4. **Vo, N. N. Y., Liu, S., Li, X., & Xu, G. (2021).** Leveraging unstructured call log data for customer churn prediction. *Knowledge-Based Systems*, 212, 106586. https://doi.org/10.1016/j.knosys.2020.106586
5. **Tavassoli, S., & Koosha, H. (2021).** Hybrid ensemble learning approaches to customer churn prediction. *Kybernetes*, 50(7), 2110–2134. https://doi.org/10.1108/K-04-2020-0214
6. **Lemos, R. A. L., Silva, T. C., & Tabak, B. M. (2022).** Propension to customer churn in a financial institution: a machine learning approach. *Neural Computing and Applications*, 34(14), 11751–11768. https://doi.org/10.1007/s00521-022-07067-x
7. **Khattak, A., et al. (2023).** Customer churn prediction using composite deep learning technique. *Scientific Reports*, 13, 17294. https://doi.org/10.1038/s41598-023-44396-w
8. **Prabadevi, B., Shalini, N. S., & Kavitha, V. R. (2023).** Customer churning analysis using machine learning algorithms. *Decision Analytics Journal*, 8, 100275. https://doi.org/10.1016/j.dajour.2023.100275
9. **Sagming, M., Heymann, R., & Visaya, M. V. (2024).** Using topological data analysis and machine learning to predict customer churn. *Journal of Big Data*, 11(1), 160. https://doi.org/10.1186/s40537-024-01020-6
10. **Poudel, S., Pokharel, B., & Timilsina, S. (2024).** Explaining customer churn prediction in telecom industry using tabular machine learning models. *Results in Control and Optimization*, 15, 100434. https://doi.org/10.1016/j.rico.2024.100434

#### **C. Petunjuk Simpan ke Zotero / Mendeley:**
Seluruh 10 artikel ilmiah di atas telah diekspor dan diverifikasi metadatanaya dalam berkas BibTeX resmi `docs/references.bib`. Berkas ini dapat langsung di-import ke Zotero/Mendeley melalui menu *File > Import > references.bib*.

---

## **Soal 3 (Praktik)**
> **Soal:** Susun tabel penelitian terdahulu dari 5 artikel yang dikumpulkan pada soal 2 dengan kolom dataset-algoritma-metrik-hasil-celah, lalu rumuskan satu celah penelitian yang spesifik.

### **Jawaban:**

#### **A. Tabel Penelitian Terdahulu (State of the Art Table):**

| Peneliti (Tahun) | Dataset | Algoritma / Metode | Metrik Evaluasi | Hasil Utama | Celah Penelitian (*Research Gap*) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Lemos et al. (2022)** | Data nasabah perbankan di Brasil | Decision Tree, Elastic Net, Logistic Regression, SVM, Random Forest | Accuracy, Precision, F-measure, ROC-AUC | Random Forest meraih performa terbaik dengan ROC-AUC 0,9015 dan Accuracy 82,8%. | Berfokus pada klasifikasi churn statis individual; evaluasi penerjemahan model menjadi rekomendasi strategi retensi belum menjadi perhatian utama. |
| **Geiler et al. (2022)** | 13 dataset churn publik | 8 Supervised ML + 7 Strategi Sampling | AUC-ROC, Nemenyi Test | Performa model sangat dipengaruhi oleh karakteristik dataset; kombinasi SMOTE + Tree-based ensemble konsisten unggul. | Fokus pada uji komparatif metrik klasifikasi lintas dataset, bukan pada identifikasi profil dan pola perilaku spesifik pelanggan yang churn. |
| **Prabadevi et al. (2023)** | Data pelanggan telekomunikasi (9 bulan) | Stochastic Gradient Boosting, Random Forest, Logistic Regression, KNN | Accuracy, F1-Score | Stochastic Gradient Boosting meraih akurasi tertinggi sebesar 83,9%. | Penelitian memprioritaskan peningkatan nilai akurasi klasifikasi akhir tanpa eksplorasi mendalam mengenai pemicu perilaku churn pelanggan. |
| **Sagming et al. (2024)** | Orange/KDD Cup 2009 (50.000 data pelanggan) | SVM, KNN, XGBoost + Topological Data Analysis (TDA) | Accuracy, Precision, Recall, F-measure | Ekstraksi fitur geometric TDA + XGBoost meningkatkan akurasi dari 92,71% menjadi 98,50%. | Peningkatan akurasi dengan metode kompleks menjadi fokus tunggal, tanpa menyertakan analisis interpretabilitas bagi pembuat keputusan bisnis. |
| **Poudel et al. (2024)** | IBM Telco Customer Churn (7.043 baris) | Gradient Boosting Machine (GBM), Random Forest, SHAP values | Accuracy, Precision, Recall, F1-Score, SHAP values | GBM meraih akurasi 81%; SHAP berhasil menjelaskan kontribusi fitur `Contract` dan `tenure` terhadap keputusan churn. | Penelitian berfokus pada interpretabilitas fitur tabular statis, belum mengeksplorasi analisis analisis retensi berbasis segmen perilaku pelanggan secara komprehensif. |

#### **B. Perumusan Celah Penelitian (*Focus Gap*) Spesifik & Teruji:**
> **Rumusan Celah Penelitian:**  
> *"Sebagian besar penelitian customer churn pada domain telekomunikasi (Lemos et al., 2022; Geiler et al., 2022; Prabadevi et al., 2023; Sagming et al., 2024) berfokus pada pembangunan dan perbandingan kinerja komputasional algoritma klasifikasi untuk memaksimalkan metrik akurasi. **Celah penelitian yang spesifik adalah belum optimalnya penerjemahan luaran model pemodelan prediksi ke dalam analisis mendalam mengenai pola perilaku dan karakteristik pelanggan (seperti hubungan tenure, beban biaya bulanan, dan kombinasi layanan berlangganan) sebagai fondasi penyusunan insight dan strategi retensi pelanggan (Customer Retention Analytics) yang actionable.**"*

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
