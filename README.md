Test Project for a company 

This repository contains a test project I completed as part of the hiring process for [some company xd]. 

### Description

The project focuses on predicting financial stress levels among gig economy workers using data on digital behavior, income streams, and financial activity. The objective was to analyze the provided dataset, build a classification model, and submit predictions in a competition-style format.

Financial stress prediction is increasingly important for fintech startups, mental health platforms, and labor unions seeking to identify at-risk individuals. With the growing prevalence of gig work (e.g., ride-sharing, freelance platforms, delivery services), understanding how digital and financial patterns correlate with stress is crucial for designing timely interventions and support systems.

The dataset includes behavioral, occupational, and financial features collected via consent-based app usage and surveys. The model classifies each worker into one of three financial stress levels: low, moderate, or high. The main goal was to achieve the highest possible accuracy, while creative approaches and unconventional ideas were also valued.

### Dataset Description

- worker_id — unique identifier of each gig economy worker
- survey_month — month when the data was collected
- worker_age — age of the worker in years
- job_sector — type of gig job (e.g., delivery, ride-hailing, freelance)
- estimated_annual_income — self-estimated total income for the year
- monthly_gig_income — actual monthly earnings from gig work
- num_savings_accounts — number of savings or checking accounts owned
- num_credit_cards — total number of active credit cards
- avg_credit_interest — average interest rate across all credit cards
- num_active_loans — total number of ongoing personal or payday loans
- avg_loan_delay_days — average delay in loan repayments, measured in days
- missed_payment_events — number of missed or late payment events
- recent_credit_checks — number of credit inquiries in the past 3 months
- current_total_liability — total amount of outstanding debt
- credit_utilization_rate — ratio of current credit used to credit limit
- credit_age_months — duration (in months) since the first credit account was opened
- min_payment_flag — 1 if only the minimum payment was made, 0 otherwise
- monthly_investments — total amount invested or saved in the current month
- spending_behavior — category describing current spending habits
- end_of_month_balance — available account balance at month’s end
- financial_stress_level — [Target] financial stress classification: low / moderate / high

### Features / Highlights
- Data preprocessing and feature engineering for financial behavior analysis
- Classification model building and evaluation
- Insights from behavioral and financial patterns correlating with stress

### Technologies Used
- Python
- Pandas / NumPy
- Scikit-learn / PyTorch
- Matplotlib / Seaborn

### How to Run
1. Clone the repository:
   git clone https://github.com/karibays/data-analysis-classification.git

2. Install dependencies:
   pip install -r requirements.txt

3. Run the main script / notebook:
   jupyter notebook
