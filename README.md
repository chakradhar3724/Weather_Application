# Weather Forecast Web Application

A modern, responsive **Weather Forecast Web Application** that provides real-time weather information, hourly updates, and weekly forecasts based on the user’s current location or searched city. The app dynamically adapts visuals and highlights key environmental metrics for a smooth and engaging user experience.

---

## Features

- Automatic location detection using IP-based geolocation  
- City search with autocomplete suggestions  
- Temperature unit conversion (°C / °F)  
- Live date and time updates  
- Hourly and weekly weather forecasts  
- Dynamic weather icons and background images  
- Today’s weather highlights:
  - UV Index with severity level  
  - Wind speed  
  - Sunrise & sunset timings  
  - Humidity with status indicator  
  - Visibility with condition status  
  - Air quality indicator  
- Responsive UI for desktop and mobile devices  

---

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript  
- **Icons:** Font Awesome  
- **Weather API:** Visual Crossing Weather API  
- **Geolocation API:** geolocation-db.com  

---

## Project Structure
```
Weather-Forecast
│
├── index.html # Main HTML file
├── weather.css # Stylesheet
├── weather.js # JavaScript logic and API handling
├── icons/ # Weather icons
└── README.md # Project documentation
```

---

## How the Application Works

1. On page load, the application detects the user’s city using an IP-based geolocation API.
2. Weather data is fetched from the **Visual Crossing Weather API**.
3. Current weather conditions, highlights, and forecasts are rendered dynamically.
4. Users can:
   - Search for any city
   - Switch between hourly and weekly forecasts
   - Toggle temperature units between Celsius and Fahrenheit

---

## API Usage

The project uses the **Visual Crossing Weather API** to fetch weather data.

```js
https://weather.visualcrossing.com/VisualCrossingWebServices/rest/services/timeline/{CITY}?unitGroup=metric&key=YOUR_API_KEY
```

---

## Author

**Chakradhar Peddavenkatagari**

Aspiring AI Engineer

Bachelor's in Computer Science with Specialization in Cloud Computing

SRM University, Chennai
