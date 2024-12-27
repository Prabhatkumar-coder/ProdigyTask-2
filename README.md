Name: Prabhat Kumar

Company: Prodigy InfoTech

CIN: PIT/DEC24/02757

Domain: DATA SCIENCE

Duration: 1st December2024 to 31st January2025

Project Overview: Titanic Dataset Analysis
Project Objective:
The primary goal of this project is to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset. This dataset contains information about the passengers of the Titanic, including demographic details, ticket class, fare, and survival status. The analysis aims to uncover patterns and trends that influence survival rates, explore relationships between variables, and prepare the data for further modeling or predictive analysis.

Dataset Description:
The Titanic dataset includes the following files:

gender_submission.csv: Provides a basic prediction on survival based on gender.
train.csv: Contains training data with features and survival outcomes.
test.csv: Contains test data with passenger details but without survival outcomes.
Key columns include:

PassengerId: Unique identifier for each passenger.
Survived: Survival status (0 = Not Survived, 1 = Survived).
Pclass: Passenger class (1 = First, 2 = Second, 3 = Third).
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard.
Parch: Number of parents/children aboard.
Fare: Ticket fare.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
Steps Followed in the Analysis:
Importing and Loading Data:

Loaded data from CSV files using Pandas.
Displayed basic information about the datasets (e.g., columns, data types, missing values).
Data Cleaning:

Handling Missing Values:
Filled missing Age values with the median age.
Replaced missing Embarked values with the most frequent port.
Dropped the Cabin column due to excessive missing data.
Filled missing Fare values with the median fare.
Duplicate Removal: Checked and removed duplicate rows (if any).
Exploratory Data Analysis (EDA):

Univariate Analysis:
Examined the distribution of numerical features like Age and Fare using histograms.
Analyzed categorical variables (Survived, Pclass, Sex, Embarked) using count plots.
Bivariate Analysis:
Explored the relationship between Survived and key features (Sex, Pclass, Age).
Created pie charts, scatter plots, and bar plots to identify patterns.
Correlation Analysis:
Computed correlations between numerical features to identify dependencies.
Visualized correlations using a heatmap.
Insights Derived:

Survival Patterns:
Higher survival rates for females compared to males.
Passengers in first class had a significantly higher chance of survival.
Age and Survival:
Younger passengers tended to have better survival rates.
Non-survivors were older on average compared to survivors.
Fare and Survival:
Higher ticket fares were associated with higher survival probabilities.
Embarkation Port:
Passengers embarking from Cherbourg (C) had higher survival rates than those from Southampton (S) or Queenstown (Q).
Descriptive Statistics:

Provided detailed statistics for numerical features (mean, median, standard deviation, etc.).
Highlighted variations between survivors and non-survivors in terms of age, fare, and class.
Data Visualization:

Used Seaborn and Matplotlib for creating intuitive and aesthetically pleasing plots.
Plotted pairwise relationships to explore multidimensional interactions.
Key Outcomes and Learnings:
EDA revealed significant relationships between survival and features like gender, class, and fare.
Missing value handling and feature engineering prepared the dataset for predictive modeling.
Data visualization aided in understanding the dataset's underlying structure and trends.
Future Steps:
Use the cleaned and analyzed data to build predictive models (e.g., logistic regression, decision trees) to predict survival.
Perform feature selection and engineering to improve model accuracy.
Explore advanced visualizations for deeper insights into passenger demographics and survival factors.
This project demonstrates foundational data analysis skills and highlights the importance of structured EDA in understanding and preparing datasets for further analysis.

![image](https://github.com/user-attachments/assets/15f6ac8b-488f-4089-a268-d75434945ff6)
![image](https://github.com/user-attachments/assets/6f81273f-4cbf-4aa5-8a6e-33d6231c7292)
![image](https://github.com/user-attachments/assets/94483a4a-3fa1-4e2b-a3db-d457dafc1e91)
![image](https://github.com/user-attachments/assets/98e07390-2d75-44c9-9148-16d7da95d058)
![image](https://github.com/user-attachments/assets/a1788ce8-5b9b-40ff-8387-bd7060afab2c)
![image](https://github.com/user-attachments/assets/04aae38f-5a71-46ef-bff5-9d71df35d92d)
![image](https://github.com/user-attachments/assets/828b4b2f-6a59-49b1-b11c-2529c3c1400e)
![image](https://github.com/user-attachments/assets/107d024f-5ef6-4d6b-ba43-5f947a894cfb)
![image](https://github.com/user-attachments/assets/ea52d024-d863-4769-b9fb-45cdb2d67ef2)
![image](https://github.com/user-attachments/assets/4808a747-26dc-4139-b1b1-ca541fc8f1f5)
![image](https://github.com/user-attachments/assets/857d451e-efcb-49b7-aa29-4116e1606480)
![image](https://github.com/user-attachments/assets/ff4f1d46-104d-4838-ac3e-2cb3c9c7d758)
![image](https://github.com/user-attachments/assets/a55de66e-c4ae-4a9e-95c6-1e7179fbe802)
![image](https://github.com/user-attachments/assets/e36a853a-1bea-4762-853a-c6038d669664)
![image](https://github.com/user-attachments/assets/17f38e95-24a7-4f74-b8ec-d423dd4a72d3)
![image](https://github.com/user-attachments/assets/fd30163f-8d84-49ac-984d-78a1d305bd64)




















