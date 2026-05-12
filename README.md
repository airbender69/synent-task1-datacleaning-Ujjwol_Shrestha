The goal of this project is to take the raw Titanic dataset from Kaggle and perform essential data cleaning and preprocessing. This ensures the data is accurate, consistent, and ready for further exploratory data analysis or machine learning modeling.

Dataset Details: 

Source: Kaggle (Titanic - Machine Learning from Disaster)

Format: CSV

Key Features: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.

Approach :

Missing Values:
- Filled Age with Median.

- Filled Embarked with Mode.

Dropped Cabin due to too many missing values.

Duplicates: Removed all redundant rows using drop_duplicates().

Data Types: Converted Sex and Embarked to Category types.

Formatting: Renamed SibSp and Parch for clarity and followed snake_case naming.

Results :

Successfully handled all null values and duplicates.
Optimized memory usage through type conversion.
Exported the final result as cleaned_train.csv.

