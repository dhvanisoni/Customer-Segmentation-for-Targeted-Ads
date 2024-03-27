## Customer Segmentation for Credit Card Marketing Ads


### Overview
Dataset for bank in New York city. The bank has extensive data on their customers for the past 6 months. The marketing team wants to launch a targeted ad marketing campaign by dividing their customers at least 3 distinctive groups. Sample Dataset summarizes the usage behaviour of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioural variables.

### Following is the Data Dictionary for Credit Card dataset:
CUST_ID: Identification of Credit Card holder (Categorical)\
BALANCE: Balance amount left in their account to make purchases\
BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 =
frequently updated, 0 = not frequently updated)\
PURCHASES: Amount of purchases made from account\
ONEOFF_PURCHASES: Maximum purchase amount done in one go.\
INSTALLMENTS_PURCHASES: Amount of purchase done in instalment.\
CASH_ADVANCE: Cash in advance given by the user\
PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 1
frequently purchased, 0 not frequently purchased)\
ONEOFFPURCHASESFREQUENCY: How frequently Purchases are happening in one go 1
frequently purchased, 0 not frequently purchased)\
PURCHASESINSTALLMENTSFREQUENCY: How frequently purchases in installments are being
done 1 frequently done, 0 not frequently done)\
CASHADVANCEFREQUENCY: How frequently the cash in advance being paid\
CASHADVANCETRX: Number of Transactions made with "Cash in Advanced"\
PURCHASES_TRX: Number of purchase transactions made\
CREDIT_LIMIT: Limit of Credit Card for user\
PAYMENTS: Amount of Payment done by user\
MINIMUM_PAYMENTS: Minimum amount of payments made by user\
PRCFULLPAYMENT: Percent of full payment paid by user\
TENURE: Tenure of credit card service for user

### Methodology
**Data Cleaning:**

* Removed missing or duplicate values.
* Standardized data formats and types.

**Exploratory Data Analysis (EDA):**

* Investigated the distribution of variables.
* Identified correlations between variables.

**Analysis and Preprocessing:**

* Normalized numerical variables.
* Encoded categorical variables.
* Split data into training and testing sets.

**K-means Clustering:**

* Applied unsupervised learning to segment customers.
* Used the elbow method to determine the optimal number of clusters.

**Principal Component Analysis (PCA):**

* Reduced dimensionality of the dataset.
* Identified important features for clustering.

**Autoencoders:**

* Implemented to learn compressed representations of input data.
* Enhanced clustering accuracy.

### Dependencies
Python/
Libraries: pandas, numpy, matplotlib, seaborn,sickit-learn, 
 
