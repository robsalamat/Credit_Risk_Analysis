# Credit_Risk_Analysis

## I. Overview of Project

### Background
Fast Lending, a peer to peer lending services company, wants to use machine learning to predict credit risk. We are tasked to build and evaluate several machine learning models or algorithms to prdeict credit risk.

### Objective
Now, we are to apply machine learning to solve a real-world challenge: credit card risk. We’ll need to employ different techniques to train and evaluate models with unbalanced classes to evaluate the performance of these models and recommend whether they should be used to predict credit risk.


## II. Results

### A. Naive Random Oversampling

![](Images/1.PNG)

### B. SMOTE Oversampling

![](Images/2.PNG)

### C. Cluster Centroid Undersampling

![](Images/3.PNG)

### D. SMOTEENN Sampling

![](Images/4.PNG)

### E. Balanced Random Forest Classifying

![](Images/5.PNG)

### F. Easy Ensemble Classifying

![](Images/6.PNG)


## III. Summary

We need to determine the best model to detect high risk loans. From our 6 Analyses:

![](Images/7.PNG)

- For Accuracy, ***Easy Ensemble Classifying*** has the highest score. It detects allmost all the high risk credit.

- For Precision rate, the results are similar for low risk but, ***Easy Ensemble Classifying*** has a slightly higher score for high risk. 

- For Recall rate, ***Easy Ensemble Classifying*** gets the highest score for high risk loans. It has the least amount of undetected high risk loans.

- In conclusion, ***Easy Ensemble Classifying*** is the best and recommended machine learning model to determine credit card risks.


