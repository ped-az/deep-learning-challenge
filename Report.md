# Module 21 Report

## Overview of the Analysis

1. Purpose: This analysis utalises supervised machine learning to to provide insights and attempt to identify credit the oveall risk from indivisuals wishing to borrow funds (Data in the Resources Folder under [File](Resources/lending_data.csv))

2. Dataset: The model's underlying dataset contains a range of different financial information about each individual borrower. This data is later analysed and interpreted by the model to make predictions whilst checking for its accuracy.

3. The Model Itseld: 
- A Linear Regression model was created by using "Training Data" (Refer to Step 1)
- Based on the training Data, Predictions were made for all the line items. (Refer to Step 2)
- A confussion Matrix was generated followed by a classification report. (Refer to Step 3)


## Results & Summary
Overall the model was seems to perform well with an accuracy score of 99%. 
- Healthy Loans have an f1 score of 1 while;
- High-risk loans have an f1 score of 0.88. 
- Precision also showed significant results with a value of 1 for healthy laons and 0.85 for High-Risk Loans. 
- Recall also showed significant results with a 100% for low irsk and 0.89 gor high risk loans. 

This highlights how the model accurately managed to predict all the healthy loans while predicting 88% of the high-risk loans. under financial diversification standards this high level predictions could be improved but still considered successfull in the prediction of loans. 

