# Ran Hands-on project (Hyper-parameter tuning included)

## Introduction
This project is about developing a decision tree model to predict the profit(dependent variable) of a startup based on the independent variables of R&D spend, Administration, Marketing Spend and State (from the startups dataset). 

## Dataset
- This salary dataset contains 6 columns in total. All columns are numerical except the state column. The state column contains New York, Florida or California. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 

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
-With hyperparameter tuning, we figure out the best combo to proceed with is squared error – none – 50 that yields a result of 0.94 r score
