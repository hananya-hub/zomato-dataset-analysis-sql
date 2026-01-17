# 🍽️ Zomato Dataset Analysis – SQL

This project focuses on **data exploration, cleaning, and analysis using SQL**
on a Zomato restaurant dataset. The goal is to understand restaurant distribution,
service availability, ratings, and pricing trends, and to derive meaningful
business insights relevant to food-tech platforms.

---

## 🎯 Project Objective

To analyze Zomato restaurant data using SQL in order to:
- Understand restaurant presence across countries and cities
- Evaluate online delivery and table booking availability
- Analyze ratings, votes, and pricing patterns
- Identify high-performing and value-for-money restaurants

---

## 🛠️ Tools Used

- **SQL (SQL Server)**
  - Data exploration and profiling
  - Data cleaning and transformation
  - Window functions and aggregations
  - Business-driven analytical queries

---

## 📂 Dataset Overview

- Contains **9000+ restaurant records**
- Key columns include:
  - RestaurantID, Restaurant Name
  - CountryCode, Country Name
  - City, Locality
  - Cuisines
  - Rating, Votes
  - Average Cost for Two, Currency
  - Online Delivery & Table Booking indicators

---

## 🔄 Data Exploration & Cleaning

The following data preparation steps were performed using SQL:

- Verified table schema, data types, and constraints
- Checked and removed duplicate `RestaurantID` values
- Removed unwanted and invalid rows
- Merged country information using `CountryCode`
- Corrected misspelled city names
- Dropped irrelevant columns
- Standardized numeric columns (Votes, Rating, Cost)
- Created a new **rating category** column using `CASE WHEN`

---

## 🧠 SQL Techniques Demonstrated

- `JOIN` for data enrichment
- `GROUP BY` with aggregations
- `CASE WHEN` for categorical logic
- Window functions (`OVER`, rolling counts)
- CTEs for readable and modular queries
- Views for reusable logic
- Data type conversions and validations

---

## 📊 Data Analysis & Key Insights

Insights derived from SQL analysis include:

- **90.67%** of restaurants are located in **India**, followed by **USA (4.45%)**
- Out of **15 countries**, only **India and UAE** offer online delivery options
  - India: **28.01%**
  - UAE: **46.67%**
- **Connaught Place (New Delhi)** has the highest number of listed restaurants
- The most popular cuisine in Connaught Place is **North Indian**
- Only **54 out of 122** restaurants in Connaught Place offer table booking
- Restaurants with table booking have higher average ratings (**3.9**) compared to those without (**3.7**)
- Best value-for-money restaurants were identified using conditions on:
  - Rating
  - Votes
  - Cost for two
  - Online delivery and table booking availability

---

## 📂 Repository Structure
```
zomato-dataset-analysis-sql/
│
├── data/
│   └── Zomato_Dataset.csv
│
├── sql/
│   ├── 01_data_exploration.sql
│   └── 02_data_analysis.sql
│
└── README.md
```
---

## 📌 Learning Note

This project was completed as part of a structured learning and portfolio-building
process using publicly available datasets.  
The primary focus was on strengthening **SQL data cleaning, analysis, and
business insight generation skills**.

---

## ⚠️ Disclaimer

This repository is intended for **learning and portfolio demonstration purposes only**.

---

## 🔗 Connect with Me

- **Name**: BRISTA HANANYA  
- **LinkedIn**: www.linkedin.com/in/bristahananya

---

