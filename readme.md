# Big Data Computation with Python

## Description
This repository contains materials and practical exercises for learning Python in the context of Big Data Computation. The focus is on analyzing and processing large datasets using various tools and techniques.

## Table of Contents
- [Overview](#overview)
- [Tools and Resources](#tools-and-resources)
- [Dataset Analysis](#dataset-analysis)
  - [Dataset Overview](#dataset-overview)
  - [Univariate Analysis](#univariate-analysis)
  - [Bivariate Analysis](#bivariate-analysis)
- [How to Run](#how-to-run)

## Overview
This project is part of the Big Data Computation course at Gunadarma University, 2023. It includes practical exercises and analysis of a concrete component dataset.

## Tools and Resources
- [GOOGLE COLAB](https://colab.research.google.com/)
- [JUPYTER NOTEBOOK](https://jupyter.org/try)
- [Hypercomputation Gunadarma](https://hypercomputation-hub.gunadarma.ac.id/)
- [Webkumal Big Data Computation](https://webkumal.com/tag/komputasi-big-data/)

## Dataset Analysis

### Dataset Overview
The dataset "Data Komponen Beton" includes the following categories:

1. **Cement (kg)**: Amount of cement in one cubic meter of concrete mix.
2. **Slag (blast furnace slag, kg)**: Amount of slag in one cubic meter of concrete mix.
3. **Ash (fly ash, kg)**: Amount of fly ash in one cubic meter of concrete mix.
4. **Water (kg)**: Amount of water in one cubic meter of concrete mix.
5. **Superplastic (superplasticizer, kg)**: Amount of superplasticizer in one cubic meter of concrete mix.
6. **Coarseagg (coarse aggregate, kg)**: Amount of coarse aggregate in one cubic meter of concrete mix.
7. **Fineagg (fine aggregate, kg)**: Amount of fine aggregate in one cubic meter of concrete mix.
8. **Age (days, 1-365)**: Age in days at the time of concrete strength testing.
9. **Strength (Concrete compressive strength, MPa)**: Compressive strength of concrete in Megapascals.

### Univariate Analysis
1. **Cement**: Mean = 281.17, Std Dev = 104.51
2. **Slag**: Mean = 73.89, Std Dev = 86.30
3. **Ash**: Mean = 54.19, Std Dev = 63.99
4. **Water**: Mean = 181.57, Std Dev = 21.35
5. **Superplastic**: Mean = 6.20, Std Dev = 5.97
6. **Coarseagg**: Mean = 972.92, Std Dev = 77.75
7. **Fineagg**: Mean = 773.58, Std Dev = 80.18
8. **Age**: Mean = 45.66, Std Dev = 63.17
9. **Strength**: Mean = 35.82, Std Dev = 16.71

### Bivariate Analysis

#### Relationship between Cement and Strength
A scatter plot shows that higher **cement** values correlate with higher **strength** values, indicating that concrete strength is significantly influenced by the amount of cement used.

#### Relationship between Water and Strength
A scatter plot shows that lower **water** values correlate with higher **strength** values, indicating that concrete strength is significantly influenced by the amount of water used.

#### Relationship between Age and Strength
A scatter plot shows that higher **age** values correlate with higher **strength** values, indicating that concrete hardens and reaches maximum strength after several weeks.

---

GUNADARMA UNIVERSITY - 2023 X Webkumal