# Profitability & Discount Impact Analysis Dashboard

## Project Overview

Proyek ini bertujuan untuk menganalisis profitabilitas perusahaan retail dengan memanfaatkan data transaksi penjualan Superstore. Analisis dilakukan menggunakan Python untuk proses data preparation dan exploratory data analysis (EDA), serta Power BI untuk membangun dashboard interaktif yang dapat membantu memahami faktor-faktor yang mempengaruhi profit perusahaan. Fokus utama proyek ini adalah mengevaluasi dampak pemberian diskon terhadap profit, mengidentifikasi kategori dan produk yang paling menguntungkan, serta memahami performa penjualan berdasarkan wilayah dan periode waktu tertentu.

## Business Problem

Dalam industri retail, diskon sering digunakan sebagai strategi untuk meningkatkan penjualan dan menarik pelanggan. Namun, pemberian diskon yang tidak terkontrol dapat menurunkan profit bahkan menyebabkan kerugian. Oleh karena itu, perusahaan perlu memahami bagaimana hubungan antara diskon dan profitabilitas, produk mana yang memberikan kontribusi keuntungan terbesar, wilayah mana yang memiliki performa terbaik, serta bagaimana tren profit berkembang dari waktu ke waktu. Melalui analisis ini, diharapkan perusahaan dapat mengambil keputusan bisnis yang lebih efektif dan berbasis data.

## Dataset Information

Dataset yang digunakan adalah Superstore Dataset yang diperoleh dari Kaggle. Dataset ini berisi 9.994 baris dan 21 kolom yang mencakup informasi transaksi penjualan, pelanggan, produk, wilayah, diskon, dan profit selama periode 2014 hingga 2017. Data ini memberikan gambaran menyeluruh mengenai aktivitas bisnis perusahaan sehingga sangat sesuai digunakan untuk analisis profitabilitas dan evaluasi strategi penjualan.

## Data Understanding

Pada tahap awal, dilakukan pemahaman terhadap struktur dataset dengan mengidentifikasi tipe data, fungsi setiap variabel, serta hubungan antar kolom yang relevan dengan tujuan analisis. Variabel utama yang digunakan dalam proyek ini meliputi Sales, Profit, Discount, Category, Sub-Category, Product Name, Region, State, dan Order Date. Tahap ini penting untuk memastikan bahwa seluruh data yang digunakan dapat mendukung proses analisis dan menghasilkan insight yang sesuai dengan kebutuhan bisnis.

## Data Preparation

Tahap data preparation dilakukan menggunakan Python untuk memastikan kualitas data sebelum digunakan dalam proses visualisasi dan analisis. Proses ini mencakup pemeriksaan tipe data, pengecekan missing values, validasi data duplikat, serta pembersihan data yang diperlukan. Selain itu, dilakukan proses feature engineering untuk menghasilkan variabel tambahan yang dapat membantu analisis, seperti Profit Ratio untuk mengukur tingkat profitabilitas, Discount Category untuk mengelompokkan tingkat diskon, serta Profit Status untuk mengidentifikasi transaksi yang menghasilkan keuntungan atau kerugian. Tahapan ini sangat penting karena kualitas data yang baik akan menghasilkan analisis yang lebih akurat dan dapat dipercaya.

## Exploratory Data Analysis (EDA)

Setelah data dipersiapkan, dilakukan exploratory data analysis menggunakan Python untuk memahami pola-pola yang terdapat dalam data. Analisis awal menunjukkan bahwa kategori Technology memiliki profit tertinggi dibandingkan kategori lainnya, sedangkan Furniture menghasilkan profit yang relatif rendah. Selain itu, ditemukan bahwa profit cenderung menurun ketika tingkat diskon meningkat. Analisis juga menunjukkan bahwa wilayah West memberikan kontribusi profit terbesar dibandingkan region lainnya. Temuan-temuan ini menjadi dasar dalam penyusunan dashboard dan analisis lebih lanjut menggunakan Power BI.

## Dashboard Development

Dashboard interaktif dibangun menggunakan Power BI untuk menyajikan hasil analisis secara visual dan mudah dipahami oleh pengguna. Dashboard terdiri dari berbagai visualisasi yang menampilkan performa profit berdasarkan kategori produk, sub-category, wilayah penjualan, tren profit dari waktu ke waktu, performa produk terbaik dan terburuk, serta hubungan antara diskon dan profitabilitas. Selain itu, dashboard juga dilengkapi dengan KPI utama seperti Total Sales, Total Profit, Average Discount, dan Profit Ratio untuk memberikan gambaran cepat mengenai kondisi bisnis perusahaan.

## Analysis Results

Hasil analisis menunjukkan bahwa kategori Technology merupakan kontributor profit terbesar perusahaan, sedangkan Furniture memiliki profit terendah. Pada tingkat sub-category, Copiers, Phones, dan Accessories menjadi penyumbang profit tertinggi, sementara Tables dan Bookcases mengalami kerugian yang cukup signifikan. Dari sisi geografis, region West menghasilkan profit tertinggi, sedangkan region Central memiliki profit paling rendah. Analisis tren menunjukkan bahwa profit perusahaan cenderung meningkat selama periode pengamatan meskipun terdapat beberapa fluktuasi. Selain itu, ditemukan bahwa produk Canon imageCLASS memberikan profit terbesar, sedangkan Cubify CubeX 3D Printer menghasilkan kerugian terbesar.

Analisis terhadap dampak diskon menunjukkan adanya hubungan negatif antara tingkat diskon dan profitabilitas perusahaan. Profit ratio tertinggi diperoleh pada transaksi tanpa diskon dan terus menurun seiring meningkatnya tingkat diskon. Pada kategori High Discount, profit ratio bahkan menjadi negatif, yang menunjukkan bahwa pemberian diskon yang terlalu tinggi dapat mengurangi keuntungan perusahaan dan meningkatkan risiko kerugian.

## Business Recommendations

Berdasarkan hasil analisis, perusahaan disarankan untuk lebih fokus pada kategori dan produk yang memiliki profit tinggi seperti Technology, Copiers, dan Phones. Selain itu, strategi pemberian diskon perlu dievaluasi karena diskon yang terlalu tinggi terbukti menurunkan profitabilitas perusahaan. Produk dan sub-category yang mengalami kerugian seperti Tables dan Bookcases juga perlu dievaluasi lebih lanjut untuk menentukan strategi harga dan promosi yang lebih efektif. Perusahaan juga dapat mengadopsi strategi penjualan yang berhasil diterapkan di region West untuk meningkatkan performa di wilayah lain. Dalam pengambilan keputusan bisnis ke depan, profit ratio dapat digunakan sebagai indikator utama untuk mengevaluasi efektivitas program diskon dan strategi penjualan.

## Conclusion

Proyek ini menunjukkan bahwa profitabilitas perusahaan dipengaruhi oleh berbagai faktor, terutama kategori produk, wilayah penjualan, dan tingkat diskon yang diberikan. Kategori Technology terbukti menjadi sumber keuntungan terbesar perusahaan, sementara beberapa produk dalam kategori Furniture masih mengalami kerugian. Hasil analisis juga membuktikan bahwa peningkatan diskon tidak selalu menghasilkan keuntungan yang lebih besar, bahkan cenderung menurunkan profit dan profit ratio perusahaan. Dengan menggabungkan proses data preparation menggunakan Python dan visualisasi interaktif menggunakan Power BI, proyek ini berhasil memberikan insight yang dapat membantu perusahaan dalam meningkatkan profitabilitas dan mendukung pengambilan keputusan bisnis yang lebih efektif dan berbasis data.
