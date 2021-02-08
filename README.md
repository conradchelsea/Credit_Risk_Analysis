# Credit_Risk_Analysis

## Project Overview

Training and evaluating unbalanced credit and loan risk with data preparation, statistical reasoning and machine learning. 
To do this we:
- Oversampled the data usingg RandomOverSampler and SMOTE algorithms. 
- Undersampled the data using ClusterCentroid algorithms. 
- Used the SMOTEENN algorithm as a cominbined under and over sampling approach.
- Compared machine learning models BalancedRandomForestClassifier and EasyEnsembleClassifier to reduce bias in our predictions. 

## Resources

- Data Source: LoanStats_2019Q.csv
- Software: Jupyter Notebook, Python 3.8.3

## Results

## Random Oversampling:
- Balanced Accuracy Score of 68%
![Random Oversampling](https://user-images.githubusercontent.com/71476009/107172669-8d7bbf00-698b-11eb-8f8e-7c945743a12c.png)
      
    
## SMOTE Oversampling
- Balanced Accuracy Score of 66%
![SMOTE](https://user-images.githubusercontent.com/71476009/107172550-41307f00-698b-11eb-9071-33f5184cfd50.png)
      

## Cluster Centroids Undersampling
- Balanced Accuracy Score of 40%
![Cluster Centroid Undersampling](https://user-images.githubusercontent.com/71476009/107172858-0713ad00-698c-11eb-83cb-2147444c7464.png)
      
      
## SMOTEENN Combined Sampling
- Balanced Accuracy Score of 57%
![SMOTEENN](https://user-images.githubusercontent.com/71476009/107172971-52c65680-698c-11eb-98a4-4d5d15bc95f1.png)

## Balanced Random Forest Classifier
- Balanced Accuracy Score of 91%
![BRF Classifier](https://user-images.githubusercontent.com/71476009/107173181-cec09e80-698c-11eb-96e0-0f6faf67aa31.png)

## Easy Ensemble Classifier
- Balanced Accuracy Score of 94%
![Easy Ensemble Classifier](https://user-images.githubusercontent.com/71476009/107173271-0f201c80-698d-11eb-92b6-88fe237a87cf.png)

## Summary

My loan risk results were all over the map ranging from 40% to 94% in Accuracy Scores. The precision (positive predictive values) were rather low as well, meaning the data is giving me enough false positives to rethink using the source. Recall (sensitivity) rates also varied with a range of 57% to 94% of retrieved relevant measurements. Where percentages of accuracy and sourcing was highest, was at 94% was with the Easy Ensemble Adaboost Classifier. The EEAC had an accuracy score of 94%, surveyed 91-94% of relevant loan info, had a large number of correctly assesed loan risks, but predicted 974 high risks that were actually low. As the data source was rather large however, this incorrect prediction isn't a deal breaker, making the Easy Ensemble Code Classifier the recommended machine learning model. 

