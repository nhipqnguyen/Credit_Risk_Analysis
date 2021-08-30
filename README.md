# Credit_Risk_Analysis
## Overview of the Analysis
- This project applies different techniques of machine learning to solve the "credit card risk" challenge for LendingClub, a peer-to-peer lending services company. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we'll use resampling to build and evaluate models.
- Resource: LoanStats_2019Q1.csv
## Results
- Below is the balanced accuracy score and the precision and recall scores of the Naive Randommodels Oversampling model :

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Naive_Random.png)

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Naive_Random.png)

- Below is the balanced accuracy score and the precision and recall scores of the SMOTE Oversampling model :

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_SMOTE.png)

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_SMOTE.png)

- Below is the balanced accuracy score and the precision and recall scores of the Cluster Centroids Undersampling model :

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_ClusterCentroids.png)

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_ClusterCentroids.png)

- Below is the balanced accuracy score and the precision and recall scores of the SMOTEENN model :

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_SMOTEENN.png)

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_SMOTEENN.png)

- Below is the balanced accuracy score and the precision and recall scores of the Balanced Random Forest model :

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Balanced_Random_Forest.png)

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Balanced_Random_Forest.png)

- Below is the balanced accuracy score and the precision and recall scores of the Easy Ensemble AdaBoost model :

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/balanced_accuracy_score_Easy_Ensemble_AdaBoost.png)

  !(https://github.com/nhipqnguyen/Credit_Risk_Analysis/blob/main/Analysis/metrics_Easy_Ensemble_AdaBoost.png)


## Summary
- As shown in the above tables, the percentages of 5-star reviews for the paid and unpaid types are 59.1% and 53.6%, respectively. The 5-star reviews account for a slightly higher percentage of all paid reviews than they do in the unpaid group. However, this difference is not significant considering the difference in size of 2 groups. Therefore, there is no significant bias for reviews for shoes products in the Vine program. 
- Below is the comparison of the average rating of the products that were rated in both Vine and non-Vine groups:
  
  ![avg_rating_paid_vs_unpaidy](https://github.com/nhipqnguyen/Amazon_Vine_Analysis/blob/main/analysis/avg_rating_paid_vs_unpaid.png)

 - Out of the 5 products that were rated in both groups, only 1 shows significant difference between the ratings (4.5 vs. 1). That being said, there is no significant bias for shoes products' review between the Vine and non-Vine groups.