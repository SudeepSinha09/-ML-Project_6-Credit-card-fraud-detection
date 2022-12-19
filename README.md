# ML-Project_6-Credit-card-fraud-detection

     Kaggle - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?select=creditcard.csv
     Colab Notebook - https://colab.research.google.com/drive/1-6Qd2hknHQwBxDXXXf_t8KvEcNMQ99pZ?usp=sharing
     info at Github - https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html
     Data - creditcard.csv (150.83 MB)

#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_6-Credit-card-fraud-detection/blob/main/Credit%20card%20fraud%20detection.ipynb

## Description

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.  

The dataset contains transactions made by credit cards in September 2013 by European cardholders.  
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.  

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.  

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.  

#### Update

A simulator for transaction data has been released as part of the practical handbook on Machine Learning for Credit Card Fraud Detection - https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html. We invite all practitioners interested in fraud detection datasets to also check out this data simulator, and the methodologies for credit card fraud detection presented in the book.

## An Overview of EDA

![image](https://user-images.githubusercontent.com/93086122/208389243-6ba1b9f7-7d0f-475a-b703-e10c442cebc1.png)

![image](https://user-images.githubusercontent.com/93086122/208389335-083b96b3-0ec1-4aa5-b1ca-5dd9c76cae58.png)

### Acknowledgements

The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.
More details on current and past projects on related topics are available on https://www.researchgate.net/project/Fraud-detection-5 and the page of the DefeatFraud project
