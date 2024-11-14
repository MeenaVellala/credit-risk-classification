**Credit Risk Classification Report**

Overview of the Analysis

The purpose of this analysis is to build a logistic regression model to predict the creditworthiness of borrowers using historical lending data from a peer-to-peer lending service. The model classifies loans as either "healthy" (low risk) or "high-risk" (potential default) based on various borrower characteristics. By accurately predicting the likelihood of default, this model aims to support informed lending decisions and risk management strategies.

**Results:**

**Accuracy Score:** The logistic regression model achieved an overall accuracy of 99%.

**Precision Score:**

Class 0 (Healthy Loans): 1.00

Class 1 (High-Risk Loans): 0.84

**Recall Score:**

Class 0 (Healthy Loans): 0.99

Class 1 (High-Risk Loans): 0.94

**F1 Score:**

Class 0 (Healthy Loans): 1.00

Class 1 (High-Risk Loans): 0.89

**Summary**

The logistic regression model demonstrates strong predictive capabilities, with high overall accuracy and excellent performance in classifying healthy loans. For high-risk loans, the model achieves good recall (0.94), meaning it identifies most high-risk cases accurately, though with a slightly lower precision (0.84), indicating room to reduce false positives. This balance of precision and recall suggests that the model effectively identifies potential defaults while minimizing misclassification of healthy loans.

Recommendation
Given its high accuracy and strong performance in identifying both healthy and high-risk loans, this model is recommended for use in the company’s loan risk evaluation processes. However, efforts to further refine precision for high-risk classifications could enhance the model's value in risk management and decision-making.

