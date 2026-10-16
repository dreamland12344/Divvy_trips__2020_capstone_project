# Divvy Trips 2020 — Rider Behaviour Analysis Using SQL

## Project Overview
This project compares casual riders and annual members using the Divvy Trips 2020 Q1 dataset. The goal is to understand differences in ride volume, trip duration, and riding patterns, then use these findings to recommend ways to encourage casual riders to become annual members.

## Dataset
- Raw Records: 426,887
- Columns: 13
- Analysis-Ready Records: 426,387
- Main Segmentation Field: `member_casual`

## SQL Analysis
The SQL workflow includes:
- Data profiling and missing-value checks
- Duplicate ride ID checks
- Timestamp parsing and ride-duration calculation
- Filtering invalid ride durations
- Ride counts and percentage share by rider type
- Average and median ride duration
- Ride volume by day of the week
- Weekday versus weekend usage
- Average ride duration by day and rider type

## Key Findings
- Members accounted for 378,344 rides (88.73%), while casual riders accounted for 48,043 rides (11.27%).
- Average ride duration was 11.50 minutes for members and 37.03 minutes for casual riders.
- Member ride volume peaked on Tuesday, while casual rider activity peaked on Sunday.
- Weekday rides represented 82.54% of member rides and 53.66% of casual rides.
- Casual riders had a more balanced weekday/weekend usage pattern than members.

## Business Recommendations
- Test annual membership promotions for casual riders who take longer or repeat trips.
- Pilot weekend-focused campaigns, especially around Sunday activity.
- Tailor campaign timing and messaging to different riding patterns.
- Evaluate campaign performance using conversion rates, acquisition costs, and retention data.

## Tools & Technologies
- Google BigQuery Standard SQL
- SQL Aggregate Functions
- Data Cleaning
- Exploratory Data Analysis
- Window Functions
- Business Analytics

## Project Files
- `Divvy_Trips_2020_SQL_Query_Analysis_Report.pdf` — SQL analysis report
- `Divvy_Trips_2020_SQL_Queries_for_Report.sql` — Core SQL queries
- `Divvy_Trips_2020_Recommendation_Queries.sql` — SQL queries supporting business recommendations

## Author
**Sarthak Sehgal**

## Note
The reported statistics are based on the original capstone report. The SQL scripts provide a reproducible workflow for analyzing the dataset. Run the queries against the source data to verify the results independently.
