# Counterfeit Medicines Sales Prediction

Task here is to build predictive model for predicting sales figures given other information related to counterfeit medicine selling operations.

Model is built by using regressor algorithm and to reduce mean absolute error.

Random Forest and XG boost is used for predicting sales (Target feature).

PCA is done on top of it as it gave better results.

### Features created
Continuous variables have been discretized using KNNdiscretizer from sklearn which gave better results.

Robust scaling was performed on features which helps XGB as it uses gradeint descent and also it is helpfull for doing PCA.
