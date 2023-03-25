#akan mempelajari penggunaan python pada komputasi big data

# Praktikum komputasi big data

tugas komputasi big data

GUNADARMA UNIVERSITY - 2023
komputasi big data

- [x] [GOOGLE COLAB](https://colab.research.google.com/)
- [x] [JUPYTER NOTEBOOK](https://jupyter.org/try)
- [x] [hypercomputation gunadarma](https://hypercomputation-hub.gunadarma.ac.id/)
- [x] [webkumal komputasi big data](https://webkumal.com/tag/komputasi-big-data/)



## Analisis Data Set "Data Komponen Beton"

## Overview Dataset
"Data Komponen Beton".

Data set ini berisikan beberapa kategori sebagai berikut

1. **cement (kg)**: Jumlah semen dalam satu meter kubik campuran beton.
2. **slag (blast furnace slag, kg)**: Jumlah campuran slag dalam satu meter kubik campuran beton.
3. **ash (fly ash, kg)**: Jumlah abu terbang dalam satu meter kubik campuran beton.
4. **water (kg)**: Jumlah air dalam satu meter kubik campuran beton.
5. **superplastic (superplasticizer, kg)**: Jumlah superplastikizer dalam satu meter kubik campuran beton.
6. **coarseagg (coarse aggregate, kg)**: Jumlah agregat kasar dalam satu meter kubik campuran beton.
7. **fineagg (fine aggregate, kg)**: Jumlah agregat halus dalam satu meter kubik campuran beton.
8. **age (days, 1-365)**: Usia dalam hari pada waktu uji kekuatan beton.
9. **strength (Concrete compressive strength, MPa)**: Kekuatan tekan beton dalam satuan Megapascal.

## Univariate and Bivariate Analysis

### Univariate Analysis
1. Kolom **cement** memiliki rata-rata sebesar 281.17 dan standar deviasi sebesar 104.51.
2. Kolom **slag** memiliki rata-rata sebesar 73.89 dan standar deviasi sebesar 86.30.
3. Kolom **ash** memiliki rata-rata sebesar 54.19 dan standar deviasi sebesar 63.99.
4. Kolom **water** memiliki rata-rata sebesar 181.57 dan standar deviasi sebesar 21.35.
5. Kolom **superplastic** memiliki rata-rata sebesar 6.20 dan standar deviasi sebesar 5.97.
6. Kolom **coarseagg** memiliki rata-rata sebesar 972.92 dan standar deviasi sebesar 77.75.
7. Kolom **fineagg** memiliki rata-rata sebesar 773.58 dan standar deviasi sebesar 80.18.
8. Kolom **age** memiliki rata-rata sebesar 45.66 dan standar deviasi sebesar 63.17.
9. Kolom **strength** memiliki rata-rata sebesar 35.82 dan standar deviasi sebesar 16.71.

### Bivariate Analysis

#### Hubungan antara kolom cement dan strength
Dari scatter plot yang dihasilkan, terlihat bahwa semakin tinggi nilai kolom **cement**, semakin tinggi pula nilai kolom **strength**. Hal ini menunjukkan kekuatan beton sangat dipengaruhi oleh jumlah semen yang digunakan pada campuran beton.

#### Hubungan antara kolom water dan strength
Dari scatter plot yang dihasilkan, terlihat bahwa semakin rendah nilai kolom **water**, semakin tinggi pula nilai kolom **strength**. Hal ini menunjukkan kekuatan beton sangat dipengaruhi oleh jumlah air yang digunakan pada campuran beton.

#### Hubungan antara kolom age dan strength
Dari scatter plot yang dihasilkan, terlihat bahwa semakin tinggi nilai kolom **age**, semakin tinggi pula nilai kolom **strength**. Hal ini menunjukkan beton akan semakin mengeras, dan akhirnya mencapai kekuatan maksimal setelah beberapa minggu.