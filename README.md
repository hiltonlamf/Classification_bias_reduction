# Reducing Bias Towards the Majority Class in Classification Models

## Overview

This notebook addresses class imbalance in a binary classification task using SMOTE (Synthetic Minority Over-sampling Technique) and evaluates multiple models, including Naïve Bayes, K-Nearest Neighbours (KNN), and Decision Trees. The dataset (appendicitis.csv) undergoes preprocessing, including categorical label binarisation, followed by hyperparameter tuning via GridSearchCV with cross-validation to minimise recall disparity between classes. A custom recall difference metric is implemented to ensure a more balanced predictive performance across both classes.

## Key Results
- SMOTE and hyperparameter tuning effectively reduce class imbalance, significantly improving recall for the minority class.
- While overall accuracy is slightly impacted, confusion matrices and classification reports show a more equitable distribution of predictions, aligning better with the true label distribution.
- The approach demonstrates the effectiveness of bias-mitigation techniques in classification tasks, ensuring fairer model performance.
