# sp500_finance
# Hunting Tomorrow's Leaders: Using Machine Learning to Forecast S&P 500 Additions & Removal

This repository applies machine learning techniques to predict changes in **S&P 500 membership**—key events influencing investor behavior and market dynamics. By leveraging **Random Forest, Logistic Regression**, and **SVC** models, we identify potential index inclusions and deletions, offering actionable insights for alpha-capturing trading strategies.

## Overview

This project was completed as part of the **Data-Driven Methods in Finance** course at **Columbia University**. The model achieves a test F1-score of **0.85**, with **SHAP analysis** ensuring model transparency and interpretability.

## Repository Structure

1. **`EDA.ipynb`**  
   - Conducts **Exploratory Data Analysis** (EDA) to understand the dataset.  
   - Includes data cleaning, visualization, and preliminary analysis.

2. **`Modeling_Process.ipynb`**  
   - Covers the **entire pipeline**: feature engineering, model building, evaluation, and SHAP analysis.  
   - Compares the performance of **Random Forest**, **Logistic Regression**, and **SVC**.

3. **SHAP Plots**  
   - SHAP visualizations for all models are included, showcasing feature importance and model transparency.

4. **`requirements.txt`**  
   - Lists all Python dependencies needed to reproduce the analysis.

## Data Sources

The dataset integrates multiple financial and market sources spanning **2013–2023**. **WRDS (Wharton Research Data Services)**  used as the central platform to access and integrate the datasets.

1. **CRSP (Center for Research in Security Prices)**  
   - Daily stock prices, market capitalization, trading volumes, and S&P 500 membership data.

2. **Compustat Fundamentals**  
   - Financial statement indicators such as total assets, liabilities, net income, and more.

3. **IBES (Institutional Brokers' Estimate System)**  
   - Analyst coverage data (number of analysts providing earnings estimates).

4. **Audit Analytics**  
   - Data on auditor changes and financial restatements.


## Key Features

- **Machine Learning Models**: Random Forest (best performer), Logistic Regression, and SVC.  
- **Transparency**: SHAP analysis explains feature contributions for model predictions.  
- **Real-World Application**: Predictions for **Q3 2023** demonstrated the model’s practical value (e.g., addition of **Uber (UBER)**, removal of **SolarEdge Technologies (SEDG)**)

## Results

The **Random Forest model** achieved:

- **Test F1-Score**: 0.85  
- Superior performance compared to Logistic Regression and SVC models.

