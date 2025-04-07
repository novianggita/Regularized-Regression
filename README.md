# 🧠 Regularized Regression with Ridge & LASSO (Python)

This project applies regularized regression techniques—**Ridge** and **LASSO**—on the Boston Housing dataset to demonstrate their effectiveness in handling multicollinearity and enhancing prediction accuracy.

## 📊 Dataset
- **Source**: Boston Housing Dataset
- **Target Variable**: `medv` (Median house value)

## 🧪 Workflow
1. Load and preview the dataset
2. Split data into:
   - Train: 64%
   - Validation: 16%
   - Test: 20%
3. Calculate VIF for multicollinearity check
4. Feature scaling using `StandardScaler`
5. Train Ridge & LASSO models with cross-validation
6. Compare models using RMSE and R²
7. Visualize predictions vs actuals

## 📈 Model Performance
| Model   | Train RMSE  | Test RMSE | R² Score |
|---------|-------------|-----------|----------|
| Ridge   | 4.78        | 5.16      | 74.85    |
| LASSO   | 5.17        | 5.13      | 70.57    |


## 📁 Files
- `Regularized Regression using Python.ipynb`: Full code
- `boston.csv`: Dataset used
- `Workflow.jpg`: Python code workflow


