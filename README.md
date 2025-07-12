# Boston-Bluebikes-Usage-Analysis-and-Seasonal-Demand-Forecasting_

# Summary
Bike-share programs offer an affordable, eco-friendly alternative to traditional transportation, allowing users to rent bikes from automated stations throughout a city and return them at their convenience. By enabling shared use, these systems provide numerous benefits—including improved health, environmental impact reduction, and personal cost savings—without the need for bike ownership.

However, despite their advantages, bike-share programs often face logistical challenges, particularly related to bike availability during peak hours. In Boston’s Bluebikes system, riders frequently encounter shortages at busy stations, especially near high-traffic areas like universities, even though bikes are rebalanced across docks multiple times daily. Weather conditions further influence bike usage, with ridership declining significantly in colder months despite management’s incentive efforts.

This project analyzes Boston Bluebikes usage patterns to understand how seasonality and time of day affect bike demand. We focus specifically on Northeastern University, visualizing demand fluctuations during academic terms and forecasting seasonal demand to support better resource planning. 

The analysis uses public Bluebikes data from 2019–2022, provided as monthly CSV files (15 columns each). Key fields include:
- **Start Time**: When the ride began
- **Trip Duration**: Ride length in seconds
- **User Type**: Customer or subscriber
- **Station Coordinates**: Latitude and longitude of start and end docks

For forecasting, I applied ARIMA and LSTM models, with LSTM delivering superior predictions of seasonal ride volume at Northeastern. Our results show the highest demand occurs in the fall, followed by summer, spring, and winter.

# Usage

Please copy this link -> [https://github.com/Rishab-KH/Boston-Bluebikes-Usage-Analysis-and-Seasonal-Demand-Forecasting_/blob/main/main.ipynb](https://github.com/AkshaySyal/Boston-Bluebikes-Usage-Analysis-and-Seasonal-Demand-Forecasting/blob/main/main.ipynb) and copy this url to https://nbviewer.org/ for viewing all the interactive visualizations.  

# References
[1]https://www.thecrimson.com/article/2022/12/1/Bluebikes-boston-logistics/

[2]https://www.Bluebikes.com/blog/2022-winter-challenge

[3]https://www.Bluebikes.com/system-data 
