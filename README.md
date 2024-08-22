# Titanic Survival Prediction
This project involves building a machine learning model to predict the survival of passengers on the Titanic. The steps taken in this project include:

Data Preprocessing:

Loaded the dataset and removed irrelevant features (e.g., Cabin).
Handled missing values by dropping rows with missing Embarked values and filling missing Age values with the mean.
Categorical variables (Embarked, Sex) were encoded numerically to prepare for model training.
Data Visualization:

Used Seaborn to create visualizations such as count plots to explore the distribution of survival across different categories, including gender (Sex) and ticket class (Pclass).
Model Building:

Selected relevant features (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked) for the model.
Split the data into training and testing sets.
Implemented a Logistic Regression model to predict passenger survival.
Evaluated model performance using accuracy.
Results:

The model achieved a certain accuracy (e.g., X%) in predicting the survival of passengers on the test set.
This project demonstrates the application of data preprocessing, exploratory data analysis, and logistic regression for binary classification tasks in a real-world dataset.

