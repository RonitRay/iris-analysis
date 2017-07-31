# iris-analysis
Basic ML project using Python, for modelling and simple analysis on the iris data set.

Based on the tutorial at http://machinelearningmastery.com/machine-learning-in-python-step-by-step/

The dataset was imported using pandas, then summarized on the console and visualized through univariate and multivariate plots to identify relationships and trends among different attributes, like a Gaussian distribution.

20% of the loaded data was separated to form a validation dataset, and the remaining 80% was used for training the model.
10-fold cross-validation (train on 9 parts, test on 1) was used, and accuracy was considered the metric for evaluation.

6 different algorithms, (2 linear, 4 non-linear) were used for predictive analysis:
* Logistic Regression (LR)
* Linear Discriminant Analysis (LDA)
* K-Nearest Neighbors (KNN).
* Classification and Regression Trees (CART).
* Gaussian Naive Bayes (NB).
* Support Vector Machines (SVM)

The results were compared for accuracy and plotted on a chart.'

KNN was then used on the validation set to generate a final accuracy score, confusion matrix, and classification report. The classification report consisted of
* precision
* recall
* f1-score
* support

The results were very good, with the consideration that the data set was very small.
