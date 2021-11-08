# Neural_Network_Charity_Analysis
Module 19 Challenge

## Overview of the Analysis

We have received a CSV file containing over 34,000 organizations that have received funding from Alphabest Soup over the past years. The goal of this challenge is to develop a neural network model that will be able to predict whether future applicatns will be successful when funded by Alphavet Soup. we have used the features to create a binary classifier neural network and then to review the model to see if its accuracy can be increased. 


## Results

## Data Preprocessing
  - Target Variables in the Model
    - the "IS_SUCCESSFUL"  field is my Target Variable
    - ![image](https://user-images.githubusercontent.com/84824391/140678015-8dee823d-be19-49d7-8be0-53577c638465.png)
  - Features in the Model
    - The features used for this model include the below. 
    - ![image](https://user-images.githubusercontent.com/84824391/140678127-8f663d8c-5e62-4da4-9a94-5d9e3a2ec73a.png)
  - Variables Removed from the Data
    - The variables removed from the data include the below. 
    -  ![image](https://user-images.githubusercontent.com/84824391/140678268-c3d56e22-a90b-4c69-a76a-4e00bd42166a.png)

## Compiling, Training, and Evaluating the Model

  - Neural Network Model Structure
    - Neurons - 8 and 5 neurons 
    - Layers - 2 layers
    - Activation functions - Relu and then Sigmoid for the output layer
    - 
  - Model Optimization Attempts
    - I was not able to optimize my model above the 75% threshold after 3 attempts. 

  - Steps take to increase the model performance
    - I dropped the ASK_AMT column to see if this had a signifant impact on the model. I also binned the ASK_AMT column in one model. I also added more neurons, 
      added one additional hidden layer, and increased the number of epochs.   

##Summmary

  - Compiling and improving the performance of a model can be very difficult because there could be an unlimited number of methods to attempt.
