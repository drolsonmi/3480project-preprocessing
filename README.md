# Class Project: Preprocessing and EDA
__MATH 3480__: Machine Learning

A survey was completed to evaluate the mental health of young people. We are going to use the dataset to create a model to predict whether a person is likely to be lonely or not. Your job in this project is to complete the entire data preprocessing for the data.

* Load the *young-people-survey-responses* dataset
  * Located in the GitHub Classroom repo
* Perform Data Preprocessing on this data
  * What variables are not needed? Drop them
  * Handle missing values 
    * If more than 10% of the values in a given row/column are missing, remove them
    * If fewer than 10% of the values in a given row/column are missing, fill them with min, max, mean, or median - whatever will best deal with each variable
  * Encode categorical variables using either one-hot encoding, ordinal encoding, or label encoding
* Divide the data into Training and Testing Groups
* Scale the features by using standardized scaling
  * Do all features need to be scaled? Consider each variable carefully.
  
To see if our data is correctly preprocessed, let’s put this through a test model. For this, we’ll use a multi-linear regression. This part is not going to be graded. It is just good for you to see if your data is good for a model.
* Apply to a multi-linear regression model to see if you can model