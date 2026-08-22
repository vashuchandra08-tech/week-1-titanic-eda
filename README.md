# Titanic Dataset - Data Acquisition, Cleaning, and Exploratory Data Analysis

## Week 1 - Virtual Data Science with Python Apprentice Intern

### Project Overview

This project was completed as part of Week 1 of the Virtual Data Science with Python Apprentice Intern program.

The objective of this project is to demonstrate the data preparation and exploratory analysis process using the Titanic passenger dataset. The project covers data acquisition, data cleaning, preprocessing, exploratory data analysis, visualization, and interpretation of findings.

## Objectives

- Acquire and inspect a publicly available dataset.
- Identify and handle missing values.
- Check and handle duplicate records.
- Verify data types and data quality.
- Perform descriptive statistical analysis.
- Explore relationships and patterns within the dataset.
- Create meaningful data visualizations.
- Summarize key analytical insights.

## Dataset

The Titanic dataset contains information about passengers who travelled on the Titanic.

The dataset includes variables such as:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket
- Fare
- Port of embarkation

The original dataset contains 891 passenger records.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Data Cleaning

The following data cleaning operations were performed:

### Missing Values

- The `Cabin` column contained approximately 77% missing values and was removed because the amount of missing information was too high for reliable imputation.
- Missing values in `Age` were replaced using the median age.
- Missing values in `Embarked` were replaced using the mode.
- After cleaning, no missing values remained.

### Duplicate Records

The dataset was checked for duplicate records. No duplicate rows were found.

### Data Types

The data types of all columns were inspected using Pandas. The numerical and categorical columns were found to have appropriate data types for analysis.

## Exploratory Data Analysis

Descriptive statistics and visualizations were used to understand:

- Passenger survival distribution
- Survival differences by gender
- Passenger age distribution
- Relationships between numerical variables
- Fare distribution and potential outliers

## Visualizations

The project includes the following visualizations:

1. Passenger Survival Distribution
2. Survival Distribution by Gender
3. Age Distribution of Passengers
4. Correlation Heatmap
5. Fare Distribution and Outliers

## Key Insights

- The overall survival rate was approximately 38%.
- Survival rates differed considerably between male and female passengers.
- Passenger class showed an association with survival, with first-class passengers generally having higher survival rates.
- Passenger ages covered a wide range, with most passengers concentrated around young and middle adulthood.
- The fare variable showed a wide range and contained high-value observations that appeared as potential outliers.
- Correlation analysis showed that some numerical variables had noticeable relationships with survival, while others showed weaker associations.

## Project Files

- `Titanic_EDA_Week1.ipynb` - Complete Python analysis notebook
- `train.csv` - Original Titanic dataset
- `titanic_cleaned.csv` - Cleaned dataset
- `survival_distribution.png` - Survival distribution visualization
- `survival_by_gender.png` - Survival by gender visualization
- `age_distribution.png` - Age distribution visualization
- `correlation_heatmap.png` - Correlation analysis
- `fare_boxplot.png` - Fare outlier analysis
- `requirements.txt` - Python dependencies

## Conclusion

The project demonstrates a complete basic data science workflow, starting from dataset acquisition and inspection through data cleaning, exploratory analysis, visualization, and interpretation.

The analysis shows that factors such as gender and passenger class were associated with survival outcomes in the Titanic dataset. The cleaned dataset is suitable for further statistical analysis or machine learning tasks.

## Author

**Vasundhara Chandra**

B.Tech Computer Science
