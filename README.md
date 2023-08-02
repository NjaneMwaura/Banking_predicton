Portuguese Bank Revenue Improvement Project
Overview
This project aims to address the revenue decline faced by a Portuguese bank due to a lack of investment in long-term deposits. The bank seeks to identify existing customers with a higher likelihood of subscribing to long-term deposits and focus its marketing efforts on these targeted customers. This will help the bank improve its long-term deposit subscriptions and boost revenue.

Model
The project uses a RandomForest classifier with SMOTE to handle the imbalanced dataset. The model’s performance is shown in the classification report below, where 0 represents customers who are not likely to subscribe and 1 represents customers who are likely to subscribe to long-term deposits.

Classification Report (SMOTE):
               precision    recall  f1-score   support

           0       0.93      0.95      0.94      5798
           1       0.57      0.45      0.51       792

    accuracy                           0.89      6590
   macro avg       0.75      0.70      0.72      6590
weighted avg       0.88      0.89      0.89      6590

Conclusion


This project demonstrates the potential of using machine learning techniques to improve the bank’s long-term deposit subscriptions and boost revenue by targeting existing customers with a higher likelihood of subscribing.




# Banking_predicton
This repository contains a model that identifies customers who are unlikely to subscribe to long-term deposits in a Portuguese bank. The model can help the bank focus its marketing efforts on customers with a higher likelihood of subscribing, thereby improving its long-term deposit subscriptions and boosting revenue .
