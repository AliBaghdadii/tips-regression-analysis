# tips-regression-analysis
## Predicting Tips Using Linear Regression

A machine learning project that explores restaurant tipping behavior and predicts the tip amount using linear regression models. The project uses the **Seaborn `tips` dataset** and covers data exploration, preprocessing, feature engineering, model training, and evaluation.

## Project Overview

The goal of this project is to predict the amount of money a customer leaves as a tip based on information about the restaurant bill and dining party.

The dataset contains **244 observations**. Each row represents one restaurant bill and its associated tip.

### Dataset Columns

| Column | Description |
|---|---|
| `total_bill` | Total bill amount in US dollars. |
| `tip` | Tip amount in US dollars. This is the target variable. |
| `sex` | Sex of the person paying the bill (`Male` or `Female`). |
| `smoker` | Indicates whether the dining party included a smoker (`Yes` or `No`). |
| `day` | Day of the week on which the meal took place (`Thur`, `Fri`, `Sat`, or `Sun`). |
| `time` | Meal period (`Lunch` or `Dinner`). |
| `size` | Number of people in the dining party. |

The dataset has no missing values. Categorical variables are encoded before training: binary categories are converted to numeric codes, while `day` is one-hot encoded.