## Fraud Detection
This project utilizes data of credit card transactions to detect fraud transactions. The highlights of this simple user case is **feature engineering part which provides insights of dealing with time series data.**

### Descriptions of files:

- Original data file: *sample.csv*
  - The file contains full purchase history of 50 selected cards. Details of creating the sample can be referred in first part of Data_Processing notebook.
  
- Processed data file: *sample_done_new.csv*
  - This is the data file ready to enter models directly for training. The file is the output of Data_Processing notebook. 

- Re-sampling and feature engineering: *Data_Processing_YW.ipynb*
  - The notebook contains functions of feature engineering, especially with making use of time-series. 
  
- Model and evaluation: *Model_Result_YW.ipynb*
  - Models and corresponding validation scores. Contains an up-sampling of minority class in the beginning.
  
#### *The project works as a good candidate for DS project mining interviews. Check Interview Project Mining PDF 
