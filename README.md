Praktikum 2 - Preprocessing & Feature Engineering

Mata Kuliah: Pembelajaran Mesin (INF62325)   
Nama : Dani Hidayat
NIM : 2488010016


Ringkasan Praktikum prapemrosesan dan rekayasa fitur pada dataset karyawan: 
penanganan nilai hilang, encoding data kategorikal, penskalaan fitur, serta pencegahan data leakage.   

Isi RepositoriPM_P4_DaniHidayat_NIM.ipynb : notebook praktikum prapemrosesan dan feature engineering

Temuan Utama

Penanganan Nilai Hilang: Imputasi nilai hilang pada kolom numerik (seperti usia dan pendapatan) dapat menggunakan metode median ataupun mean untuk memastikan integritas data sebelum masuk ke model.  

Pemilihan Teknik Encoding: Penggunaan label/ordinal encoding tepat untuk kategori berjenjang (seperti tingkat pendidikan), sedangkan one-hot encoding wajib digunakan untuk kategori nominal agar tidak memicu bias urutan angka.   Pencegahan Data Leakage: Urutan splitting (membagi data latih dan uji) harus dilakukan sebelum proses scaling, di mana fungsi fit_transform hanya diterapkan pada data latih dan data uji hanya menggunakan transform
