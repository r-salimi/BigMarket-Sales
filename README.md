# Big Mart Sales

## Project Overview
Predicting item outlet sales using machine learning regression models.

## Dataset
Big Mart Sales dataset.

## Approach
- Exploratory Data Analysis
- Data cleaning
- Missing value imputation
- Feature encoding
- Feature scaling
- Train-test split
- Cross-validation

## Models
- Dummy Regressor
- Linear Regression
- Ridge Regression
- KNN Regression
- Random Forest

## Evaluation
Models were evaluated using:
- MAE
- RMSE
- R²

## Conclusion
### Final Model Comparison

| Model                         |        MAE |        RMSE |         R² |
| ----------------------------- | ---------: | ----------: | ---------: |
| **Linear Regression**         | **792.68** | **1070.74** | **0.5782** |
| Ridge Regression (`alpha=10`) |     792.81 |     1070.99 |     0.5780 |

Linear Regression achieved slightly better performance than the tuned Ridge Regression model across two evaluation metrics. Therefore, Linear Regression was selected as the final model.

