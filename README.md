Titanic Dataset Analysis: Data Cleaning and Exploratory Data Analysis (EDA)

Project Overview

This project is the second task of my data science internship, where I conducted data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The primary goal was to uncover patterns and relationships within the data, such as the effects of passenger class and sex on survival rates. Through this analysis, I gained valuable experience in handling missing data, encoding categorical variables, visualizing data relationships, and computing correlations.

Dataset

The dataset used is the Titanic dataset from Kaggle, which contains information on passengers aboard the Titanic, including features such as:

PassengerId: Unique ID for each passenger

Pclass: Passenger class (1st, 2nd, 3rd)

Name: Passenger's name

Sex: Gender

Age: Age of the passenger

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Ticket price

Cabin: Cabin number

Embarked: Port of embarkation (C, Q, S)

Survived: Survival status (0 = No, 1 = Yes)


Analysis Process

The project focused on the following steps:

1. Data Cleaning

Handled missing values in columns like Age, Cabin, and Embarked.

Created a new feature, Cabin_known, indicating whether a cabin was recorded or missing, preserving potentially useful information.


2. Encoding Categorical Variables

Converted categorical features (Sex, Embarked) into numeric format using one-hot encoding. This transformation is essential for machine learning models that require numerical input.


3. Exploratory Data Analysis (EDA)

Visualization of Survival Rates: Created a grouped bar chart to visualize survival rates by sex and passenger class, revealing significant patterns in the data.

Correlation Analysis: Generated a correlation matrix for numerical features to explore relationships, after filtering out non-numeric columns like Name and irrelevant identifiers like PassengerId.


Key Learnings

Missing data can sometimes carry meaningful information and shouldn't always be removed.

Properly encoding categorical features is essential for accurate machine learning analysis.

Visualizations, such as grouped bar charts, can reveal important patterns between variables.

Excluding non-numeric columns is necessary for accurate correlation analysis.


Getting Started

Prerequisites

Python 3.x

Libraries: pandas, numpy, matplotlib, seaborn


Installation

Install the required libraries using:

pip install pandas numpy matplotlib seaborn

Results

This analysis provided insights into how features like passenger class and sex affected survival rates. The correlation matrix further highlighted relationships among numerical features, forming a foundation for future predictive modeling tasks.

Future Work

Implement predictive models to classify survival status based on features.

Expand feature engineering for improved model performance.


Acknowledgments

This analysis was completed as part of my data science internship. The Titanic dataset was sourced from Kaggle.
