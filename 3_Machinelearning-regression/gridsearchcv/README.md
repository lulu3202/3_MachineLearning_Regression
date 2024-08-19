#  Hands-on project to predict Insurance implementing Grid Search

## Introduction
This project is about using GridSearch method (with and without test/train split data) for SVM, MLR, DT and RT, to predict the outcome of insurance charges based on input parameters of age, sex, bmi, children, smoker, charges. 

Grid search is a machine learning technique that helps identify the best hyperparameters for a model to improve its accuracy and performance. It's a brute-force method that involves defining a grid of hyperparameter values and evaluating the model's performance at each point on the grid. The goal is to find the combination of parameters that optimizes the model's performance, which can lead to better predictions or classifications


## Dataset
- Is called insuance_pre  and has a total of 1338 rows × 6 columns. There is data preprocessing involved. Out of 6 parameters, age, sex, bmi, children, smoker, charges – the sex column and smoker column is categorical so I will be converting it into numerical value / nominal data. 

## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data 
- Create model with Train Data via regressor.fit method
- Evaluate/Test model performance with the Test set
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
	- I ran   GridSearch method (with and without test/train split data) for SVM, MLR, DT and RT
	- I found decision tree as the best model and deployed the same

