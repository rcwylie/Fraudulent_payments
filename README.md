# Fraudulent_payments

Overview
This script serves the purpose of conducting feature selection and comparing various classification models on a pre-processed dataset. The primary objectives of this script are as follows:

Data Cleaning and Pre-processing: The script starts by cleaning and pre-processing the dataset to ensure data quality and consistency.

Feature Selection: Feature selection is performed using the Mutual Information method. This step aims to identify the most relevant features for the classification task.

Model Comparison: The script evaluates and compares the performance of different classification models. The following models are included:

* Logistic Regression
* Random Forest
* XGBoost
* Artificial Neural Network (ANN)
  
Details
Data Cleaning and Pre-processing
The initial phase involves data cleaning and pre-processing to handle missing values, outliers, and ensure data consistency. It's essential to have a clean dataset as a foundation for accurate model building.

Feature Selection with Mutual Information
Mutual Information is employed to assess the importance of each feature concerning the target variable. Features with higher mutual information are considered more relevant and are retained, while less informative features are discarded.

Model Comparison
The script proceeds to build and evaluate four distinct classification models, each with its strengths and characteristics. These models are benchmarked and compared using Area Under Curve (AUC) to determine which one performs best for the specific classification task.


Data used:
https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022/


References:

1. Fraud Classification Priniciples
Fraud Detection Methods -https://journalofbigdata.springeropen.com/articles/10.1186/s40537-022-00573-8
Fraud Detection Methods -https://www.kaggle.com/code/juanjosmorenogiraldo/bank-fraud-detection-using-gbm#3-%7C-Data-Preprocessing
Fraud Detection Methods - https://trenton3983.github.io/files/projects/2019-07-19_fraud_detection_python/2019-07-19_fraud_detection_python.html

2. Feature Selection
Information Gain Method - https://jovian.com/poduguvenu/feature-selection-using-information-gain

3. Modelling Methods
Random Forest - https://www.kaggle.com/code/hassanamin/credit-card-fraud-detection-using-random-forest#Using-Scikit-learn-to-split-data-into-training-and-testing-sets
XGBoost and feature selection - https://domino.ai/blog/credit-card-fraud-detection-using-xgboost-smote-and-threshold-moving
ANN Node Optimization - https://www.analyticsvidhya.com/blog/2021/09/a-comprehensive-guide-on-neural-networks-performance-optimization/
