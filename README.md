# Logistic Regression for Classification🪂🪂
Logistic regression is a statistical method used for binary classification problems. It models the probability that a given input belongs to a particular class. It's a type of regression analysis where the dependent variable is categorical (binary in this case), unlike linear regression where the dependent variable is continuous.


![TextClassificationExample_spam](https://github.com/Abdelrahman-Amen/Logistic_Regression_From_Scratch/assets/103226865/235a53b7-22e9-45af-b421-aeb44bc60999)

In logistic regression, the logistic function (also known as the sigmoid function) is used to model the probability:



![Screenshot 2024-04-06 224333_sigmoid](https://github.com/Abdelrahman-Amen/Logistic_Regression_From_Scratch/assets/103226865/5d696fe9-7cd3-42cf-ab17-c4506f2bdebd)


# Cost Function
The cost function in logistic regression is used to measure the accuracy of the model's predictions. A common cost function for logistic regression is the binary cross-entropy loss function, also known as log loss:


![Screenshot 2024-04-06 224100_cost](https://github.com/Abdelrahman-Amen/Logistic_Regression_From_Scratch/assets/103226865/20bb2569-5778-48f7-ab24-606bb772452c)


The goal is to minimize this cost function by adjusting the parameters  during the training process using optimization algorithms like gradient descent.



# Confusion Matrix:
A confusion matrix is a table that is often used to describe the performance of a classification model on a set of test data for which the true values are known. It allows visualization of the performance of an algorithm.




Here's how a confusion matrix is typically structured for binary classification:




![Screenshot 2024-04-06 224321_matrix](https://github.com/Abdelrahman-Amen/Logistic_Regression_From_Scratch/assets/103226865/3317020c-9fd5-43de-841d-efa3efc54080)



### True Positive (TP): The cases where the model correctly predicts the positive class.
### True Negative (TN): The cases where the model correctly predicts the negative class.
### False Positive (FP): The cases where the model incorrectly predicts the positive class.
### False Negative (FN): The cases where the model incorrectly predicts the negative class.
From the confusion matrix, various performance metrics like accuracy, precision, recall, and F1-score can be calculated, which provide insight into the model's performance.



These topics covered provide a fundamental understanding of logistic regression for classification, the associated cost function, and how performance is evaluated using a confusion matrix.




