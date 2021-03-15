# bank_churn
------------------------------------------------
#### Neural network-based classifier that can determine whether customers will leave or not in the next 6 months.

###### Analysis of factors that can affect customer's decision to leave and join another providers in banks
(given the dataset. Sourced from Kaggle: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

##### Recall vs. Precision for unbalanced target variable
Often, when training classifiers for highly unbalanced targets, Recall and Precision model scores are inversly proportional to each other, means by increasing one of them, the other is decreasing (due to the overlaps in input variables of two different groups). This is controlled by certain hyperparameters, for instance, to concentrate on exiting, rare ocasions (for high recalls), though having lower precision for the majority class of loyal customers (suspecting many non-related).

