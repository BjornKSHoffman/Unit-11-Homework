# Unit-11-Homework

## Resampling
## Which model had the best balanced accuracy score?
The Logistic regression model had a balanced accuracy score of 0.5689040775791564, while the SMOTE model had a score of 0.5625576626338076, ClusterCentroids had 0.5625576626338076 and SMOTEEN had 0.5466034946074106.
is defined as the average of recall obtained on each class.

The best value is 1 and the worst value is 0, so our Logistic Regression model had the highest ACCURACY.

## Which model had the best recall score?
RECALL = TP/(TP+FN)
8065/(9053 + 8065)
8438/(8680 + 8438)
8438/(8680 + 8438)
6908/(10210 + 6908)
Its a TIE. The SMOTE and ClusterCentroids models both had 0.492931417222

## Which model had the best geometric mean score?
.56
.56
.56
.53
It's a three way tie between the Logistic regression, SMOTE and ClusterCentroids models.

## Ensemble Learning
## Which model had the best balanced accuracy score?
Both models were almost perfectly accurate at a score of 0.9949433304272014. This leads me to think that something may have gone wrong with the input variables, but I can't figure out what.
## Which model had the best recall score?
Both models had recall scores of 0.99. This leads me to think that something may have gone wrong with the input variables, but I can't figure out what.
## Which model had the best geometric mean score?
BalancedRandomForestClassifier had a superior geo score at .56. However, the other model had a geo score of 0 so the troubleshooting may be needed.
## What are the top three features?
recall, f1 score, and the geo score all scored well for the BalancedRandomForestClassifier, at .57, .72, and .56 respectively.
