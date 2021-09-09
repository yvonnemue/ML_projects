# Defaulting loand prediction

### Situation: 

On this project you'll find a solution to a classification problem in which a bank wanted to predict the risk of defaulting of their users based on their demographic features.
Due to the nature of the situation, the predicting class (defaulting vs. not defaulting) was hugely imalanced.

### Metrics:

The ROC AUC metric was used in order to compare the performance of the models.
Due to the imalance of the target class, the confussion matrix was also used to make sure that the models were not just getting a higher score by always predicting the majority class.

### Models trained:

Several models were trained and fine-tuned in order to use the best performing one to make the final predictions.

### Results:

The demographic characteristics of the users defaulting and not defaulting is extremely similar, which means that maybe additional data should be leveraged. 
Nevertheless, a model able to correctly predict if a loan is going to default or not in **7 out of 10 cases** was achieved.

![Loan](../Images/Loan.jpg)
