Latar Belakang
Dalam era e-commerce yang terus berkembang, pemahaman yang mendalam tentang perilaku pelanggan merupakan aset berharga bagi perusahaan seperti Amazon. Dengan data yang meliputi informasi penting seperti nama produk, kategori, harga, rating, dan ulasan pengguna, saya sebagai analis data memiliki kesempatan untuk menggali wawasan yang berharga. Dengan analisis yang teliti, tim data analyst bertujuan untuk mengidentifikasi pola pembelian yang mendasar, mengungkap preferensi produk yang paling diminati, dan memahami faktor-faktor yang memengaruhi keputusan pembelian. Dari sini, akan mengembangkan sistem rekomendasi yang dapat memberikan pengalaman belanja yang lebih personal dan memuaskan bagi pengguna Amazon. Dengan pendekatan ini, berharap dapat memberikan kontribusi yang signifikan dalam meningkatkan keunggulan kompetitif Amazon di pasar e-commerce yang semakin kompetitif ini.

Objektif
Tujuan dari proyek ini adalah untuk melakukan analisis data eksploratori dan menentukan kategori produk mana yang memiliki pendapatan tertinggi, kategori mana yang menawarkan diskon terbanyak, kategori mana yang memiliki keterlibatan pelanggan tertinggi, dan wawasan lainnya.

1. Identifikasi jumlah yang terjual di setiap kategori dan subkategori. Jumlah produk berbeda yang dijual per kategori dan subkategori merupakan indikasi yang baik tentang kategori dan subkategori mana yang lebih diminati pelanggan.

2. Identifikasi Kategori dan Subkategori dengan jumlah rating tertinggi.

3. Kategori dan Subkategori dengan Diskon Terbanyak : membandingkan diskon rata-rata antara kategori dan subkategori produk, untuk memahami tingkat diskon yang ditawarkan dalam setiap kategori dan subkategori.

4. Interaksi Pelanggan: Membuat visualisasi yang menunjukkan jumlah ulasan kategori dan subkategori dari jumlah ulasan per rating, untuk memahami tingkat interaksi pelanggan dengan produk dalam setiap kategori.

Goals
1. Visualisasi Pendapatan Kategori Produk: Mengidentifikasi kategori dan subkategori produk yang memberikan kontribusi terbesar terhadap pendapatan total Amazon, sehingga memungkinkan fokus pada area yang paling menguntungkan.

2. Analisis Diskon: Mengetahui kategori dan subkategori produk yang paling sering menawarkan diskon kepada pelanggan, serta memahami seberapa besar diskon yang diberikan dalam setiap kategori.

3. Analisis Interaksi Pelanggan: Memahami tingkat interaksi atau keterlibatan pelanggan dengan produk dalam setiap kategori berdasarkan jumlah ulasan yang diberikan, yang dapat membantu dalam menilai popularitas dan penerimaan produk oleh pelanggan.

Dataset
1. Pengumpulan Data
Dataset ini mencakup lebih dari 1K+ produk yang diambil berdasarkan kategorinya dari Situs Web Resmi Amazon. Ini berisi semua ulasan yang tersedia untuk setiap produk dengan kategori, harga aktual, peringkat, dll..

2. Periode Waktu
Data diambil pada bulan Januari 2023 dari Situs Web Resmi Amazon.

3. Fitur
product_id — ID Produk
product_name — Nama Produk
category — Kategori Produ
harga_diskon — Harga Diskon Produk
harga_aktual — Harga Aktual Produk
persentase_diskon — Persentase Diskon untuk Produk
rating — Peringkat Produk
rating_count — Jumlah orang yang memilih peringkat Amazon
about_product — Deskripsi tentang Produk
user_id — ID pengguna yang menulis ulasan untuk Produk
nama_pengguna — Nama pengguna yang menulis ulasan untuk Produk
review_id — ID dari ulasan pengguna
judul_ulasan — Ulasan singkat
review_content — Ulasan panjang — Ulasan panjang
img_link — Tautan Gambar Produk
product_link — Tautan Situs Web Resmi Produk

Analisis


Menentukan jumlah produk yang berbeda per kategori dan subkategori. Jumlah produk berbeda yang dijual per kategori dan subkategori merupakan indikasi yang baik tentang kategori dan subkategori mana yang lebih diminati pelanggan. Kategori dengan variasi produk yang lebih banyak yang dijual menunjukkan minat yang lebih besar pada kategori tersebut dibandingkan dengan kategori yang menjual beberapa produk yang berbeda.

Kategori “Elektronik”, “Komputer & Aksesori”, dan “Rumah & Dapur” memiliki jumlah produk berbeda yang paling banyak dijual. Masing-masing dari 3 kategori tersebut menjual 400 hingga 500 produk yang berbeda. Jumlah produk berbeda yang terjual menurun drastis untuk “Produk Kantor” yang menjual 31 produk berbeda. Kategori lainnya hanya menjual 1 hingga 2 produk yang berbeda.

Subkategori “Aksesoris & Periferal” dan “Peralatan Dapur & Rumah Tangga” memiliki jumlah produk berbeda yang paling banyak dijual. Ada kemungkinan subkategori Aksesoris & Periferal merupakan bagian dari kategori Komputer & Aksesoris. Subkategori Aplikasi Dapur & Rumah mungkin merupakan bagian dari kategori Elektronik, dan Rumah & Dapur



Peringkat rata-rata akan menunjukkan seberapa puas pelanggan dengan produk yang disediakan oleh setiap kategori atau subkategori.

