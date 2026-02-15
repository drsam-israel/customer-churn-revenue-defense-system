# customer-churn-revenue-defense-system
End-to-end churn analytics system (SQL + Tableau + XGBoost) transforming churn from reactive reporting into predictive revenue protection. Includes revenue-aware threshold optimization and quantified business impact.

# Customer Churn & Revenue Defense System  
### SQL → Tableau → Machine Learning (XGBoost)

---

##  Executive Overview

This project builds a full end-to-end churn intelligence framework that transforms customer attrition from reactive reporting into proactive revenue protection.

The system integrates:

- SQL-based data modeling
- Tableau executive dashboards
- Revenue-optimized machine learning (XGBoost)

### Core Outcomes

- 26.54% churn rate identified
- $139K monthly recurring revenue at risk
- 86% churn detection recall (optimized threshold)
- 4–6 percentage-point churn reduction potential
- $660K–$1.0M projected annual revenue protection

This is not a dashboard project.  
It is a revenue defense system.

---

##  Business Problem

A subscription-based telecom business faced elevated churn without:

- Clear structural driver visibility
- Revenue-at-risk quantification
- Lifecycle churn insights
- Predictive intervention capability

Churn was reducing revenue predictability and inflating acquisition replacement costs.

The objective was to design a scalable, financially aligned churn mitigation framework.

---

#  Phase 1 — SQL: Revenue Risk Quantification

### Objectives

- Clean and structure raw churn dataset
- Engineer tenure bands and revenue metrics
- Calculate churn KPIs
- Segment churn across contract, payment, tenure, and services

### Key Findings

- 26.54% overall churn
- $139K monthly recurring revenue at risk
- Month-to-month contracts: 42.7% churn
- Electronic check users: 45% churn
- First 6 months: 53% churn
- Bundled services reduced churn to single digits

### Insight

~30% of customers drive ~70% of churn-related revenue exposure.

Churn is structural and measurable.

---

#  Phase 2 — Tableau: Executive Decision Intelligence

Built interactive dashboards to visualize:
TableauLink: https://public.tableau.com/app/profile/samuel.israel5140/viz/ChurnAnalytics_17705602950540/ExecutiveReport?publish=yes

- Executive KPI overview
- Churn by contract type
- Payment behavior risk
- Tenure lifecycle churn
- Service bundling impact
- Revenue exposure segmentation

### Executive Insights

- ~$120K MRR risk concentrated in month-to-month customers
- Fiber customers = high ARPU + high churn risk
- Early-tenure instability is the highest-risk intervention window
- Senior citizens show elevated churn probability

Retention strategy shifted from blanket discounting to targeted, ROI-driven intervention.

---

#  Phase 3 — Machine Learning: Predictive Churn Engine

## Models Evaluated

- Logistic Regression
- Random Forest
- XGBoost

## Final Model Selected

**XGBoost with revenue-aware threshold optimization**

### Test Set Performance (1,409 observations | 374 churners)

| Metric | Value |
|--------|--------|
| ROC-AUC | 0.838 |
| Accuracy | 71% |
| Churn Recall | 86% |
| Precision | 47% |
| Threshold | 0.35 |

Threshold optimized to maximize revenue protection rather than raw statistical accuracy.

---

##  Business Impact Projection (12-Month Horizon)

- 4–6pp churn reduction
- 300–420 customers retained annually
- $660K–$1.0M annual revenue protected
- 12–18% CLV uplift
- $250K–$400K reduction in acquisition replacement costs

Retention-led optimization provides higher ROI than acquisition scaling.

---

#  Key Predictive Drivers

Consistent across SQL, Tableau, and ML:

1. Contract Type
2. Tenure (early lifecycle)
3. Tech Support
4. Online Security
5. Internet Service (Fiber)
6. Payment Method

Churn is driven primarily by structural commitment and service engagement — not pricing alone.

---

#  Deployment Framework

- Monthly churn probability scoring
- Risk-tier segmentation (High / Medium / Low)
- CRM-triggered retention workflows
- Threshold tuning based on campaign capacity
- Quarterly model retraining

Production-ready and scalable.

---

#  Strategic Transformation

| Before | After |
|--------|--------|
| Reactive churn reporting | Predictive churn prevention |
| Revenue loss post-exit | Revenue risk identified pre-exit |
| Broad retention spend | Precision-targeted intervention |
| Growth constrained by leakage | Revenue stabilized via retention |

---

#  Tech Stack

- SQL Server
- Tableau
- Python (Pandas, Scikit-learn, XGBoost)
- Jupyter Notebook

---

#  Project Architecture

Raw Data  
↓  
SQL Data Modeling  
↓  
Tableau Executive Dashboards  
↓  
Machine Learning (XGBoost)  
↓  
Revenue-Aware Threshold Optimization  
↓  
Retention Prioritization Framework  

---

##  Author

Dr. Samuel Israel  
Data Scientist
