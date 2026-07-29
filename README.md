# 🚢 Titanic Survival Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.14-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📌 Project Overview

This project performs **Data Cleaning and Exploratory Data Analysis (EDA)** on the famous Titanic passenger dataset.

The objective is to analyze passenger information and identify patterns that influenced survival outcomes using Python-based data analysis and visualization techniques.

The project explores relationships between:

- Gender
- Passenger Class
- Age
- Fare
- Family Size
- Survival Status

---

# 🎯 Objectives

The main objectives of this project are:

- Clean and preprocess Titanic dataset
- Handle missing values
- Perform exploratory data analysis
- Create meaningful visualizations
- Identify survival patterns
- Generate data-driven insights

---

# 📂 Dataset Information

**Dataset:** Titanic Dataset

**Source:** Kaggle

Dataset contains passenger information including:

- Passenger Class
- Gender
- Age
- Family Details
- Ticket Fare
- Survival Status

Dataset Size:
Records: 891
Features: 12


---

# 🛠️ Technologies Used

## Programming Language

- Python

## Libraries

| Library | Purpose |
|---|---|
| Pandas | Data processing |
| NumPy | Numerical analysis |
| Matplotlib | Visualization |
| Seaborn | Statistical visualization |

## Tools

- Jupyter Notebook
- VS Code
- Git
- GitHub

---

# 🔄 Project Workflow
Dataset Collection
|
↓
Data Understanding
|
↓
Data Cleaning
|
↓
Feature Engineering
|
↓
Exploratory Data Analysis
|
↓
Visualization
|
↓
Insights Generation


---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

### Missing Value Handling

- Age missing values filled using median
- Embarked missing values filled using mode
- Cabin column removed due to excessive missing values

### Duplicate Handling
Duplicate Records: 0


---

# ⚙️ Feature Engineering

Created a new feature:

## Family Size

Formula:
Family_Size = SibSp + Parch + 1


This feature helps analyze whether traveling alone or with family influenced survival.

---

# 📊 Exploratory Data Analysis

The following analyses were performed:

## Survival Distribution

Analyzed the number of passengers who survived and did not survive.

## Gender Survival Analysis

Compared survival rates between male and female passengers.

## Passenger Class Analysis

Studied survival differences among passenger classes.

## Age Analysis

Analyzed passenger age patterns.

## Fare Analysis

Studied ticket fare distribution.

## Family Size Analysis

Analyzed the relationship between family size and survival.

## Correlation Analysis

Identified relationships between numerical variables.

---

# 💡 Key Insights

### Gender

- Female passengers had higher survival rates compared to male passengers.

### Passenger Class

- First-class passengers had better survival chances.

### Fare

- Higher fare passengers generally had better survival outcomes.

### Family Size

- Extremely large families showed lower survival chances.

---

# 📁 Project Structure
Titanic_Survival_EDA_Analysis_week_2

│
├── data
│ ├── raw
│ │ └── titanic.csv
│ │
│ └── processed
│ └── titanic_cleaned.csv
│
├── notebooks
│ └── Titanic_EDA.ipynb
│
├── results
│ ├── survival_distribution.png
│ ├── gender_survival_analysis.png
│ ├── passenger_class_analysis.png
│ ├── age_distribution.png
│ ├── fare_distribution.png
│ ├── family_size_distribution.png
│ └── correlation_heatmap.png
│
├── reports
│ └── EDA_Report.md
│
└── README.md


---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/hsiddique-data/Titanic-Survival-EDA-Analysis.git

✅ Project Status

✔ Dataset Collection Completed
✔ Data Cleaning Completed
✔ Feature Engineering Completed
✔ EDA Completed
✔ Visualization Completed
✔ Documentation Completed

👨‍💻 Author

SIDDIQUE H

Data Analytics | Python | Machine Learning | Generative AI
