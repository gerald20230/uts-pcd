# UTS Pengolahan Citra Digital (PCD)

Repositori ini berisi tugas Ujian Tengah Semester mata kuliah Pengolahan Citra Digital. Terdapat beberapa sub-proyek yang mencakup teknik-teknik dasar pemrosesan citra digital menggunakan Python dan OpenCV.

### 1. Deteksi Warna pada Citra
- Menentukan dan mengekstrak area gambar berdasarkan warna tertentu (misalnya merah, hijau, atau biru).
- Menggunakan model warna HSV untuk segmentasi warna lebih akurat.
- Hasil deteksi warna divisualisasikan dengan pemisahan kanal warna.

### 2. Thresholding: Mengurutkan Ambang Batas
- Menghitung nilai ambang (threshold) dari citra grayscale.
- Menampilkan dan mengurutkan nilai ambang dari terkecil hingga terbesar.
- Menggunakan metode thresholding dasar seperti binary, inverse binary, trunc, dan lainnya.

### 3. Perbaikan Gambar Backlight
- Memproses gambar yang terkena efek backlight (wajah menjadi gelap karena latar terlalu terang).
- Teknik yang digunakan:
  - Konversi ke grayscale
  - Peningkatan kecerahan (brightness)
  - Peningkatan kontras
  - Kombinasi brightness & kontras
- Tujuannya agar bagian wajah tetap terlihat jelas meskipun latar sangat terang.

## ⚙️ Cara Menjalankan
1. Pastikan Anda sudah menginstal:
   - Python (disarankan 3.8+)
   - OpenCV (`cv2`)
   - NumPy
   - Matplotlib
2. Jalankan masing-masing file `.ipynb` di Jupyter Notebook atau Google Colab.

## 🧑‍💻 Penulis
- Gerald - 20230  
- UTS Pengolahan Citra Digital 2025
