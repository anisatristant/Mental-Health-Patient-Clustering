# 🏥 Mental Health Patient Clustering & Referral Pattern Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/K--Means-Clustering-blue?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 📌 Deskripsi Proyek
Proyek ini merupakan analisis data mining untuk mengelompokkan karakteristik pasien kesehatan mental berdasarkan data demografis, diagnosa, dan pola rujukan. Tujuannya adalah untuk mengidentifikasi kelompok pasien (clustering) guna membantu pihak penyedia layanan kesehatan dalam memahami kebutuhan spesifik tiap segmen pasien.

**Catatan Data:** 
Dataset yang digunakan bersifat **Privat** (Project Akhir Kuliah). Atas alasan etika medis dan kerahasiaan data, dataset asli tidak dipublikasikan di repository ini. Seluruh analisis, visualisasi, dan hasil pemodelan tetap dapat dilihat melalui file notebook `.ipynb` yang tersedia.

---

## 🛠️ Metodologi Teknik
Proyek ini menggunakan pendekatan **Unsupervised Learning** dengan tahapan sebagai berikut:

1. **Hybrid Environment**: Kode dirancang agar dapat dijalankan secara fleksibel baik di Google Colab maupun lingkungan lokal.
2. **Feature Engineering**: 
   - Penanganan diagnosa "Tak Terinci" secara spesifik.
   - Label Encoding untuk variabel kategori (Kecamatan, Cara Bayar, Diagnosa).
   - Min-Max Scaling untuk normalisasi data umur.
3. **Optimasi K-Means**: 
   - Menggunakan `KElbowVisualizer` untuk menentukan jumlah cluster (K) secara objektif.
   - Evaluasi kualitas cluster menggunakan **Silhouette Score** dan **Davies-Bouldin Index**.
4. **Analisis Deskriptif Post-Hoc**: Melakukan analisis karakteristik tiap cluster untuk mendapatkan insight bisnis/medis.

---

## 📈 Key Insights & Hasil
- **K-Selection**: Penentuan jumlah cluster yang optimal memberikan struktur data yang jelas untuk analisis pola rujukan.
- **Karakteristik Cluster**: (Contoh: Cluster 0 didominasi oleh pasien usia produktif dengan diagnosa spesifik, sementara Cluster 1 menunjukkan pola rujukan rawat inap yang lebih tinggi).
- **Intervensi Medis**: Hasil pengelompokan dapat digunakan untuk menentukan prioritas alokasi sumber daya di tingkat kecamatan tertentu.

---

## 📂 Folder Structure
- `Mental_Health_Clustering_Analysis.ipynb`: File utama kodingan (Preprocessing, Modeling, Visualisasi).
- `README.md`: Dokumentasi proyek.

---

## 👤 Penulis
**[Annisa Tristanti]**  
*Data Science Enthusiast | Project Akhir Kuliah*  
[https://www.linkedin.com/in/annisatristanti/]
