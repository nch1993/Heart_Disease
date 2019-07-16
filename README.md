## Heart Diease Prediction Project
The dataset is downloaded from Kaggle 
https://www.kaggle.com/johnsmith88/heart-disease-dataset

## Goal: 
This project aims to predict whether a patient has heart disease based on 13 medical features of patients including
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
By accurately predicting a whether a patient has heart disease, healthcare professional can narrow down the potential patients and identify any early treatement and provide corresponding recommendations. I believe that machine learning can bring tremendous values to the healthcare sector. 


## Process

1. Cleaning and Data Preprocessing. I cleaned up and rename the columns for simplicity purpose. I change some of the column type for later machine learning tasks.
2. Data Exploratory. This is a data visualization phrase to explore the distribution of each features and their correlation with each other in order to check for collinearity.
3. Kernal support vector machine(KSVM) algorithm was used to predict the outcome. It achieves a 81 % accuracy on the testing set. 
4. Logistic regression is then used. It achieves a 83% accuracy on the testing set.

## Limitation 

Since it is not a very large dataset, this proeject can be used for further development in the future. On the other hand, the medical conditions are widely covered in the features, so it can be used as a basis to predict hypothetical outcomes.
