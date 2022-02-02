# Neural_Network_Charity_Analysis

## Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in order to analyze and classify the success of charitable donations.

## Results
#### Data Reprocessing
  - The column IS_SUCCESSFUL contains binary data refering to weither or not the charity donation was used effectively. This variable is then considered as the target for our deep learning neural network.
  - The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.
  
#### Compiling, Training, and Evaluating the Model
  - This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively. The output layer is made of a unique neuron as it is a binary classification.
  - The model accuracy is under 75% so I decided to touch up the model in order to increase the accuracy.
  - To increase the performance of the model, I applied bucketing to the feature ASK_AMT and organized the different values by intervals, increased the number of neurons on one of the hidden layers, and finally used a model with three hidden layers. I got the accuracy up to 80%.

## Summary

The deep learning neural network model was raised up to 80%. Considering that this target level is above average we could say that the model is slightly outperforming.
Since we are in a binary classification situation, we could use a supervised machine learning model in order to generate a classified output and evaluate its performance against our deep learning model and decide which model is best.
