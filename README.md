# predicting-car-prices

## Objective
Use machine learning algorithms to predict a car's market price using its attributes.

### About The Dataset
The data set contains information on various cars. For each car we have information about the technical aspects of the vehicle such as the motor's displacement, the weight of the car, the miles per gallon, how fast the car accelerates, and more.
* Download [here](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data)
* See Dataset information [here](https://archive.ics.uci.edu/ml/datasets/Automobile)

## [Notebook Contents](../master/machine_learning_predicting_car_prices.ipynb)
1. Reading The Data    
  A. Handling Missing Column Names  
2. Exploring The Data  
  A. Get row count, column count, column types, summary information about columns  
  B. Determine target column  
3. Cleaning The Data  
  A. Handling missing values  
  B. Converting columns of object type containing numeric data to float type  
  C. Normalizing the numeric columns  
4. Creating A Univariate Model (k-nearest neighbors)  
  A. Train and test model for each feature column using default value for k  
  B. Evaluate models and determine features with best performance based on RMSE  
  C. Train and test model for each feature column using a range of values for k  
  D. Determine features with best performance for each value of k based on RMSE  
  E. Plot histogram of RMSE values  
5. Creating A Multivariate Model (k-nearest neighbors)  
  A. Train and test model using the 2 best features and the best k value (lowest RMSE) from the previous step  
  B. Train and test model using the 3 best features and the best k value (lowest RMSE) from the previous step  
  C. Train and test model using the 4 best features and the best k value (lowest RMSE) from the previous step   
  D. Train and test model using the 5 best features and the best k value (lowest RMSE) from the previous step  
  E. Display all the RMSE values  
6. Hyperparameter Tuning  
  A. For the top 3 models from the previous step, vary the hyperparameter value from 1 to 25  
  B. Plot the RMSE values  
  C. Determine the optimal k value for each model  
7. Using k-fold cross validation for model validation  
  
  

