# UTS Machine Learning

**Mata Kuliah:** Machine Learning  
**Nama:** M. Zacky Mahendra  
**NIM:** 241011402133  
**Kelas:** Reg B 

## Ringkasan

Notebook ini membahas penerapan **Linear Regression** untuk memperkirakan penjualan berdasarkan biaya iklan dan **Logistic Regression** untuk mengklasifikasikan email spam berdasarkan jumlah link serta kata promosi. Implementasi model, pemisahan data, dan metrik utama dibuat menggunakan NumPy; evaluasi serta visualisasi disertakan di notebook.

| Evaluasi | Hasil |
|---|---:|
| Linear Regression - RMSE testing | 6.2498 juta Rp |
| Linear Regression - R² testing | 0.9285 |
| Logistic Regression - akurasi testing | 0.9333 |
| Logistic Regression - precision / recall / F1 | 0.8750 / 1.0000 / 0.9333 |
| Logistic Regression - threshold terpilih | 0.7 |

Model regresi normal equation menghasilkan `y_hat = 27.5244 + 9.0937X`. Logistic Regression NumPy menghasilkan akurasi testing 0.9333; pada threshold 0.7, confusion matrix testing adalah `[[8, 0], [0, 7]]`. Evaluasi testing klasifikasi terdiri dari 15 email, sehingga metrik perlu ditafsirkan dengan mempertimbangkan ukuran sampel yang terbatas.

## Berkas

- `tugas_UTS.ipynb`: implementasi, eksperimen, evaluasi, dan jawaban konsep.
- `Ads_Data.csv`: dataset biaya iklan dan penjualan.
- `Email_Data.csv`: dataset email dan label spam.

## Cara Menjalankan

Buka `tugas_UTS.ipynb` di Jupyter atau VS Code, pastikan `numpy`, `pandas`, dan `matplotlib` tersedia, lalu jalankan semua sel secara berurutan. Bonus perbandingan memerlukan `scikit-learn`.
