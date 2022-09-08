# Exploratory-Data-Analysis
Exploratory Data Analysis Project on Python by Wila Arvia
# Introduction
di repository ini , saya akan meanmpilkan Exploratory Data Analysis (EDA) custumer churn pada dataset telco custumer churn
# Steps:
* Duplicated value check
* Missing value check 
* Statistical summaries of columns
* Univariate analysis 
* Bivariate analysis
* Overall summary/EDA findings

untuk detail nya dapat dilihat pada notebook di repositery ini

EDA Conclusion

* Data tidak terlalu memiliki masalah karna tidak mengandung missing value atau duplicate value hanya ada beberapa nilai yang kosong yang sudah berhasil di handle .
* Secara keseluruhan nilai minimum dan maximum masih masuk akal pada setiap kolomnya
* Pada umumnya data numerical penyebaran data nya tidak simetris.
* Dari boxplot dapat kita lihat bahwa ada outlier pada kolom `SeniorCitizen` dengan nilai 1 namun nilai pada outlier masih masuk akal dan tidak perlu dibersihkan
* Kolom `tenure`, `monthly charges`,`total charges` tidak simetris sehingga nantinya kita perlu merubahnya untuk mendekati distribusi normal
* Dalam hal variabel target, `senior citizen = 0` lebih sering dalam kumpulan data. Tapi, kondisi ketidakseimbangan TIDAK parah sehingga masih bisa diterima
* Dari heatmap kolom `tenure` dan `totalcharges` memiliki korelasi yang tinggi satu sama lain kita bisa memilih satu dari 2 itu untuk dilakukan modelling karena mereka redundan
* Pada paiplot kita dapat melihat sebaran data numerical terhadap churning seperti pada tenure penyebaran pelanggan yang churning lebih banyak pada nilai tenure yang kecil.
