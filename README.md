# Amazon Sales Report Analysis

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-brightgreen)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)

## Deskripsi Project
Project ini adalah analisis data komprehensif dari dataset **Amazon Sales Report** yang berisi lebih dari 128.900 baris data transaksi e-commerce. Tujuan utama analisis ini adalah untuk mengekstrak *valuable insights* guna meningkatkan efisiensi operasional, mengoptimalkan proses penjualan, dan memaksimalkan *customer satisfaction* di platform Amazon.

## 🎯 Objektif Analisis
Analisis ini dirancang untuk menjawab beberapa pertanyaan krusial dalam bisnis e-commerce:
1. **Sales Distribution**: Kategori produk apa yang memiliki performa tertinggi?
2. **Size vs Quantity**: Bagaimana korelasi antara ukuran produk dengan jumlah yang terjual?
3. **Courier Impact**: Sejauh mana layanan kurir memengaruhi status pengiriman dan proses penjualan secara keseluruhan?
4. **Order Status Relationship**: Bagaimana hubungan antara status pengiriman dengan keberhasilan penjualan?
5. **Geographical Insights**: Bagaimana variasi penjualan di berbagai kota dan negara bagian (state) yang bisa digunakan untuk penargetan marketing?
6. **B2B vs B2C**: Seberapa besar proporsi pendapatan yang dihasilkan dari transaksi antar bisnis (B2B) dibandingkan konsumen biasa (B2C)?

## 📊 Hasil dan Temuan Utama
- **Kategori Dominan**: Produk `Set` dan `kurta` menyumbang porsi terbesar (sekitar 78%) dari total pesanan.
- **Ukuran Terpopuler**: Ukuran **M** memimpin dengan jumlah pesanan terbanyak, diikuti erat oleh L dan XL.
- **Top Shipping Locations**: Negara bagian **Maharashtra** dan **Karnataka**, dengan kota teratas **Bengaluru**, **Hyderabad**, dan **Mumbai** merupakan pasar paling menguntungkan.
- **B2B Analytics**: Meskipun pelanggan B2B hanya menyumbang sekitar 0.68% dari total transaksi, rata-rata *order amount* mereka (INR 698.23) secara signifikan lebih tinggi daripada pembeli B2C (INR 645.57).
- **Fulfilment**: Pengiriman menggunakan layanan pemenuhan (fulfilment) dari Amazon menguasai hampir 70% pesanan dibandingkan Merchant secara langsung.

## 🛠️ Tech Stack
- **Python** - Bahasa pemrograman utama
- **Pandas & NumPy** - Pembersihan dan manipulasi data
- **Matplotlib & Seaborn** - Visualisasi data profesional
- **Jupyter Notebook** - Lingkungan analisis interaktif

## 📂 Struktur Repositori
- `Amazon_Sales_Analysis.ipynb`: File Jupyter Notebook utama yang berisi seluruh kode analisis dan grafik visualisasi.
- `data/`: Folder yang memuat dataset asli `Amazon Sale Report.csv` (harus diunduh secara terpisah dari Kaggle).

## 🚀 Cara Menjalankan
1. Clone repositori ini.
2. Unduh dataset dari [Kaggle](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data).
3. Ekstrak file CSV ke dalam folder `data/` dengan nama `Amazon Sale Report.csv`.
4. Jalankan notebook `Amazon_Sales_Analysis.ipynb` dari Jupyter Lab atau Jupyter Notebook.
