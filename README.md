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
        - Balanced Accuracy Score: 95.2%
        - Precision for class 0(Healthy Loan): 100%
        - Recall for class 0: 99%
        - Precision for class 1(High-Risk Loan): 85%
        - Recall for class 1: 91%
    - Machine Learning Model 2: Logistic Regression (Trained with Resampled Data)
        - Balanced Accuracy Score: 99.4%
        - Precision for class 0: 100%
        - Recall for class 0: 99%
        - Precision for class 1: 84%
        - Recall for class 1: 99%

    Summary
    In terms of balanced accuracy, precision, and recall, the logistic regression model trained on resampled data (Model 2) performs
    better than the model trained on the original data (Model 1). In particular, Model 2 performs better in class 1(high-risk loan prediction) 
    and has a higher balanced accuracy score, with a notable recall rise from 91% to 99%.

    Given the importance of detecting high-risk loans in the context of credit risk analysis, Model 2 is the suggested option due to its superior 
    performance. Model 2 is the recommended model for the company's risk management approach because of its capacity to reduce false negatives 
    (approaching a high-risk loan) while retaining high precision and accuracy.

    The problem being handled does affect performance, and in the case of credit risk analysis, anticipating high-risk loans is crucial. Due to its 
    superior performance in this area, Model 2 is the recommended option for deployment.

    In conclusion, because of its higher performance in detecting high-risk loans and preservation of the balance between precision and recall, I 
    advise utilizing the logistic regression model trained with resampled data (Model 2) for credit risk prediction.


