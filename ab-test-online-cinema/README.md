# A/B Test Analysis for an Online Cinema

[Open Jupyter Notebook](./online_cinema_ab_test.ipynb)

## Project Overview

This project analyzes the results of an A/B test conducted for an online cinema recommendation system.

The objective is to evaluate whether the new recommendation algorithm increases the proportion of users who start watching a movie.

The analysis includes data cleaning, statistical hypothesis testing, and user activity evaluation.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Files

- Jupyter Notebook: `online_cinema_ab_test.ipynb`
- Dataset: `data/Event_click.xlsx`

---

## Project Tasks

- Load and inspect the dataset
- Assess data quality
- Remove missing observations
- Exclude users assigned to multiple experiment groups
- Compare conversion rates between the control and test groups
- Test data normality using the Shapiro–Wilk test
- Compare groups using the Mann–Whitney U test
- Calculate and visualize DAU and WAU metrics
- Summarize the experimental results

---

## Results

- Cleaned and validated the experimental dataset
- Removed users assigned to multiple experimental groups
- Verified that the data were not normally distributed
- Applied the Mann–Whitney U test to compare conversion rates
- Calculated DAU and WAU to evaluate user activity
- Drew conclusions about the effectiveness of the recommendation system

---

## Key Findings

- Missing values and inconsistent observations were successfully removed.
- The Shapiro–Wilk test showed that the conversion data were not normally distributed.
- The Mann–Whitney U test revealed a statistically significant difference between the control and test groups.
- DAU and WAU remained generally stable during the observation period. The decrease in the final week is explained by the incomplete observation period.
- The new recommendation system demonstrated a positive impact on conversion to movie playback.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- A/B Testing
- Statistical Hypothesis Testing
- User Behavior Analysis
- Time Series Metrics (DAU & WAU)
- Data Visualization
- Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)

---

## Author

**Daria Sinitsyna**

Junior Data Analyst
