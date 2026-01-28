# 💳 Credit Card Financial Analytics: Consumer Behavior & Spend Pattern Discovery

## 📌 PROJECT OVERVIEW
This project involves a comprehensive case study for **PSPD Bank**, a global financial institution operating in 50+ countries. The goal is to leverage data analytics to evaluate customer spending and repayment behavior, identify fraud risks, and optimize marketing strategies.

## 🛠️ TECHNOLOGIES & TOOLS
* **Language:** Python 3.7
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## 🏗️ DATA ENGINEERING & CLEANING (ETL)
To ensure data integrity, the following business logic was implemented:
* **AGE NORMALIZATION:** Replaced `Age < 18` with the mean age of the dataset.
* **SPEND OPTIMIZATION:** Capped spend amounts exceeding the customer’s limit to **50% of the limit**.
* **REPAYMENT CORRECTION:** Adjusted repayment amounts to the customer's limit for accurate accounting.

---

## 🔍 BUSINESS PROBLEMS SOLVED
### 1. Financial Summaries
* Calculated **Average Monthly Spend** and **Average Monthly Repayment**.
* **PROFITABILITY ANALYSIS:** Calculated monthly bank profit based on a **2.9% interest rate** applied to positive monthly balances.

### 2. Behavioral Insights
* Identified **Top 5 Product Types** and **Top 10 Customers** by repayment.
* **GEOGRAPHIC ANALYSIS:** Determined the city with the maximum expenditure.
* **DEMOGRAPHIC SEGMENTATION:** Analyzed spend patterns across different age groups.

---

## 🚀 ADVANCED PYTHON IMPLEMENTATION
Developed a **dynamic user-defined function** that allows stakeholders to filter data and identify the **Top 10 Customers** per city based on:
1. **Product Type** (Gold, Silver, Platinum)
2. **Time Period** (Yearly or Monthly)

---

## 📈 KEY RECOMMENDATIONS
* **TARGETED MARKETING:** Launch campaigns in high-spend cities identified in the analysis.
* **RISK MANAGEMENT:** Monitor customers hitting the 50% limit cap for proactive credit adjustments.
* **SEASONAL PROMOTIONS:** Align offers with peak spending months revealed by seasonality trends.

---

## 🏁 HOW TO RUN
1. Clone the repository: `git clone https://github.com/uma-sankar-krishnagiri/Credit-Card-Financial-Analysis.git`
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open `Credit_Card_Analysis.ipynb` in Jupyter Notebook.
