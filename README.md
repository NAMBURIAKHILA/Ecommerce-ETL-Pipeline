# Ecommerce ETL Pipeline using PySpark

## Project Overview
This project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline built using PySpark on a large-scale e-commerce customer behavior dataset. The pipeline processes raw data, performs cleaning and transformation, and generates business insights.

---

## 📊 Dataset Details
- 📁 Dataset: Ecommerce Customer Behavior Dataset  
- 📈 Records: 50,000+  
- 🧾 Features: 25+ columns  
- 🌍 Includes customer demographics, behavior, engagement, and transaction data  

---

## 🛠️ Technologies Used
- Python  
- PySpark  
- Google Colab  

---

## 🔄 ETL Pipeline

### 🔹 Extract
- Loaded raw CSV dataset using PySpark

### 🔹 Transform
- Handled missing values using imputation  
- Removed duplicate records  
- Standardized categorical data (Gender, Country)  

### 🔹 Feature Engineering
- Created **Engagement Score** based on user activity  
- Defined **Customer Value Segments** (High, Medium, Low)  
- Built **Churn Risk Model** using business logic  
- Added **Activity Levels** based on login frequency  

### 🔹 Load
- Stored processed data in **Parquet format** for efficient storage and querying  

---

## 📈 Key Insights Generated
- Customer distribution by churn status  
- Revenue contribution by country  
- Engagement vs churn relationship  
- Identification of high-value customers  

---

## 📂 Project Structure
Ecommerce-ETL-Pipeline/
│
├── data/
├── scripts/
├── output/
├── requirements.txt
└── README.md

## ▶️ How to Run

### 1. Install dependencies

pip install -r requirements.txt


### 2. Run the ETL pipeline

python scripts/etl_pipeline.py


---

## 🧪 Data Quality Checks
- Verified total record count after transformation  
- Ensured no null values in derived features  
- Validated distinct categories and distributions  

---

## 💼 Resume Impact
This project demonstrates:
- Big Data Processing using PySpark  
- End-to-End ETL Pipeline Development  
- Data Cleaning and Feature Engineering  
- Business-Oriented Data Analysis  

---

## 🚀 Future Improvements
- Integrate Spark SQL queries  
- Add Machine Learning model for churn prediction  
- Deploy pipeline on cloud platforms (AWS / Azure / Databricks)  

---

## 📌 Author
Akhila Namburi
