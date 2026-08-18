# ⚽ FIFA Data Analysis

Exploratory Data Analysis of FIFA players using Python, Pandas, and Matplotlib.

## Project Overview

This project explores a FIFA players dataset with a focus on data cleaning, exploratory data analysis (EDA), player profiling, nationality analysis, age categorization, performance comparison, and data visualization.

The main goal is to demonstrate practical Data Analytics skills using Python and Pandas while transforming raw data into meaningful insights.

## Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Git
- GitHub

## Main Analysis

The project includes:

- Dataset loading with `pd.read_csv()`
- Missing value analysis
- Missing data treatment using `fillna()` and `dropna()`
- Duplicate verification with `drop_duplicates()`
- Player grouping by nationality using `groupby()`
- Average age analysis by nationality
- Age categorization using a custom function with `.apply()`
- Exploratory Data Analysis
- Player performance comparison
- Data visualization
- Feature engineering with a custom `POTENTIAL_GROWTH` metric

## Key Insights

- The original dataset contains 18,207 players.
- After data cleaning, 18,159 records remained.
- 99.74% of the original dataset was preserved.
- England has the largest number of players in the dataset.
- Young players represent 55.46% of the analyzed population.
- Veteran players have a higher average overall rating.
- Young players have a higher average potential rating.
- A custom `POTENTIAL_GROWTH` metric was created to identify young players with significant development potential.

## Project Structure

```text
fifa-data-analysis/
│
├── data/
│   └── fifa.csv
│
├── notebooks/
│   └── fifa_analysis.ipynb
│
├── .gitignore
└── README.md

Skills Demonstrated
Python
Pandas
Data Cleaning
Data Transformation
Exploratory Data Analysis (EDA)
Data Visualization
GroupBy
Apply
Feature Engineering
Analytical Thinking
Git & GitHub
Notebook

The complete analysis is available in:

notebooks/fifa_analysis.ipynb

Author

Thomas Bobadilla

IT professional with 20+ years of experience in technology, currently expanding expertise in Data Analytics with Python, SQL, Power BI, Pandas, ETL, and Data Visualization.