# App Usage Behavior Analysis

## Overview

This project analyzes user behavior based on app usage, screen time, data consumption, and demographic information. Using a dataset of daily app usage, screen-on time, data usage, and user age, the analysis explores patterns and correlations to understand trends in mobile device engagement.


## Analysis Steps

1. Data Loading: The dataset is loaded and basic information, including the first few rows, dataset structure, and descriptive statistics, is printed.
2. Visualizations:
   - Distribution of App Usage Time: A histogram is plotted to show the frequency distribution of app usage time.
   - Distribution of Screen On Time: A histogram is plotted for daily screen-on time.
   - Distribution of Data Usage: The distribution of data usage per day is visualized using a histogram.
   - Distribution of Age: A histogram shows the age distribution of users in the dataset.
   - Scatter Plot - App Usage Time vs Screen On Time: A scatter plot is generated to visualize the relationship between app usage time and screen-on time.
   - Scatter Plot - Data Usage vs Age: A scatter plot is used to examine the correlation between data usage and user age.


3. Correlation Analysis: The correlation matrix is calculated and visualized using a heatmap to identify relationships between numeric variables such as app usage time, screen-on time, data usage, and age.

## Libraries Used

- `pandas`: For data loading and manipulation.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced visualizations.

## How to Run

1. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Clone this repository and place the dataset `user_behavior_dataset.csv` in the root directory.
3. Run the script to generate visualizations and insights from the data:
   ```bash
   python app_usage_analysis.py
   ```

## Conclusion

This project provides a comprehensive analysis of mobile app usage and user behavior, offering insights into how different variables like age, data usage, and screen time relate to each other.

---

You can adjust the content as needed!
