# Analisis Sentimen Aplikasi Signal

Proyek ini menganalisis sentimen ulasan pengguna aplikasi Signal dengan teknik NLP. Terdiri dari scraping data, pelatihan model, dan prediksi sentimen.

## Struktur Proyek

- README.md
- requirements.txt
- scrapping.ipynb # Script scraping data ulasan
- pelatihan_model.ipynb # Notebook untuk training model
- ulasan_app_signal.csv # Dataset hasil scraping

## Prasyarat
- Python
- Pip

## Instalasi
1. Clone repositori:
   git clone https://github.com/leonardkumaro/signal-sentiment-analysis.git
   cd signal-sentiment-analysis
2. Pasang dependensi:
pip install -r requirements.txt

## Menjalankan Proyek
1. Scraping Data (Opsional)

2. Pelatihan Model
Jalankan notebook pelatihan

Proses ini akan:
- Load data dari ulasan_app_signal.csv
- Preprocessing teks
- Training model klasifikasi sentimen
- Simpan model (opsional)

## Dependensi Utama :
- Pandas
- Scikit-learn
- NLTK/Sastrawi (untuk NLP Bahasa Indonesia)
- Jupyter Notebook

## Kontribusi :
- Fork project
- Buat branch baru
- Commit perubahan
- Push ke branch
- Buat Pull Request

## Penyesuaian yang bisa Anda lakukan:
1. Tambahkan penjelasan spesifik tentang dataset di bagian **Struktur Proyek** jika perlu
2. Sesuaikan nama file model di bagian **Gunakan Model**
3. Tambahkan visualisasi (contoh grafik akurasi) jika ada
4. Cantumkan referensi/library khusus yang digunakan