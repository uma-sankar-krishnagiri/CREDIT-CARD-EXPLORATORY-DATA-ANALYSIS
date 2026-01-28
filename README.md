📌 Project Overview
This project involves a comprehensive case study for PSPD Bank, a global financial institution operating in 50+ countries. The goal is to leverage data analytics to evaluate customer spending and repayment behavior, identify fraud risks, and optimize marketing strategies through data-driven decision-making.

🛠️ Technologies & Tools
Language: Python 3.7

Environment: Jupyter Notebook

Libraries: * Pandas: Data manipulation and ETL processes.

NumPy: Numerical operations and data cleaning.

Matplotlib & Seaborn: Advanced data visualization and trend analysis.

📂 Dataset Architecture
The analysis is performed across three primary relational datasets:

Customer Acquisition: Demographic profiles and credit limits at the time of card issuance.

Spend (Transaction Data): Detailed records of credit card expenditures per customer.

Repayment: Historical data of credit card payments made by customers.

🏗️ Data Engineering & Cleaning (ETL)
To ensure data integrity, the following business logic was implemented during the preprocessing phase:

Age Normalization: Replaced instances where Age < 18 with the mean age of the dataset.

Spend Optimization: Capped spend amounts exceeding the customer’s limit to 50% of the limit.

Repayment Correction: Adjusted repayment amounts to the customer's limit in cases of overpayment for accurate accounting.

🔍 Key Analysis & Business Logic
The project addresses several critical business questions, including:

1. Financial Summaries
Identification of distinct customers and product categories.

Calculation of Average Monthly Spend and Average Monthly Repayment.

Profitability Analysis: Calculated monthly bank profit based on a 2.9% interest rate applied to positive monthly balances (Repayment - Spend).

2. Behavioral Insights
Top Performance: Identification of the top 5 product types and top 10 customers by repayment.

Geographic Analysis: Determining the city with the maximum expenditure.

Demographic Segmentation: Analyzing spend patterns across different age groups.

3. Time-Series & Comparative Visualizations
Yearly City-wise Spend: Breakdown of spend on various products by city and year.

Seasonality Check: Monthly comparison of spends to identify seasonal purchasing trends.

Product-specific Trends: Yearly comparison of high-value categories like Air Tickets.

🚀 Advanced Python Implementation
Developed a dynamic user-defined function that allows stakeholders to filter data and identify the Top 10 Customers per city.

Inputs: Product Type (Gold/Silver/Platinum) and Time Period (Yearly/Monthly).

Output: A ranked list of customers based on repayment behavior for the specified parameters.

📈 Dashboard & Visualizations
(Note: If you have a Dashboard.png or Matplotlib plots, insert them here) The analysis includes graphical representations for:

Monthly comparison of total spends, city-wise.

Seasonal spend patterns across different product categories.

💡 Recommendations for PSPD Bank
Targeted Marketing: Develop specific campaigns for cities identified as "High Spend" hubs.

Risk Management: Monitor customers frequently hitting the 50% limit cap for potential limit increases or risk assessment.

Proactive Servicing: Use the monthly profit trends to offer proactive help or loyalty rewards to consistently profitable customers.

🏁 How to Run
Clone this repository:

Bash
git clone https://github.com/uma-sankar-krishnagiri/Credit-Card-Financial-Analysis.git
Ensure Python 3.7+ and required libraries are installed:

Bash
pip install pandas numpy matplotlib seaborn
Open Credit_Card_Analysis.ipynb in Jupyter Notebook to view the full analysis.
