# 🦠 COVID-19 Data Analysis with SQL

This project explores COVID-19 datasets using SQL to extract insights on infection and death rates across countries and continents. It demonstrates data analysis and reporting skills relevant for entry-level data/business analyst roles.

## 📊 Project Objective

To perform a comprehensive analysis of COVID-19 cases, deaths, and vaccination trends using SQL Server. The project is designed to:
- Understand pandemic impacts across different countries and continents.
- Analyze India's day-wise case fatality rate.
- Compare vaccination progress across the globe.

## 🛠️ Tools & Technologies
- **SQL Server Management Studio (SSMS)**
- **T-SQL**
- **COVID-19 Global Datasets**
- **Microsoft Excel / Power BI (optional for visualization)**

## 🧩 Dataset Sources
This analysis uses two main tables:
- `CovidDeaths`: Contains daily records of total cases and deaths by country.
- `CovidVaccinations`: Contains vaccination data by date and location.

## 🔍 Key SQL Queries & Insights

### 1. View All Columns
```sql
SELECT * FROM COVID19.dbo.CovidDeaths
