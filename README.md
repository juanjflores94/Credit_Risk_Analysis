# Credit_Risk_Analysis

Supervised Machine Learning and Credit Risk

## Overview of the loan prediction risk analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling.



## Purpose:
1. Explain how a machine learning algorithm is used in data analytics.
2. Create training and test groups from a given data set.
3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
4. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
5. Compare the advantages and disadvantages of each supervised learning algorithm.
6. Determine which supervised learning algorithm is best used for a given data set or scenario.
7. Use ensemble and resampling techniques to improve model performance.


## Results:
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows: 

## Naive Random Oversampling 

<img width="721" alt="Screen Shot 2022-07-27 at 8 44 04 PM" src="https://user-images.githubusercontent.com/100455534/181418177-4d8a0cc5-1903-4c67-961b-4556671e8bb1.png">

Balanced Accuracy:0.6613193839000291

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .63/.66

## Smote Oversampling

<img width="721" alt="Screen Shot 2022-07-27 at 8 44 31 PM" src="https://user-images.githubusercontent.com/100455534/181418458-0f065fa1-7364-4751-a2f2-81df9228b4a6.png">

Balanced Accuracy: 0.6479511769834351

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .64/.65


## Undersampling

<img width="721" alt="Screen Shot 2022-07-27 at 8 45 58 PM" src="https://user-images.githubusercontent.com/100455534/181418654-dbe014ef-3be2-4871-b4a9-ac7a8bd4ffa8.png">

Balanced Accuracy: 0.44969485614646904

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .61/.45

## Combination Under-Over Sampling
<img width="650" alt="Screen Shot 2022-07-27 at 9 26 37 PM" src="https://user-images.githubusercontent.com/100455534/181420465-c74e81a2-17ed-4603-99f3-b4cbd6872d9a.png">

Balanced Accuracy: 0.5401918047079337

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .71/.54

## Balanced Random Forest Classifier

<img width="721" alt="Screen Shot 2022-07-27 at 8 46 37 PM" src="https://user-images.githubusercontent.com/100455534/181418702-ef4e34ba-e126-481a-8bc0-b8e915eee049.png">

Balanced Accuracy: 0.7877672625306695

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .67/.91

## Easy Ensemble AdaBoost Classifier

<img width="721" alt="Screen Shot 2022-07-27 at 8 46 53 PM" src="https://user-images.githubusercontent.com/100455534/181418710-cc9e57ab-7e96-4b18-acaf-130e364877f8.png">

Balanced Accuracy: 0.925427358175101

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .91/.94

## Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
