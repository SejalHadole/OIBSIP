# Data Cleaning — Cafe Sales Dataset

## Project Overview
This project focuses on cleaning a cafe sales dataset using Python and Pandas. The goal is to identify missing values, handle inconsistent entries, convert data types, and prepare the dataset for further analysis.

## Dataset Information
- **Original Rows:** 10,000
- **Original Columns:** 8
- **Duplicate Rows:** 0
- **Dataset:** Cafe Sales — Dirty Data for Cleaning Training

## Tools and Technologies
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## Data Cleaning Steps
1. Loaded the CSV dataset into Pandas.
2. Created a backup of the original dataset.
3. Checked dataset dimensions, column names, data types, missing values, and duplicate rows.
4. Replaced `ERROR` and `UNKNOWN` entries with missing values (`NaN`).
5. Converted `Quantity`, `Price Per Unit`, and `Total Spent` into numeric data types.
6. Converted `Transaction Date` into datetime format.
7. Checked whether `Total Spent` matched `Quantity × Price Per Unit` for rows with all three values available.
8. Removed rows missing essential fields: `Item`, `Quantity`, `Price Per Unit`, `Total Spent`, or `Transaction Date`.
9. Performed a final quality check.

## Results

| Metric | Result |
|---|---:|
| Original rows | 10,000 |
| Final rows retained | 7,382 |
| Rows removed | 2,618 |
| Columns retained | 8 |
| Duplicate rows in final dataset | 0 |
| Missing values in essential fields | 0 |

## Missing Values
Missing values remain in the `Payment Method` and `Location` columns. These were retained because they were not required for the current analysis.

## Output
The cleaned dataset is saved as `cleaned_cafe_sales.csv`.

## Conclusion
The dataset was cleaned by handling inconsistent entries, converting data types, checking total calculations, and removing records with missing essential information. The resulting dataset is ready for further exploratory data analysis.

## Author
Oasis Infobyte Data Analytics Internship Project
