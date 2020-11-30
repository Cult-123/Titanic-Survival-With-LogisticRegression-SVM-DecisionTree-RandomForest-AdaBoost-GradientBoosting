# Titanic-Survival-With-LogisticRegression-SVM-DecisionTree-RandomForest-AdaBoost-GradientBoosting
Python Data Science Project, Titanic Survival Prediction using:

- LogisticRegression (89.83 % Accuracy)
- Support Vector Machine (88.70 % Accuracy)
- Decision Tree (89.26 % Accuracy)
- Random Forest (89.26 % Accuracy)
- AdaBoostClassifier (88.13 % Accuracy)
- GradientBoostingClassifier (89.26 % Accuracy)

For other Accuracy Details Please Check the Project. Other Accuracy Criterias are AUC & ROC Curve, Confusion Matrix, Classification Report, recall_score, precision_score etc.

## Problem Statement
The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
In this challenge, we have to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## Project Overview
In this Project I have unleashed the useful Data Science insights using this Titanic dataset and performed the feature selection, feature engineering & missing data handling precisely to build Classification models. In this project I have used 6 types of Classification Algorithms which are Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, Ada-Boost-Classifier, Gradient-Boosting-Classifier. 6 Algorithms along with combining the power of best statistical rules & principles to maximise accuracy at its best followed by all statistical conditions. The best thing is my model is not having any Multicollinearity Problem. All features are fulfilling Statistically Significant concept respect to the target variable.

## This Project is divided into 44 major steps which are as follows:
1. [Check out the Data](#data-check)
2. [Importing Libraries & setting up environment](#imp-lib)
3. [Loading dataset](#data-load)
4. [Normality Check of Continuous Variables/Features](#norm-check)
5. [Treating Missing Values & Feature Engineering](#miss-val)
6. [Dropping Features after Feature Engineering](#drop-feature)
7. [Redo Feature Engineering](#redo-feature)
8. [Again Drop unwanted Features](#again-drop)
9. [Check & Drop Duplicate Rows](#drop-dupli)
10. [Exploratory Data Analysis ( EDA )](#data-expo)
11. [Measures Of Association between Categorical Variables](#cate-asso)
12. [Measures Of Association between Categorical & Continuous Variables](#cate-continu)
13. [Saving The Processed Data](#save-data)
14. [Correlation/Association Check using Phik](#corr-check)
15. [Feature Selection/Removal](#feature-removal)
16. [Encoding Features](#feature-removal)
17. [Train & Test Split Selection (Logistic Regression)](#train-split)
18. [Multi-Colinearity Check](#multi-check)
19. [Final Implmentation of Titanic Logistic Regression](#final-model)
20. [Logistic Regression Results](#log-result)
21. [Confusion Matrix (with & without Normalization)](#conf-norm)
23. [ROC Curve (Logistic Regression)](#ROC-Curve)
24. [Precision Recall Curve (Logistic Regression)](#Recall-Curve)
25. [Logistic Regression Tuning](#Log-Tuning)
26. [Logistic Regression Tuning Result](#Log-TuningResult)
27. [Support Vector Machine (Titanic)](#Titanic-SVM)
28. [SVM Results](#SVM-Result)
29. [Titanic SVM Confusion Matrix (With & Without Normalization)](#SVM-Matrix)
30. [SVM ROC Curve for Titanic](#SVM-ROC)
31. [SVM Precision Recall Curve for Titanic](#SVM-Precision)
32. [Support Vector Machine Tuning](#SVM-Tuning)
33. [SVM Tuning Result (recall_score, precision_score, classification_report)](#SVM-TuneResult)
34. [Decision Tree](#Decision-Tree)
35. [Decision Tree Result (classification_report, confusion_matrix, recall_score, precision_score)](#Decision-Result)
36. [Visualizing Decision Tree](#Viz-Tree)
37. [Decision Tree Tuning](#Tree-Tuning)
38. [Random Forest](#Random-Forest)
39. [Visualizing Random Forest Tree](#Viz-Tree)
40. [ADA-Boost Forest/Stumps Forest Classifier](#ADA-Boost)
41. [ADA-Boost Forest/Stumps Forest Classifier Hyperparametre Tuning](#ADA-Boost)
42. [GradientBoostingClassifier](#Gradient-Boosting)
43. [Random Forest](#Random-Forest)
44. [GradientBoostingClassifier Hyperparameter Tuning](#Gradient-Tune)
