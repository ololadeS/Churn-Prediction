## Predicting Customer Churn

**Goal**: To develop a machine learning model to predict the likelihood of a customer churning, i.e., canceling their subscription or service.

**Data**: The dataset used for this project contains historical customer data from kaggle ('https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction')

**Steps**:
- Data preprocessing
- Feature engineering
- Feature selection: using mutual information classifier 
- Model selection and training: logistic regression and random forest models were evaluated to select the best  model for predicting customer churn. 
- Model evaluation: using classification report and ROC


**Results**:
The Random Forest model was selected as the best model for predicting customer churn. The model achieved an AUC of 96% on the holdout test set.
