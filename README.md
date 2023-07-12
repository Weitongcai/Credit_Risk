# Credit_Risk
Hello
This is Weitong Cai's assignment for module 20. 

Overview of the Analysis
The purpose of this analysis is to use the a 77536 historical dataset from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers, which could help bank or financial institutions to avoid the potential loss from the borrower or defaults loans. The model were built based no the independent variables of Loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks to compare the loan status between healthy loan  and high-risk loan. I divided the data set as x and y training sets, as well as x and y testing sets. After that, I created a logistic regression model to compared with prediction of the logistic regression model with resampled training data.


Results
Machine Learning Model 1:
- [ ] 1. The balanced accuracy score is 99.23%
- [ ] 2. The classification report 

![Pasted Graphic](https://github.com/Weitongcai/credit-risk-classification/assets/124700884/c1495713-9735-4ae6-b71d-11fad0a50b53)

Model 1 is the Logistic Regression Model with the original data, based on the above classification report, this model shows excellent precision and perfect recall in predicting healthy loans as 100% . The model's precision and recall in predicting high-risk loans are 89% and 88%, which are not as prefect as healthy loan, but still consider as a high accuracy values.

Machine Learning Model 2:
- [ ] 1. The balanced accuracy score is 99.68%
- [ ] 2. The classification report

![Pasted Graphic 1](https://github.com/Weitongcai/credit-risk-classification/assets/124700884/9943cc06-3fba-441e-af64-7ccf22e17894) 
￼
Model 2 is the prediction of a Logistic Regression Model with resampled training data, it shows the recall for both healthy loan and high-risk loan are prefect as 1. However, the high-risk loan resulting a lower precision than healthy loan, the differences are 0.13 which are not so much.



Summary
As we can see from the above results, both accuracy score are nearly prefect, but the classification report for the Model 2 shows the better recall rate for the high risk loan. So, I will recommend the prediction of a Logistic Regression Model with resampled training data for the credit company to consider as priority, but it is better to run both of the model to get a more reliable results.

However, there are more complicated cases in reality, the above two models may not as perfect as it shows above due to the misleading dataset. These two models will help the  bank and other financial institutions to avoid part of potential loss when they are evaluating their borrowers, but of all of them, so it is better to speak as a case by case situation.

