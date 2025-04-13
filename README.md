# Capstone02
# Analisis Pola Belanja Pelanggan Supermarket

![Dashboard Preview](https://via.placeholder.com/800x400?text=Dashboard+Preview)

## Daftar Isi
- [Tentang Proyek]
- [Struktur Repositori]
- [Dataset]
- [Pertanyaan Bisnis]
- [Metodologi]
- [Visualisasi]
- [Insight Utama]
- [Tools yang Digunakan]
- [Instalasi dan Penggunaan]
- [Kontribusi]
## Tentang Proyek
Proyek ini merupakan Capstone Project Modul 2 yang berfokus pada analisis pola belanja pelanggan supermarket. Tujuan utama proyek ini adalah untuk memahami perilaku belanja pelanggan berdasarkan kategori produk dan faktor demografi seperti usia, status pernikahan, dan tingkat pendidikan.

Sebagai data analyst, saya menganalisis dataset supermarket untuk mengidentifikasi pola belanja, preferensi produk, dan strategi pemasaran yang dapat meningkatkan penjualan dan tingkat kepuasan pelanggan.

## Struktur Repositori
```
├── data/
│   └── Data_Capstone_Modul_2_Supermarket_Customers.csv
├── notebooks/
│   └── Capstone_Modul_2_Analysis.ipynb
├── presentations/
│   └── Supermarket_Customer_Analysis.pptx
├── img/
│   └── dashboard_preview.png
├── README.md
└── requirements.txt
```

## Dataset
Dataset yang digunakan dalam proyek ini adalah data pelanggan supermarket dengan 2240 entri dan berbagai variabel seperti:
- Informasi demografis (Tahun Kelahiran, Pendidikan, Status Pernikahan, Pendapatan)
- Komposisi keluarga (Kidhome, Teenhome)
- Riwayat pembelian (MntWines, MntFruits, MntMeatProducts, dll.)
- Kanal pembelian (NumWebPurchases, NumCatalogPurchases, NumStorePurchases)
- Interaksi dengan kampanye pemasaran (AcceptedCmp1-5, Response)

## Pertanyaan Bisnis
Analisis ini bertujuan untuk menjawab pertanyaan-pertanyaan bisnis berikut:
1. Produk apa yang paling sering dibeli oleh pelanggan?
2. Apakah ada korelasi antara kategori produk yang dibeli bersama?
3. Bagaimana pola pengeluaran pelanggan berdasarkan tingkat pendapatan?
4. Apakah ada perbedaan pola belanja berdasarkan usia, tingkat pendidikan, dan status pernikahan?
5. Bagaimana frekuensi belanja di berbagai kanal (store, web, katalog) berhubungan dengan jenis produk yang dibeli?
6. Apakah pelanggan dengan anak (Kidhome/Teenhome > 0) memiliki pola belanja yang berbeda dibandingkan pelanggan tanpa anak?

## Metodologi
Proyek ini dilakukan dalam beberapa tahap:

### 1. Data Cleaning
- Penanganan missing values
- Deteksi dan penanganan outliers
- Standarisasi format data
- Penghapusan data duplikat

### 2. Exploratory Data Analysis (EDA)
- Analisis demografis pelanggan
- Analisis distribusi pengeluaran di berbagai kategori produk
- Analisis pola pembelian di berbagai kanal

### 3. Feature Engineering
Beberapa variabel turunan yang dibuat:
- `Total Spending` = Total pengeluaran semua kategori produk
- `Age` = Tahun saat ini - Year_Birth
- `Customer Tenure` = Lama menjadi pelanggan (dalam tahun)
- `% Spending` per kategori produk
- `Total Transactions` = Total pembelian di semua kanal

### 4. Analisis Statistik
- Statistik deskriptif untuk menggambarkan distribusi data
- Analisis korelasi untuk melihat hubungan antar variabel
- Uji statistik (t-test, ANOVA) untuk membandingkan kelompok pelanggan

### 5. Visualisasi Data
- Dashboard interaktif menggunakan Tableau Public
- Visualisasi menggunakan Python (Matplotlib, Seaborn)

## Visualisasi
Beberapa visualisasi utama yang dibuat:
1. **Bar Chart**: Perbandingan pengeluaran pelanggan dalam berbagai kategori produk
2. **Pie Chart**: Distribusi total pembelian berdasarkan kategori produk
3. **Line Chart**: Tren pengeluaran pelanggan dalam berbagai kategori produk sepanjang waktu
4. **Heatmap**: Korelasi antara berbagai kategori produk yang dibeli bersama
5. **Box Plot**: Distribusi pengeluaran per kategori produk berdasarkan tingkat pendapatan
6. **Stacked Bar Chart**: Perbandingan pola belanja berdasarkan status pernikahan dan tingkat pendidikan

## Insight Utama
1. **Preferensi Produk**: [Akan diisi setelah analisis lengkap]
2. **Segmentasi Pelanggan**: [Akan diisi setelah analisis lengkap]
3. **Pola Belanja berdasarkan Demografi**: [Akan diisi setelah analisis lengkap]
4. **Efektivitas Kanal Penjualan**: [Akan diisi setelah analisis lengkap]
5. **Rekomendasi Strategi Pemasaran**: [Akan diisi setelah analisis lengkap]

## Tools yang Digunakan
- **Python** dan libraries:
  - Pandas untuk manipulasi data
  - NumPy untuk operasi matematika
  - Matplotlib dan Seaborn untuk visualisasi dasar
  - Scikit-learn untuk analisis statistik
- **Tableau Public** untuk pembuatan dashboard interaktif
- **Jupyter Notebook** untuk dokumentasi kode dan analisis

## Instalasi dan Penggunaan
1. Clone repositori ini:
```bash
git clone https://github.com/[username]/analisis-pola-belanja-supermarket.git
cd analisis-pola-belanja-supermarket
```

2. Buat virtual environment dan install dependencies:
```bash
python -m venv venv
source venv/bin/activate  # Untuk Linux/Mac
venv\Scripts\activate  # Untuk Windows
pip install -r requirements.txt
```

3. Buka Jupyter Notebook:
```bash
jupyter notebook notebooks/Capstone_Modul_2_Analysis.ipynb
```

4. Link Dashboard Tableau Public:
[Dashboard Analisis Pola Belanja Pelanggan]([https://public.tableau.com/app/profile/yourusername/viz/AnalisisPolaBelanjaPelanggan/Dashboar](https://lookerstudio.google.com/u/0/reporting/7a0ad43f-203d-4d85-9b9e-2a3a5409a257/page/jViGF/edit)d)

## Kontribusi
Proyek ini merupakan bagian dari Capstone Project individu. Namun, saran dan masukan sangat diapresiasi!

---

Dibuat sebagai bagian dari Capstone Project Modul 2: Data Analysis.
