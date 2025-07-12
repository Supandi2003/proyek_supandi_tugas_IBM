# Title Project
Data Classification and Summarization Using AI on eCommerce Dataset

---

## Project Overview
Proyek ini bertujuan untuk mengklasifikasikan data penjualan berdasarkan nilai penjualan (`sales`) serta membuat ringkasan otomatis menggunakan teknologi AI (model IBM Granite melalui Replicate API). 

Model AI digunakan untuk menyimpulkan insight dari data eCommerce berdasarkan kolom seperti `category`, `sku`, `sales`, dan `city`.

---

## Raw Dataset Link
Dataset yang digunakan berasal dari Kaggle:
> [https://www.kaggle.com/datasets/mfayyazgiki/ecommerce](https://www.kaggle.com/datasets/mfayyazgiki/ecommerce)

Ukuran: ~19.000 baris  
Format: CSV

---

## Insight & Findings
- Penjualan tinggi ditemukan pada produk kategori Simply9
- Kota Karachi memiliki volume transaksi tertinggi
- Produk DIY menunjukkan performa netral
- AI berhasil menyimpulkan data ke dalam bentuk ringkasan otomatis yang padat

---

## AI Support Explanation
Model AI yang digunakan:  
`t5-small-summarization` dari Replicate (via LangChain di Google Colab)

Fungsinya:
- Meringkas deskripsi gabungan dari data (category, sku, sales, city)
- Mendukung insight otomatis
- Tidak menggunakan WatsonX karena Replicate + Colab lebih ringan & gratis

