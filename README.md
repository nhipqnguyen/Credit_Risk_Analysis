# Credit_Risk_Analysis
## Overview of the Analysis
- This project applies different techniques of machine learning to solve the "credit card risk" challenge for LendingClub, a peer-to-peer lending services company. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we'll use resampling to build and evaluate models.
- Resource: LoanStats_2019Q1.csv
## Results
- Below is the balanced accuracy score and the precision and recall scores of the Naive Randommodels Oversampling model :

  ![balanced_accuracy_score_Naive_Random](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Naive_Random.png)

  ![metrics_Naive_Random](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Naive_Random.png)

- Below is the balanced accuracy score and the precision and recall scores of the SMOTE Oversampling model :

  ![balanced_accuracy_score_SMOTE](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_SMOTE.png)

  ![metrics_SMOTE](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_SMOTE.png)

- Below is the balanced accuracy score and the precision and recall scores of the Cluster Centroids Undersampling model :

  ![balanced_accuracy_score_ClusterCentroids](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_ClusterCentroids.png)

  ![metrics_ClusterCentroids](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_ClusterCentroids.png)

- Below is the balanced accuracy score and the precision and recall scores of the SMOTEENN model :

  ![balanced_accuracy_score_SMOTEENN](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_SMOTEENN.png)

  ![metrics_SMOTEENN](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_SMOTEENN.png)

- Below is the balanced accuracy score and the precision and recall scores of the Balanced Random Forest model :

  ![balanced_accuracy_score_Balanced_Random_Forest](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Balanced_Random_Forest.png)

  ![metrics_Balanced_Random_Forest](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Balanced_Random_Forest.png)

- Below is the balanced accuracy score and the precision and recall scores of the Easy Ensemble AdaBoost model :

  ![balanced_accuracy_score_Easy_Ensemble_AdaBoost](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Easy_Ensemble_AdaBoost.png)

  ![metrics_Easy_Ensemble_AdaBoost](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Easy_Ensemble_AdaBoost.png)

## Summary
- There is a summary of the results
- There is a recommendation on which model to use, or there is no recommendation with a justification 