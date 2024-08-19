#  Hands-on project to predict Insurance 
 
## Introduction
This project is about using SVMR with standardscalar method to predict the outcome of insurance charges based on input parameters of age, sex, bmi, children, smoker, charges.
 
In regression, when we use Standard Scalar, both the input and the output is preprocessed. This hands-on is to illustrate the importance of providing preprocessed input to predict value of the output and then reverse transform it to provide original value to end-users. 

In classification, when we use Standard Scalar, only the input is preprocessed. So while pre-processed input is necessary, reverse transform is not needed in this case, 
 
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
	• Input is provided in pre-processed format (preinput variable that uses transform)
	• Predicated value is then reverse transformed (preoutput variable that uses inverse transform)

