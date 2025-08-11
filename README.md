Task 5 – Exploratory Data Analysis (EDA) on Titanic Dataset
Objective
Extract insights from the Titanic dataset using visual and statistical exploration.

Outcome: Gain skill in finding patterns, trends, and anomalies.

Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn

Dataset
Source: Kaggle – Titanic Dataset
File used: train.csv

Steps Performed
- Data Loading & Inspection :
Checked dataset shape, data types, and missing values.
- Data Cleaning :
Filled missing Embarked with mode.
Filled missing Age using median grouped by Passenger Class and Sex.
Dropped Cabin due to high missing percentage.

- Feature Engineering :
Created FamilySize column.
Created AgeGroup column for categorical age analysis.

- Univariate Analysis :
Plotted distributions and counts for survival, age, and fare.

- Bivariate Analysis :
Compared survival rate by Sex, Pclass, and AgeGroup.

- Multivariate Analysis :
Generated a correlation heatmap for numeric features.
