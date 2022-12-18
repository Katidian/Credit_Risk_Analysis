# Credit risk analysis using LendingClub data

## Overview

This analysis uses a sample of LendingClub borrower data to test machine learning algorithms. LendingClub is a company that uses tech-driven methodology for loan 
underwriting, with loans extended primarily to individual borrowers through an online platform. It was one of the first so-called peer-to-peer lenders established in 
the United States.

Our analysis uses various resampling methods. For oversampling, we uses the naive random sampling and SMOTE algorithms. We undersampled using the Cluster Centroids
algorithm. We also tried a combination of over- and undersampling using the SMOTEENN algorithm. Finally, we used a Balanced Random Forest Classifier and Easy Ensemble 
Classifier. 

## Results

None of these approaches yielded particularly accurate results when it comes to predicting high-risk loans,  although the Balanced Random Forest classifier seems to do 
the least bad job. 

- Naive random oversampling gives a balanced accuracy score of 0.588%, precision of 0.01 and recall of 0.53. 
- SMOTE oversampling gives a balanced accuracy score of 0.622%, precision of 0.01 and recall of 0.57. 
- SMOTE oversampling gives a balanced accuracy score of 0.622%, precision of 0.01 and recall of 0.57. 
- Cluster Centroids undersampling gives a balanced accuracy score of 0.494%, precision of 0.00 and recall of 0.54. 
- SMOTEEN gives a balanced accuracy score of 0.589%, precision of 0.01 and recall of 0.68. 
- The Balanced Random Forest classifier gives a balanced accuracy score of 0.620, precision of 0.70 and recall of 0.24.
- The AdaBoost classifier gives a balanced accuracy score of 0.5, precision of 0.0 and recall of 0.00.

## Summary 

Not surprisingly, none of these models is very successful at predicting credit risk. Digital lenders such as LendingClub use strictly guarded proprietary 
algorithms to make credit decisions. If making these decisions were as simple as plugging a few numbers into widely available machine learning algorithms, the digital 
lending space would be even more competitive than it already is.
