# 🏦 Bank Transaction Fraud Analysis

### Business Task
Analyse bank transaction data to identify suspicious and fraudulent activities, understand customer spending behaviour across different segments, and provide actionable insights to improve fraud detection and operational efficiency.

### Data Set
- Bank transaction data containing **2,512 transactions** from **2023 to 2024** sourced from [Kaggle](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection).
- Dataset includes transaction amount, account balance, customer demographics, login attempts, channel type, and merchant information.

### Tools
- **PostgreSQL / DuckDB** for data analysis 
- **Power BI** for data visualisation

### Key Questions Explored
1. How does monthly revenue fluctuate over time?
2. Which channel (ATM / Online / Branch) has the highest transaction volume?
3. What is the Credit vs Debit ratio by channel?
4. How does account balance segment affect spending behaviour?
5. What is the spending ratio by customer occupation?
6. How many transactions show signs of fraud? (Login Attempts ≥ 3)
7. Which cities and channels have the highest fraud rates?
8. What is the fraud risk score combining transaction amount and login attempts?

### Key Findings
- 🚨 **95 suspicious transactions** detected (3.78% of total) based on login attempts ≥ 3
- 📉 **April 2023** had the lowest transaction volume — worth investigating
- 📈 **August & September 2023** peaked at ~$72k revenue
- 💳 **Online channel** leads slightly in fraud cases (37 out of 95)
- 🎓 **Students** have the highest spending ratio relative to their balance — indicating financial stress
- ⚖️ All 3 channels (ATM / Online / Branch) are nearly equal in volume and revenue

### Dashboard


