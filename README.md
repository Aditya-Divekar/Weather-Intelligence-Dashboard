# 📊 Multi-City Weather Intelligence Dashboard

## 🔹 Overview

This project is a Power BI dashboard built using real-time weather data from an API. It provides a centralized view to analyze and compare weather conditions across multiple cities.

The dashboard covers 6 cities:

* Pune
* Bangalore
* Hyderabad
* Noida
* Jaipur
* Aurangabad

---

## 🔹 Problem Statement

Weather data is often scattered and difficult to compare.
This project solves that by creating a single dashboard where users can easily understand weather trends, rain probability, and air quality.

---

## 🔹 Data Source

API Used:
[http://api.weatherapi.com/v1/forecast.json](http://api.weatherapi.com/v1/forecast.json)

Data includes:

* Current weather
* 10-day forecast
* Hourly data

---

## 🔹 Data Processing

* Converted JSON data into tables using Power Query
* Cleaned null and unnecessary values
* Created structured datasets:

  * Current
  * Forecast_day
  * Forecast_hour
  * Location

---

## 🔹 Data Model

* Built a star-schema model
* Location table connected to:

  * Current
  * Forecast_day
  * Forecast_hour
* Enables dynamic filtering based on selected city

---

## 🔹 Dashboard Features

* 🌡 Current weather summary
* ☀️ 7-day forecast cards with icons
* 📈 Temperature trend (line chart)
* 🌧 Chance of rain (percentage bar chart)
* 🌫 Air Quality Index (AQI) with color indicators
* 🌅 Sunrise & Sunset timing
* 📊 Additional metrics (Humidity, Wind, Pressure, UV, etc.)
* 🏙 Multi-city comparison

---

## 🔹 Key Insights

* Stable temperature in cities like Pune and Bangalore
* Higher temperature variation in Hyderabad
* High rain probability across multiple days
* AQI varies significantly (Noida shows hazardous levels)
* Slight temperature drop mid-week

---

## 🔹 Business Use

* Travel planning
* Logistics and delivery planning
* Health monitoring using AQI
* City comparison

---

## 🔹 Tools Used

* Power BI
* Power Query
* DAX
* Weather API

---

## 🔹 Challenges

* Handling nested JSON data
* Managing null values
* Creating relationships between datasets
* Writing DAX for calculations and formatting

---

## 🔹 Conclusion

This project demonstrates end-to-end data analysis skills, from API data extraction and transformation to building an interactive dashboard for real-world decision-making.
