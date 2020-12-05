# Credit card fraud detection
![](images/images1.jpeg)

### Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

### Content
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise. 

### Dataset
We can find dataset on kaggle.
Link to dataset :https://www.kaggle.com/mlg-ulb/creditcardfraud

### Machine Learning ALgorithm Used
Since the dataset is highly imbalanced, so we used algorithm to detect anomaly:
1. IsolationForest
2. LocalOutlierFactor
 out of which IsolatonForest worked well with 99.73% accuracy and LocalOutlierFactor achieved accuracy of 99.65%.

### Programming language used
![](images/index.jpeg)

### Platform used
![](images/index1.png)
