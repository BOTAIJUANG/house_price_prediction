# House Price Prediction

This project predicts house prices using machine learning techniques based on the Kaggle House Prices dataset.

## Dataset
Kaggle Competition:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

The dataset contains information about residential homes and their features.

## Project Structure

```
house-price-prediction
│
├── notebooks
│   └── house_price_baseline.ipynb
│
├── data
│   ├── train.csv
│   └── test.csv
│
├── scripts
│
└── README.md

```
## Methods

The following steps were applied in this project:

- Data cleaning
- Handling missing values
- Feature encoding using `pd.get_dummies`
- Training a RandomForestRegressor model

## Tools

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Model

The baseline model used in this project is:

RandomForestRegressor(random_state=42)

## Author

Botai Jiang  
MSc Data Science – University of Sheffield
