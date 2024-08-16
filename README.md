# classification-challenge

## Inital effort
* To begin, I created the git repository for this effort
* I then downloaded the Module 13 Challenge starter code
* I saved a new version of the started code notebook for my purposes


## Instructions
This challenge consists of the following subsections:
* Split the data into training and testing sets.
* Scale the features.
* Create a logistic regression model.
* Create a random forest model.
* Evaluate the models.

## Split the Data into Training and Testing Sets
* Read the data into a Pandas DataFrame.
* Predicted that the random forest model would perform better due to the non-linear nature of the data.
* Created the labels set (y) from the “spam” column, and then created the features (X) DataFrame from the remaining columns.
* Checked the balance of the labels variable (y) by using the value_counts function.
* Split the data into training and testing datasets by using train_test_split.

## Scale the Features
* Created an instance of StandardScaler.
* Fit the Standard Scaler with the training data.
* Scaled the training and testing features DataFrames using the transform function.

## Created a Logistic Regression Model
* Fit a logistic regression model by using the scaled training data (X_train_scaled and y_train). Set the random_state argument to 1.
* Saved the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.
* Evaluated the model’s performance by calculating the accuracy score of the model.

## Created a Random Forest Model
* Fit a random forest classifier model by using the scaled training data (X_train_scaled and y_train).
* Saved the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.
* Evaluated the model’s performance by calculating the accuracy score of the model.

## Evaluated the Models
* The Random Forest Model performed better due to the type of data being analyzed which is what I predicted in the beginning

## Resources
* I utilized class presentations to review methodology and definitions
* I utlized solved class student and instructer exercises to review the approach and compare some of my formulas
* I utilized Copilot to help me understand why I would used a Logistic Regression model versus a Random Forest Model