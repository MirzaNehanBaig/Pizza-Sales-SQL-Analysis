# Pizza-Sales-SQL-Analysis
SQL and Excel analysis of pizza restaurant sales performance and operational insights.
# 🍕 Pizza Sales Performance & Customer Behavior Analysis

## 📌 Project Overview
This project provides an end-to-end data analysis solution for a pizza restaurant chain. Using **SQL** for deep data extraction and **Excel** for visualization and reporting, the goal was to analyze transactional data to uncover key operational insights, revenue drivers, and customer purchasing patterns. 

These findings provide actionable recommendations to optimize inventory management, streamline kitchen operations, and drive targeted marketing campaigns.

---

## 🛠️ Tech Stack & Tools Used
* **SQL (Structured Query Language):** Used for data cleaning, running aggregate functions, and writing advanced window functions (e.g., tracking peak hours, ranking top-selling pizzas).
* **Microsoft Excel:** Used for data profiling, formatting, and building visual reporting charts.
* **Google Docs:** Used to compile the final professional stakeholder report.

---

## 📂 Repository Structure
* 📄 `Pizza_Sales_Report.pdf` - The final comprehensive business report containing chart screenshots and executive insights.
* 💻 `pizza_sales_queries.sql` - The raw, clean SQL script containing all database queries used for the analysis.
* 💾 `pizza_sales_dashboard.xlsx` - The Excel workbook containing the processed data and reporting charts.

---

## 📊 Key Business Questions Answered
1. **Financial KPIs:** What is the total revenue, average order value, and total pizzas sold?
2. **Operational Peak Times:** Which days of the week and hours of the day experience the highest volume of orders?
3. **Product Performance:** What are the top 5 best-selling pizzas by revenue and total quantities?
4. **Menu Optimization:** What are the top 3 best-selling pizzas within *each* specific pizza category? (Solved using SQL Window Functions).

---

## 💡 Top Actionable Insights
* **Peak Hour Bottlenecks:** Order volume spikes sharply between 12:00 PM - 1:30 PM and 5:30 PM - 7:00 PM. *Recommendation:* Increase kitchen staffing and pre-prep dough/ingredients during these windows to reduce delivery wait times.
* **Category Leaders:** While Classic pizzas generate the highest raw order volume, Supreme pizzas yield a higher profit margin per order. *Recommendation:* Bundle Classic pizzas with high-margin sides or drinks to increase the average transaction amount.

---

## 🚀 How to Review This Project
1. Open the [Pizza_Sales_Report.pdf](./Pizza_Sales_Report.pdf) file directly in your browser for a quick, visual overview of the business findings.
2. Review the clean code structure inside [pizza_sales_queries.sql](./pizza_sales_queries.sql) to see the exact logic used to aggregate the data.
