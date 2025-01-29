# Excel-Sales-and-Finance-Analytics


## 🎯 Objective
AtliQ is a hardware company that sells products like PCs, mice, and printers to two types of customers:
- **Brick & Mortar Stores** – Physical retail stores such as Croma and Best Buy.
- **E-commerce Platforms** – Online marketplaces like Amazon and Flipkart.

The company provided datasets containing over **1.5 million records** to build comprehensive sales and financial reports.

---

## 📈 Report Overview

The report includes multiple analytical insights, such as:
### **Sales Reports**
- Sales Report
- Customer Performance Report
- Market Performance Report
- Top 10 Products
- Division-Level Analysis
- Top & Bottom 5 Products
- New Product Performance (2021)
- Top 5 Countries by Sales

### **Finance Reports**
- **Profit & Loss (P&L) Reports** (Yearly, Monthly, Market-based)
- **Gross Margin % (GM%) Analysis (Quarterly)**

---

## 🔄 Steps to Build the Report

### **1️⃣ ETL (Extract, Transform, Load)**
- Imported all provided CSV files into **Power Query**.
- Ensured data integrity by:
  - Removing duplicates
  - Correcting spelling errors
  - Handling missing values
- Verified that all **dimension tables** contained unique columns before loading them into **Power Pivot**.

### **2️⃣ Data Modeling**
- Established a **star schema** by connecting relevant tables.
- Created a **dim_date** table using **Power Query**, including:
  - Separate columns for date, month, and year.
  - A fiscal year column (September–August) for AtliQ Hardware.
- Connected the fiscal year table to the existing dataset.

### **3️⃣ Pivot Tables & Power Pivot**
- Integrated the data model with **Pivot Tables** for quick data analysis.
- Used **Power Pivot** to create new **measures** and **calculated columns**.
- Leveraged **Power Query** for seamless data transformation and connectivity.

### **4️⃣ DAX (Data Analysis Expressions)**
- Created **10+ measures**, including:
  - Net Sales by Year
  - Gross Margin & GM%
  - Cost of Goods Sold (COGS)
- Utilized functions like `CALCULATE`, `SUM`, `DIVIDE`, and `RELATED`.
- Adjusted fiscal year calculations by shifting the standard calendar year by **four months**.

### **5️⃣ Conditional Formatting**
- Applied **rules to highlight key insights**, identify trends, and improve data readability.
- Enhanced visualization by formatting numbers and text for better interpretation.

- # Key Insights from AtliQ Hardwares Reports

Here are **9 key insights** derived from the provided documents:

---

### **1. Exponential Growth in Net Sales (2019-2021)**  
- AtliQ Hardwares experienced **massive growth in net sales**, increasing from **$87.5M in 2019** to **$598.9M in 2021**, representing a **304% growth** over two years. This indicates a strong upward trajectory in the company's revenue.

---

### **2. India as the Largest Market**  
- **India** is the largest market for AtliQ Hardwares, contributing **$161.26M in net sales in 2021**, which is **27% of the total global sales**. This highlights India's critical role in the company's overall performance.

---

### **3. Gross Margin Percentage Decline**  
- Despite the growth in net sales, the **gross margin percentage (GM%)** declined from **41.43% in 2019** to **36.43% in 2021**. This suggests that the cost of goods sold (COGS) is growing faster than net sales, potentially impacting profitability.

---

### **4. Customer Performance in India**  
- In India, **Croma** showed the highest growth among customers, with net sales increasing from **$4.7M in 2020** to **$18.4M in 2021**, a **392.6% growth**. This indicates strong performance in the Indian retail sector.

---

### **5. Underperformance Against Targets in 2021**  
- Globally, AtliQ Hardwares **missed its 2021 sales targets by $54.9M**, representing an **8.4% shortfall**. Key markets like **India (-5.6%)**, **USA (-10.4%)**, and **Canada (-12.6%)** underperformed against their targets.

---

### **6. USA as the Second-Largest Market**  
- The **USA** is the second-largest market, contributing **$87.78M in net sales in 2021**. Despite this, it underperformed against its target by **10.4%**, indicating room for improvement.

---

### **7. High Gross Margin in Japan and New Zealand**  
- **Japan** and **New Zealand** had the highest gross margin percentages in 2021, at **46.5%** and **48.2%**, respectively. This suggests efficient cost management and higher profitability in these markets.

---

### **8. Rapid Growth in Emerging Markets**  
- Emerging markets like **Bangladesh** and **Indonesia** showed significant growth, with net sales increasing by **235.9%** and **196.8%**, respectively, from 2019 to 2021. This indicates potential for further expansion in these regions.

---

### **9. Cost of Goods Sold (COGS) Growth Outpacing Sales**  
- The **COGS grew by 309%** from 2019 to 2021, slightly outpacing the **304% growth in net sales**. This trend could pressure profitability if not managed effectively.

---

### **10. Top 3 Customers 
- The top 3 customers contributing to the highest net sales were Amazon, AtliQ Exclusive, and AtliQ e-store.

---

These insights highlight AtliQ Hardwares' strong growth trajectory, regional performance variations, and areas for improvement in cost management and target achievement.


## 🎯 Soft Skills Developed
- Enhanced understanding of **Sales & Finance Reporting** 📈
- Designed user-friendly reports with a **data-driven approach** 🏗️
- Optimized report generation through careful fine-tuning ⚙️
- Developed a structured approach to **report building & analysis** 📝

## 📂 Report Links
- [Customer Performance Report](https://github.com/Adarsh2898/Excel-Sales-and-Finance-Analytics/blob/main/Customer%20Performance%20Report.pdf)
- [Market Performance vs Targets Comparison Report](https://github.com/Adarsh2898/Excel-Sales-and-Finance-Analytics/blob/main/Market%20Performance%20vs%20Target%20Report.pdf)
- [Profit & Loss (P&L) Reports by Fiscal Year)](https://github.com/Adarsh2898/Excel-Sales-and-Finance-Analytics/blob/main/P%26L%20Statement%20by%20Fiscal%20Year.pdf)
- [Profit & Loss (P&L) Reports by Fiscal Month)](https://github.com/Adarsh2898/Excel-Sales-and-Finance-Analytics/blob/main/P%26L%20by%20Months.pdf)
- [Profit & Loss (P&L) Reports by Markets](https://github.com/Adarsh2898/Excel-Sales-and-Finance-Analytics/blob/main/P%26L%20Statement%20by%20Markets.pdf)
- [Top 10 Products](https://github.com/Adarsh2898/Excel-Sales-and-Finance-Analytics/blob/main/Top%2010%20Products.pdf)
