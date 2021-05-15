# ANN-Churn-Modelling
The purpose of this project is to build a higher accurate model and  identify the key factors which are main driving factor for customer churn

## Table of Content
  * [Overview](#Overview)
  * [Problem_Definition](#Problem_Definition)
  * [Dataset_Description](#Dataset_Description)
  * [Data Preprocessing](#Data_Preprocessing)
  * [Building CNN](#Building_CNN)
  * [Model_Building](#Model_Building)
  * [Result](#Result)
  * [Credit](#Credit)
  
## Overview
Customer churn is the percentage of customers that stopped using  company's product or service during a certain time frame.Obviously, any  company should aim for a churn rate that is as close to 0% as possible. In order to do this,  company has to be on top of its churn rate at all times and treat it as a top priority .

*Impact of Churn  on Business**
Customer churn impedes growth, so companies should have a defined method for calculating customer churn in a given period of time. By being aware of and monitoring churn rate, organizations are equipped to determine their customer retention success rates and identify strategies for improvement.


 ## Problem_Definition
 One Bank Institution is facing challenges about Churn  rate whcih deteriorates buiness of the institute. The Bank Institute  is trying to address this problem by identifying patterns in their existingcustomeres  records using Artificial Neural Network.
 
 

 ## Dataset_Description
This dataset consists of below mentioned attributes:
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
12. Estimated Saalry
13. Target Variable - Exited , 1: Exited , 0 : Not Exited 


## Data Preprocessing

1. Encoding Categorical Data - Geography
2. feature Scaling on traina and test dataset
3. Applying predefined specification to training and testing dataset


## Building ANN
### Steps to Build Convolutional Neural Netwrok
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
1. The accuracy of model  is 86.60%.
2. Loss is the penalty for a bad prediction. Basically the aim is to make the validation loss as low as possible.


## Credit
This project has been done as a course project on udemy - ANN deep learning technique.

