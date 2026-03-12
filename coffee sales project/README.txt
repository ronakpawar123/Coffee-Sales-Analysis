☕ COFFEE SALES DATA ANALYSIS PROJECT
📊 Python EDA + Power BI Dashboard

--------------------------------------------------

📌 PROJECT OVERVIEW

This project analyzes coffee vending machine sales data to understand customer purchasing behavior and identify sales trends.

The analysis was performed using Python for Exploratory Data Analysis (EDA) and Power BI for interactive dashboard visualization.

The goal of this project is to extract useful business insights from sales data.

--------------------------------------------------

🛠 TOOLS AND TECHNOLOGIES USED

🐍 Python
📊 Pandas
📈 Matplotlib
📉 Seaborn
📊 Power BI
📂 Data Analysis

--------------------------------------------------

🔄 PROJECT WORKFLOW

1️⃣ Data Loading

The dataset was loaded using Python Pandas.

data = pd.read_csv("index.csv")

This allowed inspection of the dataset and understanding the structure of the data.

--------------------------------------------------

2️⃣ Data Cleaning

The dataset was checked for missing values to ensure data quality.

data.isnull().sum()

🔎 Observation:
The card column contained some missing values which correspond to cash transactions.

--------------------------------------------------

3️⃣ Exploratory Data Analysis (EDA)

EDA was performed using Matplotlib and Seaborn.

Example visualization:

sns.countplot(data=data, x='coffee_name')

This helped identify the distribution of coffee sales.

--------------------------------------------------

4️⃣ Payment Method Analysis

Payment behavior was analyzed using a count plot.

sns.countplot(data=data, x='cash_type')

💡 Insight:
More than 90% of transactions were made using card payments.

--------------------------------------------------

📊 POWER BI DASHBOARD

An interactive dashboard was created in Power BI to visualize insights from the dataset.

Dashboard includes:

📌 KPI Cards
💰 Total Revenue
☕ Total Orders
📊 Average Order Value
🧾 Total Coffee Products

📈 Sales Analysis
Coffee Sales by Product
Revenue by Coffee Type
Coffee Sales by Hour
Coffee Sales by Day
Monthly Revenue Trend

🎛 Interactive Filters
Coffee Type
Payment Method
Month
Day

--------------------------------------------------

🔑 KEY INSIGHTS

☕ Americano with Milk is the most ordered coffee product.

💰 Latte generates the highest revenue.

⏰ Peak coffee sales occur around morning hours and evening hours.

💳 More than 90% of transactions are card payments.

--------------------------------------------------

📁 PROJECT STRUCTURE

coffee-sales-analysis

data
index.csv

notebook
coffee_sales_analysis.ipynb

powerbi
coffee_sales_dashboard.pbix

README.md

--------------------------------------------------

🚀 FUTURE IMPROVEMENTS

📈 Sales forecasting using Machine Learning
👥 Customer segmentation analysis
📊 Advanced Power BI analytics
⚡ Real-time dashboard integration

--------------------------------------------------

👨‍💻 AUTHOR

Ronak
🎓 BSc IT
📊 Aspiring Data Analyst

--------------------------------------------------

🎓 INTERNSHIP

This project was completed as part of the Data Analytics Internship at Unified Mentor.

--------------------------------------------------
