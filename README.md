# Analisis Produk Terlaris dari Data Perilaku Customer Toko Online
## Overview
Salah satu informasi yang bisa didapat dari data penjualan toko online adalah data perilaku customer. Project machine learning ini bertujuan untuk memprediksi apakah seorang customer toko online akan membeli suatu barang atau tidak menggunakan data perilaku customer dari toko online tersebut. Selain machine learning, akan dianalisis juga informasi penting lain, misalnya seperti apa produk yang laris dijual berdasarkan perilaku pembelinya di toko online. Hasil analisis project machine learning ini diharapkan nantinya bisa membantu penjual di toko online, distributor barang, atau pihak-pihak berkepentingan lain untuk mengambil keputusan tentang penjualan suatu barang berdasarkan data perilaku customer barang tersebut.
## Data Description
Berikut ini adalah deskripsi tiap kolom yang ada dalam data:
-event_time: waktu tiap terjadinya event/perilaku dalam UTC.
-event_type: perilaku yang dilakukan, ada 3 jenis yaitu view, cart, dan purchase.
-product_id: ID dari produk.
-category_id: ID untuk kategori produk.
-category_code: Kategori produk.
-brand: nama brand produk.
-price: harga produk.
-user_id: ID permanen pengguna.
-user_session: ID pengguna tiap yang berubah tiap sesi.
## Data Modeling
- Model machine learning yang digunakan untuk memprediksi pembelian berdasarkan perilaku customer adalah XGBoost.
- Performa model machine learning tersebut adalah sebagai berikut:
  - Accuracy = 0.6594841311962637
  - Precision = 0.6303797468354431
  - Recall = 0.630960608154803
  - F1-Score = 0.6306700437485608