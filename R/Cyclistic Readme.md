# Cyclistic Bike-Share Case Study - Data Analysis Portfolio Project

## Overview

Analyze how casual riders and annual members use Cyclistic bike-share differently using R. This project is part of the Google Data Analytics Capstone and demonstrates data cleaning, transformation, visualization, and statistical testing using R and ggplot2.

## Tools & Technologies

- R & RStudio
- dplyr, ggplot2, lubridate, readr, scales packages

## Key Questions Answered

1. How do casual riders and annual members differ in ride behavior?
2. Which days and times are most popular for each user type?
3. Which bike types and stations are preferred?

## Process Summary

### Data Cleaning

- Combined 12 months of raw CSV data
- Parsed datetime columns (`started_at`, `ended_at`)
- Calculated `ride_length`, `day_of_week`, and `hour_of_day`
- Removed outliers (<1 min, >24 hrs)

### Data Analysis

- Descriptive statistics: average, median ride lengths
- Grouped summaries by user type, day, hour
- Conducted T-Test for ride length difference between user types

### Visualizations

- Total Rides by User Type (with data labels)
- Ride Length Distribution (0-60 mins)
- Rides by Day of Week (Faceted by user type)
- Rides by Hour of Day
- Top 10 Start Stations
- Bike Type Preference (Casual vs Member)
- (Optional) Ride Trend Over Time

## Key Findings

- Casual riders tend to take longer trips on weekends.
- Members ride more frequently during weekdays and commute hours.
- Classic bikes are most used by both groups, but casuals favor docked bikes more.
- Top stations are clustered near high-traffic leisure and business areas.

## Recommendations

- Target casual riders with weekend commuter trials.
- Promote memberships at top casual-heavy stations.
- Align marketing campaigns with usage patterns (midday/weekend for casuals).

## Credits

Prepared by **Mario Feliciano**\
Google Data Analytics Capstone Project

---

> **Note:** This case study demonstrates end-to-end data analysis using R, showcasing technical cleaning, visualization, and business insight extraction skills.

