# Unlocking Key Data Insights to Drive Bicycle Sales

## **Pengertian Proyek**
Proyek **"Unlocking Key Data Insights to Drive Bicycle Sales"** merupakan implementasi analisis data berbasis teknologi data mining untuk mendukung pengambilan keputusan strategis dalam industri sepeda. Dengan menggunakan algoritma FP-Growth, SQL, dan Python, proyek ini bertujuan untuk menggali wawasan (insight) berharga dari data transaksi penjualan sepeda guna mengoptimalkan strategi pemasaran, pengelolaan stok, serta efisiensi operasional.

Dataset yang digunakan dalam proyek ini mencakup informasi terkait pelanggan, transaksi, produk, stok, dan lokasi toko, yang disusun dalam database relasional untuk memudahkan analisis mendalam.

---

## **Latar Belakang**
Industri sepeda telah menjadi salah satu sektor yang terus berkembang pesat, seiring dengan meningkatnya kesadaran masyarakat terhadap pentingnya gaya hidup sehat dan ramah lingkungan. Namun, banyak retailer sepeda yang belum sepenuhnya memanfaatkan data transaksi mereka untuk memahami kebutuhan pasar secara mendalam.  

Tantangan utama dalam industri ini adalah kurangnya pemahaman terhadap pola pembelian pelanggan, manajemen stok yang efisien, dan penerapan strategi diskon yang efektif. Data transaksi yang besar dan kompleks membutuhkan teknologi analisis canggih agar dapat diolah menjadi informasi yang bermakna.  

Proyek ini hadir sebagai solusi untuk menjawab tantangan tersebut dengan menerapkan teknologi data mining dan visualisasi data. Dengan alat ini, retailer dapat menggali pola pembelian pelanggan, mengoptimalkan manajemen stok, serta meningkatkan penjualan melalui pendekatan berbasis data.

---

## **Tujuan Proyek**
1. **Mengidentifikasi Kombinasi Produk Terlaris:** Menggunakan algoritma FP-Growth untuk menemukan kombinasi produk yang sering dibeli bersama, yang dapat dimanfaatkan untuk strategi cross-selling dan bundling.  
2. **Menganalisis Kategori dan Lokasi Terbaik:** Menemukan kategori produk paling populer dan lokasi toko dengan performa penjualan tertinggi, memberikan wawasan untuk optimasi stok dan strategi pemasaran.  
3. **Menilai Efektivitas Diskon:** Mengukur dampak diskon terhadap total penjualan untuk menemukan tingkat diskon yang optimal bagi pelanggan.  
4. **Menyediakan Visualisasi Data yang Informatif:** Menghadirkan hasil analisis dalam bentuk heatmap, scatterplot, dan grafik lainnya, mempermudah interpretasi bagi pengambil keputusan.  
5. **Mendukung Pebisnis Baru:** Memberikan wawasan analitis yang relevan untuk membantu pebisnis baru memahami tren pasar dan merancang strategi awal bisnis mereka.  

---

## **Proses dan Metodologi**
Proyek ini dilakukan melalui beberapa tahapan sistematis:  
1. **Pengumpulan Data:** Data transaksi sepeda dari platform Kaggle dikonversi ke dalam database relasional berbasis SQLite.  
2. **Pembersihan Data:** Data diproses untuk menghilangkan duplikasi, data kosong, atau data yang tidak relevan.  
3. **Analisis Pola Pembelian:** Menggunakan algoritma FP-Growth untuk menganalisis frequent itemsets dari data transaksi.  
4. **Analisis Berdasarkan Kategori dan Lokasi:** Menemukan produk dan toko dengan performa terbaik menggunakan query SQL.  
5. **Visualisasi Hasil Analisis:** Membuat grafik seperti heatmap dan scatterplot untuk memberikan gambaran yang jelas mengenai hasil analisis data.  

---

## **Fitur Utama dalam Proyek**
1. **Analisis Kombinasi Produk:**
   - Mendeteksi kombinasi 2 hingga 3 produk yang sering dibeli bersama dalam satu transaksi.  
   - Memberikan tingkat dukungan (support) untuk setiap kombinasi produk.  

2. **Analisis Penjualan Berdasarkan Kategori dan Lokasi:**
   - Mengidentifikasi kategori produk terpopuler berdasarkan total penjualan.  
   - Menemukan lokasi toko dengan performa penjualan terbaik.  

3. **Efektivitas Diskon:**
   - Menilai pengaruh diskon terhadap total penjualan.  
   - Memberikan rekomendasi diskon optimal untuk menarik pelanggan tanpa mengurangi profitabilitas.  

4. **Visualisasi Data Kompleks:**
   - Heatmap untuk distribusi penjualan berdasarkan kategori dan lokasi toko.  
   - Scatterplot untuk hubungan antara diskon dan total penjualan.  
   - Grafik tren penjualan bulanan untuk memahami pola musiman.  

