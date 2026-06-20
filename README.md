Titanic Survival Prediction
Overview

This project uses Machine Learning to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, passenger class, fare, and family relationships.

Dataset

The dataset used in this project is the Titanic dataset from Kaggle.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Data Preprocessing

The following preprocessing steps were applied:

Filled missing values in the Age column using the median value.
Filled missing values in the Embarked column using the most frequent value.
Removed the Cabin column due to a large number of missing values.
Converted categorical variables (Sex and Embarked) into numerical values.
Features Used
Pclass
Sex
Age
SibSp
Parch
Fare
Embarked
Model

Random Forest Classifier

Results

The model achieved an accuracy of 82.68% on the test dataset.

Project Structure
titanic-survival-prediction/
│
├── titanic_survival_prediction.ipynb
└── README.md
Conclusion

This project demonstrates a complete Machine Learning workflow, including data preprocessing, feature engineering, model training, and model evaluation. The Random Forest model achieved strong performance on the Titanic dataset.
