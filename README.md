# Amazon Wipes — Price Analysis

Regression modeling of Amazon wipes prices on a scraped catalog of
17,004 ASINs.
Personal care category research · Google Colab / Python

## Objective
Understand what drives wipes prices on Amazon.com: model price from
product attributes (count/pack, ratings, brand) across the full scraped
catalog, and compare model performance to find the most reliable pricing
signals.

## Data
Cleaned Amazon web-scraped dataset: **17,004 unique ASINs** with ratings,
of which **2,979 match Profitero API ASINs**.

## What the notebook does (`Amazon_Wipes_Price_Analysis_V1_05292026.ipynb`, 338 cells)
- **EDA** of price, count/pack, ratings, and brand distributions
- **Regression models (scikit-learn)** — Linear Regression, Ridge, Lasso,
  Decision Tree, Random Forest, Bagging, and KNN regressors, tuned with
  GridSearchCV and compared on R² / MAE / RMSE
- **statsmodels** for statistical modeling; **Plotly**, matplotlib, and
  seaborn for interactive and static charts
- *(Uploaded with outputs cleared — the original notebook is 55 MB+ of
  embedded chart images, over GitHub's practical limits.)*

## Tools & packages
- **scikit-learn** — regression modeling, GridSearchCV tuning, metrics
- **statsmodels** — statistical modeling
- **pandas / numpy** — data cleaning and preparation
- **Plotly + matplotlib + seaborn** — visualization
- **Google Colab** — Drive-mounted dataset
