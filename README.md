# Logistic-Regression

Logistic regression is a statistical method used in machine learning and statistics for predicting the probability of an event occurring. It is commonly employed in binary classification problems where the outcome variable is categorical and has two classes. Logistic regression is an extension of linear regression, but it is designed for predicting the probability of an observation belonging to a particular class.

### 1. Model Formulation:
   - Input Features (X): The independent variables or features used to make predictions.
   - Output (Y): The dependent variable or target variable, which is binary (0 or 1).

### 2. Logistic Function (Sigmoid):
   - Logistic regression uses the logistic function (also called the sigmoid function) to transform the linear combination of input features into a probability between 0 and 1.
   - The logistic function is given by: P(Y=1) = 1 / {1 + e^{-(b_0 + b_1x_1 + b_2x_2 + ... + b_nx_n)}
   - Here, P(Y=1) is the probability of the event Y=1, and e is the base of the natural logarithm.

### 3. Parameters:
   - b_0, b_1, b_2, ..., b_n are the coefficients associated with each input feature.
   - The goal is to find the optimal values for these coefficients to maximize the likelihood of the observed data.

### 4. Training:
   - The model is trained using a method called Maximum Likelihood Estimation (MLE) or optimization algorithms like gradient descent.
   - The objective is to maximize the likelihood function, which represents the probability of the observed outcomes given the model.

### 5. Decision Boundary:
   - The decision boundary is a threshold that separates the two classes based on the predicted probabilities.
   - For a binary classification task, if P(Y=1) > 0.5, the observation is predicted to belong to class 1; otherwise, it's predicted to belong to class 0.

### 6. Evaluation:
   - Common evaluation metrics for logistic regression include accuracy, precision, recall, F1 score, and the ROC-AUC curve.

### 7. Regularization:
   - Logistic regression can be regularized to prevent overfitting. Common regularization terms include L1 regularization (Lasso) and L2 regularization (Ridge).

### 8. Applications:
   - Logistic regression is widely used in various fields, including healthcare (disease prediction), finance (credit scoring), marketing (customer churn prediction), and more.

### 9. Assumptions:
   - Linearity in the log-odds.
   - Independence of errors.
   - No multicollinearity among independent variables.
   - Binary logistic regression assumes a binary dependent variable.

### 10. Software Implementation:
   - Logistic regression can be implemented using various programming languages and libraries, such as Python (scikit-learn, statsmodels), R, and others.

In summary, logistic regression is a powerful and widely used algorithm for binary classification tasks, providing interpretable results and playing a crucial role in predictive modeling.

Thank you . . .!
