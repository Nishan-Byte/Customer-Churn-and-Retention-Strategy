# Customer Churn & Retention Strategy

An end-to-end machine learning and business analytics project that predicts customer churn, identifies key churn drivers, quantifies revenue at risk, and develops data-driven customer retention strategies.

---

## Project Overview

Customer churn is a major business challenge for subscription-based companies. Identifying customers who are likely to leave is only the first step; businesses also need to understand **why customers churn, which customers should be prioritized, how much revenue is at risk, and which retention actions provide the highest return**.

This project combines **machine learning, explainable AI, customer segmentation, financial analysis, and scenario-based ROI analysis** to build an end-to-end customer retention framework.

The project uses the **Telco Customer Churn dataset**, containing **7,043 customers across 21 variables**.

### Business Objective

The project aims to answer five key questions:

1. **Who is most likely to churn?**
2. **Why are customers churning?**
3. **How much revenue is at risk?**
4. **Which customers should the business prioritize for retention?**
5. **How should the retention budget be allocated to maximize ROI?**

---

## Project Architecture

```text
Telco Customer Dataset
        │
        ▼
Data Gathering
        │
        ▼
Data Understanding
        │
        ▼
Business Problem Definition
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Business KPI Analysis
        │
        ▼
Feature Selection
        │
        ▼
Feature Engineering
        │
        ▼
Data Encoding
        │
        ▼
Train / Validation / Test Split
        │
        ├──────────────────────┐
        ▼                      ▼
Logistic Regression         XGBoost
        │                      │
        └──────────┬───────────┘
                   ▼
           Model Comparison
                   │
                   ▼
        Hyperparameter Tuning
                   │
                   ▼
          Cross-Validation
                   │
                   ▼
          Best Churn Model
                   │
                   ▼
         Churn Probability Score
                   │
                   ▼
          SHAP Explainability
             ┌─────┴─────┐
             ▼           ▼
      Churn Drivers   Risk Scoring
             │           │
             └─────┬─────┘
                   ▼
        Customer Segmentation
                   │
                   ▼
       Customer Lifetime Value
                   │
                   ▼
         Revenue-at-Risk
                   │
                   ▼
       Retention Prioritization
                   │
                   ▼
       Intervention Strategies
                   │
                   ▼
       Retention Budget Allocation
                   │
                   ▼
          Scenario Analysis
                   │
                   ▼
        Expected Revenue Saved
                   │
                   ▼
             ROI Analysis
                   │
                   ▼
       Business Recommendations
