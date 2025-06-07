# 🚢 Titanic Survival Analysis - Exploratory Data Analysis (EDA)

This project explores the Titanic dataset to understand the patterns behind passenger survival during the infamous shipwreck.

## 🎯 Project Objectives

- Practice Python-based data analysis
- Apply exploratory data analysis techniques (EDA)
- Visualize relationships between features and survival status
- Prepare a GitHub-ready portfolio project

## 📦 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- File Used: `train.csv`

## 🛠️ Tools & Libraries

- Python 3
- pandas
- matplotlib
- seaborn
- Google Colab

## 🔍 Key Steps

1. **Data Cleaning**
   - Filled missing values in `Age` with median
   - Filled missing values in `Embarked` with mode
   - Dropped `Cabin` column due to excessive missing data

2. **Exploratory Data Analysis**
   - Categorical Analysis: Gender vs Survival, Class vs Survival
   - Numerical Analysis: Age Distribution, Age vs Survival
   - Visualizations: Countplot, Histogram, Boxplot


## 🧠 Key Insights

- Female passengers had significantly higher survival rates.
- First class passengers were more likely to survive.
- Younger children and infants also had higher survival likelihood.

## 📁 Folder Structure

Titanic-EDA/
├── titanic_eda.ipynb
├── README.md
└── screenshots/
├── gender_survival.png
└── age_histogram.png

