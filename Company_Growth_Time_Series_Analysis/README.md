# To invest, or not to invest, that is the question

![Loan](../Images/Invest.jpeg)

### Situation: 

On this project you'll find a time series analysis performed to asses if it is a good idea or not for comapny A to invest in company B based on its performace during the past 850 days. Company A bases its business model in lending money to other companies with an interest of 6% which is returned monthly based on the revenue of the company B. The sooner company B is able to return the money lent, the better for company A, since that means that company A can invest that money on another company, let's call it company C.

### Models trained:

Both ARIMA and Facebook Prophet were trained and their outcomes were compared in order to use the best performing one to make the final forecast, upon which the calculations of the ROI rate are based.

### Metrics:

The ROC AUC metric was used in order to compare the performance of the models.
Due to the imbalance of the target class, the confusion matrix was also used to make sure that the models were not just getting a higher score by always predicting the majority class.

### Results:

The demographic characteristics of the users defaulting and not defaulting is extremely similar, which means that maybe additional data should be leveraged. 
Nevertheless, a model able to correctly predict if a loan is going to default or not in **7 out of 10 cases** was achieved.
