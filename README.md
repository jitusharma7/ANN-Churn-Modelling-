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
  * [Business_Recommendation](#Business_Recommendation)
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


### Steps to Data Preprocessing
1. Image Rescaling for both training and testing data set
2. Applying predefined specification to training and testing dataset


## Building CNN
### Steps to Build Convolutional Neural Netwrok
1. Import required libraries
2. Initialize CNN and add Convolutional layer
3. Pooling
4. Add two convolutional layer
5. Flattening
6. Fully connected layer and output layer

<img src="/Builiding%20CNN.PNG" width="300">


## Model_Building
### Steps to model Building
1. Compile the CNN model
2. Training the CNN on Training set
3.  Evaluating on Testing set
4.  Comparison of accuracy and loss function


    
## Result
1. The accuracy of model  is 96.82%. The accuaracy of model should be next to 100% in medical domain problems .
2. Loss is the penalty for a bad prediction. Basically the aim is to make the validation loss as low as possible.

## Business_Recommendation
* CNN's are best for image classification and gives superb accuracy. Also computation is much less compared to simple ANN .
* The algorithm generated will be helpful in the area where the expert in microscopic analysis may not be available.

## Credit
This project has been done as a course project on CNN deep learning technique.

