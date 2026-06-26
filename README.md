# 🚴‍♂️ Bike Sharing Analytics Dashboard

> An interactive dashboard built with Python & Streamlit to explore bike rental patterns across weather, time, and seasonal dimensions.

🔗 **Live Demo**: [https://bike-sharing-analytict.streamlit.app/]

---

## 📌 Project Overview

Proyek ini menganalisis dataset **Bike Sharing** yang mencakup 731 hari data penyewaan sepeda (2011–2012) untuk menjawab dua pertanyaan bisnis utama:

1. **Bagaimana tren pertumbuhan pengguna sepeda berdasarkan bulan setiap tahunnya?**
2. **Bagaimana pengaruh musim terhadap volume pengguna sepeda?**

---

## 📊 Key Findings

### 📈 Tren Pertumbuhan Pengguna
- Penggunaan sepeda **meningkat signifikan di 2012 vs 2011**, dengan lonjakan paling tajam di bulan September 2012 (218.573 pengguna)
- Pola musiman konsisten: **naik dari Januari → puncak di pertengahan tahun → turun menjelang Desember**
- Pengguna terdaftar (*registered*) mendominasi — naik dari 995.851 (2011) ke 1.676.811 (2012)

### 🌤️ Pengaruh Musim
- **Musim Gugur (Fall)** mencatat pengguna tertinggi: 1.061.129
- **Musim Semi (Spring)** terendah: 471.348
- Suhu nyaman (atemp 0.3–0.6) mendorong penggunaan tertinggi; suhu ekstrem (sangat dingin/panas) menekan jumlah pengguna


## 📌 Overview
Dashboard ini dirancang untuk menganalisis pola penyewaan sepeda berdasarkan berbagai faktor seperti cuaca, waktu, dan musim. Dibangun dengan Python dan Streamlit, dashboard ini menawarkan visualisasi data yang interaktif dan informatif.

## 🚀 Getting Started
### 1. Prerequisites
Pastikan Python (versi 3.7 atau lebih baru) sudah terinstal di sistem.

### 2. Install Required Library
Jalankan perintah berikut untuk menginstal library yang diperlukan:
```sh
pip install streamlit pandas numpy matplotlib seaborn
```

### 3. Run the Dashboard
Gunakan perintah berikut untuk menjalankan dashboard:
```sh
streamlit run dashboard.py
```

### 4. Mengakses Dashboard
Setelah dijalankan, dashboard akan otomatis terbuka di browser default.

## Key Features
- **Data Visualization**: Menampilkan pola penyewaan sepeda berdasarkan berbagai faktor.
- **Time Analysis**: Tren penyewaan berdasarkan harian, jam, musim dan suhu.
- **Interactive Filters**: Memungkinkan eksplorasi data dengan filter dinamis.
- **Weather Impact**: Analisis pengaruh musim terhadap jumlah penyewaan.
- **Temperature Trends**: Analisis penyewaan berdasarkan suhu yang dirasakan.
- **Seasonal Trends**: Analisis penyewaan berdasarkan musim.
- **Hourly Trends**: Analisis penyewaan berdasarkan jam (hanya tersedia untuk dataset per jam).

## Struktur Projek
```
projek_submission
├───dashboard/
│   ├───dashboard.py             
│   ├───day_df.csv              
│   └───hour_df.csv 
├───data 
│   ├───day.csv             
│   └───hour.csv           
├───notebook.ipynb               
├───README.md                    
├───requirements.txt             
└───url.txt                      
```