---

## **Teknologi yang Digunakan**
1. **Bahasa Pemrograman:** Python, sebagai alat utama untuk manipulasi data dan analisis.  
2. **Library Python:**  
   - `pandas` untuk manipulasi data.  
   - `numpy` untuk operasi numerik.  
   - `mlxtend` untuk implementasi algoritma FP-Growth.  
   - `matplotlib` dan `seaborn` untuk visualisasi data.  
3. **Database:** SQLite digunakan untuk menyimpan dan mengelola data transaksi sepeda.  
4. **Platform:** Jupyter Notebook sebagai lingkungan pengembangan utama, serta GitHub untuk kolaborasi dan penyimpanan proyek.  

---

## **Manfaat Proyek**
Proyek ini memberikan manfaat besar bagi retailer sepeda dan pebisnis baru yang ingin memanfaatkan data transaksi mereka, antara lain:  
1. **Meningkatkan Penjualan:** Mengidentifikasi kombinasi produk yang sering dibeli bersama untuk strategi cross-selling dan bundling.  
2. **Mengoptimalkan Stok:** Menemukan pola permintaan produk untuk menghindari kekurangan barang dan meningkatkan efisiensi pengelolaan stok.  
3. **Meningkatkan Strategi Promosi:** Memberikan rekomendasi berbasis data untuk promosi produk tertentu di lokasi dan periode yang tepat.  
4. **Mempermudah Interpretasi Data:** Visualisasi data yang informatif membantu pengambil keputusan memahami pola penting dalam data transaksi.  
5. **Mendukung Pebisnis Baru:** Membantu pebisnis baru memahami tren pasar dan merancang strategi awal untuk memasuki pasar dengan lebih percaya diri.  

---


## **Cara Menggunakan Proyek**  

### **Persiapan Awal**  
1. **Kloning Repository:**  
   Unduh proyek dari GitHub ke lokal Anda:  
   ```bash  
   git clone https://github.com/username/bicycle-sales-insights.git  
   cd bicycle-sales-insights  
   ```  

2. **Instalasi Library yang Dibutuhkan:**  
   Pastikan Python sudah terinstal di komputer Anda, lalu instal library berikut:  
   ```bash  
   pip install pandas numpy matplotlib seaborn mlxtend sqlite3 tabulate  
   ```  

3. **Dataset:**  
   Dataset yang digunakan tersedia di folder `datasets/` pada repository ini. Dataset mencakup file CSV seperti `order_items.csv`, `products.csv`, dan lainnya.  

---

### **Langkah Penggunaan**  
1. **Buka Jupyter Notebook:**  
   Jalankan Jupyter Notebook:  
   ```bash  
   jupyter notebook  
   ```  
   Buka file notebook `bicycle_sales_analysis.ipynb`.  

2. **Integrasi Dataset dengan SQLite:**  
   Proyek ini memuat dataset dari file CSV ke dalam database SQLite. Jalankan blok kode awal untuk memuat data dan membuat koneksi ke database.  

3. **Analisis Kombinasi Produk:**  
   - Jalankan kode untuk analisis kombinasi 2 hingga 3 produk terlaris menggunakan algoritma FP-Growth.  
   - Hasil analisis akan menunjukkan kombinasi produk dengan tingkat dukungan (support) tertinggi.  

4. **Analisis Penjualan Berdasarkan Kategori dan Lokasi:**  
   - Jalankan kode SQL yang tersedia untuk mengidentifikasi kategori produk terpopuler dan toko dengan performa terbaik.  

5. **Visualisasi Data:**  
   - Gunakan heatmap, scatterplot, dan grafik lainnya untuk memahami pola penjualan, efektivitas diskon, dan tren bulanan.  

6. **Menginterpretasi Hasil:**  
   - Setiap hasil analisis disertai dengan rekomendasi strategis untuk meningkatkan penjualan dan mengelola stok secara efisien.  

---

## **Kesimpulan dan Manfaat**  
Proyek ini membantu retailer sepeda dan pebisnis baru dalam:  
1. **Meningkatkan Penjualan:** Mengidentifikasi kombinasi produk populer untuk strategi cross-selling dan bundling.  
2. **Mengelola Stok Lebih Baik:** Menemukan pola permintaan produk untuk menghindari kekurangan barang.  
3. **Mengoptimalkan Strategi Promosi:** Memberikan rekomendasi diskon optimal dan kampanye promosi berbasis data.  
4. **Memahami Tren Pasar:** Membantu pebisnis baru mengenali tren pasar untuk menyusun strategi awal yang efektif.  

Proyek ini dirancang sebagai alat yang kuat untuk mendukung pengambilan keputusan berbasis data di industri sepeda, dengan potensi penerapan lebih luas di berbagai sektor bisnis.  

---  
