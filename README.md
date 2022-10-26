## Customer-Segmentation-Kmeans-Cluster-Unsupervised-Learning
### Topics

#### This project used following topics :

* Data Wrangling
* Data Visualization
* Data Preparation and Feature Engineering
* Dimensionality Reduction
* Unsupervised Learning

#### Data is available in Data Folder. The data contains following tables :
* twm_customer - information about customers
* twm_accounts - information about accounts
* twm_checking_accounts - information about checking accounts (subset of twm_accounts)
* twm_credit_accounts - information about checking accounts (subset of twm_accounts)
* twm_savings_accounts - information about checking accounts (subset of twm_accounts)
* twm_transactions - information about financial transactions
* twm_savings_tran - information about savings transactions (subset of twm_transactions)
* twm_checking_tran - information about savings transactions (subset of twm_transactions)
* twm_credit_tran - information about credit checking (subset of twm_transactions)

#### Output
In this miniproject, we will :

1. create two separate customer segmentations (using clustering) to split them into 3-5 clusters:
   * based on demographics (only on the information from twm_customer)
   * based on their banking behavior. We can take following things into consideration as banking behavior:
     - do they have savings account? How much do they save?
     - do they have credit account? How much do they live in debt?
     - are they making lot of small transactions or few huge ones?

2.visualize the created clusters using radar charts and compare them agains each other

3.visualize segmentations using scatter plot. We will have to use PCA to be able to plot our observations in 2D .
