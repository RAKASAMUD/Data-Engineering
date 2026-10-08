# Assignment Data Processing

Repo ini berisi tugas mata kuliah Rekayasa Data tentang preprocessing data. Dataset yang digunakan adalah Hotel Booking dari Hugging Face.

Semua proses ada di notebook `assignment data processiing.ipynb`, mulai dari mengecek kualitas data, menghapus duplikat dan data tidak valid, mengisi nilai kosong, sampai analisis korelasi, PCA, dan pembuatan fitur baru. Notebook ini juga menampilkan grafik perbandingan data sebelum dan sesudah diolah.

Dari hasil pengolahan, jumlah data berkurang dari 119.390 menjadi 86.970 baris, dengan 36 kolom dan tanpa nilai kosong.

Untuk menjalankannya, buka notebook di Jupyter atau VS Code, lalu jalankan semua sel secara berurutan. Library yang dibutuhkan bisa dipasang dengan perintah berikut:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn requests ipython tabulate
```

Saat pertama kali dijalankan, notebook membutuhkan internet untuk mengunduh dataset. Hasilnya akan disimpan sebagai `hotel_booking_preprocessed.csv`, sedangkan grafiknya disimpan di folder `figures`.
