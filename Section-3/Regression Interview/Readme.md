📊 Regression Interview Questions for Data Science / Data Analyst Freshers

This document contains commonly asked Regression-related interview questions for freshers entering Data Science or Data Analyst roles.
Each question is followed by a concise, conceptually strong answer that demonstrates fundamental understanding.

1. What is Regression?

Answer:
Regression is a supervised machine learning technique used to model the relationship between a dependent variable (target) and one or more independent variables (features).
It is mainly used for predicting continuous values, such as salary, price, temperature, or sales.

2. What is the difference between Regression and Classification?

Answer:
Regression predicts continuous numeric values, whereas classification predicts discrete class labels.
For example, predicting house price is a regression problem, while predicting whether an email is spam or not is a classification problem.

3. What is Simple Linear Regression?

Answer:
Simple Linear Regression models the relationship between one independent variable and one dependent variable using a straight line.
The equation is:

𝑦
=
𝑚
𝑥
+
𝑐
y=mx+c

where:

m is the slope

c is the intercept

4. What does the slope (m) represent in Linear Regression?

Answer:
The slope represents the rate of change of the dependent variable with respect to the independent variable.
It tells us how much the target variable will increase or decrease when the feature increases by one unit.

5. What is Multiple Linear Regression?

Answer:
Multiple Linear Regression is used when there are more than one independent variables predicting a single dependent variable.
Its equation is:

y=b0​+b1​x1​+b2​x2​+⋯+bn​xn​
	​

6. What assumptions are made in Linear Regression?

Answer:
Linear Regression assumes:

Linear relationship between features and target

Independence of observations

Homoscedasticity (constant variance of errors)

Normal distribution of residuals

No multicollinearity among features

7. What is Multicollinearity?

Answer:
Multicollinearity occurs when independent variables are highly correlated with each other.
It can make coefficient estimates unstable and reduce the interpretability of the model.

8. What is R-squared (R²)?

Answer:
R-squared measures how much variance in the dependent variable is explained by the independent variables.
Its value ranges from 0 to 1, where higher values indicate better model fit.

9. What is Adjusted R-squared?

Answer:
Adjusted R-squared adjusts the R² value by penalizing unnecessary features.
It increases only if a new feature improves the model performance, making it more reliable for multiple regression.

10. What is Mean Squared Error (MSE)?

Answer:
MSE is the average of the squared differences between actual and predicted values.
It penalizes larger errors more heavily and is commonly used as a loss function in regression.

11. Difference between MSE and RMSE?

Answer:
MSE is the squared error, while RMSE is the square root of MSE.
RMSE is preferred because it is in the same unit as the target variable, making interpretation easier.

12. What are residuals?

Answer:
Residuals are the differences between actual values and predicted values.
They represent the error made by the regression model.

13. What is Overfitting in Regression?

Answer:
Overfitting occurs when a model learns noise instead of the actual pattern, performing well on training data but poorly on unseen data.
It usually happens when the model is too complex.

14. How can overfitting be reduced in regression models?

Answer:
Overfitting can be reduced by:

Using regularization

Removing irrelevant features

Using cross-validation

Increasing training data

15. What is Regularization?

Answer:
Regularization is a technique used to prevent overfitting by adding a penalty term to the loss function, which restricts large coefficient values.

16. Difference between Ridge and Lasso Regression?

Answer:

Ridge Regression (L2) reduces coefficient magnitude but does not make them zero

Lasso Regression (L1) can shrink coefficients to zero, performing feature selection

17. When would you use Lasso over Ridge?

Answer:
Lasso is preferred when feature selection is required, especially when the dataset has many irrelevant features.

18. What is Polynomial Regression?

Answer:
Polynomial Regression models a nonlinear relationship between variables by transforming features into polynomial terms while still using linear regression.

19. Is Polynomial Regression linear or non-linear?

Answer:
It is linear in parameters but non-linear in features, which is why it is still considered a form of linear regression.

20. What evaluation metrics are commonly used for regression?

Answer:
Common regression metrics include:

R-squared

Adjusted R-squared

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

21. What is the difference between MAE and MSE?

Answer:
MAE calculates the average absolute error and is less sensitive to outliers, whereas MSE squares the error, giving more weight to larger errors.

22. Can Linear Regression handle outliers?

Answer:
Linear Regression is sensitive to outliers because it minimizes squared error, which can significantly affect the model fit.

23. What is Gradient Descent in Regression?

Answer:
Gradient Descent is an optimization algorithm used to minimize the loss function by iteratively updating model parameters in the direction of the negative gradient.

24. Batch vs Stochastic Gradient Descent?

Answer:

Batch Gradient Descent uses the entire dataset to update parameters

Stochastic Gradient Descent updates parameters using one data point at a time

25. When should you not use Linear Regression?

Answer:
Linear Regression should not be used when:

The relationship is highly non-linear

There is severe multicollinearity

Outliers dominate the dataset

Assumptions are strongly violated