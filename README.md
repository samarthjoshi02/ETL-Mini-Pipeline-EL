# 🔄 ETL Mini Pipeline — Python (Task 14)

## 📌 Project Overview

This project demonstrates the implementation of a simple **ETL (Extract, Transform, Load) pipeline** using Python and pandas. The pipeline processes raw customer churn data, performs cleaning and transformations, and loads the processed data into structured CSV files and a SQLite database.

The objective is to understand how ETL workflows are used in real-world data analytics and data engineering environments.

---

## 🎯 ETL Process

### 1️⃣ Extract

* Loaded raw dataset from CSV file using pandas.

### 2️⃣ Transform

* Removed duplicates and missing values.
* Standardized column names.
* Created derived column (profit margin).
* Split dataset into multiple logical tables:

  * Customers
  * Usage
  * Churn

### 3️⃣ Load

* Exported processed tables as CSV files.
* Loaded tables into SQLite database.

### 4️⃣ Validation

* Verified row counts before and after transformation to ensure data consistency.

---

## 🛠 Tools & Technologies

* Python
* pandas
* SQLite
* Jupyter Notebook

---

## 📂 Project Structure

```
project/
│
├── raw/
│   └── data.csv
│
├── processed/
│   ├── customers.csv
│   ├── usage.csv
│   └── churn.csv
│
├── output/
│   └── database.sqlite
│
├── task14_etl.ipynb
└── README.md
```

---

## 📊 Tables Created

* **Customers** → Customer demographics and subscription details
* **Usage** → Customer activity and spending information
* **Churn** → Churn status and interaction history

---

## 🚀 Learning Outcomes

* Understanding ETL pipeline workflow
* Data cleaning and transformation using pandas
* Working with relational data structure
* Loading data into databases using SQLite
* Validating ETL outputs

---

## 👨‍💻 Author

Samarth Joshi

---

## ⭐ Conclusion

This project demonstrates how raw data can be transformed into structured datasets and stored in databases, enabling efficient analytics and decision-making.
