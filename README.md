# Optimalisasi Layanan Transjakarta Berbasis Analisis Karakteristik Penumpang dan Pola Mobilitas
Capstone Modul 2 Purwadhika: Data Analysis Transjakarta

Proyek ini bertujuan untuk memberikan rekomendasi strategis bagi peningkatan kualitas layanan dan operasional TransJakarta melalui pendekatan data-driven. Analisis dilakukan terhadap data perjalanan penumpang selama bulan April 2023, mencakup demografi, waktu perjalanan, rute favorit, hingga metode pembayaran.

**LATAR BELAKANG**
TransJakarta sebagai sistem transportasi publik utama di Jakarta terus menghadapi tantangan dalam memenuhi kebutuhan mobilitas masyarakat yang dinamis. Untuk itu, diperlukan pendekatan berbasis data guna memahami karakteristik pengguna dan merumuskan kebijakan layanan yang lebih inklusif, efisien, dan tepat sasaran.

**RUMUSAN MASALAH**

Berdasarkan latar belakang dan eksplorasi data yang dilakukan, ditemukan beberapa rumusan masalah sebagai berikut:
1. Demografi gender penumpang yang didominasi oleh Perempuan.
2. Penumpang usia produktif mendominasi, sementara jumlah penumpang lansia masih sangat rendah.
3. Terjadi lonjakan jumlah penumpang pada jam-jam tertentu yang berisiko menimbulkan kepadatan layanan.
4. Jumlah perjalanan di akhir pekan yang jauh lebih rendah dibandingkan hari kerja.
5. JakCard menjadi metode pembayaran favorit para penumpang

**TUJUAN ANALISA**
1. Menyusun rekomendasi untuk peningkatan layanan berbasis gender.
2. Mengoptimalkan layanan berdasarkan kelompok usia penumpang, terutama lansia.
3. Menyesuaikan strategi operasional berdasarkan waktu dan pola kepadatan.
4. Meningkatkan intensitas penggunaan layanan di akhir pekan.
5. Memaksimalkan penggunaan metode pembayaran JakCard.

**KONDISI DATA & DATA CLEANING**
1. Dataset transjakarta ini memiliki 22 kolom dengan 37.900 baris data
2. Data dalam dataset ini merupakan data selama 1 bulan, yakni 1 April –  30 April 2023 
3. Terdapat 10 kolom numerikal & 12 kolom kategorikal
4. Beberapa kolom masih memiliki data kosong (missing value) yaitu corridorID, corridorName, tapInStops, tapOutStops, tapOutStopsName, tapOutStopsLat, tapOutStopsLon, stopEndSeq, tapOutTime, dan ‘payAmount. Data kosong pada kolom-kolom tersebut diwakili dengan NaN
5. Handling Missing value dilakukan dengan 2 cara: (1) Mengisi Data yang hilang dengan acuan data dari kolom lain, dan (2) Menghapus data yang masih kosong.

**RINGKASAN ANALISA DATA**
1. Demografi Gender

  •	Perempuan mendominasi di mayoritas layanan (Non-BRT, MikroTrans, RoyalTrans)
  •	Rekomendasi: Penambahan bus khusus wanita di 3 rute Non-BRT dan peningkatan keamanan
3. Demografi Usia
  •	Mayoritas penumpang: Millennial dan Gen Z
  •	Proporsi lansia sangat kecil (2%)
  •	Rekomendasi: Kampanye halte ramah lansia, peningkatan aksesibilitas, sosialisasi tarif gratis
4. Pola Perjalanan
  •	Weekday: Didominasi jam sibuk (06.00 & 17.00)
  •	Weekend: Jumlah perjalanan menurun drastis
  •	Rekomendasi: Program loyalitas akhir pekan untuk penumpang aktif
5. Analisis Rute
  •	Weekday: Rute komuter (Cibubur – Balai Kota, Tanah Abang)
  •	Weekend: Rute wisata (Ancol, Ragunan)
  •	Rekomendasi: Alokasi armada sesuai pola perjalanan
6. Metode Pembayaran
  •	JakCard Bank DKI paling populer (49%)
  •	Rekomendasi: Integrasi aplikasi TiJe dengan mobile banking & perluasan top-up JakCard

Link Tableau Dashboard: https://public.tableau.com/app/profile/muhammad.narendra.atma.ghifari/viz/DashboardTransjakarta_17440348739240/Beranda