Pelanggan yang membeli produk dari kategori “Produk Kantor” dan “Mainan & Permainan” menunjukkan kepuasan tertinggi secara keseluruhan (sekitar 4,3 bintang). Pelanggan yang membeli dari subkategori “Tablet” menunjukkan kepuasan tertinggi secara keseluruhan (4,6 bintang). Perbedaan antara peringkat kepuasan rata-rata tertinggi dan peringkat kepuasan rata-rata terendah adalah 0,5 hingga 0,8 bintang. Tidak ada kategori atau subkategori yang memiliki peringkat kepuasan keseluruhan di bawah 3,8 yang menunjukkan bahwa pelanggan puas dengan pembelian mereka di setiap kategori dan subkategori.



Untuk memahami berapa banyak pendapatan yang dihasilkan setiap kategori, data juga harus menyertakan kerangka waktu dan jumlah unit yang terjual. Namun, dengan menemukan harga rata-rata per produk dan jumlah produk yang berbeda yang terjual akan memberikan indikasi total pendapatan yang dihasilkan setiap kategori.

Kategori “Elektronik” memiliki harga rata-rata tertinggi per produk sebelum dan sesudah diskon. Harga rata-rata tertinggi kedua dan ketiga per produk sebelum diskon adalah kategori “Rumah & Dapur” dan “Mobil & Motor”. Rata-rata, kedua kategori tersebut memiliki produk dengan harga yang hampir sama. Setelah diskon diterapkan, kategori “Rumah & Dapur” dan “Mobil & Motor” bertukar tempat. Kategori “Rumah & Dapur” mungkin memiliki diskon yang lebih tinggi secara rata-rata dibandingkan dengan kategori “Mobil & Motor”.

Meskipun kategori “Komputer & Aksesoris” memiliki jumlah produk unik terbanyak kedua, harga rata-rata sebelum dan sesudah diskon untuk setiap produk lebih rendah dibandingkan dengan produk “Elektronik” dan “Rumah & Dapur”. Harga rendah untuk produk “Komputer & Aksesori” mungkin berkontribusi pada banyaknya variasi produk yang dijual dalam kategori tersebut

Mirip dengan menemukan harga rata-rata per kategori, subkategori menawarkan pandangan yang lebih mendalam tentang jenis produk yang dibeli pelanggan.

Subkategori “Laptop” dan “Tablet” memiliki harga rata-rata tertinggi per produk sebelum dan sesudah diskon. Meskipun “Laptop” dan “Tablet” memiliki harga rata-rata tertinggi per produk, kategori “Komputer dan Aksesori” memiliki harga rata-rata yang kecil per produk.

Tiga subkategori yang termasuk dalam kategori “Elektronik” dengan harga rata-rata tertinggi adalah “Home Theater, TV & Video”, “Ponsel & Aksesori”, dan “Teknologi yang Dapat Dipakai”.



Jumlah peringkat merupakan indikasi seberapa terlibatnya pelanggan dengan setiap kategori atau subkategori. Jumlah peringkat yang lebih tinggi menunjukkan bahwa lebih banyak pelanggan yang bersedia mengambil langkah ekstra untuk memberikan umpan balik tentang produk

Kategori “Alat Musik” dan subkategori “Dapur & Makan” memiliki jumlah pelanggan terbanyak yang memberi peringkat pada produk. Meskipun kategori “Alat Musik” memiliki jumlah rating rata-rata tertinggi, kategori tersebut hanya memiliki 2 produk unik. Hal ini menunjukkan bahwa 2 produk tersebut lebih populer di antara produk lain dalam kategori tersebut. Demikian pula, jumlah rating rata-rata untuk kategori “Mainan & Permainan” lebih tinggi daripada kategori “Rumah & Dapur”, meskipun “Mainan & Permainan” hanya memiliki 1 produk unik dan “Rumah & Dapur” memiliki 448 produk unik. Investigasi lebih lanjut tentang produk yang dijual di kategori “Alat Musik” dan “Mainan & Permainan” harus dilakukan untuk mengetahui apa yang membuat produk tersebut begitu populer di kategori masing-masing.

Rekomendasi
Meningkatkan Variasi Produk: Pertimbangkan untuk menambahkan lebih banyak variasi produk ke kategori yang memiliki variasi produk yang lebih sedikit untuk menarik lebih banyak pelanggan.
Analisis Lebih Lanjut: Lakukan analisis lebih lanjut pada produk yang dijual di kategori “Alat Musik” dan “Mainan & Permainan” untuk mengetahui apa yang membuat produk tersebut begitu populer.
Strategi Harga: Pertimbangkan strategi harga yang berbeda untuk kategori “Komputer & Aksesori” mengingat variasi produk yang banyak tetapi harga rata-rata yang lebih rendah.
Pertimbangkan Diskon: Pertimbangkan penerapan diskon yang lebih tinggi pada kategori dengan harga rata-rata yang lebih tinggi untuk menarik lebih banyak pelanggan.
Kesimpulan
Kategori “Elektronik”, “Komputer & Aksesori”, dan “Rumah & Dapur” memiliki variasi produk terbanyak, menunjukkan minat pelanggan yang lebih besar.
Pelanggan umumnya puas dengan pembelian mereka di semua kategori dan subkategori, dengan peringkat kepuasan keseluruhan tidak kurang dari 3,8.
Kategori “Elektronik” memiliki harga rata-rata tertinggi per produk sebelum dan sesudah diskon, yang mungkin berkontribusi pada pendapatan yang lebih tinggi.
Meskipun kategori “Komputer & Aksesori” memiliki variasi produk terbanyak, harga rata-rata produknya lebih rendah dibandingkan dengan kategori lain seperti “Elektronik” dan “Rumah & Dapur”.
Kategori “Alat Musik” dan subkategori “Dapur & Makan” memiliki jumlah pelanggan terbanyak yang memberi peringkat pada produk, menunjukkan tingkat keterlibatan pelanggan yang lebih tinggi.
Link : github , tableau , dataset , linkedin

