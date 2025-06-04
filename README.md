This is the wellknown Titanic - Machine Learning from Disaster problem in Kaggle

In this notebook, I built a model to predict Titanic passenger survival using a default Random Forest Classifier.
I focused on cleaning data, handling missing values, and doing basic feature engineering:
Imputed missing Age,Fare and Embark values.
Created a FamilySize feature and a binary IsAlone flag.
Binned Age and FarePerPerson into quartiles.
Encoded categorical features like Sex and Embarked.
Used 10-fold cross-validation for evaluation.
Generated predictions for submission on the test set.
