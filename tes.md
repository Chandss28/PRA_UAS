# 1. Latar Belakang
Di tengah perkembangan olahraga yang semakin maju, penting bagi setiap organisasi untuk mencari dan mengembangkan bibit-bibit muda yang potensial, terutama di cabang olahraga yang berkompetisi di level internasional. Perusahaan Anda bergerak dalam bidang pelatihan olahraga, dengan fokus utama pada pengembangan atlet berbakat untuk bertanding di liga atau turnamen baik di tingkat nasional maupun internasional. Dengan adanya kebijakan pemerintah terbaru yang fokus pada pencarian bibit muda, perusahaan memiliki kesempatan untuk berperan lebih besar dalam mencetak atlet-atlet berprestasi. Oleh karena itu, dibutuhkan sebuah sistem yang efisien untuk manajemen data atlet, penjadwalan latihan, dan evaluasi kinerja atlet.

# 2. Identifikasi Masalah
Beberapa masalah yang dihadapi oleh perusahaan dalam mengelola atlet dan kegiatan pelatihan adalah sebagai berikut:

1. Manajemen Data Atlet yang Tidak Tersentralisasi: Data terkait atlet, termasuk identitas, program latihan, dan penilaian kinerja, masih tersebar di berbagai tempat.
2. Penjadwalan Latihan yang Kurang Efektif: Terkadang jadwal latihan tumpang tindih dengan pertandingan atau kegiatan lain.
3. Evaluasi dan Penilaian Kinerja Atlet yang Kurang Terstruktur: Tidak ada sistem yang terstruktur untuk menilai dan memberikan umpan balik mengenai kinerja atlet secara berkala.
4. Kesulitan dalam Melacak Progres Atlet: Pelatih kesulitan melacak perkembangan atlet dari waktu ke waktu dan menyesuaikan program latihan sesuai kebutuhan.

# 3. Rumusan Masalah
Berdasarkan identifikasi masalah di atas, rumusan masalah yang ingin diselesaikan adalah sebagai berikut:

1. Bagaimana cara mengelola data pribadi dan program latihan atlet secara efisien dan terpusat?
2. Bagaimana cara menyusun jadwal latihan yang efisien agar tidak bertabrakan dengan pertandingan?
3. Bagaimana cara melakukan evaluasi kinerja atlet secara objektif dan berkelanjutan?
4. Bagaimana cara memantau perkembangan atlet dan menyesuaikan program latihan sesuai dengan hasil evaluasi?

# 4. Tujuan Penelitian
Tujuan dari penelitian ini adalah untuk merancang dan mengimplementasikan sebuah sistem yang dapat:

1. Menyimpan dan mengelola data pribadi serta program latihan atlet secara terpusat.
2. Menyusun jadwal latihan yang terintegrasi dengan jadwal pertandingan.
3. Melakukan penilaian kinerja atlet secara objektif menggunakan metrik teknik, fisik, dan psikologis.
4. Memberikan feedback dan saran yang berguna bagi pelatih dan atlet untuk meningkatkan performa.

# 5. Metode Analisis yang Lebih Mendalam:
Metode Fishbone (Ishikawa) yang Lebih Komprehensif:
1. Sumber Daya Manusia (SDM):
    * Pelatih dan staf yang tidak terlatih dalam teknologi terbaru atau teknik evaluasi berbasis data.
    * Atlet yang belum mengerti pentingnya aspek mental dalam prestasi olahraga.
2. Metode Latihan:
    * Kurikulum pelatihan yang tidak terstruktur dan tidak memiliki penyesuaian berdasarkan data perkembangan atlet.
    * Tidak ada program pelatihan mental yang cukup mendalam untuk atlet.
3. Lingkungan:
    * Fasilitas latihan yang tidak merata, terutama di daerah-daerah yang lebih jauh.
    * Kondisi tempat latihan yang kurang ideal untuk memaksimalkan konsentrasi atlet.
