## Heart Diease Prediction Project
The dataset is downloaded from Kaggle 
https://www.kaggle.com/johnsmith88/heart-disease-dataset

## Goal: 
This project aims to assist the hospital to improve early-disease detection rate. It has been developed as a disease prediction application based on 13 medical features of patients including
1. age
2. sex
3. chest pain type 
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl 
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) 
13. thal condition

## Background 

Heart disease is an severe medical condition that can lead to heart failure and even dealth. Identifying heart disease early can help doctors take immediate medical actions to provide necessary treatments for patient. 

By predicting a whether a patient has heart disease, doctors can identify heart disease and provide early treatement and corresponding recommendations before it become worse.



## Process

1. Cleaning and Data Preprocessing. I cleaned up and rename the columns for simplicity purpose. I change some of the column type for later machine learning tasks.
2. Data Exploratory. This is a data visualization phrase to explore the distribution of each features and their correlation with each other in order to check for collinearity.
3. Kernal support vector machine(KSVM) algorithm was used to predict the outcome. It achieves a 81 % accuracy on the testing set. 
4. Logistic regression is then used. It achieves a 83% accuracy on the testing set.

5. Accuracy is used to evaluate the model performance since the dataset is balanced and cleaned.
## Limitation 

Since the dataset has less than 1000 observation, further data can be collected and added to avoid overfitting. In the healthcare industry, it can be served as a baseline for more machine learning tasks. 


A python version is added to the porfolio to solve some of the problems on the R version such as adding cross validation score and using KNN classifier.  Click [Python](https://github.com/dsjoench/Heart_Disease/blob/master/Heart%20Disease%20Detection.ipynb) Version and [R](https://github.com/dsjoench/Heart_Disease/blob/master/Heart%20disease%20prediction.Rmd) Version



