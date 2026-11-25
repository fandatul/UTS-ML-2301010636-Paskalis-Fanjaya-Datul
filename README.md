# UTS Machine Learning: Klasifikasi Jenis Beras dengan KNN

## Identitas
Nama : Paskalis Fanjaya Datul
NIM : 2301010636
Kelas : XX 
Mata kuliah : Machine Learning
Dosen : Dr. I Gede Totok Suryawan, S.Kom., M.T. 
Program studi : Informatika 
Jalur : Klasifikasi 
Algoritma K-Nearest Neighbors (KNN), dibandingkan dengan baseline `DummyClassifier` 

## Pernyataan Penggunaan AI
Alat: claude.ai
Bagian yang dikerjakan AI:
1. Pemahaman dataset: membantu menjelaskan fungsi setiap kolom pada dataset beras, menentukan kolom yang termasuk fitur dan target, serta memahami alasan kolom id      tidak digunakan sebagai fitur karena bukan karakteristik fisik beras.
2. Menentukan algoritma yang cocok untuk digunakan 
3. Prapemrosesan data: membantu menjelaskan cara memeriksa missing value, data duplikat, tipe data, label kelas, dan nilai yang tidak wajar. Saya juga meminta penjelasan tentang cara membaca hasil pemeriksaan tersebut dan menentukan apakah data perlu diperbaiki atau tidak.
4. Pemeriksaan outlier: membantu memahami penggunaan metode IQR, cara menentukan batas bawah dan batas atas, serta cara membaca jumlah data yang terdeteksi sebagai outlier. Saya sempat bingung apakah data outlier harus langsung dihapus, sehingga AI membantu menjelaskan hal-hal yang perlu dipertimbangkan sebelum mengambil keputusan.
5. Pembagian data: membantu memahami proses membagi dataset menjadi data latih sebesar 80% dan data uji sebesar 20%, fungsi stratify, serta penggunaan SEED agar pembagian data dapat diulang dengan hasil yang konsisten.
6. Scaling dan pemilihan fitur: membantu menjelaskan mengapa KNN membutuhkan proses scaling, perbedaan StandardScaler dan RobustScaler, serta alasan proses scaling perlu dilakukan di dalam Pipeline agar informasi dari data uji tidak ikut digunakan saat pelatihan.
7. Pemodelan: membantu memahami cara membuat model KNN, fungsi parameter k, dan cara mencoba beberapa nilai k ganjil dari 1 sampai 31. AI juga membantu menjelaskan penggunaan DummyClassifier sebagai model pembanding (baseline) agar hasil KNN tidak dinilai tanpa pembanding.
8. Validasi model: membantu memahami proses 5-fold cross-validation menggunakan StratifiedKFold, cara membaca nilai rata-rata dan standar deviasi akurasi dari setiap percobaan, serta cara menentukan nilai k berdasarkan hasil pengujian pada data latih.


# LINK Sumber Data #
https://www.kaggle.com/datasets/mssmartypants/rice-type-classification