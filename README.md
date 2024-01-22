# Diabetes_indicator
diabetes_012_health_indicators_BRFSS2021.csv is a clean dataset of 236,378 survey responses to the CDC's BRFSS2021. The target variable Diabetes_012 has 3 classes. 0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes. There is class imbalance in this dataset. This dataset has 21 feature variables.

Things i have done in this model:
1. Data cleaning (Basically, i have checked for any misiing or duplicate values in my dataset)
2. Data Visualization (Just to get a clear picture of how my data looks so far)
3. Data preprocessing ( Splitting my dataset into independent and dependent features to train and test my model)
4. Accuracy check ( calculated accuracy_score of the model)
5. Hyperparameter tuning ( To increase the accuracy using different parameters and GridSearchCV technique to select the best parameters)
6. performance check ( Lastly, i took out classification report of model, calculated MAE (Mean Absolute Error) and printed a confusion matrix to get the difference
   between actual value and predicted value)
