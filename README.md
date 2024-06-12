# Loan Approval Prediction

With record inflation and a struggling economy it is commonplace to see people apply for loans with the hopes that they will be approved and granted an exorbitant amount of money that could possibly change their lives. We created a loan approval prediction system that will give the user a way to know beforehand if they will get approved for a loan. For the predictor we used random forest, decision tree,logistic regression, and k-nearest neighbor models to find the most accurate way to predict if someone will be approved.


![alt text](https://github.com/rodriguezrj/PredictingLoanDefault/blob/main/Images/image.png)

# Table of Contents 
 - [Project Overview](#Project-Overview)
 - [Data Understanding](#Data-Understanding)
 - [Data Analysis](#Data-Analysis)
 - [Models initiated](#Models-initiated)
 - [Recommendations](#Recommendations)
 - [Future Considerations](#Future-Considerations)
 - [Contributors](#Contributors)
 - [References](#references)

# Project Overview
Our project is a loan approval predictor that will factor in: gender, marital status, dependents, education, employment, income, loan amount, loan amount term, credit history, and property area. Our target is to use machine learning to accurately predict loan payments. We used Logistic Regression, Random Forest, Decision Tree, and Gradient Boosting models.


# Data Understanding
The dataset that we are using for the project is named "Loan Prediction Dataset" through kaggle. The dataset contains a set of 613 records under 13 attributes.


# Data Analysis
Throughout this project we leveraged Kaggle, a reputable data repository, to acquire a comprehensive loan applicant dataset.Then we conducted a thorough review process to ensure data alignment with project requirements and suitability for machine learning modeling. After that we cleaned the data to ensure accuracy and usability. We also filled NaN data with Mode (categorical) and Mean (numerical) and changed the Test/Train percentages at increments to find the best accuracy for each model.


# Models initiated
We implemented a multi-model evaluation approach to ensure accuracy. We employed Logistic Regression, Decision Trees, Random Forests, Gradient Boosting and SVC.

Test size at 20%
![alt text](https://github.com/rodriguezrj/PredictingLoanDefault/blob/main/Images/image-1.png)
We ran our initial to the size of 20%


Test size at 60%
![alt text](https://github.com/rodriguezrj/PredictingLoanDefault/blob/main/Images/image-2.png)
To tune our model for better accuracy we increased the test size to 60%


# Recommendations 
Based on the model evaluations, we recommend using the model with the highest accuracy and best performance metrics for predicting loan approvals. The logistic regression and random forest models showed promising results and could be used as reliable predictors. Future improvements could include hyperparameter tuning, additional feature engineering, and exploring other advanced models.

# Future Considerations
In the future we should potentially seek a second data set to run the same models to see if we can get improved accuracy scores and/or combine datasets. Also we should locate a data set that contains our key columns as well as potential columns where bias could affect the model and compare accuracies.

# Contributors 
Lewis Hill
Robert Rodriguez
Ben Cross
Solomon Ajayi

# References 
https://www.kaggle.com/code/yonatanrabinovich/loan-prediction-dataset-ml-project
