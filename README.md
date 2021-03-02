Customers churn prediction

Introduction:

This dataset is about predicting whether a customer will change telecommunications provider, something known as "churning".

Data:

The training dataset contains 4250 samples. Each sample contains 19 features and 1 boolean target variable "churn" which indicates the class of the sample

Methods:

I tried different combinations of preprocessing steps, feature selection steps and hyperparameters in order to evaluate which pipeline performed the best.
The algorithm used is XGBClassifier

Results:

0.95 AUC score
