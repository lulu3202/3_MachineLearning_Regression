# Support Vector Machine Regression Hands-on project (Standardization included)

## Introduction
This project is about developing a SVMR model to predict the profit(dependent variable) of a startup based on the independent variables of R&D spend, Administration, Marketing Spend and State (from the startups dataset). 

In the SVR model we are trying out kernel as rbf,poly and sigmoid

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
-5 weights and bias/origin value is evaluated
-34 support vectors were generated as part of 
- Achieved an r_score of -0.05 on the test set (interpretation - model performs poorly as r is closer to 1) WITHOUT STANDARDIZATION
-To improve model perform, standardization is performed via standardscalar method. Again the r value is -0.05 is achieving, hence this model is not a good fit for this dataset. 

