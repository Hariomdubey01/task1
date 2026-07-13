This repository contains my internship Task 1 submission for cleaning and preparing the **Hotel Booking Demand dataset**.  
The project demonstrates data wrangling, feature engineering, and documentation skills.

# 🏨 Hotel Booking Demand - Data Cleaning & Preprocessing

## 📌 Overview

This repository presents an end-to-end **data cleaning and preprocessing pipeline** for the **Hotel Booking Demand Dataset** using Python. The project focuses on transforming raw hotel booking data into a clean, consistent, and analysis-ready dataset through data quality assessment, feature engineering, and comprehensive documentation.

The cleaned dataset is suitable for **Business Intelligence, Data Analytics, Machine Learning, and Data Visualization** projects.

---

## 📂 Repository Contents

| File                                  | Description                                                                |
| ------------------------------------- | -------------------------------------------------------------------------- |
| **Hotel_Bookings_Cleaning.ipynb**     | Complete Jupyter Notebook containing the end-to-end data cleaning workflow |
| **hotel_bookings.csv**                | Original raw dataset                                                       |
| **sample_hotel_bookings.csv**         | Sample of the raw dataset for quick preview                                |
| **cleaned_hotel_bookings.csv**        | Final cleaned and preprocessed dataset                                     |
| **sample_cleaned_hotel_bookings.csv** | Preview of the cleaned dataset                                             |
| **data_dictionary_with_examples.csv** | Data dictionary with feature descriptions and sample values                |
| **data_dictionary.xlsx**              | Professionally formatted data dictionary                                   |

---

## 🛠️ Data Cleaning Process

The following preprocessing steps were performed:

* ✔ Handled missing values using appropriate imputation techniques.
* ✔ Removed irrelevant and highly sparse columns.
* ✔ Eliminated duplicate records.
* ✔ Standardized categorical values for consistency.
* ✔ Merged fragmented date columns into a single **arrival_date** field.
* ✔ Engineered new features:

  * `total_guests`
  * `stay_length`
  * `is_weekend`
* ✔ Detected and treated outliers using the **Interquartile Range (IQR)** method.
* ✔ Generated a comprehensive **Data Dictionary** with column descriptions and examples.

---

## 📊 Dataset Information

| Attribute         | Value                |
| ----------------- | -------------------- |
| Dataset           | Hotel Booking Demand |
| Original Records  | 119,390              |
| Original Features | 33                   |
| Cleaned Records   | 87,377               |
| Cleaned Features  | 31                   |

---

## 💻 Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook
* OpenPyXL

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Data Preprocessing
* Feature Engineering
* Missing Value Imputation
* Outlier Detection
* Data Validation
* Python Programming
* Pandas
* NumPy

---

## 📈 Workflow

```text
Raw Dataset
      │
      ▼
Data Inspection
      │
      ▼
Missing Value Treatment
      │
      ▼
Duplicate Removal
      │
      ▼
Data Standardization
      │
      ▼
Feature Engineering
      │
      ▼
Outlier Treatment
      │
      ▼
Clean Dataset
```

---

## 📊 Business Applications

The cleaned dataset can be used for:

* Business Intelligence Dashboards
* Customer Segmentation
* Booking Cancellation Analysis
* Revenue Analytics
* Hotel Performance Analysis
* Demand Forecasting
* Machine Learning Models

---

## 📚 Dataset Source

**Hotel Booking Demand Dataset**

https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Hariomdubey01/task1.git
```
