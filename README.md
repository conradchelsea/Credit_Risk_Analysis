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

- Random Oversampling:
    - Balanced Accuracy Score of 68%
    - Confusion Matrix 
      ![Confusion Matrix](https://user-images.githubusercontent.com/71476009/107171503-94ed9900-6988-11eb-811d-4c7015a743d8.png)
    - Imbalanced Classification Report
      ![Imbalanced Class Report ](https://user-images.githubusercontent.com/71476009/107171573-bcdcfc80-6988-11eb-828e-982d14268efb.png)
      
    
- SMOTE Oversampling
    - Balanced Accuracy Score of 66%
    - Confusion Matrix 
      ![Confusion Matrix](https://user-images.githubusercontent.com/71476009/107171866-6fad5a80-6989-11eb-8f17-476943a5c785.png)
    - Imbalanced Classification Report
      ![Classification Report](https://user-images.githubusercontent.com/71476009/107171888-7f2ca380-6989-11eb-81f6-ac50608b5460.png)
      

- Cluster Centroids Undersampling
    - Balanced Accuracy Score of 40%
    - Confusion Matrix 
      ![Screen Shot 2021-02-07 at 9 17 09 PM](https://user-images.githubusercontent.com/71476009/107172034-ecd8cf80-6989-11eb-8c68-b9c47e17b83e.png)
    - Imbalanced Classification Report
      ![Screen Shot 2021-02-07 at 9 17 15 PM](https://user-images.githubusercontent.com/71476009/107172050-fb26eb80-6989-11eb-9271-0f1044157794.png)
      
      
- SMOTEENN Combined Sampling
    - Balanced Accuracy Score of 57%
    - Confusion Matrix 
      ![Screen Shot 2021-02-07 at 9 19 08 PM](https://user-images.githubusercontent.com/71476009/107172121-32959800-698a-11eb-97b8-7e7508d87354.png)
    - Imbalanced Classification Report
       ![Screen Shot 2021-02-07 at 9 19 13 PM](https://user-images.githubusercontent.com/71476009/107172148-40e3b400-698a-11eb-84c4-16a1e76eb00b.png)

- Balanced Random Forest Classifier
    - Balanced Accuracy Score of 
    - Confusion Matrix 
    - Imbalanced Classification Report

- Easy Ensemble Classifier
    - Balanced Accuracy Score of 
    - Confusion Matrix 
    - Imbalanced Classification Report

## Summary
