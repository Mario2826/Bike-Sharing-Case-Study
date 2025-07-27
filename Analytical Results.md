Cyclistic Bike Share Case Study: How Do Annual Members and Casual Riders Use Cyclistic Bikes Differently?
________________________________________
Business Task

Cyclistic, a bike share program in Chicago, aims to increase annual memberships. The marketing team believes that converting casual riders into annual members will significantly contribute to long term profitability. To support this initiative, my task is to analyze how annual members and casual riders use Cyclistic bikes differently and deliver actionable insights through professional data analysis and visualization.
________________________________________
Data Sources

I used publicly available historical trip data from the Divvy bike share system for the full calendar year of 2023. The dataset includes trip level data such as:
•	ride_id
•	rideable_type
•	started_at and ended_at
•	start and end station
•	member_casual (user type)
The data was sourced from Divvy Trip Data and spans January 2023 to December 2023.
________________________________________
Tools Used

•	Excel: Initial data audit, cleaning, and exploratory pivot tables
•	SQLite: Consolidated data into a single table (all_trips_2023) and performed SQL queries for aggregations
•	Tableau: Created interactive dashboards and geospatial visualizations
•	R : Deeper trend analysis and statistical testing

________________________________________
Data Preparation & Cleaning

1.	Initial Audit: Reviewed the available months and determined that 2023 had more complete and consistent data compared to 2024.
2.	Data Consolidation: CSV files for each month were converted to Excel workbooks and initially reviewed in Excel.
3.	Cleaning Steps:
o	Added columns for ride_length and day_of_week
o	Removed rows with missing values (e.g., empty station names or times)
o	Verified consistent datetime formats and station names
________________________________________
Key Analyses Conducted (SQL)

•	Created ride_length column (difference between ended_at and started_at)
•	Converted ride_length to seconds and minutes
•	Added day_of_week and hour_of_day columns
SQL Queries Performed:
•	Total rides by member type
•	Average ride duration by member type
•	Ride counts by day of the week
•	Average ride duration by day and member type
•	Ride counts by hour of day
•	Most popular start stations 
________________________________________
Tableau Visualizations

Created multiple dashboards to support storytelling:
•	Total rides by user type
•	Ride length distribution by user type
•	Ride volume by day of the week and hour of day
•	Top start stations (with map)
•	Geospatial visuals styled with color coded member/casual types
________________________________________
Key Insights

1.	Casual riders tend to take longer trips, especially on weekends.
2.	Annual members ride more frequently, particularly on weekdays and during commuting hours.
3.	Casual riders are more active during midday hours and weekends, suggesting leisure oriented use.
4.	Top start stations differ slightly by user type but tend to cluster around central Chicago.
________________________________________
Recommendations 

1.	Target casual riders with weekend promotions that offer incentives for trying weekday commutes.
2.	Promote annual memberships at high traffic leisure locations (based on top casual rider start stations).
3.	Use digital marketing during midday and weekend hours, aligning with casual rider behavior patterns.
________________________________________
Prepared by: Mario Feliciano Google Data Analytics Capstone Project - Cyclistic Bike-Share Analysis

