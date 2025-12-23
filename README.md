# student-performance-regression-analysis
Project Overview
This project explores regression-based machine learning models to understand whether student performance can be predicted using demographic and academic-related factors.
The goal is not just prediction accuracy, but to evaluate how suitable regression models are for educational data and what their limitations reveal.

Objective
To predict students’ total academic score using regression techniques
To compare Linear Regression and Polynomial Regression
To analyse model performance using standard evaluation metrics
To understand whether basic demographic features are sufficient for prediction

Dataset
Dataset Name: StudentsPerformance.csv
Description: Contains student demographic information and scores in math, reading, and writing
Target Variable: total_score (sum of math, reading, and writing scores)
Dataset is uploaded.

Technologies Used
Python
Pandas & NumPy
Matplotlib
Scikit-learn
Jupyter Notebook

Project Workflow
1 - Data Preparation
Loaded dataset and created a clean working copy
Standardised column names
Engineered a new feature: total_score

2 - Feature Encoding
Converted categorical variables (gender, lunch type, test preparation, parental education) into numerical form using encoding techniques

Model Implementation
Linear Regression
Polynomial Regression

Model Evaluation
Models were evaluated using:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score

Key Results
Linear Regression Performance
MAE ≈ 31
RMSE ≈ 40
R² ≈ 0.16

Polynomial Regression Performance
No significant improvement over linear regression
R² score dropped further, indicating overfitting

Visualization
Scatter plot comparing Actual vs Predicted Total Scores
Reveals a weak linear relationship and high prediction variance

Key Insights
Regression models struggled to accurately predict student performance
Demographic features alone are not strong predictors of academic outcomes
Adding model complexity did not improve performance

Final Conclusion
Advanced regression techniques did not improve model performance, indicating that student performance cannot be reliably predicted using demographic factors alone. This highlights the importance of academic, behavioral, and environmental variables when modeling educational outcomes.

Future Improvements
Convert the problem into a classification task
Introduce academic history or attendance-related features
Experiment with tree-based and ensemble models
