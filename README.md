# Improving the Credit Line Approval Process for Advertisers using ML

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/Jay06eng/credit-line-approval-ml/blob/main/notebooks/credit_line_approval_applied_ml.ipynb](https://colab.research.google.com/drive/1l1bkfJEkTjhjgDliyji2e1zRPmXR16l2?usp=sharing))

 Applied analytics and explainable ML to improve credit decisioning, reduce reactive interventions, and enhance advertiser experience.  

 ⚠️ This project uses **synthetic data only**. All financial information is simulated to protect confidentiality.



## Background

This project is inspired by finance transformation work I conducted while leading credit and collections initiatives within a Finance Order-to-Cash transformation organization at Pinterest.

The Credit & Collections team supported a large advertiser and agency ecosystem with diverse spend patterns, payment behaviors, and growth trajectories. Credit-line decisions directly impacted advertiser experience, revenue continuity, and financial risk exposure.

While utilization thresholds such as 80% and 100% were effective safeguards, they provided limited insight into which advertisers actually required intervention and often resulted in reactive reviews.

This project demonstrates how I used applied analytics to improve decision quality while maintaining governance.



## Why this project exists


Credit-line reviews were primarily triggered by static utilization thresholds, resulting in high alert volume, reactive actions at 100% utilization, and inconsistent prioritization.


As the program lead, my objectives were to identify predictive operational drivers, improve review prioritization, balance risk and customer experience, and enable scalable decision support.


I led the end-to-end initiative, partnering across Finance, Sales Specialists, Data Science, Product and Engineering teams, defining metrics, designing features, and applying applied analytics.


This approach can reduce unnecessary manual reviews by approximately **20–30%**, enable earlier intervention for high-risk advertisers, and improve transparency in credit decisions.



## Study Overview

**Objective**  
Identify which operational factors most strongly influence credit scores to improve credit-line evaluations and customer experience.

**Key questions**
- Which advertiser behaviors correlate with healthier credit outcomes?
- Which factors remain significant when evaluated together?
- How can analytics improve CX without increasing financial risk?





## Variables Used

**Outcome (Dependent Variable)**
- Credit Score (synthetic proxy for internal creditworthiness)

**Predictors (Independent Variables)**
- Advertiser tenure
- On-time payment rate
- Average monthly spend
- Spend volatility
- Credit utilization

---

## Methodology

Correlation Analysis
Used to assess:
- Direction of relationships
- Strength of association

Correlation supports signal discovery but does not imply causation.

Linear Regression
Multiple linear regression was applied to:
- Estimate marginal impact of each factor
- Compare predictors while controlling for others
- Identify the strongest drivers of credit outcomes

This approach prioritizes explainability, a critical requirement in finance environments.

---

## Notebook

👉 Open and run the notebook here:  
[Open in Google Colab]([https://colab.research.google.com/github/Jay06eng/credit-line-approval-ml/blob/main/notebooks/credit_line_approval_applied_ml.ipynb](https://colab.research.google.com/drive/1l1bkfJEkTjhjgDliyji2e1zRPmXR16l2?usp=sharing))

---

## Why this matters

This project reflects how applied ML is used in real finance operations:
- To support human decision-making
- To improve prioritization and transparency
- To balance risk management with customer experience
