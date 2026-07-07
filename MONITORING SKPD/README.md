# Monitoring Program dan Anggaran SKPD

Project ini merupakan simulasi dan analisis terhadap data perencanaan dan penganggaran Satuan Kerja Perangkat Daerah (SKPD). Dikarenakan data spesifik SKPD seringkali bersifat internal, project ini menggunakan dataset dummy realistis yang menyerupai nomenklatur, struktur program, dan standar harga pemerintah daerah di Indonesia.

##  Deskripsi Project
Dashboard dan notebook ini bertujuan memberikan gambaran komprehensif tentang:
- Total unit SKPD, program, kegiatan, dan jenis barang/jasa.
- Top 5 SKPD dengan alokasi anggaran terbesar.
- Distribusi anggaran berdasarkan sumber dana (DAU, PAD, Dana Desa, dll).
- Kategori harga barang pengadaan dari yang termurah hingga termahal.
- Sebaran anggaran berdasarkan Urusan Pemerintahan.

##  Struktur File
- `monitoring_skpd.ipynb`: Jupyter Notebook utama yang memuat Exploratory Data Analysis (EDA) dan visualisasi KPI.
- `generate_dataset.py`: Script Python untuk melakukan *generate* dataset dummy `data_skpd.csv` sebanyak 3.727 baris dan 58 kolom.
- `data_skpd.csv`: Dataset hasil *generate* yang digunakan dalam analisis (dihasilkan melalui script di atas).

##  Insight Utama
1. **Dominasi Anggaran**: Sekretariat Daerah sering kali menjadi top SKPD dalam alokasi anggaran.
2. **Ketergantungan Transfer Pusat**: Sebagian besar pendanaan masih didominasi oleh Dana Alokasi Umum (DAU) dibandingkan dengan Pendapatan Asli Daerah (PAD).
3. **Volume vs Harga Satuan**: Sebagian besar item belanja berada pada kategori harga satuan menengah ke bawah, namun sejumlah kecil item dengan harga di atas Rp100.000 berpotensi memberikan kontribusi besar pada total anggaran.

##  Cara Menjalankan
1. Pastikan library `pandas`, `numpy`, `matplotlib`, dan `seaborn` telah ter-install.
2. (*Opsional*) Jalankan `python generate_dataset.py` jika kamu ingin men-generate ulang dataset dengan _seed_ yang berbeda.
3. Buka dan jalankan `monitoring_skpd.ipynb` menggunakan Jupyter Notebook atau VS Code.

---
*Dibuat untuk keperluan simulasi analisis data penganggaran publik.*
