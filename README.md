# Netflix-Data-Analysis
# Netflix Data Analysis Findings

This document presents the findings from a detailed analysis of Netflix's dataset. The analysis covers data cleaning, handling missing values, identifying the number of shows released each year, and visualizing trends over time.

## 1. Data Cleaning and Preprocessing

The dataset underwent a series of cleaning and preprocessing steps, which included:
- Replacing missing values in the 'country,' 'director,' 'cast,' 'rating,' 'duration,' and 'date_added' columns with appropriate placeholders or the mode.
- Removing duplicate entries from the dataset to ensure data integrity.

## 2. Data Analysis

The analysis focused on understanding the distribution of shows released on Netflix over the years. The following findings were observed:
- The number of shows released each year was calculated, revealing trends in content production over time.
- A Savitzky-Golay filter was applied to smooth the yearly trends, providing a clearer view of the overall pattern in the number of shows released.

## 3. Visualizations

Several visualizations were created to better understand the data, including:
- A line plot depicting the number of shows released each year, with smoothed data to highlight trends.
- A histogram showing the distribution of the number of shows released per year.

## 4. Conclusion

The analysis revealed key trends in Netflix's content production over the years, highlighting fluctuations and growth in the number of shows released annually.
