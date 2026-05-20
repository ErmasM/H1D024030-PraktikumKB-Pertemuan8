# Laporan Praktikum Kecerdasan Buatan - Pertemuan 8

**Nama:** Ermas Muhammad Syatafa 
**NIM:** H1D024030  
**Kelas:** Praktikum Kecerdasan Buatan (F)  

## Deskripsi Tugas
Repositori ini berisi kode program untuk memenuhi tugas praktikum Pertemuan 8 mengenai Convolutional Neural Network (CNN). Di sini saya membuat model deep learning untuk mengklasifikasikan gambar tangan berbentuk batu, gunting, dan kertas.

## Dataset
Dataset yang digunakan adalah Rock Paper Scissors dengan total data yang diproses:
* Data Training: 1751 gambar
* Data Validation: 437 gambar (20% dari total dataset)

## Hasil Percobaan dan Analisis
Proses training model dilakukan sebanyak 10 epoch menggunakan CPU. Berikut adalah hasil akhir yang didapatkan setelah model selesai dilatih:

* **Akurasi Training:** Berhasil menyentuh angka 1.0000 atau 100%.
* **Akurasi Validasi:** Berhasil mencapai 0.9771 atau 97.71%.

Kesimpulannya, model CNN yang dibuat sudah sangat akurat dalam membedakan gambar batu, gunting, maupun kertas. Nilai akurasi data validasi yang melebih 97% menunjukkan bahwa model ini bisa menebak gambar baru dengan sangat baik dan tidak mengalami overfitting.
