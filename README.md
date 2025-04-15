# Email-Campaign-Optimization


## Overview

This project analyzes and optimizes an email marketing campaign conducted by an e-commerce site. Using data science techniques, we assess the campaign’s performance and explore how machine learning can improve targeting strategies to maximize user engagement.

---

##  Problem Statement

The marketing team randomly sent emails to a sample of users to inform them about a new feature. The goal was to encourage users to click a link inside the email that redirects them to the company site.

We aim to:
1. Evaluate the performance of the campaign (open and click rates).
2. Build a model to predict click behavior.
3. Estimate potential improvements in Click-Through Rate (CTR).
4. Analyze performance across different user segments.

---

##  Dataset

The project uses three CSV files:

- email_table.csv: Metadata for each email sent
- email_opened_table.csv: IDs of emails that were opened
- link_clicked_table.csv: IDs of emails where users clicked the internal link

---

##  Tasks Performed

###  1. Campaign Performance Analysis
- Calculated open and click-through rates
- Established a baseline for evaluation

###  2. Predictive Modeling
- Features engineered from email content, user data, and send time
- Trained a Random Forest model to predict click likelihood
- Evaluated using metrics like AUC and classification report

###  3. Click Rate Optimization
- Simulated sending emails only to top predicted users
- Compared optimized CTR to original CTR
- Quantified improvement

###  4. Segment-Based Insights
- Explored performance across:
  - Email text types (short vs long)
  - Personalization (generic vs personalized)
  - Weekdays
  - Countries
  - Purchase history

---

##  Key Results

 Metric                  | Value     
-------------------------|-----------
 Open Rate               | 10.35%     
 Click-Through Rate (CTR)| 2.12%     
 Model AUC Score         | 0.578     
 Optimized CTR (Top 10%) | 4.04%    
 Estimated CTR Increase  | 1.92% 

---

##  Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---


