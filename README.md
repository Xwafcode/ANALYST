# Amazon Sales Report Analysis

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-brightgreen)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)

## Tentang Project Ini
Halo semuanya! Jadi di project ini gue bikin analisis data lengkap banget dari dataset Amazon Sales Report. Datanya lumayan gede nih, ada lebih dari 128 ribu baris transaksi e-commerce. Intinya sih project ini dibuat buat nyari tahu insight menarik yang bisa dipake buat ningkatin efisiensi operasional, bikin jualan makin lancar, dan pastinya bikin pelanggan Amazon makin puas.

## Tujuan Analisis
Project ini dibikin buat jawab beberapa pertanyaan penting di dunia jualan online:
1. **Sebaran Penjualan**: Kategori barang apa sih yang paling laku keras?
2. **Ukuran vs Jumlah**: Ada ngaruhnya ga sih ukuran baju sama jumlah yang kejual?
3. **Pengaruh Kurir**: Seberapa ngaruh kurir pengiriman ke suksesnya jualan kita?
4. **Status Pesanan**: Apa hubungannya status pengiriman sama jualan yang sukses?
5. **Geografis**: Kota atau daerah mana aja yang paling banyak belanjanya biar kita bisa atur strategi marketing yang pas?
6. **B2B vs B2C**: Banyakan mana duit yang masuk dari pelanggan kantoran (B2B) dibandingin pelanggan biasa (B2C)?

## Hasil Temuan
* **Kategori Paling Laku**: Baju Set sama Kurta itu paling banyak dibeli, nyumbang sekitar 78 persen dari total pesanan.
* **Ukuran Paling Dicari**: Ukuran M itu juaranya, terus diikutin ketat sama L dan XL.
* **Lokasi Pengiriman Terbanyak**: Daerah Maharashtra sama Karnataka jadi langganan banget, apalagi kota Bengaluru, Hyderabad, dan Mumbai. Ini pasar yang paling cuan.
* **Fakta B2B**: Walaupun pembeli kantoran (B2B) itu dikit banget cuma sekitar 0.68 persen dari total pesanan, tapi rata-rata mereka kalau belanja ngabisin duit lebih banyak (INR 698.23) dibanding pembeli biasa (INR 645.57).
* **Pengiriman**: Sekitar 70 persen pesanan dikirim langsung pake layanan Amazon dibandingin seller yang kirim sendiri.

## Tech Stack yang Dipake
* **Python**: Bahasa andalan buat ngodingnya.
* **Pandas & NumPy**: Buat bersihin dan ngolah datanya biar rapi.
* **Matplotlib & Seaborn**: Buat bikin grafik dan visualisasi yang kece.
* **Jupyter Notebook**: Tempat nulis kode dan liat hasilnya secara langsung.

## Isi Repositori Ini
* `Amazon_Sales_Analysis.ipynb`: File utama Jupyter Notebook yang isinya semua kode analisis dan grafik grafiknya.
* `data/`: Folder yang isinya dataset asli `Amazon Sale Report.csv` yang dipake di project ini.

## Cara Jalaninnya
1. Clone dulu repositori ini ke laptop lu.
2. Buka dan jalanin file `Amazon_Sales_Analysis.ipynb` pake Jupyter Lab atau Jupyter Notebook.
3. Tinggal run aja semua cell nya buat liat proses sama hasil analisisnya.
