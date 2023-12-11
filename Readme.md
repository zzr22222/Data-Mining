**Project Name:** Customer Churn Judgement

**Project Goal:** 

1. Given corporate customer information, build a classification model to determine whether the corporate clients are likely to churn.

2. The scoring algorithm is based on accuracy; the higher the accuracy, the better the model is at correctly predicting corporate customer churn.

   The reference code for the scoring algorithm is as follows:

   from sklearn.metrics import accuracy_score y_true = [1, 0, 1, 0] y_pred = [1, 1, 1, 0] score = accuracy_score(y_true, y_pred)