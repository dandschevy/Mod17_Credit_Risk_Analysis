# Module 17 - Credit Risk Analysis

## Overview
The purpose of Module 17 was to use various models to analyze credit risk in order to find the best predictor.

## Results
Several models were used to evaluate credit risk.  Below are the models used and the result of the analysis:
1.  Logistic Regression  - using this method, an accuracy score of 66.12% was obtained:
 ![image](https://user-images.githubusercontent.com/90434559/158046576-598c8031-b151-48a6-94b8-276ff0f81f45.png)
 
2.  SMOTE Oversampling - using this method, an accuracy score of 63.03% was obtained:
![image](https://user-images.githubusercontent.com/90434559/158046641-49fbf6f5-1d9f-47a7-b0dc-19d5b4631402.png)

3.  Cluster Centroids - using this method, an accuracy score of 52.93% was obtained: 
![image](https://user-images.githubusercontent.com/90434559/158046690-2a547935-090a-4475-a671-3f55f90a2f9b.png)

4.  SMOTEENN - using this method, and accuracy score of 61.92% was obtained:
![image](https://user-images.githubusercontent.com/90434559/158046728-8aaad2e3-e6cd-4e36-9fc7-bba855c20ed1.png)

5.  Balanced Random Forest - using this method, an accuracy score of 78.8% was obtained:
![image](https://user-images.githubusercontent.com/90434559/158046763-87621494-04b0-4894-9112-fe1ed897abd4.png)

6.  Easy Ensemble - using this method, an accuracy score of 92.5% was obtained:
![image](https://user-images.githubusercontent.com/90434559/158046791-2212d5d3-a66f-4efb-91f8-450665e04ba6.png)

## Summary
Since credit risk can be difficult to predict, various models were used to see which would produce the most accurate result.  Based on the data, the Easy Ensemble method produced the highest rate of accuracy.  Additionally, the logistic modeling is not well suited for credit risk based on the scores presented.  Using ensemble learning models will produce the best result based on the current data collected.
