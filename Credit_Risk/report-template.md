# Module 12 Report Template

## Overview of the Analysis

The objective of this analysis is to utilize various machine learning techniques to train and evaluate the performance of Logistic Regression Models in assessing the creditworthiness of borrowers. Different methods were employed to build the models, and their performances were compared to determine the superior model. The predictive variables in the model represent the labels 0 (healthy loan) and 1 (high-risk loan).

The dataset was initially divided into features and labels, and then further split into training and testing sets during the model construction process.

## Results

- Model 1:
  When trained on the original data, Model 1 achieved an accuracy of 94.4% in predicting the two labels. It demonstrated excellent performance in predicting healthy loans, with both precision and recall scores of 1.00. However, the model's performance in identifying high-risk loans can be improved. The precision score for high-risk loans was 0.87, indicating that only 87% of actual high-risk loans were accurately predicted. The recall score for high-risk loans was 0.89, indicating that the model only identified 89% of all high-risk loans in the dataset.

- Model 2:
  When trained on the resampled data, Model 2 exhibited an accuracy of 99.6% in predicting the two labels. The model performed well in predicting healthy loans, with both precision and recall scores of 1.00. Although the precision score for high-risk loans remained at 0.87, the recall score improved to 1.00, indicating that the model successfully identified all high-risk loans in the dataset.

## Summary

The analysis reveals that Model 2 surpasses Model 1 in predicting high-risk loans and exhibits superior overall accuracy in predicting both labels. Notably, Model 2 demonstrates a commendable precision in predicting high-risk loans and successfully identifies all high-risk loans in the dataset, indicating exceptional performance. Therefore, I recommend employing Model 2 for identifying high-risk loans and enhancing accuracy in predicting labels overall.
