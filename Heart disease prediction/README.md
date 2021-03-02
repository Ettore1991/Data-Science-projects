Heart disease prediction

Introduction and data

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient.

Methods:

I tried different combinations of preprocessing steps, feature selection steps, hyperparameters and algorithms in order to evaluate which pipeline performed the best.
The tested algorithms include LogisticRegression, Kneighbors, DecisionTree, RandomForest and Xgboost

Results:

RandomForest associated to robust scaling and Lasso feature selection reached 0.92 AUC and 0.94 Average precision
