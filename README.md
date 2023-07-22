# credit-risk-classification - Module 20

## Summary
This challenge aims to build a credit risk classification model using historical lending data from a peer-to-peer lending services company. The goal is to create a logistic regression model that can accurately identify the creditworthiness of borrowers, distinguishing between healthy loans (0) and high-risk loans (1).

### The steps and point allocations are as follows:

1. Split the Data into Training and Testing Sets (30 points):
- Read the lending_data.csv from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the "loan_status" column and the features (X) DataFrame from the remaining columns.
- Split the data into training and testing datasets using train_test_split.

2. Create a Logistic Regression Model (30 points):
- Fit a logistic regression model using the training data (X_train and y_train).
- Save the predictions for the testing data labels using the testing feature data (X_test) and the fitted model.
- Evaluate the model's performance by generating a confusion matrix and a classification report.
- Answer the question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

3. Write a Credit Risk Analysis Report (20 points):
- Provide an overview explaining the purpose of the analysis.
- Describe the accuracy, precision, and recall scores of the machine learning model using a bulleted list.
- Summarize the results from the machine learning model and justify the recommendation for or against using the model by the company.

4. Coding Conventions and Formatting (10 points):
- Use appropriate coding conventions such as placing imports at the top, using lowercase characters with underscores for function and variable names, following DRY principles, and employing concise logic and creative engineering where possible.

5. Code Comments (10 points):
- Ensure the code is well-commented with concise and relevant notes that other developers can easily understand.

### External Resources
I used the following websites to help me complete the assignment:
- https://stackoverflow.com
- https://scikit-learn.org
- https://imbalanced-learn.org
