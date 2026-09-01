
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

### Student Score Prediction 

Proyek sederhana ini bertujuan untuk memprediksi nilai akhir siswa berdasarkan berbagai faktor akademik dan psikologis menggunakan algoritma Linear Regression.

## Hasil Analisis Utama

Berdasarkan data yang diolah, ditemukan beberapa poin menarik:

Korelasi Sangat Kuat: Jam belajar memiliki pengaruh yang sangat signifikan terhadap nilai akhir siswa.

Tingkat Stres: Terdapat pola di mana tingkat stres yang terlalu tinggi cenderung menurunkan performa akademik.

Akurasi Model: Model ini memiliki nilai R2 Score sebesar 0.99, yang menunjukkan tingkat akurasi prediksi yang sangat tinggi pada dataset ini.

## Struktur Folder

data/: Berisi file dataset student_data.csv.

images/: Hasil visualisasi data (Histogram, Scatter Plot, Heatmap).

notebook/: File analisis utama dalam format .ipynb.

requirements.txt: Daftar library Python yang dibutuhkan untuk menjalankan proyek.

## Cara Menjalankan

Clone repositori ini ke komputer kamu.

Install semua library yang dibutuhkan dengan perintah:

pip install -r requirements.txt


Jalankan notebook analysis.ipynb menggunakan Jupyter Notebook atau VS Code Editor.

## Contoh Penggunaan 

Proyek ini menyertakan fitur interaktif di bagian akhir notebook di mana pengguna dapat memasukkan data secara manual (seperti jam belajar dan tingkat stres) untuk mendapatkan estimasi nilai akhir secara instan.
