# Improving the Credit-Line Approval Process for Advertisers Using Explainable ML

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1l1bkfJEkTjhjgDliyji2e1zRPmXR16l2?usp=sharing)

Applied analytics and explainable machine learning to improve credit decisioning, reduce reactive interventions, and enhance advertiser experience.

> ⚠️ This project uses **synthetic data only**. All financial information is simulated to protect confidentiality.

---

## Overview

This project is inspired by finance transformation work I led while driving credit and collections initiatives within a Finance Order-to-Cash transformation organization at Pinterest.

The Credit & Collections team supported a large advertiser and agency ecosystem with diverse spend patterns, payment behaviors, and growth trajectories. Credit-line decisions directly affected advertiser experience, revenue continuity, and financial risk exposure.

Traditional review triggers such as `80%` and `100%` utilization were useful safeguards, but they often generated high alert volume, reactive escalations, and limited insight into which advertisers actually required intervention.

This project shows how applied analytics and explainable ML can improve decision quality while maintaining governance.

---

## Problem Statement

Credit-line reviews were primarily triggered by static utilization thresholds, resulting in:

- High alert volume
- Reactive interventions at `100%` utilization
- Inconsistent prioritization across accounts
- Limited visibility into predictive operational drivers

---

## Project Goals

As program lead, my goals were to:

- Identify operational factors that influence creditworthiness
- Improve review prioritization
- Balance risk management with customer experience
- Create scalable, explainable decision support

---

## Business Impact

This project illustrates how an analytics-driven approach could:

- Reduce unnecessary manual reviews by approximately `20-30%`
- Enable earlier intervention for higher-risk advertisers
- Improve transparency and consistency in credit decisions
- Support better customer experience without increasing financial risk

---

## Study Objective

Identify which operational factors most strongly influence a synthetic creditworthiness score used to support credit-line evaluations.

### Key Questions

- Which advertiser behaviors correlate with healthier credit outcomes?
- Which factors remain significant when evaluated together?
- How can analytics improve customer experience without increasing financial risk?

---

## Dataset

### Outcome Variable
- **Credit Score**: synthetic proxy for internal creditworthiness

### Predictor Variables
- Advertiser tenure
- On-time payment rate
- Average monthly spend
- Spend volatility
- Credit utilization

---

## Methodology

### 1. Correlation Analysis
Used to assess:

- Direction of relationships
- Strength of association
- Early signal discovery

> Correlation helps identify patterns, but it does not imply causation.

### 2. Multiple Linear Regression
Used to:

- Estimate the marginal impact of each factor
- Compare predictors while controlling for others
- Identify the strongest drivers of credit outcomes

This approach prioritizes **explainability**, which is especially important in finance environments where transparency and governance matter.

---

## Why Explainable ML

In financial operations, decision support must be understandable and defensible.

This project emphasizes explainable methods because they help teams:

- Understand why a recommendation is made
- Improve consistency in manual reviews
- Support governance and stakeholder trust
- Balance automation with human judgment

---

## Notebook

Open and run the notebook here:

[Open in Google Colab](https://colab.research.google.com/drive/1l1bkfJEkTjhjgDliyji2e1zRPmXR16l2?usp=sharing)

---

## Why This Matters

This project reflects how applied ML can support real finance operations by helping teams:

- Improve prioritization
- Reduce reactive work
- Increase transparency
- Support better human decision-making
- Balance risk management with customer experience

---

## Disclaimer

This project is intended for educational and portfolio purposes only.

All data is synthetic and does not represent real advertisers, customers, or internal financial information.
