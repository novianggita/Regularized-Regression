# 🧠 Regularized Regression with Ridge & LASSO (Python)

This project applies regularized regression techniques—**Ridge** and **LASSO**—on the Boston Housing dataset to demonstrate their effectiveness in handling multicollinearity and enhancing prediction accuracy.

## 📊 Dataset
- **Source**: Boston Housing Dataset
- **Target Variable**: `medv` (Median house value)

## 🧪 Workflow
1. Load and preview the dataset
2. Pre processing data: duplicate check, unvalid and missing value check, handling outlier
3. Split data into:
   - Pre-train: 80%
      - Train 80%
      - Validation 20% 
   - Test: 20%
4. Calculate VIF for multicollinearity check
5. Feature scaling using `StandardScaler`
6. Train Ridge & LASSO models with cross-validation
7. Applied on test set
8. Compare models using RMSE, MAE, MAPE, and R²
9. Choose the best model

## 📈 Model Performance
| Model   | Train RMSE  | Test RMSE | R² Score |
|---------|-------------|-----------|----------|
| Ridge   | 4.47        | 3.23      | 75.32    |
| LASSO   | 4.47        | 3.19      | 75.25    |


## 📁 Files
- `Regularized Regression using Python.ipynb`: Full code
- `Workflow.png`: Python code workflow



#DataScience #MachineLearning #Regularization #RidgeRegression #LassoRegression #Modeling #PredictiveAnalytics #MLTips


