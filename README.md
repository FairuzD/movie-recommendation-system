# Sistem Rekomendasi Film

Sistem ini dirancang untuk merekomendasikan film-film yang mirip berdasarkan genre dan rating rata-rata. Dibangun menggunakan Python, sistem ini memanfaatkan kemiripan kosinus antara genre film untuk memberikan rekomendasi yang akurat.

## Fitur Utama
- **Memuat Data Film dan Rating:** Mengimpor data dari file CSV.
- **Menghitung Rating Rata-rata:** Menghitung rating rata-rata untuk setiap film.
- **Model Rekomendasi:** Menggunakan kemiripan kosinus pada genre film untuk membangun model rekomendasi.
- **Rekomendasi Film:** Memberikan rekomendasi film serupa berdasarkan judul film yang diberikan.

## Teknologi yang Digunakan
- **Python:** Bahasa pemrograman serbaguna.
- **pandas:** Pustaka analisis data untuk manipulasi dan analisis struktur data.
- **scikit-learn:** Pustaka pembelajaran mesin untuk analisis data dan algoritma prediktif.

## Dataset
Dataset yang saya gunakan diunduh dari [MovieLens](https://grouplens.org/datasets/movielens/).

## Library
   ```bash
   pip install pandas scikit-learn

