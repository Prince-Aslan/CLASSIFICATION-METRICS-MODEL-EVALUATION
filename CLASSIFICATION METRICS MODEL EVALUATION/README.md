# BINARY-CLASSIFICATION-METRICS-MODEL-EVALUATION

## Brief Introduction:
The main objective of this projct is 
In this classification project, I trained a logistic regression model and evaluated its performance by calculating overall accuracy from its confusion matrix ONLY.

## Concern:
The EDA revealed that an indication of imbalance in class distribution or an implication that accuracy might not be a suitable performance metric as the model could simply predict the majority class for all instances and still achieve a deceptively high accuracy.

## Recommendation:
"The dataset exhibits a significant class imbalance, with 152 instances labeled as Unsuitable compared to 48 labeled as Suitable.

This imbalance likely contributes to the high accuracy of 87.5%, as the model may be biased towards predicting the majority class. 
Therefore, relying solely on accuracy to evaluate the model's performance is insufficient.

To gain a more comprehensive understanding, it's recommended to employ additional evaluation metrics such as precision, recall, F1 score, and AUC-ROC."

## Data Handling-Alternative Approach:
Methods or techniques such as SMOTE (Synthetic Minority Over-sampling Technique) and/or STRATIFY can be used to handle the class imbalance thereby, improving the overall model performace
