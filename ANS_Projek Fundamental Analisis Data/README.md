# Proyek Analisis Data: Brazilian E-Commerce Dashboard 📊

Proyek ini merupakan analisis mendalam terhadap dataset publik E-Commerce di Brasil. Fokus utama proyek ini adalah memahami performa kategori produk, preferensi pembayaran, dan segmentasi pelanggan menggunakan teknik **RFM (Recency, Frequency, & Monetary)**.

## 📋 Pertanyaan Bisnis

1. Kategori produk mana yang memberikan kontribusi pendapatan terbesar selama periode 2016–2018?
2. Apa metode pembayaran yang paling populer dan memiliki nilai transaksi tertinggi?
3. Bagaimana segmentasi pelanggan berdasarkan analisis RFM dan segmen mana yang paling bernilai bagi bisnis?

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
├── data/                   # Dataset mentah (CSV)
├── notebook.ipynb          # File Jupyter Notebook (Proses Analisis Lengkap)
├── README.md               # Dokumentasi proyek
├── requirements.txt        # Daftar library yang dibutuhkan
└── url.txt                 # Tautan dashboard (jika sudah dideploy)

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
streamlit run dashboard/dashboard.py

```

## 💡 Ringkasan Analisis (Insights)

* **Kategori Produk:** Kategori **Health & Beauty** memimpin pendapatan tertinggi, menunjukkan pergeseran tren belanja ke arah produk perawatan diri.
* **Metode Pembayaran:** **Credit Card** adalah metode yang paling dominan, mencerminkan kebutuhan pelanggan akan kemudahan transaksi dan fitur cicilan.
* **Segmentasi Pelanggan:** Meskipun banyak pelanggan masuk kategori *Lost*, segmen **At Risk** menyumbang pendapatan yang signifikan (26.41%), memberikan peluang besar untuk strategi *win-back*.

---