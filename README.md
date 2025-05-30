# Analisis_TURF
Menentukan Penempatan Optimal Produk Impulse Buying Berdasarkan Preferensi Pengunjung Supermarket Menggunakan Analisis TURF

---
## Latar Belakang

Supermarket XYZ memiliki kandidat 20 produk impulsif, namun hanya ada ruang untuk menampilkan maksimal 6 produk di rak kasir. Tujuan dari analisis ini adalah:

- Menentukan kombinasi produk yang mampu menjangkau minimal 80% pelanggan
- Mengukur efektivitas strategi penempatan produk berdasarkan **segmentasi pelanggan** (misalnya berdasarkan gender dan usia)

---

## Teknologi dan Tools
- Python (Pandas, Matplotlib)
- Jupyter Notebook
- Excel (.xlsx) sebagai dataset input
- TURF Analysis + Algoritma Greedy

---

## Hasil Analisis

### Segmen: Perempuan Usia <25 Tahun
- **Target Reach**: 80%
- **Total Reach yang Dicapai**: 86.2%
- **Jumlah Produk Optimal**: 4
- **Produk Terpilih**: Produk R, I, F, M

 **Visualisasi:**
 
![Screenshot 2025-05-30 224843](https://github.com/user-attachments/assets/9228d0fd-4af5-4864-a19f-0e4be8e0879a)

---

### Segmen: Semua Pelanggan
- **Target Reach**: 80%
- **Total Reach yang Dicapai**: 82.5%
- **Jumlah Produk Optimal**: 6
- **Produk Terpilih**: Produk M, P, N, B, R, I

 **Visualisasi:**
 
![Screenshot 2025-05-30 225041](https://github.com/user-attachments/assets/764257b7-bbab-4d01-8e72-258928d0b76f)


---

## Insight Strategis

- Hanya dengan 4 produk, segmen muda perempuan bisa dijangkau secara efisien (>86%).
- Dibutuhkan lebih banyak produk untuk menjangkau populasi umum.
- Produk **R** dan **I** tampil konsisten di kedua segmen → ideal untuk penempatan permanen.
- TURF membantu menghindari duplikasi preferensi dan meningkatkan efisiensi rak display.

---

## 📌 Kesimpulan

TURF Analysis dapat membantu supermarket atau retailer lainnya dalam mengambil keputusan berbasis data untuk optimalisasi ruang promosi. Dengan pendekatan ini, strategi display bisa diarahkan pada **segmen pelanggan yang paling potensial** tanpa kehilangan efisiensi.

---

## 📂 Lisensi
Proyek ini bersifat open-source dan dapat digunakan bebas untuk keperluan akademik dan praktis. Referensi metode TURF diambil dari praktik industri dan literatur riset pemasaran.

