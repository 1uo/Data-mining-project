### Random Forests
Random forest means it consists of a large number of different decision trees that operate as an ensemble. Each decision tree in the random forest will output a class prediction and the class with the most votes becomes the model’s final prediction
Design and Training of the Forest:  We build the decision trees using a standard randomized training procedure. We will use scikit-learn as the tool for random forests. We set the number of trees to 100 as a reasonable default value. More trees may (or may not) perform better but will certainly take longer to run. Likewise, the more features we include for each review, the longer this will take.


### Logistic Regression
Logistic regression is a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). It is used to predict a binary outcome (1 / 0, Yes / No, True / False) given a set of independent variables.
That how we can use LR to predict whether the review is positive or negative. We still use scikit-learn as the tool for building LR model.


### SVM
A Support Vector Machine (SVM) is a discriminative classifier formally defined by a separating hyperplane. In other words, given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples. In two dimentional space this hyperplane is a line dividing a plane in two parts where in each class lay in either side.
