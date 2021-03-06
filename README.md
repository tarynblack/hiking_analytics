# hiking_analytics
Simple analytics of my hiking data.

## Usage
The hiking_analytics.ipynb Jupyter Notebook analyzes a CSV file of hiking activity data. The file may be manually created or downloaded from Strava.

A manually created file needs to be a CSV file with the following columns:
- date
- average_moving_pace
- total_duration
- distance_mi
- elevation_gain_ft
- max_elevation_ft

To get a CSV of activity data from Strava, follow the Bulk Export instructions at [this link](https://support.strava.com/hc/en-us/articles/216918437-Exporting-your-Data-and-Bulk-Export) to download your full data archive. Once you have downloaded your data archive, the required file is 'activities.csv' in the data archive folder.

After you have created or downloaded your hiking data file, set the appropriate `filesource` and `filename` parameters in the first cell of the notebook, and run the script.

## Output
The notebook produces three plots, with examples shown below:
1. Total annual miles hiked and elevation gain
2. Annual average hiking statistics (distance, elevation gain, max elevation, steepness, fitness, speed)
3. Statistics for individual hikes (steepness, fitness, speed), colored by year

![Total annual miles hiked and elevation gain](https://github.com/tarynblack/hiking_analytics/blob/main/total_annual_distance_elevation.png)
![Annual average hiking statistics](https://github.com/tarynblack/hiking_analytics/blob/main/average_annual_stats.png)
![Individual hike statistics](https://github.com/tarynblack/hiking_analytics/blob/main/individual_hike_stats.png)
