# 📊 IBM HR Analytics ETL Pipeline using Power Query

## 📌 Project Overview

This project demonstrates an end-to-end **ETL (Extract, Transform, Load)** pipeline built using **Power Query** in Microsoft Power BI. The objective was to transform raw HR data into a clean, validated, and business-ready dataset suitable for reporting and analytical decision-making.

The project follows industry-standard ETL practices, including data profiling, cleaning, validation, transformation, feature engineering, and data preparation using the **IBM HR Analytics Employee Attrition & Performance** dataset.

---

# 🎯 Business Problem

Organizations rely on clean and reliable HR data to analyze workforce trends, employee attrition, salary distribution, and departmental performance. However, raw datasets often contain inconsistencies, unnecessary columns, formatting issues, and require transformation before they can be used for reporting.

This project focuses on preparing the dataset through a structured ETL process to improve data quality and ensure it is ready for business intelligence and analytics.

---

# 📂 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | IBM HR Analytics Employee Attrition & Performance |
| Domain | Human Resources |
| Source | Kaggle |
| File Format | Excel (.xlsx) |
| Records | 1,470 |
| Columns | 35 |

---

# ⚙️ ETL Pipeline

### 1️⃣ Extract
- Imported the HR dataset into Power Query.
- Verified data types during data loading.

### 2️⃣ Data Profiling
- Analyzed column quality.
- Reviewed column distribution.
- Examined column profiles.
- Validated data types.

### 3️⃣ Data Cleaning
- Checked for missing values.
- Identified duplicate records.
- Removed constant-value columns.
- Renamed columns for improved readability.

### 4️⃣ Data Transformation
- Created Conditional Columns.
- Created Custom Columns.
- Applied Business Rule Validation.
- Performed Group By operations.
- Created Reference Queries.
- Merged lookup tables using Left Outer Join.
- Appended multiple datasets.
- Performed Pivot and Unpivot transformations.
- Standardized data using Replace Values.
- Cleaned text fields using Trim and Clean.

### 5️⃣ Load
- Loaded the transformed dataset into the Power BI Data Model using **Close & Apply**.

---

# 🛠️ Power Query Concepts Demonstrated

- Data Profiling
- Data Cleaning
- Data Validation
- Feature Engineering
- Conditional Columns
- Custom Columns
- Group By
- Merge Queries
- Append Queries
- Pivot Columns
- Unpivot Columns
- Replace Values
- Trim & Clean
- Reference Queries
- Query Optimization

---

# 💼 Business Value

The ETL pipeline transforms raw HR data into a structured and reliable dataset by:

- Improving overall data quality.
- Removing redundant and unnecessary information.
- Standardizing text values.
- Validating business rules.
- Enriching data using lookup tables.
- Preparing data for reporting and dashboard development.
- Creating a scalable and maintainable data transformation workflow.

---

# 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- Microsoft Excel

---

# 📁 Repository Structure

```
IBM-HR-Analytics-ETL-Power-Query
│
├── README.md
├── IBM HR Analytics Employee Attrition & Performance.xlsx
├── IBM HR Analytics ETL.pbix
└── IBM HR Analytics ETL Documentation.pdf

```

---

# 🎓 Skills Demonstrated

- ETL (Extract, Transform, Load)
- Data Profiling
- Data Cleaning
- Data Validation
- Data Transformation
- Data Preparation
- Feature Engineering
- Data Standardization
- Power Query
- Power BI
- Microsoft Excel
- Business Intelligence

---

# 🚀 Future Enhancements

- Build an HR Analytics Dashboard using the transformed dataset.
- Recreate the ETL pipeline using Python (Pandas).
- Implement the same ETL workflow using SQL.

---

# 👩‍💻 Author

**Anisha Kamila**

Power Platform Developer | Aspiring Data Analyst

📧 Email: anishakamila.11002@gmail.com

---

⭐ If you found this project useful, feel free to explore the repository and provide your feedback.
