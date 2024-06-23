# NYC Vehicle Collision Analysis

## Project Overview

This project aims to analyze vehicle collision data in New York City (NYC) to identify trends, patterns, and factors contributing to accidents. By examining various aspects such as the number of injuries and fatalities, contributing factors, and temporal trends, we can provide valuable insights for targeted interventions and safety improvements.

## Data Source

The primary data used in this analysis is sourced from the NYC Open Data portal:
[NYPD Motor Vehicle Collision][https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data]

## Objectives

1. Analyze the Number of People Injured and Killed by Borough: Visualize the total number of injuries and fatalities in each borough.
2. Monthly Trends of Fatalities and Injuries: Examine the trends in injuries and fatalities over different months and years.
3. Impact of Contributing Factors: Focus on the leading cause of collisions, such as distraction/driver inattention, and analyze its impact on injuries and fatalities.
4. Collision Rates by Traffic Volume: Calculate collision rates per traffic volume for both weekdays and weekends.

## Methodology
## Data Preparation

1. Loading and Cleaning Data:

- Ensure that the dataset includes relevant columns such as crash_date, number_of_persons_injured, number_of_persons_killed, contributing_factor_vehicle_1, borough, and zip_code.
- Convert date columns to datetime format and handle missing values appropriately.

2. Feature Engineering:

- Extract additional features such as year, month, day_of_week, and hour from the crash_date column.
- Create binary indicators for weekend and weekday collisions.

3. Analysis and Visualization
