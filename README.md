# Credit-card-default-risk-prediction

In order to have high volumes of market share in the financial sector, banks tend to issue large 
credits to their clients – some of which are unqualified to handle such a great volume of credit. 
Majority of clients, regardless of their payback power, spend their credit recklessly and start 
collecting large debts. This will result in a crisis which targets the consumer finance confidence. 
Therefore, creating a model to perform risk prediction that can forecast unqualified clients would 
be a great help to both the banks and the cardholders. We chose "default of credit card clients" dataset to utilize Taiwan’s important bank data to develop a model that has the predicting power to classify if clients 
will default on their future payments to solve the consumer finance crisis. The dataset contains 30,000 observations with mix clients that have and have not default on their payments (Target Variable). Important features such as the given credit amount, education, age, history of past payment, etc., is provided within 
the dataset. We used Recursive Feature Elimination and other feature elimination methods to 
disregard features that are of low importance to our target variable. knn and logistic regression used with best knn model giving test accuracy of 78% and f1 of 0.8.
