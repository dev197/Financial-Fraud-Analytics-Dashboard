FinSight — Financial Performance & Fraud Risk Analytics
Overview

FinSight is a Power BI dashboard project that provides real-time insights into financial transaction performance and fraud risk exposure. It combines transaction-level analytics with fraud detection metrics to help stakeholders identify where revenue is being generated — and where it's being lost.

The project answers one core question: Is transaction growth actually converting into profit, or is fraud eating into it?

Key Insight

Despite 43.04% YoY growth in transaction volume (₹455.26M total), the business currently operates at a net revenue of -₹5.11M. Analysis shows this is driven largely by fraud concentrated in the Retail segment, which accounts for 54% of transaction volume but 85% of total fraud losses (₹5.97M).

Dashboard Pages
1. Financial Analysis

High-level view of transaction performance: total amount, transaction count, average transaction value, fees, and tax. Includes breakdowns by month, transaction status, customer segment, state, transaction type, and gender.

2. Fraud and Risk Analysis

Deep dive into fraud exposure: fraud amount, fraud rate, average fraud amount, and risk category distribution. Breaks down fraud by customer segment, transaction type, channel, merchant category, and month.

3. Transaction Detail View

Row-level transaction table with filters for drill-down investigation (transaction ID, date, customer, type, status, segment, amount, fee, tax).

4. Executive Summary

A condensed, decision-ready view combining the most critical KPIs, trend lines, risk concentration, a ranked "Where to Act" table, and recommended next steps — designed for a 30–60 second executive read.

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
Power BI — dashboard design, DAX measures, data modeling
DAX — time intelligence (YoY growth), dynamic KPI cards, conditional flagging
Data model — Transactions table with related Date, Customer, and Merchant dimension tables
Findings & Recommendations
Retail segment is both the largest revenue driver and the largest fraud liability — targeted fraud controls here offer the highest ROI.
Loan EMI and Transfers are the top transaction types by both revenue and fraud exposure.
ATM and Mobile App channels show the highest fraud concentration and should be prioritized for stronger authentication controls.
10.4% transaction failure rate represents a separate revenue leak worth operational review.
2026 fraud figures are based on partial-year data and should not yet be read as a confirmed downward trend.
