# Quantium-customer-impact-analysis
Quantium customer behavior and sales impact analysis using Python

Quantium Retail Analytics Project

📌 Project Overview

This project analyzes customer purchasing behavior using large, transaction-level retail data to evaluate the 
impact of strategic business interventions.
It is independently developed and inspired by the Quantium – Data Analytics Job Simulation, 
following a consulting-style, decision-focused analytics approach.

--------------------------------------------------------------------------------
🎯 Business Objective

To understand:
1. Which customer segments drive revenue
2. How customer behavior changes over time
3. Whether observed sales uplift is driven by frequency, basket size, or customer base
4. The directional impact of a business intervention using test–control logic
---------------------------------------------------------------------------------------
Dataset Overview

Transaction-level retail data
Fields include invoice, customer ID, product, quantity, price, date, and country
Large, real-world dataset with noise, returns, and missing values
------------------------------------------------------------------------------------
🛠 Tools & Technologies

Python (Pandas, NumPy, SciPy)

Jupyter Notebook

GitHub

🔄 Methodology (High Level)
1. Data Preparation

Cleaned transactions and removed cancellations

Validated customer records

Created revenue and time-based features

2. Customer Feature Engineering

Aggregated data to customer-month level

Built behavioral metrics (frequency, basket value, revenue)

Created lifetime profiles and RFM-style value segments

3. Impact Analysis

Defined a simulated intervention period

Applied pre–post and test–control comparisons

Decomposed revenue change into behavioral drivers

Performed light statistical validation (directional)

4. Insights & Recommendations

Translated analysis into executive-level insights

Provided actionable recommendations with stated assumptions

📊 Key Insights

High-value customers showed stronger post-intervention uplift

Revenue growth was primarily driven by purchase frequency

Control group behavior remained relatively stable

Customer segmentation was essential to isolating true impact

📈 Recommendations

Prioritize targeted engagement for high-value customers

Focus on increasing purchase frequency rather than discount-led basket growth

Use test–control frameworks for evaluating future initiatives

⚠️ Assumptions & Limitations

Intervention is simulated using historical data

Test/control groups are value-based, not randomized

Statistical results are directional and decision-oriented
