# Proyek Analisis Data: Brazilian E-Commerce Dashboard 📊

Proyek ini merupakan analisis mendalam terhadap dataset publik E-Commerce di Brasil. Fokus utama proyek ini adalah memahami performa kategori produk, preferensi pembayaran, dan segmentasi pelanggan menggunakan teknik **RFM (Recency, Frequency, & Monetary)**.

## 📋 Pertanyaan Bisnis

1. Kategori produk apa yang memberikan kontribusi pendapatan terbesar
   pada E-Commerce selama periode 2016–2018?
2. Metode pembayaran apa yang paling sering digunakan pelanggan dan
   memiliki nilai transaksi tertinggi selama periode 2016–2018?
3. Bagaimana segmentasi pelanggan E-Commerce berdasarkan Recency, Frequency,
   dan Monetary (RFM) selama periode 2016–2018, serta segmen pelanggan
   mana yang memberikan kontribusi pendapatan terbesar?

## 🛠️ Teknologi & Library

Proyek ini dikembangkan menggunakan **Python 3.9+** dengan beberapa library utama:

* **Pandas & Numpy**: Untuk manipulasi dan pembersihan data.
* **Matplotlib & Seaborn**: Untuk visualisasi data yang informatif dan estetis.
* **Streamlit**: Untuk membangun dashboard interaktif.

## 📁 Struktur Direktori

```text
.
├── dashboard/
│   ├── main_data.csv       # Dataset yang telah dibersihkan untuk dashboard
│   └── dashboard.py        # File utama aplikasi Streamlit
├── data/                   # Dataset mentah (CSV) dan terpisah
├── notebook.ipynb          # File Jupyter Notebook (Proses Analisis Lengkap)
├── README.md               # Dokumentasi proyek
├── requirements.txt        # Daftar library yang dibutuhkan
└── url.txt                 # Tautan dashboard

```

## 🚀 Cara Menjalankan Proyek

### 1. Persiapan Lingkungan

Pastikan kamu sudah menginstal Python. Disarankan menggunakan *virtual environment*:

```bash
python -m venv venv
source venv/bin/activate  # Untuk Linux/Mac
.\venv\Scripts\activate   # Untuk Windows

```

### 2. Instalasi Library

```bash
pip install -r requirements.txt

```

### 3. Menjalankan Dashboard

```bash
streamlit run "path"

```
Keterangan : ganti bagian path dengan path file dasboard.py di komputer kamu