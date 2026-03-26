# Project Title

Financial Health Prediction Challenge

## Overview

This project aims to classify Small and Medium Enterprises (SMEs) into three tiers of financial health: Low, Medium, and High. The index is a composite measure reflecting four key dimensions of business stability:
- Savings & Assets
- Debt & Repayment Ability
- Resilience to Shocks
- Access to Credit & Financial Services

The model is designed to help financial institutions and policymakers identify vulnerable businesses and support high-growth SMEs in emerging markets (Eswatini, Lesotho, Zimbabwe, Malawi).

https://zindi.africa/competitions/dataorg-financial-health-prediction-challenge


## Tech Stack

Language: Python 3.x

Modeling: XGBoost, CatBoost, LightGBM

Data Engineering: Pandas, NumPy

Visualization: Matplotlib

## Project Structure

```text
├── data/
│   ├── raw/           
│   ├── processed/     
│   └── submissions/
├── notebooks/
│   ├── 01_Exploratory_Data_Analysis.ipynb
│   └── 02_Model_Training.ipynb          
├── .gitignore  
├── README.md
└── requirements.txt
```

## Performance & Leaderboard Results

The model demonstrated strong generalization capabilities, maintaining high performance across both public and private evaluation sets.

* **Public F1-Score:** 0.8884
* **Private F1-Score:** 0.8749
* **Stability:** < 2% variance between sets, indicating minimal overfitting and high model reliability.
