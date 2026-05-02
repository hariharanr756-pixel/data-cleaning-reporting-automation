# 📊 Data Cleaning & Reporting Automation

## 📌 Overview

This project demonstrates how to automate data cleaning and reporting workflows using Python. It focuses on handling real-world messy data, including missing values, duplicate records, and inconsistent formats.

---

## 🎯 Objectives

* Clean raw dataset
* Handle missing values and duplicates
* Standardize data format
* Generate summary reports
* Export cleaned dataset
* Visualize insights

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```
data-cleaning-project
│
├── data.csv
│
└── data_cleaning_automation.ipynb
│
├── output/
│   └── cleaned_data.csv
```

---

## ⚙️ Steps Performed

### 1. Data Loading

Loaded dataset using Pandas:

```python
df = pd.read_csv('sales_data.csv')
```

### 2. Data Inspection

* Checked structure using `df.info()`
* Identified missing values

### 3. Data Cleaning

* Removed missing values
* Removed duplicate records
* Standardized column names
* Converted date format

### 4. Data Analysis

* Category-wise sales summary
* City-wise sales summary

### 5. Visualization

* Bar chart for sales by category

### 6. Export

Saved cleaned dataset:

```python
df.to_csv('cleaned_data.csv', index=False)
```

---

## 📈 Sample Output

* Cleaned dataset with no missing values
* Aggregated sales reports
* Visual representation of data

---

## 🚀 How to Run

1. Open Anaconda Navigator
2. Launch Jupyter Notebook
3. Navigate to `notebooks` folder
4. Open `data_cleaning_automation.ipynb`
5. Run all cells

---

## 📌 Key Features

* Automated data cleaning workflow
* Handles missing and duplicate data
* Generates summary reports
* Easy to understand and beginner-friendly

---

## 📚 Learning Outcome

* Understanding of data preprocessing
* Hands-on experience with Pandas
* Data analysis and reporting skills
* Workflow automation concepts

---

## 👤 Author

HARI HARAN R

This project demonstrates efficient data cleaning and reporting techniques that are essential for real-world data analysis tasks.
