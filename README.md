
# Prodigy Infotech Internship Task 02

This repository contains the work completed for Task 2 of my Prodigy Infotech internship, which focuses on the Titanic Survival Prediction project. The objective of this task was to clean and explore the Titanic dataset, conduct Exploratory Data Analysis (EDA), and prepare the data for machine learning. The dataset includes various features such as passenger demographics, ticket class, and other attributes that help predict survival on the Titanic.


## Tools and Libraries:

* Jupyter notebook 
* Pandas
* Numpy
* Matplotlip & Seaborn for visualization
## Key Steps

1. Data Cleaning:

* Handled missing values by filling them with appropriate measures (e.g., median for Age, mode for Embarked).
* Dropped unnecessary or irrelevant features, such as the Cabin column, due to excessive missing data.

2. Feature Engineering:

* Created new features like FamilySize (sum of SibSp and Parch + 1) to capture family relationships.
* Added the IsAlone feature to indicate whether a passenger was traveling alone.

3. Exploratory Data Analysis (EDA):

* Visualized the survival distribution and trends based on various features such as Sex, Pclass, and Age.
* Analyzed the relationships between features using correlation heatmaps and other plots.

4. Data Preprocessing:

* Encoded categorical variables (Sex and Embarked) using integer mappings.
* Split the data into features (X_train and X_test) and labels (y_train).

5. Output:

* Processed data files (processed_train.csv, processed_test.csv, train_labels.csv) are saved for future model training and evaluation.
## Conclusion

In this project, I performed essential data cleaning and preprocessing to prepare the Titanic dataset for modeling. Missing values were handled, and irrelevant features were dropped. Feature engineering allowed us to create meaningful variables, such as FamilySize and IsAlone, to enhance the dataset's predictive power. Through Exploratory Data Analysis (EDA), we gained insights into the relationships between key features and survival trends. Categorical variables were encoded, and the data was split for model training and evaluation. The processed datasets are now ready for further model development and testing.

Thank you for reviewing my submission!