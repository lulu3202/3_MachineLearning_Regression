# Regression Hands-on project to predict Insurance 

## Introduction
This project is about developing the best regression model to predict the outcome of insurance charges based on input parameters of age, sex, bmi, children, smoker, charges

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
	- I ran MLR, SVM, RT and DF algorithms for this dataset and also hyper-tuned parameters for each model 
	- I chose Random forest (poisson – sqrt- 100) parameter combo as it gives the highest R score of 0.87

