📊 Multi-City Weather Intelligence Dashboard
🔹 Overview

This project is a Power BI Weather Dashboard built using real-time data from a weather API.

It provides insights into:

Current weather conditions
7-day forecast trends
Rain probability
Air Quality Index (AQI)
Multi-city comparison

The dashboard covers 6 Indian cities:
Pune, Bangalore, Hyderabad, Noida, Jaipur, and Aurangabad.

🔹 Problem Statement

Weather data is often scattered and difficult to compare across cities.

This project solves that by creating a centralized dashboard that helps users:

Understand weather trends
Compare cities
Make better decisions
🔹 Data Source

API Used:

http://api.weatherapi.com/v1/forecast.json

Data extracted:

Current weather
Forecast (10 days)
Hourly data
🔹 Data Processing
Converted JSON API data into tables using Power Query
Cleaned null values and unnecessary columns
Created structured datasets:
Current
Forecast_day
Forecast_hour
Location
🔹 Data Model
Built a star schema model
Location table connected to:
Current
Forecast_day
Forecast_hour

This allows dynamic filtering based on selected city.

🔹 Dashboard Features
🌡 Current weather summary
☀️ 7-day forecast cards with icons
📈 Temperature trend (line chart)
🌧 Chance of rain (percentage bar chart)
🌫 Air Quality Index with color indicators
🌅 Sunrise & Sunset timing
📊 Additional metrics (Humidity, Wind, UV, etc.)
🏙 Multi-city comparison
🔹 Key Insights
Temperature is stable in cities like Pune and Bangalore
Hyderabad shows higher temperature trends
High rain probability across multiple days
AQI varies significantly (Noida = Hazardous)
Slight temperature drop mid-week
🔹 Business Use
Travel planning
Logistics & delivery decisions
Health monitoring (AQI)
City comparison
🔹 Tools Used
Power BI
Power Query
DAX
Weather API
🔹 Dashboard Preview

(Add your screenshots here 👇)

![Dashboard]("C:\Users\Aditya\OneDrive\Documents\ADITYA DIVEKAR\PROJECTS\POWER_BI\4.Weather_Forcast_Dashboard\Screenshot 2026-04-05 193251.png")


🔹 Challenges
Handling nested JSON data
Managing null values
Creating proper relationships
Writing DAX for AQI color logic
🔹 Conclusion

This project shows my ability to:

Work with real-time API data
Clean and transform data
Build data models
Create interactive dashboards
