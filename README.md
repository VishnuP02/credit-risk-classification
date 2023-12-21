In this Challenge, I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending 
activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Resources used in completion of challenge:
    - Lecture Slides, Class Recordings, Tutoring session w/ Mark Fullton, and AskBCS sessions with Ashwin Bhatnagar & Tristen Ortiz

                                            
                                            Credit Risk Analysis Report
    Overview of the Analysis
    The purpose of the analysis was conducted to asses how well machine learning model predicted credit risk. To determine 
    whether a loan is likely to be a high risk (1) or a healthy loan(0), financial data pertaining to loan applications made 
    up the data used. The loan amount, imterest rate, borrower income, debt-to-income ratio, number of accounts, negative credit
    history, and overall debt were among the variables. Data preparation, model training, and evaluation were among the phases of 
    the machine learning process that were engaged in the analysis.

    I used a logistic regression model as my main approach for machine learning. In addition, I resampled the training data using 
    the RandomOverSampler from the imbalanced-learn module to correct the class imbalance and improve model performance.

    Results
    - Machine Learning Model 1: Logistic Regression (Trained on Original Data)
        - Balanced Accuracy Score:
        - Precision for class 0(Healthy Loan):
        - Recall for Class 1(High-Risk Loan):
        - Recall for class 1:
    - Machine Learning Model 2: Logistic Regression (Trained with Resampled Data)
        - Balanced Accuracy Score:
        - Precision for class 0(Healthy Loan):
        - Recall for Class 1(High-Risk Loan):
        - Recall for class 1:

