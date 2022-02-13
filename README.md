# Credit_Risk_Analysis

# Overview

The purpose of this analysis was to utilize machine learning techniques to predict credit risk for loans. The goal is to use this machine learning model to reduce the loan default rate to improve profitability. 

# Results

## Naive Random Oversampling ##
<img width="656" alt="Screen Shot 2022-02-11 at 1 12 30 PM" src="https://user-images.githubusercontent.com/89474406/153670905-0e7eb860-c22a-45db-88e5-2f11ec09aa51.png">

- Accuracy Score - 64.03%
- Precision Score Low - 1.00%
- Precision Score High - 100.00%

## SMOTE Oversampling ##
<img width="652" alt="Screen Shot 2022-02-11 at 5 24 10 PM" src="https://user-images.githubusercontent.com/89474406/153690694-f50d0703-cd34-4f03-a98a-90d6eb1aa2cf.png">

- Accuracy Score - 65.15%
- Precision Score Low - 1.00%
- Precision Score High - 100.00%

## Cluster Centroid Undersampling ##
<img width="658" alt="Screen Shot 2022-02-11 at 5 25 42 PM" src="https://user-images.githubusercontent.com/89474406/153690751-a4ece55f-0c3c-4082-8a3b-6cd85abc513e.png">

- Accuracy Score - 54.47%
- Precision Score Low - 1.00%
- Precision Score High - 100.00%

## SMOTEEN Combosampling ##
<img width="651" alt="Screen Shot 2022-02-11 at 5 26 42 PM" src="https://user-images.githubusercontent.com/89474406/153690788-667a8307-9539-402b-91ad-35b881f7c3bd.png">

- Accuracy Score - 64.29%
- Precision Score Low - 1.00%
- Precision Score High - 100.00%

## Random Forest ##
<img width="658" alt="Screen Shot 2022-02-11 at 5 25 42 PM" src="https://user-images.githubusercontent.com/89474406/153691060-31c88982-fb1b-468e-a83d-2e4bee08372a.png">

- Accuracy Score - 78.85%
- Precision Score Low - 1.00%
- Precision Score High - 100.00%

## Easy Ensemble Adaboost Classifier ##
<img width="658" alt="Screen Shot 2022-02-11 at 5 25 42 PM" src="https://user-images.githubusercontent.com/89474406/153691476-5f811f27-179e-4bd7-bb63-63d2f4f2522b.png">

- Accuracy Score - 93.17%
- Precision Score Low - 9.00%
- Precision Score High - 100.00%

# Summary

We utilized six different mahcine learning models to see which one best predeicts credit score ratings. When comparing the six models, the one I would recommend for use would be the Easy Ensemble Adaboost Classifer. As detailed above, this model provides the highest Accuracy Score at 93.17% and a high precision score of 1. Both of these indicate that this model would predict with a high degree of accuracy and precision, both of which are needed in a good machine learning model. Although the other models have similar precision scores, their accuracy is signifacntly lower which would lend to the results being off.

Accuracy = ( True Positives + True Negavites ) / Total Outputs
Precision = True Positives / ( True Positives + False Positives )



