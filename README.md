# Indian Union Budget Analysis Financial Year 2021-22 till 2022-23

## Project Overview
This project analyzes the Indian Union Budget data spanning from the fiscal year 2021-2022 to 2023-2024. The dataset contains information about revenue, capital, and total budget estimates for various ministries/departments.

### Project Overview
- The dataset was loaded using the Pandas library, and initial exploration was performed to understand its structure and identify any missing values.
- Missing values in the 'Budget Estimates 2022-2023 Revenue' column were filled with the mean value.
- Rows with null values in the 'Budget Estimates 2022-2023 Capital' and 'Budget Estimates 2022-2023 Total' columns were deleted.
- The top ministries based on revenue and total budget estimates were identified and visualized using bar charts.
- Pair plots and a correlation heatmap were created to explore relationships between different numerical columns in the dataset.
- Summary statistics such as mean, median, mode, standard deviation, variance, range, skewness, and kurtosis were calculated for the 'Actuals 2021-2022 Total' column.
- Outliers were identified using z-scores, and a histogram of the log-transformed data was plotted to explore the distribution.

### Code Overview
The code is organized into sections, each performing specific tasks:

1. Data Loading and Initial Exploration
2. Data Preprocessing (Handling Missing Values)
3. Data Visualization (Bar Charts, Pair Plots, Heatmap, Histogram)
4. Statistical Analysis (Summary Statistics, Outlier Detection)

### Libraries Used
- NumPy: For numerical computations
- Pandas: For data manipulation and analysis
- Matplotlib: For creating visualizations such as bar charts, histograms, and scatter plots
- Seaborn: For creating advanced visualizations like pair plots and heatmaps

### Conclusion
This project provides valuable insights into the Indian Union Budget data, enabling stakeholders to understand revenue patterns, budget allocations, and relationships between different variables. Further analysis and interpretation can be performed based on the findings from this exploratory analysis.
