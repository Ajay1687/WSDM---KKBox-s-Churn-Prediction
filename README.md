# WSDM---KKBox-s-Churn-Prediction
KKBOX has a music subscription service for which it wants to predict the user churn prediction; i.e whether the user will continue the subscription. 

Data set is available at Kaggle (https://www.kaggle.com/c/kkbox-churn-prediction-challenge/data).

We do initial Exploratory Data Analysis on this data, then data cleaning is carried out.

After the above two steps Feature Engineering is done to extract some new features, also some memory saving techniques (data type range reduction) is implemented. Label Encoding is done for the categorical variables.

Then data is split into train and test portions, also we use random smapling to avoid undersampling.

We then use Grid Search to find relative importance amongst the features, after that RandomForestClassifier is used to train the model and do the final prediction.

Final prediction is reported using Classification Report and the ROC curve




