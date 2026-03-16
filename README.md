Titanic Survival Prediction Model

This project builds a machine learning classification model to predict whether a passenger survived the Titanic disaster using passenger attributes.

Dataset

Titanic passenger dataset containing features such as:

Passenger Class

Sex

Age

Fare

Embarked Port

Family Information

Dataset Source:
https://www.kaggle.com/datasets/bhanupratapbiswas/titanic-survival-datasets

Feature Engineering

The following new features were created:

Title Extraction from passenger names

Family Size (SibSp + Parch + 1)

Cabin Presence (whether a cabin number exists)

Missing values for Age, Fare, Cabin, and Embarked were handled during preprocessing.

Algorithms Used

Logistic Regression

Random Forest Classifier

Model Explanation

Feature importance was analyzed using Random Forest Feature Importance to understand which features influence survival prediction.

Best Model

Random Forest Classifier (Higher Accuracy)
