# Brazilian E-Commerce Analysis

Dataset: Olist Public Dataset (Kaggle)

Proyek ini bertujuan untuk menganalisis kinerja penjualan, logistik, metode pembayaran, dan kepuasan pelanggan dari platform e-commerce terbesar di Brasil (Olist). Analisis ini melibatkan proses penggabungan 9 dataset relasional yang terpisah.

File utama dalam analisis ini adalah **Brazilian_Ecommerce_Analysis.ipynb** yang menyajikan visualisasi data komprehensif terkait operasional e-commerce.

## Hasil Analisis Utama

Berdasarkan pengolahan data, ditemukan beberapa wawasan bisnis yang signifikan:

1. **Distribusi Pemesanan (Geospasial)**
   Negara bagian São Paulo (SP) mendominasi jumlah pemesanan secara signifikan dibandingkan wilayah lain, menjadikannya pasar terbesar dan terpenting bagi Olist.

2. **Kinerja Pengiriman Logistik**
   Sebagian besar proses pengiriman memakan waktu antara 10 hingga 15 hari. Evaluasi ketepatan waktu menunjukkan hasil yang sangat memuaskan, di mana **92.2%** pesanan berhasil tiba tepat waktu atau bahkan mendahului estimasi jadwal.

3. **Preferensi Metode Pembayaran**
   Kartu kredit merupakan opsi pembayaran yang paling diminati oleh pelanggan Brasil dalam bertransaksi e-commerce, disusul oleh boleto (metode transfer atau pembayaran tunai lokal).

4. **Kepuasan Pelanggan**
   Mayoritas pelanggan merasa puas dan memberikan ulasan bintang 5. Terdapat korelasi langsung antara logistik dan kepuasan: pelanggan yang memberikan ulasan bintang 1 terbukti mengalami waktu tunggu pengiriman dua kali lebih lama dibandingkan pelanggan yang memberikan ulasan bintang 5.

## Langkah Menjalankan Proyek

1. Pastikan Anda memiliki Jupyter Notebook atau Jupyter Lab.
2. Buka file `Brazilian_Ecommerce_Analysis.ipynb`.
3. Seluruh dataset telah disatukan dalam direktori `data/`.
4. Jalankan seluruh sel secara berurutan untuk memuat data, melakukan pembersihan, dan menghasilkan grafik analisis.

## Keterampilan yang Ditunjukkan

* Data Wrangling dan Penggabungan Data Relasional (Operasi Join dengan Pandas)
* Feature Engineering (Ekstraksi tanggal, perhitungan metrik keterlambatan)
* Data Visualization (Matplotlib, Seaborn)
* Analisis Logistik dan Kinerja Pengiriman
* Analisis Kepuasan Pelanggan (Korelasi Waktu Pengiriman terhadap Ulasan)
