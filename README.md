# Earthquake Data Analysis

This project explores earthquake data using Python and Pandas. The dataset ('Earthquakes_database.csv') contains information on earthquake magnitude, depth, location, and date.

## Overview

The initial steps involve loading and cleaning the data:

- Duplicates are removed.
- The 'ID' column is dropped.
- Date is split into 'Month,' 'Day,' and 'Year.'
- Earthquakes are categorized based on depth.

## Exploratory Data Analysis

The analysis includes visualizations:

1. **Earthquake Count Over the Years (Line Chart):**
   - Shows the trend of earthquake counts annually.

2. **Distribution of Earthquakes by Depth Category (Bar Chart):**
   - Illustrates the distribution of earthquakes into depth categories.

3. **Earthquake Distribution - Latitude vs Longitude (Scatter Plot):**
   - Displays the geographical distribution of earthquakes.

4. **Proportion of Earthquakes by Depth Category (Pie Chart):**
   - Highlights the percentage of earthquakes in different depth categories.

## Date Manipulations

Dates are transformed with two functions:

1. **Day of the Week Extraction:**
   - The 'Date' column is converted to datetime with UTC.
   - A new column, 'DayOfWeek,' is added to represent the day of the week.

2. **Resampling for Monthly Averages:**
   - 'Date' is set as the index.
   - The data is resampled to monthly frequency, and the mean magnitude is calculated.

Feel free to explore the code snippets for more details. For further information, contributions, or issues, please refer to the project repository.

