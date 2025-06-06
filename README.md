# Task-4-SQL-for-Data-Analysis
# 📊 Layoff Trends

This project contains a series of SQL queries aimed at analyzing layoff trends across industries, companies, and time using a dataset named `layoffs_staging2`. The queries were written and executed using **MySQL** as part of a data analysis learning module.

---

## 🗃️ Dataset

The dataset (`layoffs_staging2`) includes fields such as:
- `company`
- `industry`
- `total_laid_off`
- `percentage_laid_off`
- `date`
- `stage`
- `funds_raised_millions`

This dataset tracks tech layoffs, company stages, and capital funding over time.

---

## 🧠 Key Analysis Performed

- ✅ Total and maximum layoffs across companies and industries
- 📅 Layoff trends over time (monthly, yearly)
- 🏢 Top companies by total layoffs
- 🏭 Industry-wise analysis of layoff distribution
- 🔁 Rolling total layoffs over months
- 🥇 Yearly top 5 companies with highest layoffs using CTEs and window functions
- 📈 Staging and average layoffs across funding stages

---

## 📂 Files Included

- `Task 4 SQL for Data Analysis.sql` – All SQL queries used for analysis


---

## 🛠️ Tools Used

- **MySQL**
- SQL features: `SELECT`, `GROUP BY`, `ORDER BY`, `WHERE`, `CTE`, `DENSE_RANK()`, `OVER()` (window function), and aggregate functions (`SUM`, `AVG`, `MAX`, `MIN`)

---

## 🚀 Getting Started

To replicate the analysis:
1. Import your `layoffs_staging2` dataset into MySQL.
2. Run the SQL queries from the provided `.sql` file.
3. Explore insights and visualize if needed.

---
