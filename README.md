# task1-mall-customers-cleaning
Data cleaning and preprocessing project for internship task.
# 🧹 Task 1 Internship Task Overview
As part of the Data Analyst Internship, this task focuses on cleaning and preparing a raw dataset for analysis using Python (Pandas).

### ✅ Dataset Used
- Mall Customer Segmentation Data (Kaggle)
- Original file: `Mall_Customers.csv`

## 🔧 Tools & Libraries
- Python
- Pandas
- Seaborn (for outlier visualization)

## 📌 Steps Performed
1. **Loaded Dataset**  
   Used `pandas.read_csv()` to read the CSV file.

2. **Checked for Missing Values**  
   Used `.isnull().sum()` and handled missing values using forward fill (`.fillna(method='ffill')`).

3. **Removed Duplicates**  
   Used `.drop_duplicates()` to ensure unique records.

4. **Standardized Column Names**  
   Converted all column headers to lowercase and snake_case using `str.replace` and `str.lower()`.

5. **Standardized Text Values**  
   Cleaned inconsistent gender entries using `.str.capitalize()`.

6. **Data Type Fixes**  
   Ensured correct data types for columns like age (`int`) and checked data integrity.

7. **Outlier Detection**  
   Visualized numerical columns using boxplots (`seaborn.boxplot()`).

8. **Saved the Cleaned Dataset**  
   Output saved to `Mall_Customers_Cleaned.csv`.

## 📤 Submission
Repository includes:
- 📄 `Mall_Customers.csv`
- 🧠 `task1_data_cleaning.py`
- 📝 `README.md`
