# credit-risk-classification

An Overview of the Analysis:

The dataset initially contained both low-risk and high-risk loan data points, split into training and testing sets. Logistic Regression Model 1, built using scikit-learn's LogisticRegression module, was applied to the testing set to predict loan risk. To address data imbalance, the training set was resampled using RandomOverSampler from imbalanced-learn, creating an equal number of low-risk and high-risk data points. This resampled data was then used to train Logistic Regression Model 2, aimed at predicting loan risk for the testing set. The results of Model 2 are outlined below.

Results:

For label 0 (healthy loans):
Precision Score: 100%
Recall Score: 99%
For label 1 (high-risk loans):
Precision Score: 85%
Recall Score: 91%

Summary:

The machine learning model achieved excellent precision and recall scores for both healthy loans (label 0) and high-risk loans (label 1). For healthy loans, the model demonstrated 100% precision, indicating that all loans classified as healthy were indeed healthy. The recall score of 99% for healthy loans indicates that the model correctly identified 99% of all actual healthy loans. For high-risk loans, the model achieved an 85% precision score, correctly identifying 85% of all predicted high-risk loans. The recall score for high-risk loans was 91%, showing that the model correctly identified 91% of all actual high-risk loans.

Based on these results, I highly recommend using this model for loan risk classification. Its high precision and recall scores for both healthy and high-risk loans make it a reliable tool for accurately identifying loan risks, which is essential for effective risk management in financial decision-making.
