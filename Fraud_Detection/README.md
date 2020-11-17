## Fraud Detection
This project utilizes data of credit card transactions to detect fraud transactions. The highlights of this simple user case is feature engineering part which provides insights of dealing with time series data.

### Descriptions of files:

- Original datafiles provided: fraud_train.csv and fraud_test.csv
  * The initial way of splitting train and test was by arbitary transaction time (before 2019/06/21 and after). We think this way of splitting is not beneficial for contructing features related to personal purchase history, so we rather combined file and conducted re-sampling. More details can be viewed in data_processing notebook. 
- Re-sampling and feature engineering: Data_Processing_YW.ipynb
