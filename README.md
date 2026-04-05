# 🏎️ Formula 1 Performance Analytics & Race Outcome Prediction

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Tech Stack
![Python](https://img.shields.io/badge/Python-blue?)
![Pandas](https://img.shields.io/badge/Pandas-purple?)
![NumPy](https://img.shields.io/badge/Numpy-darkblue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-darkgreen)
![Seaborn](https://img.shields.io/badge/Seaborn-teal)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-yellow)
![fastf1](https://img.shields.io/badge/FastF1-red)
![Jupyter](https://img.shields.io/badge/Jupyter-orange)

## Skills
![Python](https://img.shields.io/badge/Data--Cleaning-darkgreen)
![Python](https://img.shields.io/badge/Feature--Engineering-darkgreen)
![Python](https://img.shields.io/badge/Exploratory--Data--Analytics-darkgreen)
![Python](https://img.shields.io/badge/Visualisation-darkgreen)
![Python](https://img.shields.io/badge/Sport--Analytics-darkgreen)
![Python](https://img.shields.io/badge/Machine--Learning-darkgreen)
![Python](https://img.shields.io/badge/Predictive--Modeling-darkgreen)



# 📌 Project Overview

This project explores historical **Formula 1 Races Dataset** to analyze driver performance, constructor dominance, overtaking patterns, and the impact of qualifying position on race outcomes.

Using multiple relational datasets containing race results, drivers, constructors, circuits, lap times, pit stops, and standings, the project demonstrates a **complete data analytics workflow**:

- Data preprocessing
- Exploratory data analysis
- Statistical analysis
- Predictive modeling

A **machine learning model** was also developed to estimate race-winning probability based on qualifying position.

---
# 🧠 Concepts Demonstrated

This project demonstrates multiple data analytics and machine learning concepts.

## Data Analytics

 - Data Cleaning

 - Data Wrangling

 - Feature Engineering

 - Exploratory Data Analysis

 - Data Visualization

 - Trend Analysis

 - Sports Analytics

## Machine Learning

 - Binary Classification

 - Logistic Regression

 - Random Forest

 - Model Evaluation

 - Predictive Modeling

---

# 📊 Data Description

The dataset contains historical **Formula 1 race data (1950–Present)**.

### Key Data Tables
circuits.csv

constructors.csv

constructor_standings.csv

drivers.csv

driver_standings.csv

lap_times.csv

pit_stops.csv

qualifying.csv

races.csv

results.csv

seasons.csv

status.csv


These relational datasets were **merged and cleaned** to create a master dataframe for analysis.

---

# ⚙️ Data Preprocessing

Key preprocessing steps included:

- Merging multiple datasets using relational IDs:
- Handling missing values
- Converting data types
- Removing inconsistent entries
- Creating derived performance features

Additional engineered features:

 - `is_winner`

 - `is_podium`

 - `position_change`

 - `win_rate`

 - `seasonal_points`


---

# 📈 Exploratory Data Analysis (EDA)

Several exploratory analyses were conducted to understand Formula 1 performance patterns.

## Constructor Dominance Over Time

A stacked area chart was used to visualize how top teams dominated different eras of Formula 1.

## Driver Win Rate Comparison

Driver win rates were calculated as:

`Win Rate = Total Wins / Total Races

## Driver Consistency Analysis

Driver consistency was analyzed by tracking seasonal points across multiple years.

## Overtaking Analysis (Grid vs Finish Position)

A new metric was created:

`Position Change = Grid Position − Race Finish Position`

This metric highlights drivers with strong overtaking ability and racecraft.

## Correlation Analysis

Correlation analysis was conducted between key variables:

 - Grid position

 - Qualifying position

 - Race finish

 - Points scored


---

# 🤖 Predictive Modeling

A binary classification model was built to predict race winners.

Target Variable

`is_winner = 1 → Driver won the race`
`is_winner = 0 → Driver did not win`

Models Implemented

 - Logistic Regression

 - Random Forest Classifier


## Model Workflow

 - Feature selection
 
 - Train-test split

 - Model training

 - Prediction

 - Model evaluation


## Evaluation Metrics

Models were evaluated using:

 - Confusion Matrix

 - Accuracy

 - ROC-AUC Score

 - Classification Report

The results highlight the strong predictive importance of qualifying position.

---

# 🌐 Upcoming Full Stack Version

A full-stack version of this project with an interactive analytics dashboard will be developed soon.
