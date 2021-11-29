# ANN-Churn-Modelling
The purpose of this project is to build a higher accurate model and  identify the key factors which are the main driving factor for customer churn

## Table of Content
  * [Overview](#Overview)
  * [Problem_Definition](#Problem_Definition)
  * [Dataset_Description](#Dataset_Description)
  * [Data Preprocessing](#Data_Preprocessing)
  * [Building ANN](#Building_ANN)
  * [Model_Building](#Model_Building)
  * [Result](#Result)
  * [Credit](#Credit)
  
## Overview
Customer churn is the percentage of customers that stopped using the company's product or service during a certain time frame. Obviously, any company should aim for a churn rate that is as close to 0% as possible. To do this, the company has to be on top of its churn rate at all times and treat it as a top priority.

*Impact of Churn  on Business**
Customer churn impedes growth, so companies should have a defined method for calculating customer churn in a given period. By being aware of and monitoring churn rate, organizations are equipped to determine their customer retention success rates and identify strategies for improvement.


 ## Problem_Definition
 One Bank Institution is facing challenges about the Churn rate which deteriorates the business of the institute. The Bank Institute is trying to address this problem by identifying patterns in their existing customer's records using Artificial Neural Network.
 
 

 ## Dataset_Description
This dataset consists of the below-mentioned attributes:
1. SLNO
2. CustomerID
3. Surname
4. Credit Score
5. Gender
6. Age
7. Tenure
8. Balance
9. Number of Products
10. Credit Card - 1:yes,0:No
11. Active Number - 1:yes,0:No
12. Estimated Salary
13. Target Variable - Exited, 1: Exited, 0: Not Exited 


## Data Preprocessing

1. Encoding Categorical Data - Geography
2. feature Scaling on train and test dataset
3. Applying predefined specification to training and testing dataset


## Building ANN
### Steps to Build Convolutional Neural Network
1. Import required libraries
2. Initialize ANN and add Convolutional layer
3. Adding the input layer and the first hidden layer
4. Adding the second hidden layer
5. Adding the output layer




## Model_Building
### Steps to model Building
1. Compile the ANN model
2. Training the ANN  on Training set
3. Evaluating on Testing set
4.  Comparison of accuracy and loss function


    
## Result
1. The accuracy of the model is 86.60%.
2. Loss is the penalty for a bad prediction. The aim is to make the validation loss as low as possible.


## Credit
This project has been done as a course project on udemy - ANN deep learning technique.

