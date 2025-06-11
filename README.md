# Analisis_TURF
Menentukan Penempatan Optimal Produk Impulse Buying Berdasarkan Preferensi Pengunjung Supermarket Menggunakan Analisis TURF

---
## Latar Belakang

Supermarket XYZ memiliki kandidat 20 produk impulsif, namun mereka memiliki kendala yakni keterbatasan ruang di sekitar area kasir, sehingga hanya beberapa produk saja yang dapat dijadikan display. Tujuan dari analisis ini adalah:

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

### Segmen: Semua Pelanggan
- **Target Reach**: 80%
- **Total Reach yang Dicapai**: 82.5%
- **Jumlah Produk Optimal**: 6
- **Produk Terpilih**: Produk M, P, N, B, R, I

 **Visualisasi:**
 
![Screenshot 2025-05-30 225041](https://github.com/user-attachments/assets/764257b7-bbab-4d01-8e72-258928d0b76f)

---

### Segmen: Perempuan Usia <25 Tahun
- **Target Reach**: 80%
- **Total Reach yang Dicapai**: 86.2%
- **Jumlah Produk Optimal**: 4
- **Produk Terpilih**: Produk R, I, F, M

 **Visualisasi:**
 
![Screenshot 2025-05-30 224843](https://github.com/user-attachments/assets/9228d0fd-4af5-4864-a19f-0e4be8e0879a)

Terdapat perbedaan hasil di mana ternyata dibutuhkan 6 produk impulsif untuk mencapai target dengan kategori **seluruh pelanggan** dengan capaian target sejauh 82,5%. Sedangkan untuk segmen khusus yakni pelanggan perempuan di bawah 25 tahun, dengan capaian target hingga 86,2% ternyata 4 produk saja sudah cukup untuk melampaui target. Ini menunjukkan bahwa strategi dapat menghasilkan efisiensi ruang sekaligus protensi penjualan yang lebih tinggi berdasarkan segmen pelanggan.

---

## Insight Strategis

- Penempatan produk alangkah baiknya jika disesuaikan dengan segmen target pelanggan 
- Segmentasi khusus berdasarkan usia dan gender dinilai sangat membantu dalam penyusunan strategi display di area kasir agar tepat sasaran.
- Produk R dapat menjadi produk maskot untuk segmen khusus karena memberikan impact paling besar. Produk ini cocok dijadikan produk utama dalam display kasir.
- Dengan adanya ruang terbatas pada area kasir, mengetahui dan memahami preferensi pilihan tiap segmen dapat menghasilkan penyusunan produk impulsif yang lebih efisien dan memiliki impact yang lebih besar.
- TURF membantu menghindari duplikasi preferensi dan meningkatkan efisiensi rak display.

---

## 📌 Kesimpulan

Analisis TURF membantu supermarket dalam mengambil keputusan berbasis data untuk mengoptimalkan ruang promosi. Dengan pendekatan ini, strategi display bisa diarahkan pada **segmen pelanggan yang paling potensial** tanpa kehilangan efisiensi.

---

## 📂 Lisensi
Proyek ini bersifat open-source dan dapat digunakan bebas untuk keperluan akademik dan praktis. Referensi metode TURF diambil dari praktik industri dan literatur riset pemasaran.

