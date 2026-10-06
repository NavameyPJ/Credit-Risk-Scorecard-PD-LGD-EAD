# Consumer Credit Risk Scorecard: PD, LGD, EAD & Expected Loss Engine

## Executive Summary
This project builds an institutional-grade Credit Risk Scorecard to forecast Probability of Default (PD) and quantify portfolio Expected Loss (EL) under Basel III and IFRS 9 regulatory frameworks.

## Key Outcomes & Risk Metrics
* **Dataset:** 150,000 borrower credit records.
* **Model Performance:** Achieved an **ROC-AUC score of 0.8107** using Logistic Regression with Feature Scaling (`StandardScaler`).
* **Primary Risk Drivers:** Identified Revolving Credit Line Utilization ($IV = 1.11$) and Historical Late Payments ($IV = 0.37 - 0.64$) via Weight of Evidence (WOE) and Information Value (IV) diagnostics.
* **Portfolio Loss Estimation:** Estimated **$9,100,000** in Expected Loss across a $300M test portfolio ($EAD = \$10,000$, $LGD = 45\%$), requiring a **3.03% statutory capital reserve ratio**.

## Tech Stack
* **Languages & Libraries:** Python (`pandas`, `numpy`, `scikit-learn`)
* **Frameworks & Models:** Basel III, IFRS 9 Rules, Logistic Regression, WOE/IV Diagnostics