4. Proses:
    * Pengelolaan waktu yang kurang efektif antara latihan dan pertandingan, menyebabkan atlet kelelahan.
    * Sistem evaluasi yang tidak berkelanjutan dan tidak cukup spesifik untuk setiap atlet.
5. Material:
    * Peralatan latihan yang terbatas atau kurang tepat untuk melatih keterampilan teknis yang dibutuhkan.
    * Teknologi yang belum dimanfaatkan sepenuhnya dalam proses pelatihan.

# 6. Perancangan Sistem yang Diperluas
1. Modul Manajemen Atlet:
 * 1. Data Pribadi Atlet: Menyimpan data seperti nama, usia, riwayat kesehatan, dan status fisik.
 * 2. Evaluasi Kinerja: Sistem penilaian yang memberikan skor berdasarkan teknik, fisik, dan mental atlet.
 * 3. Penyesuaian Program Pelatihan: Sistem yang memungkinkan pelatih untuk merancang program pelatihan yang disesuaikan dengan kekuatan dan kelemahan atlet.
2. Modul Penjadwalan:
 * 1. Jadwal Latihan dan Pertandingan: Manajemen waktu yang efisien antara sesi latihan dan pertandingan.
 * 2. Pengingat dan Notifikasi: Sistem pemberitahuan untuk mengingatkan atlet tentang jadwal dan tugas latihan.
3. Sistem Penilaian dan Evaluasi:
 * 1. Evaluasi Teknik: Menggunakan teknologi analisis video atau sensor untuk memantau teknik tembakan atlet.
 * 2. Evaluasi Mental: Menggunakan psikometri atau survei untuk mengukur kesejahteraan mental atlet, termasuk tingkat stres, fokus, dan motivasi.
4. Modul Fasilitas:
 * 1. Pencatatan Fasilitas yang Tersedia: Daftar tempat latihan yang dapat diakses oleh atlet dan fasilitas yang dimiliki.
 
# *6.1. ERD (Entity Relationship Diagram):
Berikut adalah ERD untuk menggambarkan hubungan antar entitas dalam sistem ini:
![alt text](<Screenshot 2025-01-30 211034.png>)

# *6.2. Flowchart:
Flowchart berikut menunjukkan alur sistem secara umum, dari pemilihan atlet hingga penilaian dan pemberian program latihan:
![alt text](<Screenshot 2025-01-30 212637.png>)

# *6.3. Use Case:
Use case diagram berikut menggambarkan interaksi antara aktor (pelatih dan atlet) dan sistem:

![alt text](<Screenshot 2025-01-30 212717.png>)

# *6.4. Susunan Database:
Berikut adalah struktur tabel yang digunakan untuk menyimpan data dalam sistem ini:
- Tabel Atlet:

![alt text](<Screenshot 2025-01-30 212758.png>)

- Tabel program:

![alt text](<Screenshot 2025-01-30 212830.png>)

- Tabel penilaian:

![alt text](<Screenshot 2025-01-30 212852.png>)

- Tabel jadwal_latihan:

![alt text](<Screenshot 2025-01-30 212919.png>)

- Tabel pertandingan:

![alt text](<Screenshot 2025-01-30 212937.png>)

# 7. Implementasi Teknologi yang Lebih Rinci:
Sistem ini akan dikembangkan menggunakan Laravel, Docker, dan MySQL.
- Laravel:
Laravel digunakan untuk mengembangkan backend dan frontend sistem. Framework ini menawarkan banyak fitur built-in seperti sistem autentikasi, routing, dan pengelolaan database yang efisien, yang akan sangat membantu dalam membangun sistem yang aman dan terstruktur.
- Docker:
Docker digunakan untuk mengelola lingkungan pengembangan secara terisolasi. Dengan menggunakan Docker, pengembangan aplikasi dapat dilakukan di lingkungan yang seragam dan dapat dipindahkan dengan mudah antar mesin pengembang.
- Konfigurasi Docker untuk Laravel dan MySQL:

![alt text](<Screenshot 2025-01-30 213625.png>)