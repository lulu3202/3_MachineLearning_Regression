# Boosting Algorithm Hands-on project to predict Insurance with AdaBoost regressor, XG and LG boost regressor

## Introduction
This project is about developing boosting algorithmsl to predict the outcome of insurance charges based on input parameters of age, sex, bmi, children, smoker, charges via boosting algorithms. 

A single weak model may not be enough for our complex problems. In such cases we aggregate various weak models to make a powerful and more accurate model for our problem. This process of aggregating several small problems to create a strong model is what we do in boosting. 


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
	- I ran ADA, XG and LG Boost algorithms for this dataset and also hyper-tuned parameters for each model 
	- Ada Boost and XG Boost gave me the highest R score of 0.92
