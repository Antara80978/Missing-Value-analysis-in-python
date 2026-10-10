# Task: Missing Value Analysis

## 📌 Description
This project demonstrates how to identify and analyze missing values in a dataset using Python, Pandas, and NumPy. It calculates the number and percentage of missing values in each column and identifies columns that require data cleaning.

## 🎯 Objectives
- Identify missing values in a dataset.
- Calculate missing-value counts for each column.
- Find the percentage of missing values in each column.
- Identify columns that require missing-value treatment.

## 🛠️ Technologies Used
- **Python** – Programming language
- **Pandas** – Data analysis and manipulation
- **NumPy** – Handling missing numerical values

## ⚙️ Implementation
The program creates a sample DataFrame containing missing values represented by `NaN`. It uses Pandas' `isnull()` and `sum()` functions to count missing values in each column. The missing-value percentage is calculated by dividing the missing count by the total number of rows and multiplying by 100. Finally, a summary DataFrame displays the missing counts and percentages and identifies the columns requiring treatment.

## 📊 Sample Dataset
The sample dataset contains the following columns:
- `PassengerId`
- `Survived`
- `Age`
- `Cabin`
- `Embarked`

Missing values are intentionally included in the `Age`, `Cabin`, and `Embarked` columns for analysis.

## 📈 Expected Output
The program displays:
1. A missing-value summary containing the count and percentage for each column.
2. A list of columns that contain missing values and may require treatment.

For the sample dataset, `Age` has 2 missing values (40%), `Cabin` has 3 (60%), and `Embarked` has 1 (20%).

## 💡 Key Learnings
- Understanding missing values in datasets.
- Using Pandas to detect and count missing data.
- Calculating missing-value percentages.
- Identifying columns that require data-cleaning operations.

## 🚀 Conclusion
This task helped me understand how to analyze missing values using Python, Pandas, and NumPy. Missing-value analysis is an important step in data preprocessing because it helps prepare datasets for further analysis and machine learning.

## 👩‍💻 Author
Antara Sarvade
