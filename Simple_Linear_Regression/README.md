## Simple linear regression
The equation for Simple Linear Regression is Y= b0 + b1*X
- where, Y-> dependent variable
- X-> Independent variable
- b0-> slope
- b1-> co-efficient

### Problem Statement:
Here, in this problem our aim is to predict the salary of a person based on his experience. The dataset contains two variable, one being experience and the other being salary. This is model is developed to predict a person's salary based on the industry standards for the given dataset.

### Steps involved to approach this simple dataset
1. Importing the libraries
- We import the pandas library: this library is used to handle datasets
2. Reading the dataset
- We read the dataset which is a .csv file and store it in an object
3. Chossing the dependent and independent variables
- Here we extract the DV and IDV 
- **Note:** Since this is a simple dataset, we are not dealing with any **categorical variables** , **missing value treament** , **data cleaning**
4. Splitting the data into training and test data
- In this step we split the dataset into xtrain, xtest, ytrain, ytest
5. Fit the dataset to the Regressor model
- Here we fit our xtrain and ytrain to our Regressor model
- Here the model trains itself by the input provided.
6. Predicting the ouput for ytest
- After our model has learnt from the data fed, we predict the test results
7. Visualization 

**NOTE:** Currently we are not talking about how well the model is performing or whats the measure to know the model's performance
