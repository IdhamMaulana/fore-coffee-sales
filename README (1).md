# ☕ Fore-Coffee Sales Analysis: Power BI Interactive Dashboard
Data Modeling, DAX Calculations, and Interactive Business Dashboard

## 🧭 Business Context
Sebuah jaringan kedai kopi membutuhkan sistem pemantauan yang komprehensif untuk mengevaluasi kinerja penjualan di berbagai lokasi. Pemilik bisnis ingin memahami pola pembelian pelanggan, mengidentifikasi produk terlaris, dan melihat fluktuasi transaksi berdasarkan hari serta jam operasional untuk mengoptimalkan ketersediaan produk dan jadwal operasional.

📊 Dashboard : Sales Analytics
Berfokus pada visualisasi performa penjualan, metrik pertumbuhan, dan perilaku transaksi pelanggan.

Project ini berfokus pada pengembangan dashboard analitik end-to-end menggunakan Power BI:
- Total sales, total orders, & total quantity sold
- Month-on-Month (MoM) growth metrics
- Calendar heat map untuk intensitas transaksi harian
- Sales trends (Average line dinamis & komparasi Weekday vs Weekend)
- Sales by days and hours (peta jam sibuk)
- Sales by store location
- Top 10 products & performa berdasarkan kategori

## 🎯 Project Objective
Project ini bertujuan untuk:
1. Melakukan pembersihan dan transformasi data secara efisien menggunakan Power Query.
2. Membangun model data (Data Modeling) yang solid dengan mendefinisikan relasi antar tabel (Fact & Dimension).
3. Menggunakan formula DAX (Data Analysis Expressions) tingkat lanjut untuk menghitung KPI utama dan metrik time-intelligence.
4. Menghasilkan visualisasi data interaktif dan intuitif untuk mendukung pengambilan keputusan bisnis.

## 📂 Data Overview
🔗 [Access Dataset](https://www.kaggle.com/datasets/jaspearson/pizzeria-data-for-4-weeks)

Dataset simulasi mencakup riwayat transaksi harian yang terdiri dari:

- Transaction Details: ID transaksi, tanggal, jam operasional, dan kuantitas pesanan.
- Product Information: Kategori produk, nama produk, dan harga satuan.
- Store Details: Lokasi cabang gerai kedai kopi.

Data telah melalui proses:
- Relational Mapping: Menentukan Primary Key dan Foreign Key antar tabel.

## 🔍 Analysis Approach
Pendekatan yang dilakukan dalam projek ini difokuskan pada alur kerja Business Intelligence:
- Data Preparation (Power Query): Membersihkan data mentah, mengubah tipe data, dan mengekstrak informasi waktu/hari dari kolom tanggal.
- Data Modeling: Menyusun skema relasional antar tabel untuk memastikan interaksi antar filter (cross-filtering) dan visualisasi berfungsi dengan akurat.
- DAX Calculations: Menulis measure kustom untuk menghitung performa bisnis, seperti pertumbuhan MoM, nilai rata-rata dinamis, dan kalkulasi logis lainnya.
- Data Visualization & UI/UX: Mendesain antarmuka visual interaktif, termasuk pembuatan calendar heat map kustom menggunakan matriks dan grafik time-series.

## 💼 Business Impact
Dengan adanya dashboard interaktif ini, manajemen kedai kopi dapat memantau kesehatan finansial secara visual dan dinamis. Wawasan mengenai jam-jam sibuk (peak hours) sangat membantu dalam optimalisasi penugasan staf. Selain itu, pemahaman tentang lokasi gerai dengan performa tertinggi dan tren produk terlaris memungkinkan manajemen untuk merancang strategi promosi dan inventaris stok yang lebih akurat.

## 📊 Dashboard
🔗 [View Interactive Dashboard](https://lookerstudio.google.com/reporting/7d1de712-b80c-46a6-aec2-6688fd871d65)

Hasil analisis divisualisasikan dalam dashboard interaktif menggunakan Power BI:

Sales Dashboard:

## 🧰 Tools & Technologies
- Power BI: Digunakan secara eksklusif untuk ETL (Power Query), Data Modeling, DAX, dan visualisasi dashboard.

## 📌 Note
Project ini merupakan dokumentasi portfolio data analyst yang berfokus pada penguasaan alat Business Intelligence (Power BI). Seluruh data yang digunakan bersifat simulasi untuk keperluan demonstrasi kemampuan visualisasi data dan perancangan dashboard analitik.
