# 🍽️ Zomato Restaurant Analysis Dashboard

## 📌 Project Overview

An interactive Power BI dashboard built to analyze Zomato restaurant data across multiple countries, cities, cuisines, ratings, pricing, and customer engagement metrics. The dashboard provides restaurant-level, customer-level, and business-level insights to help understand market trends, customer preferences, and restaurant performance for better business decision-making.

---

## 🛠️ Tools Used

- **Microsoft Power BI** — Dashboard Design & Data Visualization
- **Power Query** — Data Cleaning & Transformation
- **DAX (Data Analysis Expressions)** — KPI Measures & Calculated Columns
- **Python (Pandas, NumPy)** — Data Cleaning & Feature Engineering
- **Jupyter Notebook** — Data Preprocessing & Exploratory Data Analysis
- **Excel** — Country Code Mapping
- **Dataset:** Zomato Restaurant Dataset

---

## 📊 Dashboard Features

### 📈 Executive Overview Dashboard

Provides a high-level summary of restaurant performance across countries and cities.

### KPI Cards

- 🍴 Total Restaurants: **8K**
- 🌍 Total Countries: **14**
- 🏙️ Total Cities: **112**
- ⭐ Average Rating: **2.37**
- 💰 Average Cost: **213.35**

### Visualizations

- Bar Chart — Total Restaurants by Cuisines
- Bar Chart — Top 4 Cities by Restaurant Count
- Donut Chart — Restaurants by Rating Category
- Column Chart — Average Rating by Price Range
- Map Visual — Restaurants by Country
- Interactive Filters
  - Rating Category
  - Country
  - City

---

## 👥 Restaurants & Customer Insights Dashboard

Analyzes customer engagement, restaurant popularity, ratings, and service quality.

### KPI Cards

- ⭐ Highest Rating: **4.90**
- 🌟 Highest Popularity Score: **1.22K**
- 👍 Highest Votes: **251**
- 💵 Average Price Range: **1.55**
- 💰 Average Cost: **213.35**

### Visualizations

- Top Restaurants by Popularity Score
- Rating Distribution by Price Range
- Average Rating by Online Delivery
- Average Rating by Table Booking
- Average Rating by Cuisine
- Customer Insight Panel
- Interactive Filters
  - Rating Category
  - Country
  - City

---

## 📊 Business Insights Dashboard

Provides strategic insights into restaurant distribution, pricing, customer behavior, and correlations.

### Visualizations

- Correlation Heatmap
- Donut Chart — Restaurant Distribution by Price Range
- Bar Chart — Average Rating by City
- Decomposition Tree
- Interactive Filters
  - Country
  - City

---

## 🧹 Data Preparation

- Imported raw restaurant dataset into Python.
- Cleaned missing values and removed duplicate records.
- Standardized column formats.
- Merged Country Code lookup table with restaurant dataset.
- Created new calculated columns such as:
  - Rating Category
  - Popularity Score
  - Cost Category
- Performed Exploratory Data Analysis (EDA).
- Loaded cleaned data into Power BI.
- Built relationships and developed custom DAX measures.
- Designed interactive dashboards using Power BI.

---

## 🔍 Key Insights

- India accounts for the majority of restaurants in the dataset.
- Most restaurants fall under the **"Good"** rating category (4.0–4.5).
- North Indian cuisine is the most commonly offered cuisine.
- Budget and moderate price-range restaurants dominate the market.
- New Delhi has the highest number of listed restaurants.
- Restaurants offering online delivery generally receive higher average ratings.
- Restaurants with table booking tend to have better customer ratings.
- Popular restaurants receive significantly more customer votes.
- Blue-chip restaurant chains such as Subway, Domino's Pizza, and McDonald's achieve the highest popularity scores.
- Higher prices do not necessarily indicate better customer ratings.

---

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `Zomato_Restaurant_Analysis.pbix` | Power BI Dashboard |
| `zomato_analysis_project.py` | Python Data Cleaning & EDA |
| `zomato_analysis_dataset.csv` | Main Restaurant Dataset |
| `Country-Code.csv` | Country Code Lookup Table |
| `Executive_Overview.png` | Executive Dashboard Screenshot |
| `Restaurant_Customer_Insights.png` | Customer Dashboard Screenshot |
| `Business_Insights.png` | Business Dashboard Screenshot |
| `README.md` | Project Documentation |

---

## 📸 Dashboard Preview

### 📊 Executive Overview Dashboard

> ![Executive Overview Report](https://github.com/AmarjeetPanchal/Zomato_Restaurant_Analysis/blob/main/Executive_Overview_Report.png?raw=true)

---

### 👥 Restaurants & Customer Insights Dashboard

> ![Restaurants & Customer Insights Dashboard](https://github.com/AmarjeetPanchal/Zomato_Restaurant_Analysis/blob/main/Restaurants_&_Customer_Insights.png?raw=true)

---

### 📈 Business Insights Dashboard

> ![Business Insights Dashboard](https://github.com/AmarjeetPanchal/Zomato_Restaurant_Analysis/blob/main/Business_Insights.png?raw=true)

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Data Modeling
- DAX Calculations
- Power Query
- Dashboard Design
- Business Intelligence
- Data Visualization
- Customer Segmentation
- Restaurant Performance Analysis
- Business Insights Generation

---

## 📬 Contact

**Amarjeet Panchal**

📧 **Email:** *bhawanabatra2003@gmail.com*

💼 **LinkedIn:** *https://www.linkedin.com/in/bhawana-batra-5583b9293*

🐙 **GitHub:** *https://github.com/bhawanabatra*

---
