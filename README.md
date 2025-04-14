# Task-5

# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs detailed Exploratory Data Analysis (EDA) on the famous Titanic dataset to discover patterns and relationships that affected passenger survival.



## Objective

To analyze passenger data and identify key factors that influenced survival during the Titanic disaster using data visualization and statistical techniques.


## Dataset

- Source:Titanic-Dataset.csv
- Features Include:
  - `Survived`: 0 = No, 1 = Yes
  - `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
  - `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.
  - 
## jupyter file: "Task_5.ipynb"

## Summary of findings : " Summary_of_findings.txt "

## Process Overview

### 1. Data Loading and Initial Exploration
- Used `.head()`, `.info()`, `.describe()` to understand data structure.
- Checked for null values and data types.
- Applied `.value_counts()` for categorical distributions.

### 2. Data Cleaning
- Filled missing values in `Age` with median.
- Dropped or imputed missing values in `Embarked` and other columns as needed.

### 3. Data Visualization (Seaborn, Matplotlib)
- **Heatmap** to examine correlations.
- **Pairplot** to understand relationships between numeric features and survival.
- **Countplots** for survival by gender and class.
- **Histograms** to show distributions (e.g., Age).
- **Boxplots** to spot outliers in `Age` and `Fare`.
- **Scatterplot** to observe Fare vs Age colored by survival.


## Observations

- **Gender:** Females had a significantly higher survival rate than males.
- **Pclass:** 1st class passengers had higher survival; 3rd class had the lowest.
- **Fare:** Higher fare correlated with increased survival.
- **Age:** Younger passengers were more likely to survive.
- **Correlations:** Strongest features linked to survival were `Sex`, `Pclass`, and `Fare`.

(See full observations for each visual in `Task_5.ipynb`)


## **Technologies Used**

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook



## How to Use

1. Clone this repo or download the `Task_5.ipynb` notebook.
2. Ensure you have Python and Jupyter installed.
3. Run each cell to explore the data and visualizations.
4. Check the inline comments and observations to understand key insights.


## Conclusion

This EDA revealed that gender, passenger class, and fare were strong indicators of survival. The findings will help guide future modeling for predicting survival outcomes.


## Author
Shaiik Sameer Ali  
B.Tech, Data Science | Acharya Nagarjuna University  
