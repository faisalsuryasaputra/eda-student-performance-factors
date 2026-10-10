# 🚀 Exploratory Data Analysis (EDA) & Predictive Insights: Student Performance Factors

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-3776AB.svg)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

Repositori ini berisi dokumentasi lengkap dan kode sumber untuk **Exploratory Data Analysis (EDA)** mendalam guna mengidentifikasi faktor-faktor utama yang memengaruhi kinerja akademik siswa (skor ujian). Proyek ini disusun sebagai bagian dari pemenuhan tugas **Sub-CLO-12-1-1 — Visualisasi Data**.

---

## 👤 Identitas Pengembang
* **Nama:** Faisal Surya Saputra
* **NIM:** 103012330152
* **Mata Kuliah / Tugas:** Visualisasi Data / Sub-CLO-12-1-1

---

## 📌 Daftar Isi
1. [Tentang Proyek](#-tentang-proyek)
2. [Dataset & Sumber Data](#-dataset--sumber-data)
3. [Struktur Repositori](#-struktur-repositori)
4. [Alur Pengerjaan (Workflow)](#-alur-pengerjaan-workflow)
5. [Ringkasan Temuan & Key Insights](#-ringkasan-temuan--key-insights)
6. [Instalasi & Cara Menjalankan](#-instalasi--cara-menjalankan)
7. [Pustaka & Referensi](#-pustaka--referensi)

---

## 📖 Tentang Proyek
Keberhasilan akademik siswa tidak ditentukan oleh satu faktor tunggal saja, melainkan gabungan dari kebiasaan belajar, lingkungan sosial, kehadiran, fasilitas belajar, hingga kondisi psikologis/fisik. Proyek ini bertujuan untuk:
* Menggali pola tersembunyi (*hidden patterns*) dari data performa siswa.
* Melakukan visualisasi data univariat, bivariat, dan multivariat secara komprehensif.
* Menerapkan teknik reduksi dimensi untuk melihat kontribusi variabel utama.
* Memberikan rekomendasi berbasis data (*data-driven recommendations*) bagi institusi pendidikan atau pengajar.

---

## 📊 Dataset & Sumber Data
* **Sumber Asli:** Kaggle — *Student Performance Factors* oleh Lai Nguyen.
* **Jumlah Data:** Memuat lebih dari 6.000 baris data unik dan 20 kolom atribut.
* **Fitur Utama (Contoh):**
  * `Hours_Studied`: Rata-rata jam belajar mandiri per minggu.
  * `Attendance`: Persentase tingkat kehadiran siswa di kelas.
  * `Sleep_Hours`: Rata-rata jam tidur harian.
  * `Tutoring_Sessions`: Jumlah sesi les tambahan yang diikuti per bulan.
  * `Parental_Involvement`: Tingkat keterlibatan orang tua dalam pendidikan anak (Low, Medium, High).
  * `Access_to_Resources`: Ketersediaan fasilitas belajar (Library, Internet, Buku, dll.).
  * **`Exam_Score` (Target):** Nilai ujian akhir siswa.

---

## 📁 Struktur Repositori
```text
├── dataset/                  # Berisi file dataset (.csv) - opsional/terhubung via API
├── notebooks/                # File Jupyter Notebook utama (.ipynb)
├── images/                   # Grafik dan visualisasi hasil ekspor EDA
├── README.md                 # Dokumentasi proyek
└── requirements.txt          # Daftar pustaka Python yang digunakan
