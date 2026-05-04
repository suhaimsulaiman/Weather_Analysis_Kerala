# Power BI Weather Analysis Dashboard

## Project Overview

This project is an interactive **Power BI Weather Analysis Dashboard** built using live weather data from **WeatherAPI** through URL-based API integration. The dashboard provides a **7-day weather forecast** for **6 locations across Kerala** with dynamic visualizations and city-wise insights.

The goal of this project is to analyze weather conditions, monitor air quality, and present real-time weather insights using professional Power BI dashboards.

---

## Features

* 7-Day Weather Forecast Analysis
* Temperature Trend Visualization
* Humidity Monitoring
* Wind Speed Tracking
* Visibility and Pressure Analysis
* UV Index Monitoring
* Precipitation Tracking
* Sunrise and Sunset Information
* Chance of Rain Prediction
* Air Quality Index (AQI) Dashboard
* City-wise Interactive Navigation

---

## Locations Covered

* Kochi
* Alappuzha
* Kollam
* Kottayam
* Palakkad
* Malappuram

---

## Tools Used

* Power BI Desktop
* WeatherAPI
* Power Query
* DAX Measures
* Data Modeling
* Data Visualization Techniques

---

## Data Source

Live weather and forecast data were collected using **WeatherAPI** through API URL integration.

### API Example

```bash
https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=CITY_NAME
```

---

## Project Workflow

### Step 1: Get WeatherAPI Key

* Created an account on WeatherAPI
* Generated API Key for authentication

### Step 2: Build API URL

* Used API endpoint for current weather and forecast data
* Connected city-wise weather details using dynamic URL parameters

### Step 3: Connect Power BI to WeatherAPI

* Opened Power BI Desktop
* Selected **Get Data → Web**
* Entered WeatherAPI URL
* Loaded JSON response into Power BI

### Step 4: Transform the Data

Using Power Query:

* Expanded nested records
* Extracted current weather details
* Expanded sub-records like condition and air_quality
* Renamed columns for better understanding
* Applied Close & Apply

### Step 5: Build the Dashboard

Created:

* KPI Cards for temperature, humidity, pressure, etc.
* Gauges for wind speed and AQI
* Charts for daily weather variations
* Slicers for city-wise filtering
* Interactive report pages for better user experience

---

## Dashboard Highlights

### Main KPIs

* Temperature
* Humidity
* Wind Speed
* Visibility
* Pressure
* UV Index
* Precipitation

### Advanced Visuals

* Weekly Forecast Line Chart
* AQI Monitoring Section
* Chance of Rain Bar Chart
* Sunrise & Sunset Display
* Dynamic City Selection Buttons

---

## Skills Demonstrated

* API Integration in Power BI
* Real-Time Data Handling
* Data Cleaning and Transformation
* Power Query Development
* DAX Calculations
* Dashboard Design
* Business Intelligence Reporting
* Data Visualization Best Practices

---

---

## Future Improvements

* Add historical weather comparison
* Include monthly weather trends
* Add severe weather alerts
* Mobile-optimized dashboard layout
* Publish report using Power BI Service

---

## Author

**Suhaim Sulaiman**

Data Analyst | Power BI Developer | Analytics Enthusiast

GitHub: https://github.com/suhaimsulaiman
LinkedIn: https://www.linkedin.com/in/suhaim-sulaiman-9638a5190/
Completed and actively improving with advanced features.

