# SWYNEX – Data Cleaning and Preparation

## Project Overview
This project focuses on cleaning and preparing the Netflix Movies and TV Shows dataset using Python. The objective is to identify and handle missing values, duplicate records, inconsistent text formatting, incorrect data types, and data quality issues.

## Dataset Information
- **Dataset:** Netflix Movies and TV Shows
- **Source:** [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Original Records:** 8,807
- **Original Columns:** 12
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## Tasks Performed
1. Loaded and inspected the original dataset.
2. Identified missing values and duplicate records.
3. Checked inconsistent whitespace in text columns.
4. Examined unique categorical values.
5. Visualized missing values.
6. Corrected misplaced duration values in the rating column.
7. Handled missing values using appropriate placeholders.
8. Standardized text formatting.
9. Converted date columns into datetime format.
10. Standardized duration values and units.
11. Validated the cleaned dataset.
12. Compared data quality before and after cleaning.

## Data Cleaning Results

| Metric | Before | After |
|---|---:|---:|
| Total Records | 8,807 | 8,807 |
| Total Columns | 12 | 14 |
| Missing Values | 4,307 | 10 |
| Duplicate Records | 0 | 0 |
| Missing Director | 2,634 | 0 |
| Missing Country | 831 | 0 |
| Missing Cast | 825 | 0 |
| Missing Rating | 4 | 0 |
| Missing Duration | 3 | 0 |

The remaining 10 missing values belong to the `date_added` column and were retained rather than replaced with fabricated dates.

## Project Structure
```text
SWYNEX-Data-Cleaning-Preparation/
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
├── outputs/
├── README.md
└── requirements