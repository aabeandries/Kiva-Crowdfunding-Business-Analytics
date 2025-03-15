# 📊 Kiva-Crowdfunding-Business-Analytics


Analisis Data Pinjaman Mikro dari Kiva
# 📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis data pinjaman mikro dari Kiva, sebuah platform yang menghubungkan pemberi pinjaman dengan peminjam di berbagai negara berkembang. Analisis ini dilakukan untuk memahami aktivitas mana yang paling layak diberikan pinjaman berdasarkan berbagai faktor, seperti jumlah peminjam, durasi pinjaman, dan pola pembayaran.

# 📂 Dataset

Dataset yang digunakan berisi berbagai informasi terkait pinjaman Kiva. Beberapa kolom penting dalam dataset ini adalah:

Kolom	Deskripsi
+ `id`:	ID unik untuk setiap pinjaman
+ `loan_amount`:	Jumlah pinjaman yang diberikan
+ `term_in_months`:	Durasi pinjaman dalam bulan
+ `activity`:	Jenis usaha/kegiatan yang dibiayai oleh pinjaman
+ `sector`:	Sektor industri dari aktivitas (misalnya, Pertanian, Pendidikan, Perdagangan)
+ `country`:	Negara asal peminjam
+ `region`:	Wilayah spesifik dalam suatu negara
+ `repayment_interval`:	Pola pembayaran pinjaman (bulanan, mingguan, tidak teratur, dll.)
+ `partner_id`:	ID mitra lokal yang memfasilitasi pinjaman
+ `borrower_genders`:	Jenis kelamin peminjam (Laki-laki, Perempuan, atau Campuran)

# 🎯 Tujuan Analisis

- Mengidentifikasi aktivitas yang paling sering menerima pinjaman dan memiliki potensi pengembalian yang baik.
- Menganalisis pola pembayaran berdasarkan interval pengembalian (mingguan, bulanan, dll.).
- Menentukan durasi pinjaman yang ideal untuk mengurangi risiko gagal bayar.
- Melihat distribusi pinjaman berdasarkan negara dan sektor ekonomi.
- Memberikan rekomendasi aktivitas mana yang bisa menjadi prioritas dalam pemberian pinjaman.

# 🔍 Hasil yang Diharapkan

✅ Wawasan tentang aktivitas dengan jumlah pinjaman terbesar, yang dapat menjadi fokus bagi investor atau pemberi pinjaman.
 
✅ Pola pembayaran yang paling umum dan efektif, yang dapat membantu menentukan skema pembayaran terbaik.

✅ Identifikasi durasi pinjaman terbaik untuk meminimalkan risiko gagal bayar.

✅ Analisis pinjaman berdasarkan negara, untuk melihat peluang dan tantangan dalam ekosistem Kiva.

✅ Visualisasi data di Tableau, untuk membantu pengambilan keputusan berbasis data.

# 📊 Dashboard Tableau

Untuk melihat visualisasi lengkap hasil analisis, silakan kunjungi dashboard Tableau Public berikut:

🔗 https://public.tableau.com/app/profile/abednego.andries/viz/KivaLendingBusinessAnalysis/MainMenu

Dashboard ini mencakup:

✅ Timeline `funded amount` berdasarkan `sector` bisnis

✅ Analisis pola pembayaran berdasarkan `repayment_interval`

✅ Persentase pinjaman dipenuhi berdasarkan `sector` bisnis

✅ Analisis sebaran pinjaman, dana dipinjamkan, dan jumlah partner penyalur dana pinjaman di berbagai negara

✅ Analisis tentang `activity` bisnis mana yang memeiliki rata-rata tenor pembayaran paling cepat berdasarkan `repayment_interval`

