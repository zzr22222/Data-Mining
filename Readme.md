**Project Name:** Customer Churn Judgement

**Project Goal:** 

1. Given corporate customer information, build a classification model to determine whether the corporate clients are likely to churn.

2. The scoring algorithm is based on accuracy; the higher the accuracy, the better the model is at correctly predicting corporate customer churn.

   The reference code for the scoring algorithm is as follows:

   from sklearn.metrics import accuracy_score y_true = [1, 0, 1, 0] y_pred = [1, 1, 1, 0] score = accuracy_score(y_true, y_pred)

**Solution:**

• Utilized data visualization and feature engineering techniques such as LabelEncoder to examine costomer characteristics, and employed chi-square tests and ANOVA for feature selection.
• Combined various machine learning techniques, including GridSearchCV, coordinate descent, model fusion, ensemble learning, and deep neural networks to finalize prediction model.
• Evaluated the model with confusion matrix and obtained the accuracy of 0.8034.
