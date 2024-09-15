# Loan-Approval-Prediction
Loan approval prediction involves the analysis of various factors, such as the applicant’s financial history, income, credit rating, employment status, and other relevant attributes. By leveraging historical loan data and applying machine learning algorithms, businesses can build models to determine loan approvals for new applicants.

I found an ideal dataset for the task of Loan Approval Prediction. You can download the dataset from [here](https://www.kaggle.com/datasets/ninzaami/loan-predication).

## Model Preparation Steps
    - convert categorical columns into numerical ones;
    - split the data into training and test sets;
    - scale the numerical features;
    - train the loan approval prediction model.

## Support Vector Classifier (SVC)
The model used here for loan approval prediction is a Support Vector Classifier (SVC) from the sklearn library. Here’s a brief overview:

- **Data Preparation:** Categorical columns are converted to numerical using one-hot encoding. The dataset is split into training and testing sets.
- **Scaling:** Numerical features are scaled using StandardScaler to standardize the data.
- **Model Training:** The SVC model is trained on the training set with random_state=42 to ensure reproducibility.
- **Prediction:** The trained model makes predictions on the test set.
