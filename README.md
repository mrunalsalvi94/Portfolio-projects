# Portfolio-projects

This repository contains my portfolio projects that portray my learning and skills for a career in Machine Learning.

## 1.NLP project - Kaggle Mercari Challenge
Source: https://www.kaggle.com/c/mercari-price-suggestion-challenge

**Evaluation metric: RSMLE**

### Part1:
- **Mercari, a community-powered shopping app, is looking for an algorithm that would predict and suggest the right product prices to their customers.**
- This project is a combination of NLP and regression task.
- It includes indepth EDA of the features with vizualizations using Seaborn and Matplotlib.
- Use of different techniques including text processing for NLP, encoding and vectorization.

### Part2:
- Use of **Topic Modeling** with the help of **LDA** to find the topics and the effectiveness of LDA using Coherance.
- Use of Eli5 library. (https://eli5.readthedocs.io/en/latest/overview.html)
- Eli5 library shows the correlation of each feature/text with the target variable. We can inspect features and weights because we’re using a bag-of-words vectorizer and a linear classifier (so there is a direct mapping between individual words and classifier coefficients).
- Use of different combinations of vectorizers and models to understand the correlation of text with the target and checking their weights and predictions.
- Fitting Ridge and Lasso regression models and predicting the target variable.



## 2. Bank Marketing Analysis
**Evaluation metric: ROC-AUC**

- The Bank Marketing project involves prediction of whether a client will subscribe to a Term deposit loan or not.
- Data preprocessing, EDA and feature visualization using Matplotlib.
- Handling the imbalance dataset by applying SMOTE oversampling technique.
- Use of classification models Logistic Regression, DecisionTree Classifier, RandomForest Classfier, XGBClassifier, GradientBoostingClassifier.
- Use of RFE on training models.
- Hyperparameter tuning using GridSearchCV.


## 3. HR analytics:
**Evaluation metric: F1-score**

- The HR analytics project involves understanding the employee turnover.
- To create a model that predicts the likelihood if a certain employee will leave the company or not.
- Extensive EDA and addressing data imbalance using resampling techniques.
- Use of Logistic regression, RandomForest and Gradient Boosting algorithms to determine F1-scores.
- Understanding feature importance.
