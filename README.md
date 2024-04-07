# LendingClub Loan Repayment Prediction
## Introduction
This project is part of the "Python for Data Science and Machine Learning Bootcamp" on Udemy.  
This project aims to build a machine learning model to predict whether a borrower will pay back their loan or not using historical data from LendingClub. The dataset used is a subset of the LendingClub DataSet obtained from Kaggle.

## About LendingClub
LendingClub is a US peer-to-peer lending company headquartered in San Francisco, California. It is the world's largest peer-to-peer lending platform, allowing individuals to apply for loans directly from other individuals, cutting out the traditional banking intermediaries.

## Project Goals
The main goal of this project is to develop a predictive model that can assess the likelihood of a borrower repaying a loan. By analyzing historical data on loans issued by LendingClub and whether or not they were repaid, the model can help in making more informed decisions when evaluating potential borrowers in the future.

## Data Overview
The dataset contains various features related to loans issued by LendingClub, including loan amount, interest rate, borrower's employment details, home ownership status, annual income, loan status, and more. The target variable, 'loan_status', indicates whether the loan was fully paid or charged off (defaulted).

## Project Tasks
The project is divided into several sections:

* Exploratory Data Analysis (EDA): This section involves exploring the dataset, understanding the distribution of features, visualizing relationships between variables, and identifying patterns or trends.

* Data Preprocessing: In this section, data preprocessing techniques are applied to handle missing values, convert categorical variables into numerical format using dummy variables, and prepare the data for modeling.

* Train-Test Split: The dataset is split into training and testing sets to evaluate the performance of the predictive model.

* Model Building: A sequential neural network model is built using TensorFlow/Keras to predict loan repayment based on the available features. The model architecture includes multiple dense layers with dropout regularization to prevent overfitting.

* Model Evaluation: The trained model is evaluated using the testing dataset, and performance metrics such as classification report and confusion matrix are generated to assess its effectiveness.

* Prediction: Finally, the model is used to predict whether a new customer would repay their loan based on their information.

## Conclusion
This project demonstrates the application of machine learning techniques to predict loan repayment using historical data from LendingClub. By leveraging predictive modeling, financial institutions can make more informed decisions when evaluating loan applications, ultimately minimizing default risks and optimizing lending strategies.
