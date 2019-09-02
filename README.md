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

1. Define and understand the business problem. This task aims to built up the foundation of the whole project

2. Cleaning and Data Preprocessing. I cleaned up and rename the columns for simplicity purpose. I change some of the column type for later machine learning tasks.
3. Data visualization phrase to explore the distribution of each variables, checking for collearity.  Transforming and scaling the data for faster convergence, etc.

4. Accuracy was used to evaluate the model performance for simplicity purpose. Other options include F1, ROC/AUC curve
5. Building baseline model of random forest, plotting feature importances using the in-built function of the model. 

6. Building logistic regression, KNN, support vector machine algorithms to compare against the baseline model.

7. Model tuning and evaluation and find the optimized parameter for bias and variance trade off. Check for overfitting through plotting.




## Future improvement

- Feature engineering - Further understanding of variables, potentially combine some columns or adding new features.
- Accuracy is not the best metric to evaluate the model performance even with the balanced dataset. Will try F1 or AUC curve.
- Further tuning on random forest, adding gradient boosting to compare results


A python version is added to the porfolio to add cross validation score and KNN model.  Click [Python](https://github.com/dsjoench/Heart_Disease/blob/master/Heart%20Disease%20Detection.ipynb) Version and [R](https://github.com/dsjoench/Heart_Disease/blob/master/Heart%20disease%20prediction.Rmd) Version



