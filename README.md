# DS223-Survival-Analysis
# Homework 3 | Survival Analysis

**Author:** Yeva Stepanyan 
**Course:** MArketing Analytics  
**Date:** 15.11.2025

---

## Project Overview

This project analyzes subscriber churn risk using survival analysis techniques. The goal is to understand the factors affecting churn, calculate Customer Lifetime Value (CLV), and identify valuable customer segments to inform retention strategies.

Key tasks include:  
- Building Accelerated Failure Time (AFT) models with multiple distributions  
- Comparing model performance and selecting the most suitable model  
- Visualizing survival curves for all models  
- Calculating CLV per customer and exploring segment-level CLV  
- Developing actionable insights for retention strategies  

---

## Dataset

The dataset contains information about subscribers, including demographic, usage, and service details:

| Column    | Description                          |
|-----------|--------------------------------------|
| ID        | Subscriber ID                         |
| region    | Region code                           |
| tenure    | Lifetime of the subscription          |
| age       | Subscriber’s age                      |
| marital   | Marital status                        |
| address   | Years living at the same address      |
| income    | Annual income (K)                     |
| ed        | Education level                        |
| retire    | Retired (Yes/No)                      |
| gender    | Gender                                |
| voice     | Voice service usage                    |
| internet  | Internet service usage                 |
| forward   | Call forwarding                        |
| custcat   | Customer category                      |
| churn     | Churn indicator (Yes/No)             |

---

## Project Structure
├── code/ 
│   └── Homework_3.rmd 
├── data/
│   └── telco.csv
├── img/
├── README.md 

---

## Methodology

1. **Modeling Churn:** Built AFT models using all available distributions to understand the effect of subscriber characteristics on churn risk.  
2. **Feature Selection:** Retained significant predictors based on model results.  
3. **CLV Calculation:** Calculated customer lifetime value for individual subscribers using predicted survival probabilities.  
4. **Segmentation Analysis:** Identified the most valuable segments based on CLV and churn risk.  
5. **Retention Strategies:** Suggested targeted interventions to reduce churn and maximize revenue.  

---

## Findings & Insights

- Engagement, tenure, and subscription type are significant factors affecting churn.  
- The most valuable segments are those with high CLV and moderate-to-high churn risk.  
- Based on survival probabilities and CLV, the annual retention budget should cover expected revenue lost from at-risk subscribers.  
- Recommended retention strategies include personalized offers, targeted campaigns for high-risk high-value subscribers, and monitoring early warning signals in usage patterns.  

---

## Usage Instructions

1. Clone the repository:  
```bash
git clone https://github.com/yevastepanyan8/DS223-Survival-Analysis

