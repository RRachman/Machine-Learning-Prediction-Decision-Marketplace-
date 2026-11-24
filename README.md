# Prediksi Pembatalan Pesanan Shopee

Aplikasi berbasis Streamlit untuk memprediksi status pesanan Shopee menggunakan model Random Forest. Aplikasi menerima data transaksi dalam format CSV atau Excel, menampilkan ringkasan hasil prediksi, dan menyediakan file hasil yang dapat diunduh.

## Fitur

- Upload data transaksi dalam format CSV atau XLSX.
- Prediksi status pesanan: **Selesai** atau **Batal**.
- Menampilkan ringkasan dan visualisasi hasil prediksi.
- Menyediakan rekomendasi dan analisis hasil.
- Mengunduh hasil prediksi dalam format CSV..

## Teknologi

- Python
- Streamlit
- Pandas dan NumPy
- Scikit-learn
- Matplotlib
- SHAP (untuk aplikasi dengan analisis SHAP)

## Struktur file

```text
.
├── streamlit.py                                  # Aplikasi Streamlit dengan analisis SHAP
├── python.py                                     # Aplikasi Streamlit alternatif
├── fix_final_sidang_prediksi_pesanan_batal_dan_selesai.py
├── random_forest_model.pkl                       # Model Random Forest
├── scaler.pkl                                    # Scaler untuk preprocessing
├── feature_cols.json                             # Daftar fitur model
└── requirement.txt                               # Daftar dependensi
