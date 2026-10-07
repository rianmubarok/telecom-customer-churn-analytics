# Telecom Customer Churn & Retention Analytics

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Dataset: Telco Churn](https://img.shields.io/badge/Dataset-Telco_Customer_Churn-orange.svg)](data/raw/Telco-Customer-Churn.csv)
[![License: Open Access Sample Data](https://img.shields.io/badge/License-IBM_Open_Access-green.svg)](https://www.kaggle.com/blastchar/telco-customer-churn)

**Mata Kuliah:** 24TIF505 – Metodologi Penelitian  
**Topik Penelitian:** Telecom Customer Churn & Retention Analytics  
**Program Studi:** Teknik Informatika, Fakultas Sains dan Teknologi, Universitas Islam Nahdlatul Ulama (UNISNU) Jepara  

---

## 1. Deskripsi Proyek

Proyek penelitian ini bertujuan untuk mengeksplorasi dan menganalisis risiko pelanggan berhenti berlangganan (*Customer Churn*) serta menerjemahkan luaran pemodelan *machine learning* menjadi rekomendasi strategi retensi pelanggan (*Customer Retention Analytics*) pada industri telekomunikasi menggunakan dataset **IBM Telco Customer Churn (7.043 sampel, 21 atribut)**.

Fokus utama penelitian meliputi:
- Identifikasi hubungan antara atribut demografi, jenis layanan berlangganan (seperti `tenure`, `TechSupport`, `OnlineSecurity`), dan aspek finansial (`Contract`, `MonthlyCharges`) terhadap probabilitas *churn*.
- Pemodelan klasifikasi kuantitatif dan evaluasi metrik performa (*Accuracy, Precision, Recall, F1-Score, ROC-AUC*).
- Analisis interpretabilitas dan penerjemahan luaran model ke dalam *actionable insights* untuk program retensi pelanggan.

---

## 2. Struktur Folder Proyek

```text
telecom-customer-churn-analytics/
├── data/
│   ├── raw/                  # Dataset mentah asli (Telco-Customer-Churn.csv)
│   └── processed/            # Dataset terstruktur CSV siap olah (telco_customer_churn.csv)
├── docs/                     # Dokumentasi tugas & penelitian
│   ├── TUGAS_BAB_3.md        # Laporan jawaban resmi Latihan Bab III (Audited & Verified)
│   ├── SOAL_BAB_3.md         # Naskah soal latihan Bab III
│   └── references.bib        # Koleksi 10 referensi BibTeX terverifikasi (2021–2026)
├── notebooks/                # Jupyter Notebooks untuk Exploratory Data Analysis & Pemodelan
├── src/                      # Source code Python modul pra-pemrosesan & evaluasi
├── .gitignore                # Berkas penyaring repositori Git
├── README.md                 # Dokumentasi utama proyek
└── tugas.md                  # Lembar checklist pengerjaan tugas
```

---

## 3. Panduan Memulai (Getting Started)

### 3.1 Prasyarat dan Instalasi
Pastikan Python versi 3.9 atau yang lebih baru telah terpasang pada sistem Anda. Pasang seluruh dependensi pustaka dengan menjalankan perintah berikut pada terminal:

```bash
pip install -r requirements.txt
```

### 3.2 Integrasi Manajemen Referensi (Zotero / Mendeley)
Koleksi 10 referensi ilmiah bereputasi (2021–2026) yang telah diaudit metadatanaya disediakan dalam format BibTeX pada berkas `docs/references.bib`.

Langkah impor ke Zotero / Mendeley:
1. Buka aplikasi **Zotero** atau **Mendeley Desktop**.
2. Pilih menu **File > Import...**
3. Pilih berkas `docs/references.bib`.

---

## 4. Spesifikasi Dataset

- **Nama Dataset:** IBM Telco Customer Churn (Tabel 3.1 Buku Ajar Metodologi Penelitian)
- **Sumber Data:** Kaggle / IBM Open Data Repository
- **Lisensi Data:** IBM Sample Data / Open Access (Data files © Original Authors)
- **Dimensi Data:** 7.043 sampel pelanggan, 21 atribut (demografi, jenis layanan, dan data finansial).
- **Variabel Target:** `Churn` (Biner: *Yes* / *No*).

