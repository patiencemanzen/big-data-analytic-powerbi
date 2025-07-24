# 🚕 Uber Fares Data Analysis Project

## 📘 Introduction

This project analyzes Uber ride data using Python and Power BI. The aim is to uncover patterns in fare prices, ride distances, and temporal ride trends. The final outcome includes a professional Power BI dashboard and actionable insights.

---

## 🧪 Methodology

### 1. Data Source

Dataset: [Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)

### 2. Tools Used

- **Python (Pandas, NumPy, GeoPy)** for data cleaning and feature engineering
- **Power BI Desktop** for visualization and dashboard creation

### 3. Key Steps

- Data cleaning: Removed nulls and outliers
- Feature engineering: Extracted hour, day, month, weekday, distance
- Exported cleaned data to CSV
- Imported data into Power BI for exploration and dashboarding

---

## 📊 Analysis & Insights

### 📌 Fare Distribution

Most fares are under $25, with very few exceeding $100. Outliers removed to avoid distortion.

### 📌 Distance vs Fare

A clear positive correlation: longer trips generally cost more. However, some short trips had high fares due to traffic or surge pricing.

### 📌 Hourly Trends

Peak ride demand and higher fares are visible at:

- Morning rush (7–9 AM)
- Evening rush (5–7 PM)

### 📌 Day of Week Analysis

Fridays and Saturdays showed slightly higher ride volumes and fares.

### 📌 Monthly Trends

Seasonal patterns observed, with slight ride increases in warmer months.

### 📌 Geographic Patterns (if map used)

Pickups are concentrated in central NYC zones.

---

## 📈 Dashboard Highlights

Key visuals on the dashboard:

- Histogram of fare amounts
- Line chart: Avg fare by hour
- Bar chart: Rides by weekday
- Pie chart: Peak vs Off-peak rides
- Scatter plot: Fare vs Distance
- Map: Pickup locations

---

## 💡 Recommendations

- Uber could **encourage rides during off-peak** times with discounts.
- Target areas with **high demand during peak** hours for driver allocation.
- Monitor **surge pricing impact** on fare anomalies.

---

## 🧾 Files in This Repo

- `uber_cleaned.csv`: Cleaned dataset
- `uber_analysis.pbix`: Power BI dashboard
- `screenshots/`: Images of development stages and visuals
- `README.md`: This report

---

## 👨‍🏫 Submitted To

**Eric Maniraguha**  
INSY 8413 – Introduction to Big Data Analytics  
AUCA | July 2025
