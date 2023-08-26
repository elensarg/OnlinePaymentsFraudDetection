# OnlinePaymentsFraudDetection
About Project

This is a machine learning project made on Online Payments Fraud Detection. 
Different classification machine learning algorithms have been applied to get the maximum accuracy.

The purpose of the project is to make a machine learning model that will be able to detect whether the transaction made is fraud or genuine based upoen the given parameters. The parameters used to calculate the whether the class is fraud or genuine.

In this machine learning project, we solve the problem of online transactions fraud detecting using machine numpy, sklearn, and few other python libraries.
The below column reference:
step: represents a unit of time where 1 step equals 1 hour
type: type of online transaction
amount: the amount of the transaction
nameOrig: customer starting the transaction
oldbalanceOrg: balance before the transaction
newbalanceOrig: balance after the transaction
nameDest: recipient of the transaction
oldbalanceDest: initial balance of recipient before the transaction
newbalanceDest: the new balance of recipient after the transaction
isFraud: fraud transaction

About The Dataset
The data is taken from Kaggle. You need to go to by this link:
https://www.kaggle.com/datasets/ealaxi/paysim1?resource=download  
to download dataset CSV file and put in project root folder 
please check if file name is not “PS_20174392719_1491204439457_log.csv” rename to “PS_20174392719_1491204439457_log.csv”

Dataset Link
https://www.kaggle.com/datasets/ealaxi/paysim1?resource=download  

Machine Learning Algorithms Used
Decision Trees
By constructing a decision tree, the decision tree classifier builds the classification model. Each node in the tree represents a test on an attribute, and each branch descending from that node represents one of the property's possible values. The training set's instances are categorised by navigating them from the root of the tree to a leaf, based on the results of the tests along the way. Each node in the tree splits the instance space into two or more sub-spaces based on an attribute test condition, starting with the root node. After that, the procedure is repeated for the subtree rooted at the new node, until all records in the training set have been processed.




