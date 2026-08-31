# Titanic Dataset — Exploratory Data Analysis

## 📌 Project Overview

This project explores the famous Titanic passenger dataset using Python and Pandas. The goal is to understand the dataset, identify patterns related to passenger survival, handle missing data, and perform exploratory data analysis through visualizations and statistical summaries.

This project is part of my learning journey in Data Analysis and Machine Learning, with a focus on understanding the complete workflow rather than simply applying pre-written models.

## 🎯 Objectives

- Understand the structure and characteristics of the Titanic dataset.
- Identify and analyze missing values.
- Explore relationships between passenger characteristics and survival.
- Perform exploratory data analysis using statistical summaries and visualizations.
- Engineer useful features from the existing data.
- Prepare the dataset for machine learning.

---

## 📂 Dataset

The dataset contains information about **891 Titanic passengers** and initially consists of **12 columns**.


### Main Features

| Feature | Description |
|---|---|
| `PassengerId` | Unique identifier of each passenger |
| `Survived` | Whether the passenger survived (`0` = No, `1` = Yes) |
| `Pclass` | Passenger's ticket class (`1`, `2`, `3`) |
| `Name` | Passenger's name |
| `Sex` | Passenger's sex |
| `Age` | Passenger's age |
| `SibSp` | Number of siblings/spouses travelling with the passenger |
| `Parch` | Number of parents/children travelling with the passenger |
| `Ticket` | Passenger's ticket number |
| `Fare` | Fare paid by the passenger |
| `Cabin` | Passenger's cabin information |
| `Embarked` | Port where the passenger boarded |

---

## 🔍 Initial Data Exploration

The dataset was first inspected using Pandas to understand:

- Number of rows and columns
- Data types
- Missing values
- Basic statistical characteristics
- Distribution of the target variable (`Survived`)

The dataset contains:

- **891 rows**
- **12 original columns**
- Missing values in `Age`, `Cabin`, and `Embarked`
- `Age` contains 714 non-null values
- `Cabin` contains 204 non-null values
- `Embarked` contains 889 non-null values

---

## 📈 Outlier Analysis

The IQR method was used to investigate potential outliers, particularly in the `Fare` column.

Although several high-fare observations were identified as statistical outliers, they appeared to represent genuine passengers rather than obvious data-entry errors.

Therefore, the outliers were **retained** rather than removed.

> **Key principle:** An outlier is not necessarily an error. It should be investigated before being removed.

--- 

## 🚧 Project Status
The project is currently being developed incrementally.

Completed so far:

- Dataset understanding
- Exploratory Data Analysis
- Missing-value handling
- Visualization
- Correlation analysis
- Outlier analysis
- Initial feature engineering and preprocessing

Further machine-learning experimentation and model evaluation will be added as the project progresses.
