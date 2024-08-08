# classification-challenge

## Inital effort
* To begin, I created the git repository for this effort
* I then downloaded the Module 13 Challenge starter code
* I saved a new version of the started code notebook for my purposes


Instructions
This challenge consists of the following subsections:

Split the data into training and testing sets.

Scale the features.

Create a logistic regression model.

Create a random forest model.

Evaluate the models.

## Split the Data into Training and Testing Sets

Read the data from https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csvLinks to an external site. into a Pandas DataFrame.

In the appropriate markdown cell, make a prediction as to which model you expect to do better.

Create the labels set (y) from the “spam” column, and then create the features (X) DataFrame from the remaining columns.

note
A value of 0 in the “spam” column means that the message is legitimate. A value of 1 means that the message has been classified as spam.

Check the balance of the labels variable (y) by using the value_counts function.

Split the data into training and testing datasets by using train_test_split.

Scale the Features
Create an instance of StandardScaler.

Fit the Standard Scaler with the training data.

Scale the training and testing features DataFrames using the transform function.

Create a Logistic Regression Model
Employ your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the scaled training data (X_train_scaled and y_train). Set the random_state argument to 1.

Save the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.

Evaluate the model’s performance by calculating the accuracy score of the model.

Create a Random Forest Model
Employ your knowledge of the random forest classifier to complete the following steps:

Fit a random forest classifier model by using the scaled training data (X_train_scaled and y_train).

Save the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.

Evaluate the model’s performance by calculating the accuracy score of the model.

Evaluate the Models
In the appropriate markdown cell, answer the following questions:

Which model performed better?

How does that compare to your prediction?