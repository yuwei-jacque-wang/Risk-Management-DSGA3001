## Hurricane Flood Recovery Prediction
This project predicts recovery time on county level after flood or hurricane happens, from data of power consumption. The highlights here is **multiple layer model structure** (in adoption with dataset) which significantly improves regression performance.

### Descriptions of files:

- Original data file: *sampleStruc.csv* and *sampleUnstr.csv*
  - Information on county level, target variable is 'recovery' column in the files. These two dataset can be directly applied to script Two_Layer_Model.ipynb
  
- Alternative data file: *sampleStormCounties.csv*
  - Alternative data on county level, contains additional variables that are not included in previous files
  
- Script for codes: *Two_Layer_Model.ipynb*
  - All codes starting from importing data, basic transformation, and construction of two layer models. Also contains comparison of test scores from two-layer model and single layer model. 
