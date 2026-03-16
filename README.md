## Project Overview: Telecom Retention Strategy
This repository contains a full-cycle Business Intelligence project aimed at diagnosing a 26.5% churn rate within a major telecommunications provider. Using Power BI, I transformed a raw dataset of 7,043 customers into a four-page strategic dashboard.

### Key Objectives
Market Comparison: Analyzing the gap between 454 acquisitions and 1,869 departures.

Customer Profiling: Identifying the "Value Dilution" where high-spend veterans are replaced by low-spend joins.

Root Cause Discovery: Using AI-driven Decomposition Trees to isolate Fiber Optic and Month-to-Month contract friction.

Revenue Recovery: Generating an "At-Risk" watchlist to protect £137K in monthly revenue.

### Technical Stack
Data Modeling: Star Schema design with related dimensions for Geography and Service.

DAX Measures:

Churn Rate % = DIVIDE([Total Churned], [Total Customers])

Revenue Leakage = CALCULATE([Total Revenue], Status = "Churned")

AI Visuals: Decomposition Tree for root cause analysis and Smart Narrative for executive summaries.

### Business Recommendations
Incentivize Long-term Contracts: 88% of churned users were Month-to-Month.

Stabilize Fiber Infrastructure: Fiber users churn at 2x the rate of DSL.

Proactive Outreach: Target the identified "At-Risk" list of 100+ high-value customers.
