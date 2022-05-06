# Telco Customer Churn Prediction

![download](https://github.com/AndiRen/group7_project1/blob/main/telco_churn.png)

### Basic Information

* **Person or organization developing model**: 
* **Project date**: April, 2022
* **Project topic**: Determine if the key risk factors listed by the CDC were good predictors for heart disease and also explore if there are other, less prevalent factors that were also useful predictors. 


### Data Information

* Data dictionary: Brief Description of Final Set of Variables

1.  Senior.Citizen [whether customer is a senior citizen]
2.  Partner [whether customer is single]
3.  Dependnts [whether customer has dependents]
4.  Tenure.Months` [length of time as customer]
5.  Phone.Service [whether customer using phone services]
6.  Internet.Service [type of internet service used -- affects speed]
7.  Online.Security [whether customer uses online security service]
8.  Online.Backup [whether customer uses online backup service]
9.  Tech.support [whether customer enrolled in tech support plan]
10. Contract [type of contract (month-to-monthly, year, etc.)]
11. Paperless.Billing [whether customer uses paperless billing]
12. Payment.Method [payment method that customer uses]
13. Monthly.Charges [average total monthly charge for customer]
14. Churn.Label [whether a customer did or did not churn]
15. Churn.Reason [specific reason customer gave for churning]
16. Statisfaction.Score [rating customers gave for their satisfaction as a customer]
17. Churn.Category [for customers who churned, category of reason for leaving]
18. Ave.Monthly.Long.Distance.Charges [average long-distance charges in a month]
19. Avg.Monthly.GB.Download [avg amount of data downloaded in a month]
20. Unlimited.Data [whether customer has unlimited data plan]
21. Total.Extra.Data.Charges [lifetime extra data charges customer has accrued]

* **Source of test data**: https://www.kaggle.com/ylchang/telco-customer-churn-1113


### Model Evaluation:

| Model | Logistic Regression | Randomforest | SVM | Decision Tree(prune) |
|------| ------ | -------- | --------- | ------ |
| Accuracy | 73.5% | 80.3% | 80.9% | 80.63% |
| Sensitivity | 76.9% |85.3% | 58.8% | 50.45% |
| Specificity | 71.4% | 64.2% | 88.9% | 91.23% |
| AUC | 82% | 73% | 74% | 82% |




