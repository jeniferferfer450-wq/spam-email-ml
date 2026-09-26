# Deteksi Spam Email dengan Machine Learning

## Identitas Mahasiswa

- Nama: Jenifer Magdalena
- NIM: 2024606601039
- Mata Kuliah: Kecerdasan Buatan
- Program Studi: Sistem dan Teknologi Informasi

## Deskripsi Proyek

Proyek ini merupakan implementasi Machine Learning untuk mendeteksi
pesan spam pada sistem email.

Metode yang digunakan adalah:

- TF-IDF Vectorizer untuk mengubah teks menjadi fitur numerik
- Multinomial Naive Bayes untuk klasifikasi spam dan ham

## Fitur Proyek

- Membaca dataset CSV
- Prapemrosesan teks
- Pembagian data latih dan data uji
- Pelatihan model Machine Learning
- Evaluasi accuracy, precision, recall, dan F1-score
- Visualisasi confusion matrix
- Prediksi pesan baru
- Simulasi tindakan inbox, tandai mencurigakan, atau karantina

## Struktur Folder

```text
spam-email-ml/
├── README.md
├── requirements.txt
├── notebooks/
│   └── spam_detection_colab.ipynb
├── docs/
│   ├── Laporan_ML_Deteksi_Spam_Email.pdf
│   ├── Slide_Presentasi_Deteksi_Spam_Email.pptx
│   ├── diagram_deteksi_spam_email.drawio
│   └── diagram_deteksi_spam_email.png
└── data/
    └── README_DATA.md
```

## Cara Menjalankan

1. Buka file `notebooks/spam_detection_colab.ipynb`.
2. Upload notebook ke Google Colab.
3. Siapkan dataset CSV dengan kolom `label` dan `message`.
4. Jalankan semua cell secara berurutan.
5. Catat hasil classification report dan confusion matrix.

## Dataset

Dataset demonstrasi menggunakan SMS Spam Collection dari UCI Machine Learning Repository.

Format data:

```csv
label,message
ham,"Meeting proyek pukul 10.00."
spam,"Claim your free prize now!"
```

## Etika dan Privasi

- Jangan gunakan email pribadi atau data kampus yang sensitif.
- Jangan mengunggah password, token, API key, atau data rahasia.
- Model tidak boleh menghapus email otomatis.
- Pesan yang dianggap spam sebaiknya masuk karantina dan dapat dipulihkan.

## Tautan Google Colab

(https://github.com/jeniferferfer450-wq/spam-email-ml.git)
