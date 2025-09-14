# Customer_Segmentation_Unsupervised_Learning
## Project Overview

This project focuses on **customer segmentation** using a retail dataset. The goal is to clean, analyze, and transform customer data into meaningful insights that can support marketing strategies and decision-making. The notebook demonstrates end-to-end steps of a typical data science workflow, including data preprocessing, exploratory analysis, and feature engineering for segmentation.

---

## Steps Performed in the Notebook

### 1. Importing Libraries

Essential Python libraries such as **pandas**, **numpy**, and visualization tools were imported to handle data manipulation, cleaning, and analysis.

### 2. Loading Datasets

Two datasets were used:

* **Online Retail dataset** (Excel format)
* **Mall Customers dataset** (CSV format)

Both were loaded into pandas DataFrames for processing.

### 3. Exploring the Data

* Used `.shape` to check dataset dimensions.
* Displayed `.head()` samples for an initial look at the data.
* Counted unique values per column.
* Listed the top 10 most frequent values for categorical features (e.g., `Country`).

### 4. Handling Missing Values

* Identified missing data using `.isnull().sum()`.
* Dropped rows with missing values in key columns (e.g., `Description`).
* Re-checked to confirm that null values were handled.

### 5. Detecting Unrealistic Values

* Checked for **zero or negative values** in numeric columns such as `Quantity` and `UnitPrice`.
* Ensured that only realistic transaction values remained in the dataset.

### 6. Feature Engineering

* Created **bins** for numeric features (e.g., `Quantity`) to group customers into ranges.
* Constructed new categorical variables based on numeric conditions, enabling more interpretable analysis.

### 7. Preparing Data for Segmentation

* Selected important numerical and categorical features.
* Processed data into a clean format for segmentation tasks (such as clustering or grouping customers).

---

## Key Learning Outcomes

* Gained hands-on experience in **data cleaning** and **preprocessing**.
* Learned to handle **missing values** and **outliers**.
* Applied **feature engineering** techniques to transform raw data into meaningful categories.
* Prepared data for **customer segmentation analysis**.

---

## How to Use This Notebook

1. Clone or download this repository.
2. Open the notebook in **Google Colab** or **Jupyter Notebook**.
3. Ensure the datasets (`Online Retail.xlsx` and `Mall_Customers.csv`) are available in the correct path.
4. Run cells step by step to reproduce the workflow.

---

## Project Significance

Customer segmentation helps businesses understand their customers better, enabling them to:

* Target marketing campaigns effectively.
* Improve customer satisfaction.
* Optimize product and service offerings.

This project demonstrates the **fundamental steps of preparing retail data for segmentation**, forming a strong foundation for more advanced modeling such as clustering (e.g., K-Means).

---
