# Analisis Dataset Sakila Menggunakan R Markdown dan SQL

Project ini merupakan analisis data menggunakan dataset Sakila dengan pendekatan SQL, eksplorasi data, visualisasi, dan analisis statistik non-parametrik menggunakan R.

Dataset Sakila merupakan sample database resmi dari MySQL yang merepresentasikan sistem rental film DVD dengan berbagai tabel seperti customer, rental, payment, inventory, film, dan store.

---

## Deskripsi Project

Analisis dilakukan untuk mengeksplorasi pola transaksi rental film serta hubungan antara rating film, pembayaran pelanggan, dan performa toko rental.

Project ini mencakup:

- Pengambilan data menggunakan SQL Query
- Data preprocessing menggunakan R
- Exploratory Data Analysis (EDA)
- Visualisasi data
- Analisis statistik inferensial
- Pembuatan laporan HTML menggunakan R Markdown
- Custom styling menggunakan HTML dan CSS

---

## Dataset

Dataset yang digunakan adalah Sakila Sample Database dari MySQL.

[View Dataset Sakila](https://dev.mysql.com/doc/index-other.html)


---

## Deployment

Klik [Laporan HTML](https://achmadsolikhin-web.github.io/analisis-dataset-sakila) untuk melihat hasil analisis.

Klik [Repository GitHub](https://github.com/achmadsolikhin-web/analisis-dataset-sakila) untuk melihat repository github.

---

## Software yang Digunakan

- R
- R Markdown
- SQL
- HTML
- CSS
- ggplot2
- dplyr
- DBI

---

## Struktur Project

```text
analisis-dataset-sakila/
│
├── data/
│   └── sakila.db
├── assets/
│   └── erd.png
├── SIM_CM1_D_M0725023.Rmd
├── style.css
├── index.html
├── analisis-dataset-sakila.Rproj
├── README.md
└── .gitignore
```

---

## Analisis yang Dilakukan

### Exploratory Data Analysis

- Summary statistik
- Distribusi data
- Analisis pola transaksi
- Visualisasi variabel

### Analisis Statistik

- Kruskal-Wallis Test
- Mann-Whitney Test
- Analisis hubungan variabel
- Perbandingan performa antar kategori

---

## Cara Menjalankan Project

1. Clone repository

```bash
git clone https://github.com/achmadsolikhin-web/analisis-dataset-sakila.git
```

2. Buka file `.Rproj`

3. Install package yang dibutuhkan

```r
install.packages(c(
  "rmarkdown",
  "tidyverse",
  "DBI",
  "RSQLite",
  "ggplot2",
  "kableExtra"
))
```

4. Render R Markdown

```r
rmarkdown::render("analysis.Rmd")
```

---

## Output

Output menghasilkan:

- Laporan HTML
- Visualisasi data
- Analisis statistik
- Interpretasi hasil analisis

---

## Author

Achmad Solikhin  
M0725023  
Universitas Sebelas Maret
