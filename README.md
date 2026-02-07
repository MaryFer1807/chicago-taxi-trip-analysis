# Chicago Taxi Trip Analysis

## Project Overview
This project analyzes taxi trip data from Chicago to understand demand patterns across taxi companies and neighborhoods, as well as to evaluate how weather conditions affect trip duration.

The analysis combines exploratory data analysis and statistical hypothesis testing using real-world transportation data. The goal is to extract actionable insights that can support operational and business decisions in urban mobility.

## Objective
The main objectives of this project are to:
- Analyze taxi trip volume by company.
- Identify the most popular drop-off neighborhoods in Chicago.
- Visualize demand patterns using clear and informative charts.
- Test whether weather conditions impact trip duration.
- Apply statistical hypothesis testing to support data-driven conclusions.

## Datasets
The project uses three datasets obtained through SQL queries:

### project_sql_result_01.csv
Contains taxi company trip data:
- `company_name`: Name of the taxi company
- `trips_amount`: Number of trips on November 15–16, 2017

### project_sql_result_04.csv
Contains neighborhood-level trip data:
- `dropoff_location_name`: Chicago neighborhoods
- `average_trips`: Average number of trips ending in each neighborhood in November 2017

### project_sql_result_07.csv
Contains trip duration and weather data:
- `start_ts`: Trip start date and time
- `weather_conditions`: Weather conditions at trip start
- `duration_seconds`: Trip duration in seconds

## Data Preparation
- Imported CSV files using pandas.
- Verified and corrected data types.
- Checked for missing or inconsistent values.
- Prepared datasets for grouping, aggregation, and analysis.

## Exploratory Data Analysis
The exploratory analysis focused on:
- Comparing taxi companies based on total number of trips.
- Identifying the top 10 neighborhoods by average number of drop-offs.
- Visualizing demand distribution using bar charts.
- Interpreting patterns and differences across companies and locations.

## Hypothesis Testing
The following hypothesis was tested:

**Hypothesis:**  
The average duration of trips from the Loop to O'Hare International Airport changes on rainy Saturdays.

### Statistical Approach
- Defined null and alternative hypotheses.
- Selected a significance level (alpha).
- Applied a statistical test to compare trip durations under different weather conditions.
- Interpreted the results to determine whether the null hypothesis should be rejected.

## Tools Used
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Business Value
This analysis provides insights into:
- Taxi demand concentration across companies and neighborhoods.
- Urban mobility patterns in Chicago.
- The impact of external factors such as weather on travel time.
- How statistical analysis can support operational decisions in transportation services.

The project demonstrates the use of exploratory data analysis and hypothesis testing on real-world datasets with a strong business-oriented focus.
