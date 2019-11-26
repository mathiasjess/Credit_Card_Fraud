# Credit_Card_Fraud
Analysis of Credit card fraud detection using data mining and visualization techniques.

## Problem Statement

With the advent of modernization, the advancement of technology in our everyday life has exponentially increased. In the finance sector
with the introduction of credit cards, sales and purchases of goods has become easy and convenient. Everyone nowadays has his own 
credit card. While some people use technology for the betterment of society, there are others who use it for their own personal good. 
Similarly is the case of credit cards. Identity thefts and fraudulent transactions are very common forms of credit card fraud. 
Even with many strict and complex security measures taken, people always find a way to trick the security into making them think
it is a validated access. Thus, many financial establishments have turned to machine learning and artificial intelligence to provide 
with an efficient and cost effective solution for this unending problem. Our project is to implement and analyse these solutions and 
come up with an estimate of which solution is better suited for this problem.

## Dataset

The dataset used for the analysis of credit card detection in this paper contains data from European credit card holders 
consisting of rows of transactions made by credit cards. The total number of transactions captured were 500,000 and the number of features
captured were 320. Data preprocessing was done to drop the missing values. Principal component analysis was done to determine the most 
relevant features. The result of data preprocessing yielded 284,807 records and 31 most prominent features were chosen. The features 
included 28 masked features which are intentionally masked by the data source, and ‘time’ and ‘amount’ of the transaction.

## Data Preprocessing

Techniques used in Data Preprocessing

1. Data Cleaning
2. Memory Reduction
3. Under Sampling
4. Dimensionality Reduction
5. Feature Selection
6. Outlier detection


## Data mining Models

Below supervised as well as unsupervised models have implemented for the classification of fraud and non fraud transactions.

### Supervised
1. Logistic Regression
2. Support Vector Machines
3. Decision Tree
4. K Nearest neighbor
5. Neural Networks

### Unsupervised
1. K Means Clustering

## Performance of models

1. LogisticRegression

Classifiers:  LogisticRegression Has a training score of 94.0 % Training accuracy score
Classifiers:  LogisticRegression Has a test score of 92.38578680203045 % Testing accuracy score

2. KNeighborsClassifier

Classifiers:  KNeighborsClassifier Has a training score of 94.0 % Training accuracy score
Classifiers:  KNeighborsClassifier Has a test score of 91.87817258883248 % Testing accuracy score

3. SVC

Classifiers:  SVC Has a training score of 94.0 % Training accuracy score
Classifiers:  SVC Has a test score of 91.37055837563452 % Testing accuracy score

4. DecisionTreeClassifier

Classifiers:  DecisionTreeClassifier Has a training score of 92.0 % Training accuracy score
Classifiers:  DecisionTreeClassifier Has a test score of 88.3248730964467 % Testing accuracy score

5. MLPClassifier

Classifiers:  MLPClassifier Has a training score of 95.0 % Training accuracy score
Classifiers:  MLPClassifier Has a test score of 93.90862944162437 % Testing accuracy score

## Tools Usage

1. AWS Sagemaker 
Amazon AWS SageMaker is a platform that is professionally operated. It performs the entire machine learning workflow. Using AWS SageMaker, with far less effort and lower cost, our models get to production faster. Additionally, we can provide API to connect to our project. 

2. Tensor Flow
It is an open source library used for machine learning applications.

3. Google Collab
It is a cloud service which provides python programming platform along with free GPU.

