# Task 2: Data Cleaning & Missing Value Handling

## 📌 Objective
The objective of this task is to perform data cleaning by identifying and handling missing values in real-world datasets. This task helps improve data quality and prepares the data for further analysis or machine learning models.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- GitHub (Version Control)

---

## 📊 Datasets Used
1. House Prices Dataset  
2. Medical Appointment No Shows Dataset  

---

## 🧹 Data Cleaning Steps Performed

### 1. Data Loading
- Loaded datasets using Pandas.
- Inspected dataset structure, data types, and shape.

### 2. Missing Value Identification
- Identified missing values using `isnull().sum()`.

### 3. Missing Data Visualization
- Visualized missing data patterns using simple bar charts.

### 4. Missing Value Imputation
- Numerical columns: Applied **median imputation**.
- Categorical columns: Applied **mode imputation**.

### 5. Handling High Missing Value Columns
- Removed columns having more than **40% missing values**.

### 6. Validation After Cleaning
- Rechecked missing values to ensure proper cleaning.
- Verified dataset structure and consistency.

### 7. Before vs After Comparison
- Compared dataset size and quality before and after cleaning.

### 8. Medical Appointment Dataset Observation
- The Medical Appointment No Shows dataset contained **no missing values**.
- The dataset was validated and saved without applying imputation.

---

## 📁 Project Folder Structure

Task-2-Data-Cleaning/
│
├── data/
│ ├── raw/
│ │ ├── house_prices.csv
│ │ └── medical_appointments.csv
│ │
│ └── cleaned/
│ ├── house_prices_cleaned.csv
│ └── medical_appointments_cleaned.csv
│
├── notebook/
│ └── Task2_Data_Cleaning_and_Missing_Value_Handling.ipynb
│
└── README.md
