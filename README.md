# Data Cleaning & Structural Validation

## 📌 Project Overview

This project demonstrates the process of transforming raw and unstructured data into a clean, reliable, and analysis-ready dataset.

The Titanic dataset was used to perform data cleaning, structural validation, duplicate removal, missing value treatment, outlier detection, and data visualization using Python.

---

## 🎯 Objectives

* Identify and handle missing values
* Remove duplicate records
* Standardize inconsistent data formats
* Validate dataset structure and data types
* Detect and remove outliers
* Generate visual insights from cleaned data
* Export a cleaned dataset for further analysis

---

## 🛠 Technologies Used

* Python
* Pandas
* Matplotlib
* NumPy

---

## 📂 Project Structure

```text
Data-Cleaning-Structural-Validation/
│
├── task1.csv
├── titanic_cleaning.py
├── requirements.txt
├── README.md
│
└── output/
    ├── cleaned_titanic.csv
    ├── gender_distribution.png
    ├── age_distribution.png
    └── survival_count.png
```

---

## 🔍 Data Cleaning Steps

### 1. Data Loading

* Loaded the Titanic dataset using Pandas.

### 2. Missing Value Handling

* Filled missing values in the Age column using the mean.
* Filled missing values in the Embarked column using the mode.
* Removed the Cabin column due to excessive missing values.

### 3. Duplicate Removal

* Identified and removed duplicate records.

### 4. Data Standardization

* Removed unnecessary spaces from names.
* Converted gender values to lowercase for consistency.

### 5. Structural Validation

* Verified data types.
* Checked uniqueness of Passenger IDs.
* Removed invalid age values.

### 6. Outlier Detection

* Used the Interquartile Range (IQR) method to detect and remove Fare outliers.

### 7. Data Visualization

Generated the following visualizations:

* Gender Distribution
* Age Distribution
* Survival Count

### 8. Data Export

* Saved the cleaned dataset as `cleaned_titanic.csv`.

---

## 📊 Output Files

After execution, the following files are generated:

* cleaned_titanic.csv
* gender_distribution.png
* age_distribution.png
* survival_count.png

---

## ▶️ How to Run

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Program

```bash
python titanic_cleaning.py
```

---

## 📈 Features

✔ Missing Value Detection and Handling

✔ Duplicate Record Removal

✔ Structural Validation

✔ Data Type Validation

✔ Outlier Detection Using IQR

✔ Data Visualization

✔ Clean Dataset Export

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Data validation techniques
* Data quality improvement
* Exploratory data analysis
* Python data science libraries

---

## 👩‍💻 Author

Akshitha Yadavalli

GitHub: https://github.com/Akshitha-Yadavalli
