# 🚜 Dashboard Analisis Penjualan Alat Berat B2B

Proyek ini merupakan implementasi **End-to-End Data Analytics** yang menganalisis data penjualan alat berat B2B mulai dari proses pembersihan data, pembangunan Data Warehouse sederhana, pembuatan Key Performance Indicator (KPI) menggunakan SQL, hingga visualisasi interaktif menggunakan Tableau.

Tujuan utama proyek ini adalah mengubah data transaksi mentah menjadi informasi yang dapat membantu perusahaan dalam mengevaluasi performa penjualan, pertumbuhan pendapatan, serta pengambilan keputusan bisnis.

---

# 🎯 Tujuan Proyek

Proyek ini bertujuan untuk:

- Melakukan pembersihan dan transformasi data menggunakan Python.
- Membangun Data Warehouse sederhana dengan konsep Star Schema.
- Menghitung KPI bisnis menggunakan SQL.
- Membuat dashboard interaktif menggunakan Tableau.
- Menghasilkan insight bisnis dari data penjualan alat berat.
- Menunjukkan proses lengkap (End-to-End) dalam Data Analytics.

---

# 📂 Dataset

Dataset yang digunakan merupakan data transaksi penjualan alat berat B2B.

Dataset mencakup beberapa informasi penting, antara lain:

- Tanggal Transaksi
- Nama Pelanggan
- Produk
- Kategori Produk
- Jumlah Pembelian
- Harga Satuan
- Nilai Deal
- Revenue
- Status Transaksi
- Sales Representative
- Wilayah Penjualan

Sebelum dilakukan analisis, data dibersihkan dan diproses menggunakan Python agar siap dimuat ke dalam Data Warehouse.

---

# ⚙️ Alur Pengerjaan Proyek

```text
Data Mentah
      │
      ▼
Data Cleaning & Preprocessing (Python)
      │
      ▼
Feature Engineering
      │
      ▼
Data Warehouse (SQL Server)
      │
      ▼
Perhitungan KPI (SQL)
      │
      ▼
Dashboard Tableau
      │
      ▼
Business Insight
```

---

# 🛠️ Tools yang Digunakan

| Tools | Kegunaan |
|--------|----------|
| Python | Data Cleaning & Transformasi |
| Pandas | Pengolahan Data |
| Jupyter Notebook | Proses Analisis Data |
| SQL Server | Data Warehouse |
| SQL | Perhitungan KPI |
| Tableau | Dashboard & Visualisasi |
| GitHub | Dokumentasi Portfolio |

---

# 📁 Struktur Repository

```text
heavy-equipment-sales-analysis/
│
├── data/
│
├── notebooks/
│   └── 01_data_cleaning.ipynb
│
├── tableau/
│   └── Heavy_Equipment_Sales_Dashboard.twbx
│
├── docs/
│   └── KPI.pdf
│
├── images/
│   ├── dashboard.png
│   └── star_schema.png
│
└── README.md
```

---

# 🏗️ Data Warehouse

Pada proyek ini digunakan Data Warehouse sederhana dengan pendekatan **Star Schema**.

### Tabel Dimensi

- Dim Customer
- Dim Product
- Dim Sales
- Dim Time

### Tabel Fakta

- Fact Sales

Struktur ini memudahkan proses analisis dan meningkatkan performa query pada dashboard.

---

# 📊 Key Performance Indicator (KPI)

Dashboard menampilkan beberapa KPI utama, yaitu:

### 📌 Total Volume Penjualan

Menampilkan jumlah total unit produk yang berhasil terjual selama periode analisis.

---

### 📌 Rata-rata Nilai Deal

Mengukur rata-rata nilai transaksi dari seluruh penawaran yang masuk.

---

### 📌 Total Pendapatan Riil

Menampilkan total revenue dari transaksi yang berhasil diselesaikan.

---

### 📌 Pertumbuhan Revenue Bulanan

Mengukur pertumbuhan revenue dari bulan ke bulan (Month over Month Growth).

---

### 📌 Nilai Deal Tertinggi

Menampilkan transaksi dengan nilai terbesar selama periode analisis.

---

### 📌 Nilai Deal Terendah

Menampilkan transaksi valid dengan nilai terkecil setelah data dibersihkan.

---

# 📈 Dashboard Tableau

Dashboard dibuat menggunakan Tableau agar pengguna dapat menganalisis data secara interaktif.

Fitur dashboard meliputi:

- KPI Cards
- Tren Revenue Bulanan
- Analisis Penjualan
- Analisis Status Transaksi
- Analisis Kategori Produk
- Analisis Wilayah Penjualan
- Analisis Pelanggan
- Filter Interaktif

---

# 💡 Insight Bisnis

Beberapa insight yang dapat diperoleh dari dashboard ini antara lain:

- Tren pertumbuhan revenue perusahaan dari waktu ke waktu.
- Produk dengan performa penjualan terbaik.
- Distribusi nilai transaksi.
- Kontribusi revenue berdasarkan status transaksi.
- Performa penjualan berdasarkan wilayah.
- Identifikasi transaksi dengan nilai tertinggi.
- Analisis perilaku pelanggan dalam melakukan pembelian.

---

# 🚀 Skill yang Ditunjukkan

Melalui proyek ini saya mempraktikkan beberapa kemampuan, antara lain:

- Data Cleaning
- Data Transformation
- Feature Engineering
- SQL Query
- Data Warehouse
- ETL
- Business Intelligence
- Tableau Dashboard
- Data Visualization
- Business Analytics

---

# 📚 Pembelajaran yang Diperoleh

Melalui proyek ini saya memperoleh pengalaman dalam membangun proses analisis data secara menyeluruh, mulai dari pengolahan data mentah, pembangunan Data Warehouse, perhitungan KPI menggunakan SQL, hingga penyajian dashboard interaktif menggunakan Tableau.

---

# 🔮 Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan pada proyek ini antara lain:

- Otomatisasi proses ETL.
- Integrasi Tableau dengan SQL Server.
- Pembuatan model prediksi penjualan.
- Integrasi data secara real-time.
- Analisis segmentasi pelanggan.
- Dashboard monitoring performa penjualan secara berkala.

---

# 📷 Tampilan Dashboard

Silakan tambahkan screenshot berikut ke folder **images**:

- `dashboard.png`
- `workflow.png`
- `star_schema.png`

---

# 👨‍💻 Tentang Saya

**Armanta Tarigan**

Lulusan Sistem Informasi yang memiliki ketertarikan pada bidang **Data Analyst**, **Business Intelligence**, dan **Data Visualization**.

### Keahlian

- Python
- SQL
- SQL Server
- Tableau
- Data Warehouse
- ETL
- Data Visualization
- Business Intelligence

---

# ⭐ Dukungan

Apabila repository ini bermanfaat, jangan lupa memberikan ⭐ pada repository ini.

Terima kasih telah mengunjungi portfolio saya.
