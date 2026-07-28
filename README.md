# Football Data Analysis with Python

## Project Overview

This project presents an exploratory data analysis (EDA) of a football players dataset using Python. The analysis focuses on player performance, demographics, positions, and nationality to uncover meaningful insights that can support scouting, recruitment, and performance evaluation.

The project demonstrates the use of Python for data cleaning, feature engineering, aggregation, and data visualization using Matplotlib.

---

## Objectives

The objectives of this project are to:

- Analyze player performance based on Overall ratings.
- Identify the nationalities that produce the highest-rated football players.
- Determine which countries have the largest number of professional players.
- Compare player performance across different age groups.
- Evaluate player performance by preferred playing position.
- Create informative visualizations to communicate insights.

---

## Dataset

The dataset contains professional football player information, including:

- Player Name
- Age
- Nationality
- Overall Rating
- Preferred Position
- Preferred Position Type
- Other player attributes

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Data Analysis |
| Pandas | Data Cleaning & Manipulation |
| Matplotlib | Data Visualization |
| Jupyter Notebook | Interactive Analysis |

---

## Python Libraries

```python
import pandas as pd
import matplotlib.pyplot as plt
```

---

## Project Workflow

```
Football Dataset
        │
        ▼
Data Preparation
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Visualization
        │
        ▼
Business Insights
```

---

# Data Preparation

The dataset was loaded into a Pandas DataFrame for analysis.

Activities performed include:

- Loading the CSV dataset
- Inspecting the dataset
- Preparing data for analysis

---

# Feature Engineering

Additional variables were created to improve the analysis.

### Age Group

Players were classified into three age categories:

- Under 17
- Under 21
- Senior

### Player Category

Players were also grouped according to their Overall rating to simplify performance analysis.

---

# Exploratory Data Analysis

The following analyses were performed.

## 1. Highest Rated Nationalities

Calculated the average Overall rating for each nationality to identify countries producing the highest-rated football players.

**Visualization**

- Bar Chart

---

## 2. Preferred Position Analysis

Compared the average Overall rating across different Preferred Position Types.

**Visualizations**

- Pie Chart
- Performance Ranking

---

## 3. Age Group Performance

Compared average Overall ratings among:

- Under 17
- Under 21
- Senior

**Visualizations**

- Pie Chart
- Bar Chart

---

## 4. Nationality Distribution

Identified the countries with the largest number of football players.

**Visualizations**

- Bar Chart
- Histogram

---

# Visualizations

The project includes several Matplotlib visualizations, including:

- Bar Charts
- Pie Charts
- Histograms

These visualizations were used to clearly communicate player performance and demographic trends.

---

# Key Insights

The analysis provides insights such as:

- Countries that produce the highest-rated players.
- Nationalities with the largest number of football players.
- Preferred playing positions with the highest average Overall ratings.
- Performance differences across age groups.
- Player distribution by nationality.

---

# Skills Demonstrated

This project demonstrates proficiency in:

- Python Programming
- Pandas Data Analysis
- Feature Engineering
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Aggregation
- Data Visualization
- Statistical Summarization
- Business Insight Generation
- Jupyter Notebook

---

# Repository Structure

```
Football-Data-Analysis/
│
├── FootballDataAnalysis.ipynb
├── football_players.csv
├── README.md
└── images/
    ├── nationality_bar_chart.png
    ├── position_pie_chart.png
    ├── age_group_bar_chart.png
    └── nationality_histogram.png

---

# Future Improvements

Possible enhancements include:

- Interactive dashboards using Power BI or Tableau.
- Advanced statistical analysis.
- Player clustering using Machine Learning.
- Predictive modelling for player performance.
- Interactive visualizations using Plotly.

---

# Author

**Emmanuel Egabor**

*MSc Data Science | Data Analyst | Business Intelligence Analyst*

---

## Connect with Me

**GitHub**

https://github.com/EmmanuelEgabor

**LinkedIn**

https://www.linkedin.com/in/egabor-emmanuel/

---

## Support

If you found this project useful, please consider giving it a ⭐ on GitHub. Your support is greatly appreciated.
