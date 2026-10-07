# Data Cleaning Utility

## 📌 Project Overview

This project was completed as part of the **Syntecxhub Data Science Internship**.

The objective of this project is to create a simple and reusable **Data Cleaning Utility** that prepares raw datasets for further analysis and machine learning.

The utility performs important data-cleaning operations such as handling missing values, correcting data types, parsing dates, removing duplicate records, and standardizing column names.

---

## 🎯 Objectives

* Detect and handle missing values
* Correct incorrect data types
* Parse and standardize date values
* Remove duplicate records
* Standardize column names
* Generate a cleaned dataset
* Maintain a cleaning log
* Generate a summary of the data-cleaning process

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **Google Colab / Jupyter Notebook**
* **CSV files**

---

## 🔧 Data Cleaning Process

The project follows these main steps:

### 1. Load Dataset

The raw dataset is loaded using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

### 2. Check Data Quality

The dataset is checked for:

* Missing values
* Duplicate rows
* Incorrect data types
* Column names
* Basic dataset information

### 3. Handle Missing Values

Missing values are identified and handled using appropriate methods such as:

* Filling missing values
* Replacing invalid values
* Removing rows where necessary

### 4. Fix Data Types

Incorrect data types are converted into appropriate formats.

For example:

* Numeric columns → numeric data types
* Date columns → datetime format
* Categorical columns → standardized values

### 5. Parse Dates

Date columns are converted into a proper datetime format so that they can be used correctly during analysis.

### 6. Remove Duplicates

Duplicate records are identified and removed to improve data quality.

### 7. Standardize Column Names

Column names are cleaned and standardized to make them easier to work with in Python.

For example:

```text
Student Name → student_name
Date of Birth → date_of_birth
```

### 8. Final Quality Check

After cleaning, the dataset is checked again for:

* Missing values
* Duplicate records
* Data types
* Column names
* Overall dataset quality

---

## 📂 Project Files

| File                   | Description                                                  |
| ---------------------- | ------------------------------------------------------------ |
| `cleaned_dataset.csv`  | Final cleaned dataset                                        |
| `cleaning_log.csv`     | Record of cleaning operations performed                      |
| `cleaning_summary.csv` | Summary of the data-cleaning process                         |
| `README.md`            | Project documentation                                        |
| `data_cleaning.ipynb`  | Python/Colab notebook containing the complete implementation |

---

## 📊 Output

The project produces:

1. A cleaned dataset ready for further analysis
2. A cleaning log documenting the changes
3. A summary containing information about the cleaning process

---

## 💡 Key Learning Outcomes

Through this project, I learned:

* How to work with datasets using Pandas
* How to identify data-quality problems
* How to handle missing values
* How to correct data types
* How to work with date columns
* How to remove duplicate records
* How to standardize column names
* How to perform final data-quality validation
* How to save cleaned data for further use

---

## 👩‍💻 Internship

**Organization:** Syntecxhub
**Domain:** Data Science
**Project:** Data Cleaning Utility
**Task:** Project 3

This project was completed as part of the **Syntecxhub Data Science Internship Program**.

---

## 📌 Conclusion

The Data Cleaning Utility successfully prepares raw data by identifying and resolving common data-quality issues. The resulting cleaned dataset can be used for further **data analysis, visualization, and machine learning tasks**.
