# Heart-Failure-prediction
We have used 9 different classification models to predict the chances of heart failure.
The intial data set is an amalgation of 5 different data sets combined toghether :https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
The data sets has 11 different attributes among which 10 attributes(indepent) are used to predict whether the person is at risk of suffering a heart failure or not.
It was filtered for duplicates and other anomalies and outliers to give us 918 observations for prediction.
We have used 11 known classification models:1)Logistic Regression 2)Naives Bayes prediction 3)K-nearest Neighbour
4)SVM 5)kernel-SVM 6)Desicion Tree 7)Random forrest classifier 8)XGboost 9)A-NN
We tried both the train_test_split as well as k-fold(with 10 folds) methods and determined that Random forrest was the best performing Model giving us an intial accuracy of 87.29
We fine tuned the model via grid search to arrive at an accuracy of 87.94
