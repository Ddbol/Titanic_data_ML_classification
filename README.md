# Titanic Machine Learning from Disaster: Classification model investigation

Files:

train.csv, test.csv - data input. Separate train and test (without target) data set provided. Competition data where have to upload generated predicition for test data to get accuracy result. Used train data for modelling and testing by splitting. Test data went through exploratory data analysis but was not modelled. 

Titanic_survival_prediction - Final DBoland.ipynb - code

Titanic Survival Classification_DBoland.pptx - Presentation of data analysis, visualisation and linear regression (View raw to view online and interact with links)

Titanic Survival Classification_DBoland.pdf - Pdf of presentation of data analysis, visualisation and linear regression

Model comparison.xlsx - Excel table comparing model parameters and results  (View raw to view online)

Objective: Fit Logistic Regression model  to Titanic – Machine Learning from Disaster Kaggle competition data to predict survival rates and measure accuracy. 
Compared performance of different classifier models, not focussed on optimising for accuracy due to assignment time limits
Reference –  Will Cukierski. Titanic - Machine Learning from Disaster. https://kaggle.com/competitions/titanic, 2012. Kaggle.

Summary: Conducted an exploratory data analysis and generated new Adult/Child and bucketed Fare features. Generated and compared performance of classification models by splitting the test data - Logistic Regression, SVM, KNN, Decision Tree and Naive Bayes. Due to imbalanced dataset where majority training data being for those who didn't survive, the models struggled to predict those that actually survived. 

Tools used: Python, pandas, numpy, matplotlib, seaborn, scikitlearn, Logistic Regression, SVM, KNN, Decision Tree, Naive Bayes
