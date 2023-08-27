# deep-learning-challenge

## Overview
This analysis has the objective of helping the nonprofit foundation Alphabet Soup to know which applicants for funding have the best chance of success in their ventures, so that they can know who to fund.

## Results
We will answer to the following questions to give a general overview of the results.

### Data Preprocessing

#### What variable(s) are the target(s) for your model?
We stablished as target and were looking to predict the variable ' IS_SUCCESSFUL ' 

#### What variable(s) are the features for your model?
Feature variables are:
* APPLICATION_TYPE            
* AFFILIATION                 
* CLASSIFICATION              
* USE_CASE                    
* ORGANIZATION                
* STATUS                      
* INCOME_AMT                  
* SPECIAL_CONSIDERATIONS      
* ASK_AMT                   
* IS_SUCCESSFUL
    
#### What variable(s) should be removed from the input data because they are neither targets nor features?
In order for us to have a good prediction, we should eliminate the ID columns 'EIN' and 'NAME´.

### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
To begin with we selected 80 neurons, 2 hidden layers and we used activation fuction 'relu' as we had good experiences with this function in the past.
![image](https://github.com/Peby1407/deep-learning-challenge/assets/127780305/4a4f0916-3014-4d7c-a0ac-2116a0c54156)

![image](https://github.com/Peby1407/deep-learning-challenge/assets/127780305/014df566-fa3e-4e46-83b2-1454f167ab0e)

#### Were you able to achieve the target model performance?
We achieved a 73% accuracy, we did not attaign the >75% accuracy
![image](https://github.com/Peby1407/deep-learning-challenge/assets/127780305/0e0aeaf9-cc66-4b0f-a6ac-ece3552257b0)

#### What steps did you take in your attempts to increase model performance?
In order the try and increase the performance we modified the following:
* We increased the amount of hidden layers to 5
* We increased the neurons to 100
* We changed to function 'tanh'
* We combined 'relu' with 'tanh'

Unfortunately we were not able to increase the accuracy.

## Summary

This 73% can be important in certain environments. When we are talking about investment, we might want to hay something closer ot 90%. But that is in a perfect world, normally investments are risky so this 73% could be a strong number.


  
