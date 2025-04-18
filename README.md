# FINANCIAL-ANALYSIS-USING-(POWER-BI+SQL)
# 📊 FINANCIAL-ANALYSIS-Credit Card Data Analysis – DAX Metrics & Insights
# 📁 Project Overview
This project aims to analyze customer credit card behavior using Power BI with DAX expressions to generate actionable financial insights. The dataset includes customer demographics, transaction history, credit risk indicators, and satisfaction scores.

# 🔧 DAX Measures & Calculations
## 1. Running Total of Credit Card Transactions
Cumulative sum of Total_Trans_Amt over time.

dax
Copy
Edit
RunningTotal_TransAmt = ...

## 2. 4-Week Moving Average of Credit Limit
Calculates the 4-week moving average of creditLimit per client.

dax
Copy
Edit
MovingAvg_4Week_CreditLimit = ...

## 3. Month-over-Month (MoM) and Week-over-Week (WoW) % Growth
Measures growth in transaction amount across time.

dax
Copy
Edit
MoM_Growth_TransAmt = ...
WoW_Growth_TransAmt = ...

## 4. Customer Acquisition Cost (CAC) as a Ratio of Transactions
Shows marketing or onboarding cost relative to transaction volume.

dax
Copy
Edit
CAC_Ratio = ...

## 5. Yearly Average Utilization Ratio
Average avg_utilization_ratio across all clients annually.

dax
Copy
Edit
YearlyAvg_Utilization = ...
## 6. Interest vs Revolving Balance (%)
Proportion of Interest_Earned relative to Total_Revolving_Bal.

dax
Copy
Edit
Pct_Interest_vs_Revolving = ...
## 7. Top 5 Clients by Total Transactions
Identifies highest transaction contributors.

dax
Copy
Edit
Top5_Clients_TransAmt = ...

## 8. High Utilization Clients
Filters clients with avg_utilization_ratio over 80%.

dax
Copy
Edit
HighUtilizationClients = ...

## 9. Customer Churn Indicator
Flags clients with no transactions in the past 6 months.

dax
Copy
Edit
Churn_KPI = ...

## 10. Delinquency Rate
Percentage of clients with Delinquent_Acc > 0.

dax
Copy
Edit
DelinquencyRate = ...

## 11. Credit Risk Score
Weighted risk score based on:

avg_utilization_ratio

Delinquent_Acc

Total_Revolving_Bal

dax
Copy
Edit
CreditRiskScore = ...

## 12. Income vs Credit Limit Correlation
Quantifies relationship between client income and credit limit.

dax
Copy
Edit
IncomeCredit_Correlation = ...

## 13. Average Satisfaction Score by Card Category
Shows customer happiness segmented by card type.

dax
Copy
Edit
Avg_CustSat_ByCategory = ...

## 14. Loan Approval vs Credit Limit
Compares credit limits for clients with vs. without personal loans.

dax
Copy
Edit
Avg_CreditLimit_Loan = ...
Avg_CreditLimit_NoLoan = ...

## 15. High-Risk Client Flag
Flags clients with:

Total_Revolving_Bal > 90% of creditLimit

avg_utilization_ratio > 80%

dax
Copy
Edit
HighRiskClientFlag = ...
# 📈 Recommended Visuals
Line Charts: Running total, MoM & WoW growth

Cards/KPIs: Delinquency rate, CAC ratio, churn indicator

Bar Charts: Top 5 clients, satisfaction by card type

Scatter Plot: Income vs credit limit

Heatmap/Matrix: Risk score by segment

# 📦 Datasets Used
customer.csv

credit_card.csv

cust_add.csv

cc_add.csv

# 💡 Insights Uncovered
Identified high-risk customers based on revolving balance & utilization.

Highlighted top-performing clients and card categories.

Estimated churn and calculated loan-related credit limits.

Quantified client behavior trends with time-based metrics.

# 🛠️ Tools & Technologies
Power BI

DAX

Excel (for data cleaning)

SQL ( for preprocessing)
