# Analisis Sentimen Ulasan Produk Amazon Menggunakan Machine Learning & Deep Learning 📦

## Deskripsi Proyek
Proyek ini berfokus pada pembangunan model klasifikasi untuk mendeteksi sentimen (positif atau negatif) dari ulasan produk pada dataset Amazon. Proyek ini membandingkan dua pendekatan: model machine learning klasik (**Naive Bayes**) sebagai *baseline*, dan model deep learning modern (**DistilBERT**) untuk menunjukkan kemampuan pemahaman konteks.

Alur kerja proyek mencakup pra-pemrosesan teks, pembuatan dan pelatihan model, evaluasi kinerja, serta visualisasi hasil untuk memastikan efektivitas dan perbandingan yang jelas antara kedua model.

### Link ke Dataset
Dataset yang digunakan dalam proyek ini https://drive.google.com/drive/folders/19X0shXRsMgXXBAHiLzNg7FnUBJJPOMZZ?usp=sharing.

Analisis sentimen pada ulasan produk sangat penting bagi bisnis untuk memahami opini pelanggan secara luas, mengidentifikasi kelemahan produk, dan membuat keputusan strategis berbasis data.

Tugas klasifikasi ini melibatkan pembedaan antara dua kategori:
- **Positif** (rating 4 & 5)
- **Negatif** (rating 1 & 2)

## Tujuan Proyek
- **Persiapan Data:** Melakukan pra-pemrosesan dan pembersihan data teks dari jutaan ulasan.
- **Pembangunan Model:** Mengembangkan model Naive Bayes sebagai *baseline* dan melakukan *fine-tuning* pada model DistilBERT.
- **Evaluasi:** Menilai kinerja kedua model pada data uji menggunakan metrik seperti akurasi, presisi, dan F1-score.
- **Visualisasi:** Menyajikan perbandingan kinerja model secara visual untuk interpretasi yang mudah.

## Teknologi yang Digunakan
<p align="left">
  <a href="https://www.python.org" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /></a>
  <a href="https://pandas.pydata.org/" target="_blank"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" /></a>
  <a href="https://scikit-learn.org/" target="_blank"><img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" /></a>
  <a href="https://pytorch.org/" target="_blank"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" /></a>
  <a href="https://huggingface.co/" target="_blank"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=hugging-face&logoColor=black" /></a>
  <a href="https://git-scm.com/" target="_blank"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /></a>
</p>

## Wawasan (Insights)
### Perbandingan Model:
- Model DistilBERT yang berbasis arsitektur Transformer secara signifikan mengungguli Naive Bayes. Ini menunjukkan pentingnya pemahaman konteks kalimat, yang tidak dimiliki oleh model Naive Bayes yang hanya menghitung frekuensi kata.

### Akurasi Model:
- Model **Naive Bayes** mencapai akurasi **84.0%**, menunjukkan performa yang solid untuk sebuah *baseline*.
- Model **DistilBERT** mencapai akurasi **88%**, membuktikan kekuatan *deep learning* untuk tugas NLP yang kompleks.

### Contoh Prediksi:
- Pengujian dengan kalimat sarkastik (misalnya, "Luar biasa, produk ini rusak dalam sehari") menunjukkan keunggulan DistilBERT dalam menangkap sentimen yang sebenarnya, sementara Naive Bayes sering terkecoh oleh kata-kata positif.

## Saran Pengembangan (Advices)
### Optimisasi Model:
- Eksperimen lebih lanjut dengan *hyperparameter tuning* (seperti `learning rate` untuk DistilBERT atau `alpha` untuk Naive Bayes) dapat meningkatkan performa.
- Mencoba arsitektur Transformer yang lebih besar seperti RoBERTa atau BERT-large untuk potensi akurasi yang lebih tinggi.

### Peningkatan Fitur:
- Menggunakan n-grams (bigram, trigram) pada model Naive Bayes untuk menangkap sedikit konteks antar kata.

### Analisis Mendalam:
- Menggunakan teknik interpretasi model seperti LIME atau SHAP untuk memahami kata-kata apa yang paling memengaruhi prediksi sentimen pada sebuah ulasan.

Jika Anda memiliki saran atau masukan, jangan ragu untuk menghubungi saya:
- **Email:** marvinugraha@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/marvinugraha/

#datascience #nlp #sentimentanalysis #machinelearning #deeplearning #transformers #python
