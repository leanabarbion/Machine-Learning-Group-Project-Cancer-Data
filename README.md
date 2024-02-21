# Breast Cancer Predictive Analysis Using Machine Learning

## Overview
This repository contains the culmination of our Machine Learning group project, focusing on the application of artificial intelligence in the medical field, specifically for breast cancer diagnosis. Understanding the high stakes involved in medical diagnostics, our project emphasizes the critical need for accuracy, the implementation of a human-in-the-loop approach, and the potential of AI to significantly enhance patient outcomes through early and precise cancer detection.

## Dataset
The dataset, curated by Dr. William H. Wolberg from the University Of Wisconsin Hospital, consists of 569 cases with 33 attributes, including diagnostic results (malignant or benign), and various cellular features of breast cancer specimens. The data has been meticulously cleaned and preprocessed for analysis, ensuring the removal of null values and the optimization of feature representation for our machine learning models.

## Methodology
Our approach leverages K-fold cross-validation (five folds) to ensure unbiased model evaluation and prevent overfitting. We've explored multiple machine learning algorithms, including Logistic Regression, Decision Trees, Random Forest, SVM, and Neural Networks, prioritizing Recall to minimize the risk of false negatives. Hyperparameter tuning was performed to optimize model performance, with a particular focus on enhancing the Recall metric due to its critical importance in medical diagnosis.

### Key Findings
- **Logistic Regression** emerged as our model of choice, offering a balance between high Recall and interpretability.
- **Feature Importance Analysis** using SHAP values and Permutation Feature Invariance identified key predictors such as `area_worst`, `concave_points_mean`, and `radius_se`.
- **Economic Analysis** underscored the cost-effectiveness of minimizing false negatives in a medical context.

## Conclusion and Future Recommendations
Our analysis underscores the importance of Recall in medical diagnostic models and the potential of machine learning to improve healthcare outcomes. 
Future directions include expanding the dataset, incorporating additional predictive variables, and further exploring the economic impact of diagnostic algorithms.
