# Analisis Sentimen Ulasan Pengguna Aplikasi Alfagift

Proyek ini menggunakan teknik *Natural Language Processing* (NLP) untuk mengklasifikasikan sentimen ulasan pengguna aplikasi **Alfagift** di Google Play Store menjadi kategori **Positif** atau **Negatif**.

## 🔗 Akses Link Colab
Analisis dan kode lengkap dapat diakses melalui tautan di bawah ini:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fjcrU9CI3bWmV5emH17T3SJPbRBXtqa0?usp=sharing)

## 📌 Deskripsi Proyek
Tujuan utama proyek ini adalah mengotomatisasi pemantauan ulasan pelanggan Alfagift. Dengan memahami persepsi pengguna, tim pengembang dapat lebih cepat mengidentifikasi keluhan teknis atau fitur yang paling disukai pengguna berdasarkan feedback nyata.

## ⚙️ Tahapan NLP yang Dilakukan
Sesuai dengan kriteria pengolahan teks bahasa Indonesia, tahapan yang dilakukan meliputi:
* **Cleaning:** Menghapus angka, tanda baca, dan karakter spesial.
* **Case Folding:** Menyeragamkan semua teks menjadi huruf kecil.
* **Tokenizing:** Memecah kalimat menjadi unit kata.
* **Stopword Removal:** Menghapus kata umum yang tidak memiliki bobot informasi.
* **Stemming:** Mengembalikan kata ke bentuk dasar menggunakan library **Sastrawi**.

## 🧠 Metode & Pemodelan
Proyek ini membandingkan dua teknik representasi teks (vektorisasi) menggunakan algoritma **Support Vector Machine (SVM)** sebagai classifier:
1. **TF-IDF (Term Frequency-Inverse Document Frequency)**
2. **Word2Vec (Word Embedding)**

## 📊 Visualisasi & Hasil
* **Word Cloud:** Mengidentifikasi kata-kata kunci dominan seperti "promo", "lambat", dan "voucher".
  <img width="790" height="427" alt="image" src="https://github.com/user-attachments/assets/32a2b35c-096d-49f7-9317-31ea979ade95" />

* **Perbandingan Akurasi:** Analisis efektivitas antara metode statistik (TF-IDF) dan metode semantik (Word2Vec).
<img width="567" height="435" alt="image" src="https://github.com/user-attachments/assets/ade09ed2-8d89-4698-a0a0-7ef38c6d8a3f" />

---
**Teknologi:** Python, Sastrawi, NLTK, Scikit-Learn, Gensim, Google-Play-Scraper.

Dibuat oleh **Theresia Roxanne** - 2301020052- Informatika.
