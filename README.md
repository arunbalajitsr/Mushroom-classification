# Mushroom-classification

[![N|Solid](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/arunbalajitsr/Mushroom-classification/blob/main/Mushroom_Classification_using_Backpropagation.ipynb)

Mushroom Classification using Back propagation - Project for elective Soft computing (BEIDEI708) Sastra Deemed to be university - Done by Arun Balaji T S R (121006097)

# Aim:
To classify mushrooms as edible or poisonous using Back propagated neural network. Dataset is obtained from Kaggle and UCI Machine Learning Repository.
  
# Process:
  - The dataset is converted to numerical form from labeled from using LabelEncoder library of ScikitLearn
  - Additional preprocessing of data like addition/removal of rows and columns are done using Pandas and Numpy libraries
  - After completing preprocessing, the given dataset is split into two - Train data and Test data using train_test_split library
  - The structure of the neural network, hidden layers are defined
  - Random weights are alloted initially
  - The system forward propagates through the network, calls Activation function and calculates the cost through cost function
  - Then the system propagates backwards and changes the weights through Gradient Descent method
  - This process is done for multiple iterations to obtain minimum cost/error

# Notes:
- The activation may be Sigmoid function or a Tanh function. Here, I have used Tanh function because of low accuracy in sigmoid function.
- Cost function used here is cross-entropy cost

# References:
- Andrew Ng Neural Network and deep learning courses



