# Customer-Segmentation
- Deskripsi Proyek
Proyek ini melakukan segmentasi pelanggan menggunakan teknik machine learning (khususnya K-Means Clustering) untuk mengelompokkan pelanggan berdasarkan pola perilaku dan transaksi mereka. Dengan segmentasi pelanggan, bisnis dapat membuat strategi pemasaran yang lebih tepat, meningkatkan pengalaman pelanggan, dan mendukung pengambilan keputusan yang lebih efektif.

Seluruh proses analisis dilakukan melalui Jupyter Notebook (A25_CS309_Capstone_Project.ipynb) yang mencakup preprocessing, pemodelan, dan pembuatan profil cluster.

- Tujuan Proyek
Menganalisis data pelanggan untuk menemukan pola yang bermakna

Mengidentifikasi kelompok pelanggan dengan karakteristik serupa

Membangun dan menyimpan model segmentasi untuk digunakan kembali

Menyediakan profil cluster sebagai dasar insight bisnis

📁 Struktur Repository
├── A25_CS309_Capstone_Project.ipynb  
├── Capstone_Result_Segmented.csv  
├── cluster_profile.csv  
├── kmeans_customer_segmentation_model.joblib  
├── scaler_model.joblib  
├── requirements.txt  
└── README.md


A25_CS309_Capstone_Project.ipynb — Notebook utama berisi seluruh proses analisis.

Capstone_Result_Segmented.csv — Hasil segmentasi tiap pelanggan.

cluster_profile.csv — Profil ringkas masing-masing cluster.

kmeans_customer_segmentation_model.joblib — Model K-Means yang sudah disimpan.

scaler_model.joblib — Model scaler yang digunakan saat preprocessing.

requirements.txt — Daftar dependensi Python.

- Cara Instalasi

Clone repository:

git clone https://github.com/afifahzhraa/Customer-Segmentation.git
cd Customer-Segmentation


(Opsional) Buat virtual environment:

python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate


Install dependensi:

pip install -r requirements.txt

- Cara Menggunakan

Buka notebook
Jalankan A25_CS309_Capstone_Project.ipynb.

Jalankan seluruh sel
Notebook sudah berisi langkah-langkah mulai dari loading data, cleaning, preprocessing, clustering, hingga visualisasi.

Lihat hasil segmentasi

File Capstone_Result_Segmented.csv berisi data pelanggan beserta label cluster.

File cluster_profile.csv berisi ringkasan karakteristik masing-masing cluster.

Gunakan model untuk data baru
Anda dapat memuat file .joblib untuk melakukan prediksi cluster pada data pelanggan baru.

- Metodologi

Import Data
Membaca dataset pelanggan.

Preprocessing

Menangani missing values

Feature scaling

Normalisasi/transformasi jika diperlukan

Clustering dengan K-Means
Menentukan jumlah cluster optimal (misalnya menggunakan Elbow Method), lalu melatih model.

Evaluasi & Visualisasi
Menentukan karakteristik utama tiap cluster dan membuat insight bisnis.

Menyimpan Model & Output
Model dan hasil segmentasi disimpan untuk pemakaian ulang.

- Dependensi

Dependensi utama (lihat lengkap di requirements.txt):

pandas

numpy

scikit-learn

matplotlib

seaborn

joblib

Install dengan:

pip install -r requirements.txt

- Catatan Tambahan

Pastikan menggunakan Python versi 3.8 atau lebih baru.

Proyek ini dapat dikembangkan lebih lanjut dengan menambahkan model clustering lain, dashboard visualisasi, atau integrasi API.

- Kontak

Jika ingin memberi masukan, membuka issue, atau mengajukan pull request, silakan langsung melalui repository ini.
