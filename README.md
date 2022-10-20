# Neural_Network_Charity_Analysis

## Overview of the analysis:

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results:

## Data Preprocessing

variable(s) that are considered the target(s) for your model?
- The variable we are targeting in this module is the IS_SUCCESSFUL column.

variable(s) that are considered to be the features for your model?
- The features that we are using are every column except the ones that we will drop. 

What variable(s) are neither targets nor features were removed? 
- First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.

## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model?
- This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

Was the model able to achieve the target model performance?
- Although the target for the model was to be 75% or above, I was not able to reach the target.

What steps were taken to try and increase model performance?
- Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.

## Summary: 

The models accuracy ended up being 72.8% - we started with a data set and tried to predict whether or not the project would be successful on all of the features that we used after dropping two features that we figured to be irrelevant. Although I did not get to the accuracy of 75% that I wanted it is possible the reason for this is we may have had to drop more features which may have affected how good the neural network actually is. The best way to increase the accuracy of your model is to have more data. If we have solid data added to this model, the accuracy of this model will be much more concrete.
