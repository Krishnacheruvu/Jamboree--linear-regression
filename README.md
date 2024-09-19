# Jamboree--linear-regression
This project aims to predict the likelihood of admission to a graduate program based on various features such as GRE score, TOEFL score, academic ratings, and more. We developed and evaluated several regression models, including Ordinary Least Squares (OLS), Ridge Regression, and Lasso Regression, to identify the best-performing model for this task.

Features
GRE Score: Graduate Record Examination score.
TOEFL Score: Test of English as a Foreign Language score.
University Rating: Rating of the university.
SOP: Statement of Purpose strength.
LOR: Letter of Recommendation strength.
CGPA: Cumulative Grade Point Average.
Research: Whether the applicant has research experience (1 if yes, 0 if no).
Academic Rating: A calculated feature based on academic performance.
Models and Evaluation
1. Ordinary Least Squares (OLS) Regression
MAE: 0.0433
RMSE: 0.0624
R²: 0.8094
Adjusted R²: 0.7971
2. Ridge Regression
MAE: 0.0425
RMSE: 0.0609
R²: 0.8185
Adjusted R²: 0.8003
3. Lasso Regression
MAE: 0.0427
RMSE: 0.0617
R²: 0.8140
Adjusted R²: 0.7954
Insights
Ridge Regression achieved the best performance across all metrics, indicating it is the most effective model for predicting admission likelihood.
OLS and Lasso models showed comparable results, with OLS slightly better in MAE and Lasso in Adjusted R².
Residual Analysis
Breusch-Pagan Test: Failed to reject the null hypothesis, indicating homoscedasticity is present in the residuals.
Jarque-Bera Test: Rejected the null hypothesis, indicating that residuals are not normally distributed.
