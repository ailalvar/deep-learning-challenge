# Module 20 Report

## Overview of the Analysis

The purpose of this analysis is to select applicants for funding with the best success in their ventures.


## Data Preprocessing

The target in our model is the category if the applications are successfull or not. 

The features in our model include the application type and classification. Other variables include; use cse. organization, status, income amount, special considerations, and the ask amount. 

The variables that were removed from from the input data was the EIN and Name column because it is neither targets nor features. 

## Compiling, Training, and Evaluating the Model

For the neural network model I selected 3 layers and three activations functions because deeper networks an capture more complex patterns. For the activiation functions I choose relu and sigmoid. I chose Relu because it allows the model to learn complex relations will provide outputs that are easier to read. Sigmoid was also chosen because it is ideal when producing probabilities for classifications, which in this case was to see if the applicantions were going to be successfult or not.
<img width="604" alt="Screenshot 2023-10-12 at 11 05 42 AM" src="https://github.com/ailalvar/deep-learning-challenge/assets/131564308/071ff8a9-7b6c-4b74-b18d-e1dd16840890">


I was able to reach a reasonable model peformance. The results are shown below:
<img width="542" alt="Screenshot 2023-10-12 at 10 54 03 AM" src="https://github.com/ailalvar/deep-learning-challenge/assets/131564308/47796298-7f74-484a-b0a0-ddd80496f0f5">

To try to increase model peformance I tried to increase the size of the training data set, up to 100.

Overall the results are a results of a decent deep learning model. If we were to try this with a different model we could use random forest to see if it can peform better. 
