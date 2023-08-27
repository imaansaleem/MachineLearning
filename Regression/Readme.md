## Comment on the results by comparing all models

Polynomial Regression and Model Complexity
The complexity of a polynomial regression model is determined by its degree. A linear model has a degree of 1, while a quadratic model has a degree of 2, and so on. The degree of the model corresponds to the number of coefficients that need to be estimated. As the degree increases, the model becomes more complex and requires more coefficients to be estimated.
In general, a more complex model will fit the training data better, but it may not generalize well to new data. Therefore, it is important to balance model complexity with model performance to avoid overfitting. Fitting polynomial regression models of different degrees can provide insight into the relationship between input features and the output variable. A linear model assumes a linear relationship between the input features and the output variable, while higher degree models can capture more complex relationships.
In our case, we found that a more complex model with higher degree provided better fit to the training data. However, we observed that the performance of the higher degree models decreased on the test data, indicating overfitting. Therefore, we concluded that a quadratic model provided the best balance between complexity and performance for our data.