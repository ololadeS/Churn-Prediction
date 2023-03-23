# Customer Churn Prediction Model
This project implements a churn prediction model that can be used to predict customer churn for a E commerce company.

### Data Preparation
The first step involves cleaning and preprocessing by loaded the data into a pandas DataFrame and then performed various data cleaning and preprocessing steps, such as handling missing values.

### Data Splitting
The data were split into training, validation and testing sets. The training set is used to train the model, while the validation and testing set were used to evaluate the performance of the model.

### Training and Validation
The model were trained on the training set using logistic regression, then evaluated the performance of the model on the validation set and perform parameter tuning to ensure that it was not overfitting the training data and use roc auc score to evaluate the performance of the model.

### K-Fold Cross-Validation
To further validate the performance of the model, k-fold cross-validation was use. This involves splitting the data into k folds and then training and evaluating the model k times, each time using a different fold as the validation set. I used k=5 for our model, which means that it trained and evaluated the model 5 times, each time using 4 folds for training and 1 fold for validation.

### Testing
After training and validating the model, i tested it on the testing set to get a final performance evaluation. The same metrics used in the validation step was used to evaluate the performance of the model on the testing set.

### Saving the Model with Pickle
Saved it to a file using the pickle library which allows to easily load the model in the future and use it to make predictions on new data.

### Making Predictions with the Model
I simply load the model using pickle and then use it to make predictions on new data. I passed the new data to the predict method of the model object and get the predicted values.

### Knowledge Gain
In this project, i learned about the importance of data preparation and preprocessing in building an effective churn prediction model. I also learned about various evaluation metrics for binary classification problems and how to use k-fold cross-validation to validate the performance of the model. Finally, I learned how to save the trained model using pickle and use it to make predictions on new data.
