
*** Titanic Data Analysis Project
*** Project Overview

This project focuses on analyzing the Titanic dataset using Python and pandas.
The goal is to perform data cleaning, exploratory data analysis (EDA), and extract meaningful insights about passenger survival patterns.

The project also includes creating a custom dataset to demonstrate basic DataFrame construction.

---

## 🎯 Objectives

* Create a custom dataset using a dictionary
* Load and explore the Titanic dataset
* Perform data cleaning (handle missing values, remove duplicates)
* Conduct exploratory data analysis using pandas
* Analyze survival patterns using grouping and filtering
* Extract insights from the dataset

---

## 📂 Dataset

* **Custom Dataset:** Created manually using a Python dictionary
* **Titanic Dataset:** Sourced from Kaggle
  Path used in the project:

  ```
  /kaggle/input/datasets/yasserh/titanic-dataset/Titanic-Dataset.csv
  ```

---

## 🛠️ Tools & Libraries

* Python
* Pandas

---

## 🔷 Part 1: Custom Dataset

A custom dataset was created with the following features:

* PassengerId
* Survived
* Pclass
* Sex
* Age

This dataset contains 15 rows and is indexed using custom labels.

---

## 🔷 Part 2: Titanic Dataset Analysis

### 🔍 Data Exploration

* `.head()` → Preview dataset
* `.info()` → Data types and missing values
* `.describe()` → Statistical summary

---

### 🧹 Data Cleaning

* Filled missing values in:

  * Age → median
  * Embarked → mode
* Dropped the Cabin column due to excessive missing values
* Removed duplicate records

---

### 📊 Data Analysis

Used `groupby()` to analyze:

* Survival rate by gender
* Survival rate by passenger class
* Average age per class
* Survival rate by age groups (Child, Teen, Adult, Senior)

---

### 🔎 Filtering

* Female passengers who survived
* Children who survived
* First-class passengers with high survival probability

---

## 📈 Key Insights

* Females had a higher survival rate than males
* First-class passengers had the highest survival rate
* Children were more likely to survive compared to adults
* The highest survival group was female passengers in first class

---

## 🚀 How to Run the Project

1. Open Kaggle Notebook
2. Add the Titanic dataset
3. Upload or paste the notebook code
4. Run all cells sequentially

---

## ✅ Conclusion

This project demonstrates how to:

* Clean real-world data
* Perform exploratory data analysis
* Use pandas for grouping and filtering
* Extract meaningful insights from structured data
