# student-performance-regression-analysis
Explored regression models to predict students’ total scores from demographic and academic features, assessing model suitability and limitations.

The Objective is to:
* Predict total academic score
* Compare Linear vs Polynomial Regression
* Evaluate models using MAE, RMSE, R²

**Dataset:**
* `StudentsPerformance.csv` – contains demographics and scores in math, reading, and writing
* Target: `total_score` (sum of all subjects)

**Technologies:**
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook

**Workflow:**
1. Data cleaning and feature engineering (`total_score`)
2. Encoding categorical variables
3. Implemented Linear & Polynomial Regression
4. Evaluated using MAE, RMSE, R²
5. Visualized Actual vs Predicted scores

**Key Results:**
* Linear Regression: R² ≈ 0.16 (weak correlation)
* Polynomial Regression: Overfitting, no improvement

**Insights:**
* Demographics alone are poor predictors
* Model complexity didn’t improve performance

**Conclusion & Future Work:**
* Regression cannot reliably predict performance using basic demographics
* Future: classification approach, include academic/attendance features, explore tree-based models

