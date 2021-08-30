# Credit_Risk_Analysis
## Overview of the Analysis
- This project applies different techniques of machine learning to solve the "credit card risk" challenge for LendingClub, a peer-to-peer lending services company. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we'll use resampling to build and evaluate models.
- Data source: LoanStats_2019Q1.csv
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

  ![balanced_accuracy_score_SMOTEENN](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_SMOTEEN.png)

  ![metrics_SMOTEENN](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_SMOTEEN.png)

- Below is the balanced accuracy score and the precision and recall scores of the Balanced Random Forest model :

  ![balanced_accuracy_score_Balanced_Random_Forest](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Balanced_Random_Forest.png)

  ![metrics_Balanced_Random_Forest](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Balanced_Random_Forest.png)

- Below is the balanced accuracy score and the precision and recall scores of the Easy Ensemble AdaBoost model :

  ![balanced_accuracy_score_Easy_Ensemble_AdaBoost](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Easy_Ensemble_AdaBoost.png)

  ![metrics_Easy_Ensemble_AdaBoost](https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Easy_Ensemble_AdaBoost.png)

## Summary
- Among six machine learning models, the balance accuracy score of the Cluster Centroids algorithm is the lowest (54%). The 2 ensemble algorithms result in the best performance, with balance accuracy scores 93% for the Easy Ensemble AdaBoost classifier and 79% for the Balanced Random Forest Classifier. The other 3 models' scores fall in the range of 64% - 66%.
- The model using the Easy Ensemble AdaBoost classifier also results in the highest precision and recall scores for both "high risk" and "low risk" samples.
- For credit card risk, the recall score is more important than the precision score since we'd rather mistake a low risk account to be high risk than to miss a high risk one. Therefore, we could use the model using Easy Ensemble AdaBoost classifier, which seems to give the best performance in dedecting both types of account, especially the high risk ones. 92% of the high risk accounts and 94% of the low risks accounts can be detected using this model. The F1 (97%) score for this model is also relatively high. 