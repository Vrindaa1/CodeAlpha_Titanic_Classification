# CodeAlpha_Titanic_Classification

Titanic Dataset Analysis and Survival Prediction:

This project aims to analyze the Titanic dataset containing information about passengers aboard the Titanic and predict their survival using machine learning techniques.

Dataset Overview:

The dataset contains 1309 entries and 8 columns.
Features include passenger class (Pclass), gender (Sex), age (Age), number of siblings/spouses aboard (SibSp), number of parents/children aboard (Parch), fare (Fare), and port of embarkation (Embarked).
Missing values were handled by imputing the mean for age, the mode for embarked, and dropping the cabin column due to excessive missing values.
Categorical variables were encoded for model training.

Exploratory Data Analysis (EDA):

Analyzed the distribution of passengers by gender, passenger class, age, and other factors.
Visualized survival rates based on gender, passenger class, port of embarkation, and other variables.
Detected outliers using box plots and explored correlations among numeric features.

Model Building:

Selected relevant features for prediction, including passenger class, gender, age, family size, fare, and port of embarkation.
Split the dataset into training and testing sets.
Utilized a Decision Tree Classifier for survival prediction with hyperparameter tuning (max depth = 5, min samples split = 10).
Achieved an accuracy of approximately 75.19% on the testing set.

Conclusion:

This project provides insights into the factors influencing survival on the Titanic and demonstrates the application of machine learning in predicting survival outcomes based on passenger attributes.
