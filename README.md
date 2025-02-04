# Titanic Dataset Solution

This notebook presents a solution to the Titanic dataset challenge. It outlines the steps taken to load and prepare the data, perform exploratory data analysis (EDA), engineer features and optimise machine learning (ML) models to predict passenger survival outcomes.

| PassengerId | Survived | Pclass | Name                                           | Sex   | Age  | SibSp | Parch | Ticket              | Fare    | Cabin | Embarked |
|-------------|----------|--------|------------------------------------------------|-------|-------|-------|-------|---------------------|---------|-------|----------|
| 0           | 1        | 0      | Braund, Mr. Owen Harris    | male  | 22.0  | 1     | 0     | A/5 21171           | 7.2500  | NaN   | S        |
| 1           | 2        | 1      | Cumings, Mrs. John Bradley ... | female | 38.0  | 1     | 0     | PC 17599            | 71.2833 | C85   | C        |
| 2           | 3        | 1      | Heikkinen, Miss. Laina    | female | 26.0  | 0     | 0     | STON/O2. 3101282    | 7.9250  | NaN   | S        |

# Contents

- Initialisation  
- Custom Functions  
- Data Analysis
- Preparation  
- Optimisation  
- Prediction  

# Initialisation  
In this section, the necessary libraries were imported and the Titanic dataset is loaded. The environment is set up for further analysis, and initial data checks are conducted.

# Custom Functions  
This section defines custom functions that are used throughout the notebook. These functions include data imputation, model evaluation and hyperparameter optimisation.

# Analysis  
EDA is performed to examine the distribution of key features, their relationship to survival and any potential correlations within the dataset. The presence of missing data is also assessed and the necessary steps for addressing it are outlined.

# Preparation  
Data preprocessing tasks are conducted in this section. Missing values are imputed, new features are engineered and categorical variables are encoded in preparation for the modelling phase.

# Optimisation  
This section focuses on optimising hyperparameters for multiple ML models, including Decision Trees, XGBoost, LightGBM, Random Forest, SVM and Logistic Regression. Optuna is used for hyperparameter tuning to maximise model performance.

# Prediction  
In this final section, the best models are used to make predictions on the test set.
