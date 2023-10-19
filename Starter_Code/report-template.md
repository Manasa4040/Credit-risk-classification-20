# Module 12 Report Template
## Credit Risk Analysis Report
!!"C:\Users\prudh\OneDrive - Saipem\Desktop\module 20 assignment\Starter_Code\shutterstock_91856543-1024x778.jpg"

##Contents:
 1.Overview of the Analysis

 2.Results

 3.Summary

##Overview of the Analysis:

**Lending companies lend money/properties to borrowers with the expectation that the borrower will either return the asset or repay the lender. Credit Risk is associated with a borrower not returning an asset or paying a loan back causing a lender to lose money. This is measured by lenders in many ways, however in this analysis we will use Machine Learning to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

*Using a machine learning model, I will try to determine which loans are healthy (low-risk) or non-healthy (high-risk) based on the loan status provided by the lending company.

  **The Logistic Regression Algorithm is the best tool to use for our machine learning model since it is widely used to predict the probability of a target variable in classification problems.

*Using the dataset provided by the lending company, I created a Logistic Regression Model that generated an accuracy score of 95%. Although the model generated a high-accuracy, the models recall value (0.91) for non-healthy loans is lower than the recall value (0.99) for healthy loans. This indicates that the model will predict loan status's as healthy better than being able to predict loan status's as non-healthy. This is due to the dataset being imbalanced, meaning that most of the data belongs to one class label (in this case healthy loans greatly outweighed non-healthy loans).

**Out of the 18,765 loan status's that are healthy (low-risk), the model predicted 18,663 as healthy correctly and 102 as healthy incorrectly.

**Out of the 619 loan status's that are non-healthy (high-risk), the model predicted 563 as non-healthy correctly and 56 as non-healthy incorrectly.

!"C:\Users\prudh\OneDrive - Saipem\Desktop\module 20 assignment\Starter_Code\Screenshot 2023-10-18 112139.png"



##Results:

*The model fitted with imbalanced data has a higher possibility of making these mistakes:

  **a healthy loan (low-risk) is classified as a non-healthy loan (high-risk).
  **a non-healthy loan (high-risk) is classified as a healthy loan (low-risk).

  "C:\Users\prudh\OneDrive - Saipem\Desktop\module 20 assignment\Starter_Code\Screenshot 2023-10-18 112231.png"

  *The logistical regression model was 95% accurate predicting the "healthy loan" vs "high-risk loan"

##Summary:

*A lending company might want a model that requires classifying healthy loans and High-risk loans correctly most of the time:

**healthy loans being identified as a Hgh-risk loan might be more costly for a lending company since it might cause the loss of customers.

**High-risk loans being identified as a healthy loan might also be more costly for a lending company due to the loss of funds being provided by the lender.



