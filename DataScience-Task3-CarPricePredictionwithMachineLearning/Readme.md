# Car Price Prediction with Machine Learning

Oasis Infobyte Data Science Internship 

## Overview

This project builds a regression model to predict the selling price of a used car using features like brand, age, mileage, fuel type, transmission, seller type, and ownership history. It uses the Vehicle Dataset from Cardekho (Kaggle).

## Objective

Predict used car selling prices and identify which features most influence resale value.

## Dataset

- Source: Vehicle Dataset from Cardekho — https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho
- Target variable: Selling_Price
- Features: Brand, Year, Present Price, Kms Driven, Fuel Type, Seller Type, Transmission, Owner
- Download the CSV and place it in the same folder as the notebook before running.

## Tech Stack

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## Workflow

1. Data loading and inspection
2. Data cleaning (duplicates, missing values)
3. Feature engineering (Car_Age, Brand extraction)
4. Exploratory data analysis
5. One-Hot Encoding of categorical variables
6. Train-test split
7. Model training: Linear Regression, Random Forest Regressor
8. Model evaluation: MAE, RMSE, R2 Score
9. Feature importance analysis
10. Prediction example

## Results

| Model | MAE | RMSE | R2 Score |
|-------|-----|------|----------|
| Linear Regression |180194.99 | 385606.09 | 0.54 |
| Random Forest Regressor | 158918.38| 365567.41 | 0.59 |

Best performing model: Random Forest Regressor.

## Key Findings

- Car age and present price are the strongest predictors of resale value.
- Transmission type has a notable effect on price.
- Fuel type and brand contribute, but rare brands individually add little predictive value.





## Future Improvements

- Try Gradient Boosting or XGBoost
- Hyperparameter tuning with GridSearchCV
- Add features like engine capacity and mileage
- Apply log transformation to reduce price skewness
- Deploy as a web app using Streamlit or Flask

## Author

**Aman Sharma**
Data Science Intern, Oasis Infobyte

## Acknowledgment

Completed as part of the Oasis Infobyte Data Science Internship.