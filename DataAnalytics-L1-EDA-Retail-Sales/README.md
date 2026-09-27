# EDA - Retail Sales Analysis Dashboard
**OIBSIP Data Analytics Internship | Level 1 Task 1**

### 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on Retail Sales data to identify sales trends, top-performing categories, customer demographics, and pricing strategies. An interactive dashboard was created using Plotly.

### 🛠️ Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook

### 📊 Analysis Performed
1.  Sales performance by Product Category (Beauty, Books, Electronics are top)
2.  Sales distribution by Age Group (55+ is highest contributor)
3.  Correlation analysis between `unit_price`, `quantity`, `discount` and `sales_amount`
4.  Interactive Dashboard Creation

### 💡 Key Strategic Insights & Recommendations
1.  **Revenue Concentration in Premium Categories:** Beauty, Books and Electronics drive majority of revenue (over 3M each). Focus on premium inventory and upselling.
2.  **Age-Agnostic Demand:** Sales variance across age groups is less than 2% (4.11M to 4.17M). Marketing budget should be equally distributed.
3.  **Pricing Power is Growth Lever:** Strong correlation of 0.64 between unit_price and sales_amount proves revenue is price-driven.
4.  **Discount Inefficiency:** Discount has negligible correlation of -0.09 with sales_amount, indicating margin erosion without incremental revenue.
5.  **Volume Does Not Equal Value:** Weak correlation of 0.14 between quantity and sales_amount. Focus should shift to AOV optimization.

### 📂 Repository Structure
- `EDA_Retail_Sales.ipynb` - Main analysis notebook
- `dashboard/` - Screenshots of dashboard
- `Retail_Sales.csv` - Dataset

### 👩‍💻 Author
**Bareera Maryam** - Data Analytics Intern @ Oasis Infobyte

- Dataset Source: Kaggle
