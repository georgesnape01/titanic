# Titanic Survival

This notebook presents a solution to the Titanic dataset challenge. It outlines the steps taken to load and prepare the data, perform exploratory data analysis (EDA), engineer features and optimise machine learning (ML) models to predict passenger survival outcomes.

# Project Description

The dataset consists of 891 passengers, with each entry providing details about their demographics, ticket information and survival outcome. The variables include:

| PassengerId | Survived | Pclass | Name                                           | Sex   | Age  | SibSp | Parch | Ticket              | Fare    | Cabin | Embarked |
|-------------|----------|--------|------------------------------------------------|-------|-------|-------|-------|---------------------|---------|-------|----------|
| 0           | 1        | 0      | Braund, Mr. Owen Harris    | male  | 22.0  | 1     | 0     | A/5 21171           | 7.2500  | NaN   | S        |
| 1           | 2        | 1      | Cumings, Mrs. John Bradley ... | female | 38.0  | 1     | 0     | PC 17599            | 71.2833 | C85   | C        |
| 2           | 3        | 1      | Heikkinen, Miss. Laina    | female | 26.0  | 0     | 0     | STON/O2. 3101282    | 7.9250  | NaN   | S        |

# Methodology

The project first explored basic feature engineering and optimisation using Optuna along with classical machine learning techniques. Feature engineering techniques included extracting titles from the Name column, creating bins for Age, Fare, Pclass, and SibSp columns, and extracting letters and numbers from the Ticket and Cabin columns. Additional efforts included handling missing data and evaluating model performance through cross-validation.

# Results

Using accuracy as the performance metric, the model correctly predicted the survival outcome for 77.9% of passengers.
