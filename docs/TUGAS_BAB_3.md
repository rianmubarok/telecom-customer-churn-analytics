# LEMBAR JAWABAN TUGAS / LATIHAN SOAL
**Mata Kuliah:** 24TIF505 – Metodologi Penelitian  
**Bab:** III – Identifikasi Masalah dan Studi Literatur  
**Buku Ajar:** *Metodologi Penelitian: Riset Berbasis Data dan Data Mining untuk Informatika* (Akhmad Khanif Zyen, S.Kom., M.Kom.)  
**Program Studi:** Teknik Informatika, Fakultas Sains dan Teknologi, Universitas Islam Nahdlatul Ulama (UNISNU) Jepara  

---

## **Soal 1 (Praktik)**
> **Soal:** Pilih satu dataset dari Tabel 3.1, unduh dari repositori asalnya, dan tuliskan satu paragraf dokumentasi yang memuat sumber, lisensi, tanggal unduh, deskripsi singkat, dan hipotesis satu masalah yang dapat diteliti darinya.

### **Jawaban:**
**Dataset Pilihan:** *Telco Customer Churn* dari IBM GitHub Repository (Tabel 3.1).

**Dokumentasi Dataset:**
Dataset *Telco Customer Churn* yang digunakan dalam penelitian ini diperoleh dari repositori resmi **IBM GitHub** (`IBM/telco-customer-churn-on-icp4d`). Repositori resmi IBM memuat lisensi **Apache Software License 2.0** (ditujukan untuk struktur repositori/code pattern, sementara lisensi berkas data sampel tidak dinyatakan secara terpisah dalam repositori) dan diunduh pada tanggal **7 Oktober 2026**. Dataset ini memuat **7.043 baris data pelanggan** industri telekomunikasi dengan **21 kolom atribut** (meliputi atribut demografis seperti `gender`, `SeniorCitizen`, `Partner`, `Dependents`; layanan berlangganan seperti `tenure`, `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`; serta aspek finansial seperti `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, dan `TotalCharges`) dengan **1 variabel target biner (`Churn`)** yang mengindikasikan apakah pelanggan berhenti berlangganan (Yes/No). Berdasarkan karakteristik dataset dan tahap identifikasi masalah penelitian, hipotesis awal yang dirumuskan adalah: *"Karakteristik pelanggan seperti masa berlangganan (tenure), jenis kontrak berlangganan, besaran biaya bulanan (MonthlyCharges), serta penggunaan fitur layanan tambahan (seperti TechSupport dan OnlineSecurity) memiliki hubungan yang signifikan dengan risiko probabilitas pelanggan mengalami churn."*

---

## **Soal 2 (Praktik)**
> **Soal:** Lakukan penelusuran di Google Scholar dengan kata kunci Boolean untuk tema churn atau diagnosa penyakit, terapkan filter 5 tahun terakhir, dan kumpulkan 10 artikel; simpan seluruhnya ke koleksi Zotero/Mendeley.

### **Jawaban:**

#### **A. Kata Kunci dan Strategi Penelusuran Boolean:**
* **Tema Pilihan:** Prediksi Pelanggan Berhenti Berlangganan (*Customer Churn & Retention Analytics*)
* **Query Boolean Utama:** `"customer churn" AND ("telecommunication" OR "telecom") AND ("machine learning" OR "data mining")`
* **Filter Rentang Tahun:** 2022 – 2026 (5 Tahun Terakhir per Oktober 2026)
* **Mesin Pencari Utama:** Google Scholar / ScienceDirect / Springer Link / IEEE Xplore / Nature Scientific Reports / PLOS ONE / Journal of Big Data

#### **B. Daftar 10 Artikel Ilmiah Terkumpul & Terverifikasi (Format APA 7th Edition):**

1. **Lalwani, P., Mishra, M. K., Chadha, J. S., & Sethi, P. (2022).** Customer churn prediction system: A machine learning approach. *Computing*, 104(2), 271–294. https://doi.org/10.1007/s00607-021-00908-y
2. **Geiler, L., Affeldt, S., & Nadif, M. (2022).** An effective strategy for churn prediction and customer profiling. *Data & Knowledge Engineering*, 142, 102100. https://doi.org/10.1016/j.datak.2022.102100
3. **Mishra, A., & Reddy, U. S. (2022).** A novel approach for customer churn prediction using machine learning in telecom sector. *Journal of Big Data*, 9(1), 87. https://doi.org/10.1186/s40537-022-00637-x
4. **Sana, J. K., Abedin, M. Z., Rahman, M. S., & Rahman, M. S. (2022).** A novel customer churn prediction model for the telecommunication industry using data transformation methods and feature selection. *PLOS ONE*, 17(12), e0278095. https://doi.org/10.1371/journal.pone.0278095
5. **Khattak, A., et al. (2023).** Customer churn prediction using composite deep learning technique. *Scientific Reports*, 13, 17294. https://doi.org/10.1038/s41598-023-44396-w
6. **Prabadevi, B., Shalini, R., & Kavitha, B. R. (2023).** Customer churning analysis using machine learning algorithms. *International Journal of Intelligent Networks*, 4, 145–154. https://doi.org/10.1016/j.ijin.2023.05.005
7. **Wagh, S. K., Andhale, A. A., Wagh, K. S., Pansare, J. R., Ambadekar, S. P., & Gawande, S. H. (2024).** Customer churn prediction in telecom sector using machine learning techniques. *Results in Control and Optimization*, 14, 100342. https://doi.org/10.1016/j.rico.2023.100342
8. **Sikri, A., Jameel, R., Idrees, S. M., & Kaur, H. (2024).** Enhancing customer retention in telecom industry with machine learning driven churn prediction. *Scientific Reports*, 14, 13097. https://doi.org/10.1038/s41598-024-63750-0
9. **Sagming, M., Heymann, R., & Visaya, M. V. (2024).** Using topological data analysis and machine learning to predict customer churn. *Journal of Big Data*, 11(1), 160. https://doi.org/10.1186/s40537-024-01020-6
10. **Poudel, S. S., Pokharel, S., & Timilsina, M. (2024).** Explaining customer churn prediction in telecom industry using tabular machine learning models. *Machine Learning with Applications*, 17, 100567. https://doi.org/10.1016/j.mlwa.2024.100567

#### **C. Petunjuk Simpan ke Zotero / Mendeley:**
Seluruh 10 artikel ilmiah di atas telah diekspor dan diverifikasi metadatanya dalam berkas BibTeX resmi `docs/references.bib`. Berkas ini dapat langsung di-import ke Zotero/Mendeley melalui menu *File > Import > references.bib*.

---

## **Soal 3 (Praktik)**
> **Soal:** Susun tabel penelitian terdahulu dari 5 artikel yang dikumpulkan pada soal 2 dengan kolom dataset-algoritma-metrik-hasil-celah, lalu rumuskan satu celah penelitian yang spesifik.

### **Jawaban:**

#### **A. Tabel Penelitian Terdahulu (State of the Art Table):**

| Peneliti (Tahun) | Dataset | Algoritma / Metode | Metrik Evaluasi | Hasil Utama | Celah Penelitian (*Research Gap*) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Sana et al. (2022)** | 4 dataset telekomunikasi publik (termasuk IBM Telco 7.043 data) | XGBoost, Random Forest, LightGBM + Data Transformation & Feature Selection | Accuracy, Precision, Recall, F1-Score, ROC-AUC | Penerapan data transformation dan feature selection meningkatkan performa prediksi churn pada dataset telekomunikasi yang diuji. | Berfokus pada optimasi metode transformasi data dan efisiensi seleksi fitur klasifikasi. |
| **Geiler et al. (2022)** | 13 dataset churn publik (termasuk domain telekomunikasi) | 8 Supervised ML + 7 Strategi Sampling | AUC-ROC, Nemenyi Test | Performa model dipengaruhi oleh karakteristik dataset dan strategi sampling yang digunakan. | Berfokus pada evaluasi komparatif metrik klasifikasi dan teknik resampling lintas dataset. |
| **Prabadevi et al. (2023)** | Data pelanggan telekomunikasi (9 bulan) | Stochastic Gradient Boosting, Random Forest, Logistic Regression, KNN | Accuracy, F1-Score | Stochastic Gradient Boosting meraih akurasi tertinggi sebesar 83,9%. | Fokus utama penelitian adalah menentukan algoritma yang memberikan performa klasifikasi terbaik. |
| **Sagming et al. (2024)** | Orange/KDD Cup 2009 dataset (50.000 pelanggan) | SVM, KNN, XGBoost + Topological Data Analysis (TDA) | Accuracy, Precision, Recall, F-measure | Ekstraksi fitur geometric TDA + XGBoost meningkatkan akurasi dari 92,71% menjadi 98,50%. | Fokus utama penelitian adalah peningkatan performa prediksi melalui integrasi TDA dan machine learning. |
| **Poudel et al. (2024)** | IBM Telco Customer Churn (7.043 baris) | Gradient Boosting Machine (GBM), Random Forest, SHAP values | Accuracy, Precision, Recall, F1-Score, SHAP values | GBM meraih akurasi 81%; SHAP menjelaskan kontribusi fitur `Contract` dan `tenure` terhadap keputusan churn. | Fokus penelitian berada pada explainability model dan faktor fitur yang berkontribusi terhadap prediksi churn. |

#### **B. Perumusan Celah Penelitian (*Focus Gap*) Spesifik & Teruji:**
> **Rumusan Celah Penelitian:**  
> *"Penelitian customer churn pada domain telekomunikasi (seperti Sana et al., 2022; Geiler et al., 2022; Prabadevi et al., 2023; Sagming et al., 2024; Poudel et al., 2024) sebagian besar berorientasi pada pembangunan dan evaluasi model prediksi pada tingkat pelanggan menggunakan metrik klasifikasi. **Oleh karena itu, masih terdapat ruang untuk memperdalam analisis hubungan antara karakteristik pelanggan dan layanan, seperti masa berlangganan (tenure), jenis kontrak, biaya bulanan, serta fitur layanan tambahan, dengan kecenderungan churn sebagai dasar pembentukan insight retensi yang lebih spesifik pada domain telekomunikasi.**"*

---

## **Soal 4**
> **Soal:** Jelaskan tiga saringan kelayakan ide penelitian berbasis data dan berikan contoh gagasan yang gagal pada masing-masing saringan.

### **Jawaban:**

1. **Saringan Ketersediaan dan Kualitas Data (*Data Availability & Quality*):**
   * **Penjelasan:** Data harus tersedia, legal untuk diakses, dan memiliki atribut/fitur yang relevan serta berkualitas untuk menjawab pertanyaan penelitian.
   * **Contoh Gagal:** Memprediksi tingkat churn nasabah rahasia bank swasta nasional secara *real-time* tanpa akses API legal atau tanpa izin penggunaan data internal bank.
2. **Saringan Kebermaknaan dan Keterukuran Masalah (*Meaningfulness & Measurability*):**
   * **Penjelasan:** Masalah harus memiliki nilai guna praktis/akademik yang nyata dan variabel pendukungnya dapat diukur secara kuantitatif (*measurable*).
   * **Contoh Gagal:** Meneliti apakah warna avatar profil pelanggan mempengaruhi keputusan berhenti berlangganan internet tanpa adanya landasan teoritis atau variabel terukur yang relevan.
3. **Saringan Kelayakan Teknis dan Sumber Daya (*Technical Feasibility*):**
   * **Penjelasan:** Skala data, kompleksitas algoritma, dan alokasi waktu komputasi harus realistis untuk diselesaikan dengan sumber daya perangkat komputasi dan rentang waktu yang tersedia (seperti 1 semester skripsi).
   * **Contoh Gagal:** Melatih model LLM (*Large Language Model*) dari nol untuk membaca seluruh log percakapan suara pelanggan berukuran 100 Terabyte menggunakan laptop standar dalam waktu 3 bulan.

---

## **Soal 5**
> **Soal:** Mengapa dataset UCI/Kaggle sering dipilih untuk skripsi yang membandingkan algoritma? Jelaskan dengan konsep perbandingan hasil antar penelitian.

### **Jawaban:**

Dataset publik yang populer dan sering digunakan dalam penelitian (seperti *Telco Customer Churn*) sering dipilih untuk skripsi perbandingan algoritma karena:

1. **Standar Penilaian Bersama (*Standardized Benchmark*):**  
   Dataset ini digunakan secara luas dalam publikasi ilmiah internasional, sehingga dapat berfungsi sebagai tolak ukur standar (*baseline benchmark*).
2. **Perbandingan yang Adil (*Fair Comparison*):**  
   Dengan menggunakan dataset yang sama (seperti 7.043 baris dan 21 fitur), pengaruh variasi karakteristik data dasar dapat dikurangi, sehingga perbedaan performa antaralgoritma dapat dibandingkan secara lebih fair dan konsisten, selama prosedur preprocessing, pembagian data, dan evaluasi dibuat sebanding.
3. **Replikasi Penelitian (*Reproducibility*):**  
   Memungkinkan penguji skripsi dan peneliti lain memverifikasi serta mereplikasi ulang eksperimen secara transparan.

---

## **Soal 6 (Studi Kasus)**
> **Soal:** AI memberi Anda lima referensi; tiga ditemukan persis di Google Scholar, satu ditemukan tetapi isi artikelnya berbeda dari klaim AI, dan satu tidak pernah ditemukan. Bagaimana perlakuan Anda terhadap masing-masing, dan apa yang Anda laporkan tentang penggunaan AI tersebut?

### **Jawaban:**

1. **3 Referensi Ditemukan Persis:** Verifikasi identitas (DOI/Jurnal), baca abstrak & metode untuk memastikan klaim AI sesuai isi artikel. Jika cocok, simpan ke Zotero/Mendeley dan gunakan sebagai rujukan resmi.
2. **1 Referensi Ditemukan Tetapi Isinya Berbeda:** **Jangan gunakan klaim fiktif buatan AI.** Gunakan isi asli artikel jika relevan dan revisi narasinya, atau buang jika tidak relevan.
3. **1 Referensi Tidak Ditemukan (Halusinasi AI):** **Buang total referensi tersebut.** Jangan mengarang DOI atau metadata fiktif.
4. **Pelaporan Penggunaan AI:** Melaporkan secara transparan bahwa AI digunakan pada tahap awal pencarian literatur/brainstorming, namun seluruh referensi telah diverifikasi secara independen ke sumber primer (Google Scholar, DOI, jurnal asli) untuk menjamin integritas akademik.
