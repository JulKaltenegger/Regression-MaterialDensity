# Material property prediction
Phyisical properties for materials in existing buildings is hardly known and documented. This code studies ML methods to predict materials bulk density, based on material types, material thermal conductivity and specific heat capacity. 

# Data source
This study uses the ASHRAE dataset and can be found in the folder /Data

# Impute and Regression
This code studies missing data with imputation methods (mean, median, mode, knn and iterative impuation). Further, diverse ML methods are tested to predict bulk density. The linear regression, extra tree regression and ensemble model is used. 

* (1) Inpute.ipynb
* (2) 01_LinearRegression.ipynb ; 01_extraTreeRegressor.ipynb ; 01_Ensemble Model.ipynb
* (3) 02_EnsembleModel_extraTree_linReg
    
the RAG insights and parses the predicted information
as semantic graph statements.

##### Installation guid
* To reproduce the environment use pip install -r requirements.txt.

##### Project content
In this project you will find the .py files, the datasets (train, test and validation), the results.


