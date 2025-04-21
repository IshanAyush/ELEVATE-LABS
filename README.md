# Task 1: Data Cleaning and Preprocessing

## 🧼 Objective
This task involves cleaning and preparing a raw dataset (`Mall_Customers.csv`) to make it suitable for analysis by:
- Handling missing values
- Removing duplicates
- Standardizing text values
- Renaming column headers
- Ensuring consistent data types

## 📁 Files
- `Mall_Customers.csv` – Original dataset
- `Mall_Customers_Cleaned.csv` – Cleaned output dataset
- `1.ipynb` – Python script used for cleaning

## 🛠 Tools Used
- Python
- pandas

## 🔧 Cleaning Steps Performed
1. **Removed duplicates** (none found).
2. **Standardized gender values** to lowercase (`'male'`, `'female'`).
3. **Renamed columns** for consistency:
   - Lowercase
   - Replaced spaces with underscores
4. **Verified data types** (all appropriate).
5. **Saved cleaned dataset** as a new CSV.

## 📊 Summary of Changes

| Step                | Description                                                  |
|---------------------|--------------------------------------------------------------|
| Duplicate Removal   | Checked and confirmed no duplicate rows were present         |
| Text Standardization| Normalized `Gender` values to lowercase                      |
| Column Renaming     | All column names changed to lowercase with underscores       |
| Data Types Check    | Verified data types: `int64` for numeric fields, `object` for text |
| Exported Output     | Final cleaned file saved as `Mall_Customers_Cleaned.csv`     |

## ▶ How to Run
1. Ensure `pandas` is installed:
