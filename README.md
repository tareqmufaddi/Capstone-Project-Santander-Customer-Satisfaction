# Capstone-Project-Santander-Customer-Satisfaction
Udacity Capstone Project
Udacity Machine Learning Engineer Nanodegree - Capstone Report

Tareq Mufaddi
September, 2018

	
Project Report: Table of Contents

I. Definition
II. Analysis
III. Methodology
IV. Results
V. Conclusion

Project Overview:

Santander has created a Kaggle competition to help them retain unsatisfied customers. The first step is to be able to identify them before leaving, and this is the problem. By providing a customer dataset, Santander needs an algorithm which can predict the probabilityof the customer being satisfied or unsatisfied based on hundreds of anonymized customer related features.This will give the bank enough time to act before it’s too late.

Install: 

	- RandomForestClassifier
	- GradientBoostingClassifier
	- ExtraTreesClassifier
	- QuadraticDiscriminantAnalysis
	- GridSearchCV
	- cross_validation
	- seaborn

Code: 

	All the parts of code are compiled in one file:

Udacity+Machine+Learning+Engineer+Nanodegree+-+Tareq+Mufaddi+Capstone+Report+.ipynb

Data:

Santander provided an anonymized dataset containing a large number of numeric variables. The "TARGET" column is the variable to predict. It equals one for unsatisfied customers and 0 for satisfied customers. The task is to predict the probability that each customer in the test set is an unsatisfied customer.

File descriptions:

	train.csv - the training set including the target
	test.csv - the test set without the target
	sample_submission.csv - a sample submission file in the correct format
