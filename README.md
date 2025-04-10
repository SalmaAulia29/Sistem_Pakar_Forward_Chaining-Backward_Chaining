# Sistem Pakar Forward Chaining & Backward Chaining

Sistem pakar ini merupakan implementasi sederhana dari sistem berbasis aturan (*rule-based expert system*) untuk mendiagnosa beberapa penyakit umum berdasarkan gejala yang dialami oleh pengguna. Sistem menggunakan dua pendekatan inferensi: **Forward Chaining** dan **Backward Chaining** dengan bantuan pustaka [experta](https://github.com/noxdafox/experta).

## Penyakit yang Dapat Dideteksi

- Flu
- Pneumonia
- Common Cold
- Throat Infection
- COVID-19
- Allergic Rhinitis
- Asthma
- Tonsillitis
- Sinusitis
- Kondisi Sehat

### 🚀 Menjalankan di Google Colab

1. Buka [Google Colab](https://colab.research.google.com)
2. Klik menu **"File" > "Upload Notebook"** atau klik ikon 📁 
3. Upload file `forward_chaining.ipynb` atau `backward_chaining.ipynb` dari repository yang sudah diunduh
4. Tambahkan cell baru di awal notebook dan jalankan perintah:
   ```python
   !pip install experta
   ```
5. Jalankan semua cell dengan klik menu **"Runtime" > "Run all"** atau dengan menekan **Ctrl+F9**

## 📋 Penjelasan Sistem

### Forward Chaining
Metode inferensi maju (forward chaining) bekerja dengan:
1. Mengumpulkan fakta-fakta (gejala) dari pengguna
2. Menerapkan aturan berdasarkan fakta yang dikumpulkan
3. Menarik kesimpulan (diagnosis penyakit) berdasarkan aturan yang terpicu

### Backward Chaining
Metode inferensi mundur (backward chaining) bekerja dengan:
1. Mulai dari hipotesis (kemungkinan penyakit)
2. Mencari fakta (gejala) yang dapat mendukung hipotesis
3. Konfirmasi atau tolak hipotesis berdasarkan fakta yang ditemukan

## ⚠️ Disclaimer

Sistem pakar ini dibuat untuk tujuan pembelajaran dan tidak dimaksudkan untuk menggantikan diagnosis medis profesional. Selalu konsultasikan dengan dokter atau tenaga medis profesional untuk masalah kesehatan Anda.

2306143 Salma Aulia Nisa
