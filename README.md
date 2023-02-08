# Credit Risk Analysis

## Overview of Analysis
### Purpose and Approach
The purpose of this analysis is to predict credit risk. As a part of this analysis, multiple models will be tested in order to determine which Machine Learning (ML) model is able to best predict credit risk. The models tested include Logistic Regression model with a variety of sampling techniques including (1) an oversampling model, (2) a Synthetic Minority Oversampling Technique (SMOTE), (3) a Cluster Centroid undersampling technique, (4) a combination SMOTE and Edited Nearest Neighbor (ENN) technique. In addition, we tested a Balanced Random Forest model and an Ensemble Model.
  

## Results
### Outcomes from Models
- The Logistical Regression model with an oversampling technique had a balanced accuracy score of 0.64, precision score of 0.99, and recall of 0.64.
- The Logistical Regression model with the SMOTE technique had a balanced accuracy score of 0.65, precision score of 0.99, and recall of 0.65.
- The Logistical Regression model with the Cluster Centroid undersampling technique had a balanced accuracy score of 0.56, precision score of 0.99 and recall of 0.56.
- The Logistical Regression model with the SMOTEENN technique had a balanced accuracy score of 0.63, precision score of 0.99 and recall of 0.63.
- The Balanced Random Forest model had a balanced accuracy score of 0.77, precision score of 0.99 and recall of 0.89.
- The Ensemble Model had a balanced accuracy score of 0.77, precision score of 0.99 and recall of 0.89.

Note that links to the models can be found below.

Logistial Regression Models
https://github.com/jessica1258/credit_risk_analysis/blob/main/credit_risk_resampling.ipynb

Ensemble Models
https://github.com/jessica1258/credit_risk_analysis/blob/main/credit_risk_ensemble.ipynb

## Summary
### Key Findings and Recommendations
For this analysis, the Random Forrest and Ensemble models performed better than Logistical Regression models. In particular, they performed better in terms of accuracy and recall. Recall is a critical improvement given the low instances of high risk loan status. There was very little difference in outcome between the Random Forrest or and Ensemble models, so either of those models are the best of the models evaluated.  However, further financial analysis should be conducted to understand the net impact of potentially underestimating the credit risk associated with credit card customers. 
