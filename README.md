# predicting-car-prices

## Objective
Use machine learning algorithms to predict a car's market price using its attributes.

### About The Dataset
The data set contains information on various cars. For each car we have information about the technical aspects of the vehicle such as the motor's displacement, the weight of the car, the miles per gallon, how fast the car accelerates, and more.
* Download [here](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data)
* See Dataset information [here](https://archive.ics.uci.edu/ml/datasets/Automobile)

##Jupyter Notebook Contents
1. Reading The Data
  1. Handliing Missing Column Names
2. Exploring The Data
  1. Get row count, column count, column types, summary information about columns
  2. Determine target column
3. Cleaning The Data
  1. Handling missing values
  2. Converting columns of object type containing numeric data to float type
  3. Normalizing the numeric columns
4. Creating A Univariate Model (k-nearest neighbors)
  1. Train and test model for each feature column using default value for k
  2. Evaluate models and determine features with best performance based on RMSE
  3. Train and test model for each feature column using a range of values for k
  4. Determine features with best performance for each value of k based on RMSE
  5. Plot histogram of RMSE values
5. Creating A Multivariate Model (k-nearest neighbors)
  1. Train and test model using the 2 best features and the best k value (lowest RMSE) from the previous step.
  1. Train and test model using the 3 best features and the best k value (lowest RMSE) from the previous step.
  1. Train and test model using the 4 best features and the best k value (lowest RMSE) from the previous step.
  1. Train and test model using the 5 best features and the best k value (lowest RMSE) from the previous step.
  1. Display all the RMSE values
6. Hyperparameter Tuning
  1. For the top 3 models from the previous step, vary the hyperparameter value from 1 to 25
  2. Plot the RMSE values
  3. Determine the optimal k value for each model
7. Using k-fold cross validation for model validation
  
  

