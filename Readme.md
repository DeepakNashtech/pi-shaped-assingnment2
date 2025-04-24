# Titanic Dataset Analysis: Data Manipulation with NumPy & Pandas

## Overview

This project involves exploring and analyzing the Titanic passenger dataset to practice data manipulation and analysis skills using Python libraries such as **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to clean the data, explore key patterns, and extract meaningful insights through visualizations.

---

## Dataset

- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **File Used:** `train.csv` (primary dataset for analysis)
- *(Optional)* `test.csv` can be used for extended practice.

---

## Objectives

- Load and familiarize with the dataset.
- Perform initial exploration to understand data structure and identify missing values.
- Clean the dataset by handling missing data and irrelevant columns.
- Analyze survival trends based on features such as gender, passenger class, and age.
- Visualize key findings to support insights.
- Document the entire process in a Jupyter Notebook with clear commentary.

---

## How to Run

1. **Clone the repository** (if applicable) or download the files locally.
2. **Install required Python packages** (preferably in a virtual environment):

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook**:

   ```bash
   jupyter notebook session2-Assignment.ipyunb
   ```

4. **Follow the notebook steps** to reproduce the analysis and visualizations.

---

## Key Findings

- **Gender:** Females had a significantly higher survival rate than males.
- **Passenger Class:** First-class passengers had better survival chances compared to lower classes.
- **Age:** Children were more likely to survive than adults.
- **Data Cleaning:** Missing values in 'Age' and 'Embarked' were filled with median and mode respectively; irrelevant columns like 'Cabin', 'Ticket', and 'Name' were dropped.

---

## Visualizations Included

- Survival rate by gender (bar chart)
- Survival rate by passenger class (bar chart)
- Age distribution by survival status (stacked histogram)

---

## Notes

- The analysis uses Python 3.x and popular data science libraries.
- The dataset contains some missing values and categorical variables that were preprocessed accordingly.
- This notebook is designed for educational purposes to practice data manipulation and exploratory data analysis.

