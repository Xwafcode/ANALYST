# Amazon Sales Report Analysis

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-brightgreen)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)

## Tentang Proyek Ini
Pada proyek ini, saya menyusun analisis data yang komprehensif menggunakan dataset Amazon Sales Report. Dataset yang digunakan cukup besar, mencakup lebih dari 128.000 baris data transaksi e-commerce. Tujuan utama dari proyek ini adalah untuk menemukan berbagai wawasan penting yang dapat dimanfaatkan untuk meningkatkan efisiensi operasional, melancarkan proses penjualan, serta meningkatkan kepuasan pelanggan di platform Amazon.

## Tujuan Analisis
Proyek ini disusun untuk menjawab beberapa pertanyaan penting dalam bisnis e-commerce, yaitu:
1. **Distribusi Penjualan**: Kategori produk apa yang memiliki performa penjualan tertinggi?
2. **Ukuran dan Kuantitas**: Bagaimana korelasi antara ukuran produk dengan jumlah barang yang terjual?
3. **Dampak Layanan Kurir**: Sejauh mana layanan kurir memengaruhi status pengiriman dan keseluruhan proses penjualan?
4. **Hubungan Status Pesanan**: Bagaimana kaitan antara status pengiriman produk dengan keberhasilan suatu penjualan?
5. **Wawasan Geografis**: Bagaimana variasi penjualan di berbagai kota dan negara bagian untuk keperluan target pemasaran?
6. **B2B dan B2C**: Seberapa besar perbandingan pendapatan dari transaksi pelanggan bisnis (B2B) dengan konsumen reguler (B2C)?

## Hasil dan Temuan Utama
* **Kategori Dominan**: Produk Set dan kurta merupakan produk yang paling banyak dibeli, menyumbang sekitar 78 persen dari total pesanan keseluruhan.
* **Ukuran Terpopuler**: Ukuran M menduduki peringkat pertama dengan pesanan terbanyak, yang kemudian disusul oleh ukuran L dan XL.
* **Lokasi Pengiriman Utama**: Negara bagian Maharashtra dan Karnataka merupakan tujuan pengiriman terbanyak. Kota Bengaluru, Hyderabad, dan Mumbai menjadi pasar yang paling potensial dan menguntungkan.
* **Fakta B2B**: Walaupun pelanggan dari sektor bisnis (B2B) hanya mencakup sekitar 0.68 persen dari total transaksi, rata-rata nominal pesanan mereka (INR 698.23) jauh lebih tinggi dibandingkan pembeli reguler (INR 645.57).
* **Metode Pemenuhan**: Sekitar 70 persen pesanan dikirim menggunakan layanan dari Amazon secara langsung, mengungguli pengiriman oleh penjual (merchant).

## Teknologi yang Digunakan
* **Python**: Sebagai bahasa pemrograman utama dalam analisis.
* **Pandas & NumPy**: Digunakan untuk membersihkan dan memanipulasi data agar rapi.
* **Matplotlib & Seaborn**: Dimanfaatkan untuk merancang visualisasi data dan grafik yang profesional.
* **Jupyter Notebook**: Berperan sebagai lingkungan penulisan kode dan analisis yang interaktif.

## Struktur Repositori
* `Amazon_Sales_Analysis.ipynb`: File utama Jupyter Notebook yang memuat seluruh kode analisis beserta visualisasi grafiknya.
* `data/`: Folder yang menyimpan dataset asli `Amazon Sale Report.csv` yang dianalisis dalam proyek ini.

## Panduan Menjalankan Kode
1. Lakukan clone pada repositori ini ke komputer Anda.
2. Buka file `Amazon_Sales_Analysis.ipynb` menggunakan Jupyter Lab atau Jupyter Notebook.
3. Jalankan seluruh sel untuk melihat proses dan hasil analisis secara lengkap.
