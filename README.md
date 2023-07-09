# AmericanBankruptcyLogisticRegression

In this project, predictions were made on whether companies would sink or survive based on their data. Since the data is imbalanced, with a higher probability of "survive" instances, I recommend researching SMOTE (Synthetic Minority Over-sampling Technique) to balance and analyze the data.

![shutterstock_605354063](https://github.com/ahmetdzdrr/AmericanBankruptcyLogisticRegression/assets/117534684/ebc95597-ec7f-4250-a66a-a322a1d6bf67)


DATA PREPROCESSING

In the data preprocessing stage, only the column names were changed as the relevant columns did not contain meaningful information.

CORRELATION ANALYSIS

All the information in the dataset was examined using a correlation matrix to identify the relationships between variables. After the examination, the column named "net_income" was removed from the dataset as it was found to have no impact on the other variables in the dataset.

![download](https://github.com/ahmetdzdrr/AmericanBankruptcyLogisticRegression/assets/117534684/c6c80b2e-810c-405c-bd3b-2c3c7ac1a2bd)

BUILDING THE LOGISTIC REGRESSION MODEL

With the logistic regression model, a prediction accuracy of 92% was achieved. The predictions made on the test data were highly successful with this accuracy rate.
However, as mentioned at the beginning of the report, due to the imbalanced nature of the dataset, where the "survive" instances are more prevalent, our model has exhibited overfitting.

![download](https://github.com/ahmetdzdrr/AmericanBankruptcyLogisticRegression/assets/117534684/c278213f-1900-4df1-93e4-77790b4f772e)
