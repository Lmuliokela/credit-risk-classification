# Credit Risk Classification

---

## An overview of the analysis

**Overview:** In this Challenge, I was asked to use various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.  The dataset was already provided for the challenge.

---

## Step by Step Analysis

### Split the Data into Training and Testing Sets
- Step 1: Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Step 2: Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- Step 3: Check the balance of the labels variable (y) by using the value_counts function.
- Step 4: Split the data into training and testing datasets by using train_test_split.¶

### Create a Logistic Regression Model with the Original Data
  - Step 1: Fit a logistic regression model by using the training data (X_train and y_train).
  - Step 2: Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
  - Step 3: Evaluate the model’s performance by doing the following:
  - Step 4: Answer the following question.

### Predict a Logistic Regression Model with Resampled Training Data
  - Step 1: Use the RandomOverSampler module from the imbalanced-learn library to resample the data. Be sure to confirm that the labels have an equal number of data points.
  - Step 2: Use the LogisticRegression classifier and the resampled data to fit the model and make predictions.
  -  Step 3: Evaluate the model’s performance by doing the following:¶Calculate the accuracy score of the model; Generate a confusion matrix; Print the classification report.











