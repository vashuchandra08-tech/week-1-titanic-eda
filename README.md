# Virtual Data Science with Python Apprentice Internship

This repository contains my work and assignments completed as part of the **Virtual Data Science with Python Apprentice Internship**.

The projects focus on data acquisition, data cleaning, exploratory data analysis, data visualization, and data storytelling using Python.

---

## 🗂️ Internship Tasks

### Week 1 – Data Acquisition, Cleaning, and Exploratory Analysis

#### Objective

The objective of Week 1 was to understand the basic data science workflow, including data acquisition, data cleaning, preprocessing, and exploratory data analysis (EDA).

#### Dataset

For this task, I used the publicly available **Titanic Passenger Dataset**.

The dataset contains information about passengers such as:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Ticket
- Fare
- Embarkation port

#### Data Cleaning

The following preprocessing steps were performed:

- Checked the structure and data types of the dataset.
- Identified missing values.
- Removed the `Cabin` column because it contained a large percentage of missing values.
- Filled missing `Age` values using the median.
- Filled missing `Embarked` values using the mode.
- Checked for duplicate records.
- Verified the final dataset after cleaning.

#### Exploratory Data Analysis

Summary statistics and exploratory visualizations were created using Pandas, Matplotlib, and Seaborn.

#### Week 1 Visualizations

- `survival_distribution.png`
- `survival_by_gender.png`
- `age_distribution.png`
- `correlation_heatmap.png`
- `fare_boxplot.png`

#### Key Insights

- The overall survival rate was approximately 38%.
- Female passengers had a higher survival rate than male passengers.
- Passenger class was associated with survival.
- Age showed variation between passengers who survived and those who did not.
- Fare values contained noticeable variation and outliers.

---

# Week 2 – Advanced Data Visualization and Storytelling with Python

## Objective

The objective of Week 2 was to create advanced visualizations and use them to communicate a clear data story to a non-technical audience.

The Titanic dataset from Week 1 was reused for deeper analysis.

## Feature Engineering

Two additional features were created:

### FamilySize

```python
FamilySize = SibSp + Parch + 1


**Author**

**Vasundhara Chandra**

B.Tech Computer Science

Virtual Data Science with Python Apprentice Intern


