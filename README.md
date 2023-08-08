We trained and evaluated 9 supervised machine learning classification models.

Logistic Regression
Naive Bayes
Decision Tree
Random Forest
AdaBoost
Support Vector Machine
Linear Discriminant Analysis
Multilayer Perceptron
K-Nearest Neighbors



Further, to get the best performance, hyperparameter tuning was carried out using RandomSearchCV and GridSearchCV. K-fold cross-validation with 5 folds was also performed on the training set. To handle model interpretability, appropriate graphs and figures were used.Accuracy for the attrition decision is a biased metric, and hence we evaluated the model on all the following classification metrics: accuracy, precision, recall and F1 Score.

We observe that the most important features were MonthlyIncome followed by OverTime and Age, while the least important features were Performance Rating, Gender and BusinessTravel.


Best Performing Model
The best performance was obtained in Random Forest Model with PCA and Oversampling with an accuracy of 99.2%, the precision of 98.6%, recall of 99.8% and F1 Score of 99.2%.
