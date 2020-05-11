# Churn-Prediction-Model-in-Banking-Sector
Developed a Machine Learning Model that predicts customer churn by assessing their propensity of risk to churn.

Well, from the Business point of view of a Bank — they would likely wish to identify customers who are ultimately going to exit from the Banking Business with greater accuracy — this allows the Banks to better handle the customers and provide them with offers so that they don't churn . Identifying customers who are not going to close their account with the bank may not necessarily add value to the Churn analysis, as the Bank knows that a significant proportion of customers will ultimately follow through in any case.

In this project the following have been implemented

Used Bank Customer Churn dataset available on Kaggle.

Used Dataprep, Seaborn and Pandas for Exploratory Data Analysis(EDA) and used one-hot encoding for Categorical Columns.

Used Extra Tree Classifier and Forward/Backward Feature Selection method for feature selection.  Also implemented the ML models on features selected through Recursive Feature Elimination with cross-validation (RFECV) for comparing the results.

Applied different models – Logistic Regression, Random Forest, KNN and XGBoost.

Evaluated the model classification accuracy on the test dataset through confusion matrix, AUC Score, recall and F1 measure.

Hypertuned the parameters on the XGBoost Model to achieve an accuracy of 81% on test data, AUC Score of 0.75 with less number of False Negatives which was the requirement of the Business Model.

Used Random Forest feature importance attribute to get the important features that would determine if the customer will churn or not.

Used SHAP to decrypt the Machine Learning Model for Model Explainability
