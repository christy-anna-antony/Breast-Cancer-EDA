# 🎗️ Breast Cancer Wisconsin — Exploratory Data Analysis

## Project Overview
End-to-end Exploratory Data Analysis on the Breast Cancer 
Wisconsin Diagnostic Dataset using Python.

## Dataset
- **Source:** UCI Machine Learning Repository
- **URL:** https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
- **Records:** 569 patients
- **Features:** 32 columns

## Project Structure
| File | Description |
|------|-------------|
| `wdbc.data` | Original raw dataset from UCI |
| `wdbc_cleaned.csv` | Cleaned dataset after Stage 1 |
| `Stage1_Data_Cleaning.ipynb` | Data cleaning notebook |
| `data_visualization.ipynb` | EDA and visualizations notebook |

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Stages
- Stage 1 — Data Cleaning & Pre-processing ✅
- Stage 2 — EDA & Visualizations ✅

## Key Insights
1. Malignant tumors are 44% larger than Benign tumors
2. Cell concavity is the strongest cancer predictor
3. Radius, area and perimeter are 99% correlated
4. Larger tumors show higher malignancy rate
5. Dataset is 62.7% Benign and 37.3% Malignant

## Citation
Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993).
Breast Cancer Wisconsin (Diagnostic). UCI ML Repository.
https://doi.org/10.24432/C5DW2B
