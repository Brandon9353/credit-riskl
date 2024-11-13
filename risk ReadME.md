# credit-risk

# Review of the Analysis

This analysis decisively assesses the accuracy of the logistic regression model in predicting the health and risk of a loan using training data.

The dataset comprises essential variables, including loan size, interest rate, borrower income, debt-to-income ratio, number of credit accounts, derogatory marks, total debt, and loan status. I established a label variable for loan status and effectively organized the remaining data into features for precise prediction.

Subsequently, I split the data into training and testing sets using the train_test_split module. By applying the Logistic Regression Model, I captured

# Risk Results
Here are the classification report results for the logistic regression model:

**Training Data:**
- **Precision**: Achieved an impeccable 100% for healthy loans and 85% for high-risk loans.
- **Recall**: Scored an outstanding 99% for healthy loans and 89% for unhealthy loans.

This model reliably demonstrates exceptional accuracy in predicting loan health.

**Testing Data:**
- **Precision**: Maintained a flawless 100% for healthy loans and 87% for high-risk loans.
- **Recall**: Achieved a perfect 100% for healthy loans and 89% for unhealthy loans.

The model consistently delivers strong accuracy in predicting loan health with the test data.

# Risk Results
Upon reviewing the classification reports for both the training and test datasets, I observed that the model's performance remains consistent across the two sets. With strong precision and recall metrics on both the training and test data, I can confidently conclude that the model is likely to yield accurate results in real-world applications.

However, when analyzing the prediction data regarding high-risk loans, it becomes evident that the model's accuracy in this area is not as strong as its ability to predict healthy loans. This is an important factor to consider in practical scenarios, especially since a 15% error rate might be unacceptable.

If our objective were solely to identify healthy loans, I would recommend using this model. Conversely, if the goal is to detect unhealthy loans, I would advise caution, as the model may overlook some risky loans.