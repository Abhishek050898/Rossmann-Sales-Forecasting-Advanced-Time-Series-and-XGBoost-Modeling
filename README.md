# Rossmann Sales Forecasting: Advanced Time Series and XGBoost Modeling

## Project Overview
This project focuses on predicting sales for Rossmann stores using historical sales data. The dataset contains information for over 1,000 stores located in different regions of Germany. The goal is to forecast daily sales for a six-week period using various features, including promotions, competition, holidays, and store types.

## Dataset Information
- **train.csv**: Historical sales data from 2013 to 2015.
- **store.csv**: Additional store-related information such as competition and promotions.
- **test.csv**: Data for which sales predictions need to be made.

## Objectives
1. **Data Preprocessing**:
   - Handle missing values using imputation techniques (mean, median, mode).
   - Feature extraction and creation (e.g., competition duration, promotions).
   - Encoding categorical features (e.g., store type, assortment).

2. **Exploratory Data Analysis (EDA)**:
   - Univariate, multivariate, and time-series analysis of sales data.
   - Insights into promotions, holidays, store types, and their impact on sales.

3. **Modeling**:
   - Use XGBoost for sales prediction due to its ability to handle time-series data and non-linear relationships.
   - Hyperparameter tuning for improved performance.

## Key Features
- **Handling Missing Data**: Imputation techniques to fill in missing values.
- **Feature Engineering**: Extracted additional features such as `PromoOpen` and `CompetitionOpen`.
- **Time Series Analysis**: Seasonal and trend analysis of store sales.
- **Model Selection**: XGBoost was selected for its strong performance on time-series and tabular data.

## Results
- **Initial RMSE**: 1271.0006 (basic model).
- **Tuned RMSE**: 691.433 with an RMSPE of 11.98%.

## Installation & Usage
### Requirements:
- Python 3.9
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`

### Install Dependencies
```bash
pip install requirements.txt
