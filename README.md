# credit-risk-classification

# Module 12 Report Template

## Overview of the Analysis

In this section, I have described the analysis completed for the machine learning models; this includes:

  * The purpose of the analysis.

  This analysis was performed to identify the creditworthiness of borrowers.

  * An explanation of what financial information the data was on, and what what was needed to calculate the predictions.

  I have used various techniques to train and evaluate a model based on loan risk by using a dataset of historical lending activity from a peer-to-peer lending services company to   build a model that can identify the creditworthiness of borrowers.

  * Variables used for the predictions:

  'value_counts' was used to check the balance of our target values.

  * The stages of the machine learning process as part of this analysis:

    - The Data was split into Training and Testing Sets
    -  A Logistic Regression Model was created with the Original Data
    -  Credit Risk Analysis Report was written which provided an overview of the analysis with a summary of the results. 

  * Methods you used:
  
  The Logistic Regression Model was used to perform this analysis.

---

## Results

The balanced accuracy scores and the precision and recall scores are appended below:

  - Accuracy:  99.24%
  - Precision: 87.46%
  - Recall:    89.28%
  - F1 Score:  88.36%

---

## Summary

After observing the above results, the accuracy seems to be good enough to start exploring this kind of algorithms to assess loan risk and to identify the creditworthiness of borrowers.

For the 0 (healthy loans) label: Precision, Recall and f1-score are all 1.00.

This means that the model has high precision and does really well when predicting a healthy loan (except for a small percentage of false positives).
The model also has high recall which means that it can identify most of the healthy loans (small percentage of false negatives). 
The F1-score is also high, indicating a good balance between precision and recall.

For high-risk loans the precision is 0.87, the recall is 0.89, and the f1-score is 0.88, meaning that this model does moderately well in predicting instances.
______________________________________________________________________________________________________________

For the 1 (high-risk loans) label: Precision = 0.87, Recall = 0.89, f1-score = 0.88.

The model's performance for high-risk loans is relatively good but not as perfect as for healthy loans. It has a precision of 0.87 indicating that when the model predicts a high-risk loan, it is correct about 87% of the time, but there would still be some false positives. The recall is 0.89, suggesting that the model captures 89% of the actual high-risk loans but may still miss a few (false negatives). The F1-score is 0.88, indicating a reasonable balance between precision and recall.

In summary, this logistic regression model performs very well for both the 0 (healthy loan) and 1 (high-risk loan) labels, with high accuracy, precision, recall, and F1-scores for both classes. 
The data has a  disproportionately larger number of healthy loans compared to high-risk loans so it is especially good at correctly identifying healthy loans, while its performance for high-risk loans is not quite as strong.
