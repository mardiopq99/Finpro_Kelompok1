# Analisis Penjualan E-Commerce

## Deskripsi Proyek
Proyek ini melakukan _Exploratory Data Analysis_ (EDA) pada data penjualan di platform e-commerce untuk memahami pola transaksi, preferensi konsumen, performa kategori produk, dan faktor lain yang mempengaruhi penjualan. EDA bertujuan mengidentifikasi insight berharga yang dapat mendukung pengambilan keputusan bisnis, terutama terkait strategi pemasaran dan optimalisasi stok produk.

## Tujuan EDA
Proses EDA dilakukan untuk:
- Memahami distribusi data dan karakteristik tiap variabel.
- Mengidentifikasi pola atau tren dalam penjualan berdasarkan kategori produk, metode pengiriman, ukuran, dan variabel lainnya.
- Menemukan hubungan antara variabel yang berpotensi mempengaruhi performa penjualan.
- Memberikan rekomendasi bisnis berdasarkan insight dari hasil analisis.

## Ringkasan Insight dari EDA
Berikut adalah beberapa insight utama yang diperoleh dari EDA:

1. **Jumlah Pesanan Unik**: Terdapat 120,378 pesanan unik dari total 128,975 transaksi.
2. **Frekuensi Pesanan Tertinggi**: Terjadi peningkatan frekuensi pesanan yang signifikan pada awal Mei.
3. **Distribusi Kuantitas dan Harga Pesanan**: Kolom kuantitas (_Qty_) memiliki distribusi yang cenderung terpusat di nilai 1, sementara harga pesanan mendekati distribusi normal.
4. **Dominasi Pemenuhan Pesanan oleh Amazon**: Sebagian besar pesanan dipenuhi langsung oleh Amazon dibandingkan oleh merchant pihak ketiga.
5. **Platform Dominan**: Amazon.in mendominasi sebagai platform penjualan, menunjukkan produk lebih efektif dipasarkan melalui Amazon.
6. **Model Bisnis B2C**: Sebagian besar transaksi adalah B2C, yang berarti perusahaan berfokus pada penjualan langsung ke konsumen akhir.
7. **Kategori Produk Populer**: Set dan Kurta adalah dua kategori dengan jumlah pesanan tertinggi, mendekati 10,000 baris pesanan.
8. **Metode Pengiriman**: Pengiriman cepat (_expedited_) lebih umum digunakan daripada pengiriman standar.
9. **Ukuran Produk Terpopuler**: Ukuran M, L, dan XL memiliki jumlah pesanan tertinggi.
10. **Hubungan Kuantitas dan Harga Pesanan**: Tidak ada korelasi kuat antara kuantitas dan harga pesanan.
11. **Status Produk Berdasarkan Ukuran**: Ukuran populer seperti M, L, dan XL lebih banyak dikirim dan diterima tanpa pengembalian atau penolakan.
12. **Kategori Produk dengan Harga Rata-Rata Tinggi**: Set, Saree, dan Western Dress menunjukkan harga rata-rata yang lebih tinggi.
13. **Pesanan Berdasarkan Negara Bagian**: Maharashtra dan Karnataka memiliki jumlah pesanan tertinggi.

## Rekomendasi Bisnis
Berdasarkan insight di atas, berikut beberapa rekomendasi bisnis yang dapat diambil:
- **Optimalkan Stok Produk Populer**: Menyediakan stok yang cukup untuk kategori Set dan Kurta, serta ukuran M, L, dan XL, dapat membantu meningkatkan kepuasan pelanggan dan mengurangi risiko kehabisan stok.
- **Perkuat Strategi Pemasaran di Amazon**: Mengingat Amazon.in mendominasi penjualan, pertimbangkan strategi pemasaran lebih lanjut di platform ini, seperti kampanye promosi atau diskon eksklusif.
- **Fokus Pengiriman Cepat untuk Kategori Utama**: Karena pengiriman cepat lebih umum digunakan, menawarkan opsi _expedited_ untuk kategori populer dapat meningkatkan kepuasan pelanggan.
- **Analisis Wilayah Penjualan**: Pertimbangkan kampanye atau iklan khusus di Maharashtra dan Karnataka untuk memaksimalkan penjualan di wilayah dengan pesanan tertinggi.

## Struktur Folder
- `Python_Stage_1_Kel_1.ipynb` - Notebook yang berisi kode analisis data.
- `README.md` - Berisi ringkasan proyek dan insight utama.
- Stage 1 - Kelompok 1.docx
