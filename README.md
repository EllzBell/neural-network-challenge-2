# neural-network-challenge-2
Starting code provided by Rutgers AI Bootcamp. 

This jupyter notebook is used to demonstrate familiarity with making a neural network using tensorflow. A neural network is used to predict the attrition and the corresponding department of an overall attrition dataset. This means there are two classification outputs required, the department and whether the corresponding row attrites or not. To derive two outputs from the model, the common shared branch is split into two branches with their respective hidden layer and output layer. Then the model is trained on the transformed and scaled dataset. 

The model achieves an accuracy of 87.2% for the attrition and 97.8% for the department. This makes sense as there are columns which probably have values more likely to correspond to specific departments (such as job role, level, and educational field) which may not have as strong an affiliation with whether attrition happens. 
