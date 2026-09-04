FinSight — Financial Performance & Fraud Risk Analytics
Overview

FinSight is a Power BI dashboard project analyzing financial transaction performance and fraud risk exposure across a simulated banking dataset. It combines transaction-level analytics with fraud detection metrics to help stakeholders identify where revenue is being generated — and where it's being lost.

The project answers one core question: Is transaction growth actually converting into profit, or is fraud eating into it?

Key Insight

Despite 43.04% YoY growth in transaction volume (₹455.26M total across 50K transactions), the business operates at a net revenue of -₹5.11M. Analysis shows this is driven largely by fraud concentrated in the Retail segment, which accounts for 52.9% of fraud losses (₹3.16M) — the single largest share by customer segment.

Dashboard Pages
1. Financial Analysis
   <img width="1155" height="605" alt="Financial analysis" src="https://github.com/user-attachments/assets/ca515e67-ee0d-4a2f-a26a-2cca8637fdc3" />

High-level view of transaction performance: total amount, transaction count, average transaction value, fees, and tax. Breaks down by month, transaction status, customer segment, state, transaction type, and gender.

2. Fraud and Risk Analysis
   <img width="1155" height="614" alt="Fraud and risk analysis" src="https://github.com/user-attachments/assets/a708062d-fa4a-4861-85ed-ad3ed83e9e4b" />

Deep dive into fraud exposure: fraud amount, fraud rate (1.26%), average fraud amount, and risk category distribution (535 High-risk vs 95 Medium-risk transactions). Breaks down fraud by customer segment, transaction type, channel, and merchant category.

3. Transaction Detail View
   <img width="1153" height="606" alt="transactions" src="https://github.com/user-attachments/assets/1ba311c6-070b-4c81-9287-480703f46904" />

Row-level transaction table with filters for drill-down investigation — transaction ID, date, customer, type, status, segment, amount, fee, and tax.

4. Executive Summary
<img width="1162" height="614" alt="executive summary" src="https://github.com/user-attachments/assets/e512a41e-361e-487c-89ae-8192b0edb072" />
A condensed, decision-ready view combining the most critical KPIs, YoY trend, fraud concentration by segment and state, and recommended next steps — designed for a 30–60 second executive read.

Key Metrics Tracked
Metric	Description
Total Amount	Total transaction value processed
Total Transactions	Count of all transactions
Avg Transaction Value	Total Amount / Total Transactions
Total Fee / Total Tax	Revenue-related deductions
Fraud Amount / Fraud Rate	Value and % of transactions flagged as fraudulent
Net Revenue	Total Amount minus fraud losses, fees, and other costs
YoY Growth %	Year-over-year change in transaction volume
Risk Category	High/Medium classification of flagged transactions
Tools & Tech
SQL — storing and structuring the cleaned transaction data before loading into Power BI
Python (Pandas, NumPy) — data cleaning and exploratory data analysis
Power BI — dashboard design, DAX measures, data modeling
DAX — time intelligence (YoY growth), dynamic KPI cards, conditional risk flagging
Data model — Transactions table with related Date, Customer, and Merchant dimension tables
Data Source

Findings & Recommendations
Retail segment is both the largest revenue driver and the largest fraud liability — targeted fraud controls here offer the highest ROI.
Loan EMI and Transfers are the top transaction types by both revenue and fraud exposure.
ATM and Mobile App channels show the highest fraud concentration and should be prioritized for stronger authentication controls.
10.4% transaction failure rate represents a separate revenue leak worth operational review, unrelated to fraud.
50% of fraud cases are concentrated in Maharashtra, Karnataka, Tamil Nadu, and Gujarat.
2026 fraud figures are based on partial-year data and should not yet be read as a confirmed downward trend.
