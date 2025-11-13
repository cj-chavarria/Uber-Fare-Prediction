# Uber Fare Prediction

A Data Science class project predicting Uber ride fares using machine learning regression models.

## Overview
This project analyzes historical Uber ride data to build and compare multiple predictive models, selecting the best performer for fare estimation.

## Models Compared
1. **Linear Regression** - Baseline model
2. **Random Forest** - Best performer ✓
3. **Linear SVR** - Support vector regression
4. **MLP Regressor** - Neural network

All models were tuned using GridSearchCV with 5-fold cross-validation.

## Technologies
- **Python libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib
- **Evaluation metric**: RMSE (Root Mean Squared Error)

## Results
Random Forest Regressor achieved the best performance. Key findings:
- Geographic distance is the strongest predictor
- Temporal features (hour, day, month) significantly impact fares
- Ensemble methods outperformed linear models
