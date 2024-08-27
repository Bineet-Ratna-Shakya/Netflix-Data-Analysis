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

# Final Findings

## 1. Content Growth Over Time
The number of shows on Netflix has grown significantly over time. There is a clear upward trend in the number of shows released each year, with 2017 being the year with the most releases (around 1032) out of the data provided.

## 2. Top Show Categories
The analysis reveals that Drama is the most common genre for shows on Netflix, followed by Comedy and International Movies. This suggests that Netflix offers a wide variety of content, but dramas are particularly well-represented.

## 3. Genre Correlations
The correlation heatmap of genres shows how different genres are related to each other. This could be helpful for Netflix to understand which genres are often watched together by users and use that information to recommend content.

## 4. Top Content Producing Countries
The United States is the top country producing content for Netflix, followed by India and the United Kingdom. This suggests that Netflix invests heavily in content from these regions.

