## Proyect description

A new ridesharing company in Chicago needs to find behavior patterns within the available data. Understanding passenger preferences and the impact of external factors on trips will enable the launch of an optimal and competitive service in the city.

## Tasks

1. Import the files and study the data they contain.
2. Ensure that the data types are correct.
3. Identify the top 10 neighborhoods in terms of trip endpoint.
4. Graphically represent the main results and conclusions.
5. Test the hypothesis: "The average duration of trips from the Loop to O'Hare International Airport changes on rainy Saturdays."

## Data description:

We have two files for data analysis:

1. project_sql_result_01.csv. It contains the following data:

- company_name: the name of the taxi company
- trips_amount: the number of trips for each taxi company on November 15 and 16, 2017.

2. project_sql_result_04.csv. It contains the following data:

- dropoff_location_name: Chicago neighborhoods where trips ended
- average_trips: the average number of trips that ended in each neighborhood in November 2017.

And we have a separate file for hypothesis testing:

project_sql_result_07.csv
It contains data about trips from the Loop to O'Hare International Airport.

- start_ts: pickup date and time
- weather_conditions: weather conditions at the time the trip started
- duration_seconds: duration of the trip in seconds

## Table of contents

 1. Initialization:
 
    - Data Loading
    - Initial Exploration
    - Preliminary Conclusions
    
3. Data Preprocessing:
 
    - Data Type Correction
    - Implicit Duplicates Checking
    - Duplicate Records
    - Value Checking
 
 4. Data Analysis:
 
    - Question Formulation
    - Taxi Companies and Trips Made
    - Trip Endings in Chicago Neighborhoods
    
 5. Hypothesis Testing:
 
    - Levene Tests
    - T Tests
    - Final Results
    
 6. Conclusions

## Used libraries

- pandas 
- matplotlib
- scipy
- numpy
- seaborn
