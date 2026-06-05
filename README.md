# Titanic-Dataset-Cleaning
# Titanic Dataset Exploratory Data Analysis (EDA)

## Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, trends, relationships, and anomalies in passenger data. The analysis uses Python libraries such as Pandas and Matplotlib to explore factors that influenced passenger survival during the Titanic disaster.

## Objective

The objective of this project is to:

* Understand the structure of the dataset.
* Perform statistical analysis on passenger data.
* Visualize important trends and relationships.
* Extract meaningful insights from the dataset.

## Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (Pclass)
* Name
* Gender (Sex)
* Age
* Number of Siblings/Spouses Aboard (SibSp)
* Number of Parents/Children Aboard (Parch)
* Ticket Fare
* Embarked Port
* Survival Status

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Analysis Performed

### 1. Data Exploration

* Examined dataset structure using `info()`
* Generated statistical summaries using `describe()`
* Identified missing values
* Analyzed survival distribution

### 2. Data Visualization

* Age Distribution Histogram
* Fare Distribution Boxplot
* Survival by Gender Analysis
* Survival by Passenger Class Analysis
* Correlation Matrix Visualization

### 3. Findings and Observations

* Female passengers had significantly higher survival rates than male passengers.
* First-class passengers had better survival chances compared to second and third-class passengers.
* Higher ticket fares were generally associated with increased survival probability.
* Most passengers were between 20 and 40 years old.
* Fare data contained several outliers.
* Missing values were identified in Age, Cabin, and Embarked columns.

## Key Insights

1. Gender was one of the strongest predictors of survival.
2. Passenger class played a major role in survival outcomes.
3. Socioeconomic status, represented by fare and class, influenced survival rates.
4. Data preprocessing is important due to missing values in multiple columns.

## Project Structure

```text
Titanic-EDA/
│
├── Titanic_EDA.ipynb
├── Titanic-Dataset.csv
├── Titanic_EDA_Report.pdf
├── README.md
```

## Conclusion

This project demonstrates the use of Exploratory Data Analysis techniques to uncover meaningful patterns within the Titanic dataset. Through statistical summaries and visualizations, key factors affecting passenger survival were identified, providing valuable insights into the dataset.

## Author

**Nisarga**
