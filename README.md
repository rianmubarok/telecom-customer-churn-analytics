# Telecom Customer Churn Prediction & Retention Analytics

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Dataset: Telco Churn](https://img.shields.io/badge/Dataset-Telco_Customer_Churn-orange.svg)](data/processed/telco_customer_churn.csv)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-green.svg)](https://opensource.org/licenses/Apache-2.0)

**Mata Kuliah:** 24TIF505 – Metodologi Penelitian  
**Topik Penelitian:** Optimasi Klasifikasi Prediksi Customer Churn Menggunakan Algoritma Random Forest dan XGBoost Berbasis Resampling SMOTE & Analisis Fitur SHAP  
**Program Studi:** Teknik Informatika, Fakultas Sains dan Teknologi, Universitas Islam Nahdlatul Ulama (UNISNU) Jepara  

---

## 1. Deskripsi Proyek

Proyek penelitian ini bertujuan untuk menguji dan membandingkan performa algoritma *machine learning* (Random Forest, XGBoost, Decision Tree, dan Logistic Regression) dalam memprediksi risiko pelanggan berhenti berlangganan (*Customer Churn*) pada industri telekomunikasi menggunakan dataset **IBM Telco Customer Churn (7.043 sampel, 21 atribut)**.

Fokus utama eksperimen meliputi:
- Penanganan ketidakseimbangan kelas (*class imbalance*) menggunakan teknik **SMOTE** (*Synthetic Minority Over-sampling Technique*).
- Evaluasi performa berbasis metrik kuantitatif (*Accuracy, Precision, Recall/Sensitivity, F1-Score, dan ROC-AUC*).
- Analisis interpretabilitas model menggunakan nilai **SHAP** (*SHapley Additive exPlanations*) untuk mendukung penyusunan strategi retensi pelanggan (*customer retention analytics*).

---

## 2. Struktur Folder Proyek

```text
telecom-customer-churn-prediction/
├── data/
│   ├── raw/                  # Dataset mentah asli (Telco-Customer-Churn.csv)
│   └── processed/            # Dataset terstruktur CSV siap olah (telco_customer_churn.csv)
├── docs/                     # Dokumentasi tugas & penelitian
│   ├── TUGAS_BAB_3.md        # Laporan jawaban resmi Latihan Bab III
│   ├── SOAL_BAB_3.md         # Naskah soal latihan Bab III
│   ├── p.md                  # Catatan acuan topik & metodologi penelitian
│   └── references.bib        # Koleksi 10 referensi BibTeX (Zotero/Mendeley)
├── notebooks/                # Jupyter Notebooks untuk Exploratory Data Analysis & Pemodelan
├── src/                      # Source code Python modul pra-pemrosesan & evaluasi
├── .gitignore                # Berkas penyaring repositori Git
├── README.md                 # Dokumentasi utama proyek
└── requirements.txt          # Daftar dependensi pustaka Python
```

---

## 3. Panduan Memulai (Getting Started)

### 3.1 Prasyarat dan Instalasi
Pastikan Python versi 3.9 atau yang lebih baru telah terpasang pada sistem Anda. Pasang seluruh dependensi pustaka dengan menjalankan perintah berikut pada terminal:

```bash
pip install -r requirements.txt
```

### 3.2 Integrasi Manajemen Referensi (Zotero / Mendeley)
Koleksi 10 referensi ilmiah bereputasi (2021–2026) telah disediakan dalam format BibTeX pada berkas `docs/references.bib`.

Langkah impor ke Zotero / Mendeley:
1. Buka aplikasi **Zotero** atau **Mendeley Desktop**.
2. Pilih menu **File > Import...**
3. Pilih berkas `docs/references.bib`.

---

## 4. Spesifikasi Dataset

- **Nama Dataset:** IBM Telco Customer Churn (Tabel 3.1 Buku Ajar Metodologi Penelitian)
- **Sumber Data:** Kaggle / IBM Open Data Repository
- **Lisensi:** Apache License 2.0 / Open Data
- **Dimensi Data:** 7.043 sampel pelanggan, 21 atribut (demografi, jenis layanan, dan data finansial).
- **Variabel Target:** `Churn` (Biner: *Yes* / *No*).
