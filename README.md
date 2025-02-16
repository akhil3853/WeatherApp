WEATHER APP
-----------
Overview
This is a simple Weather App that allows users to check the weather for their current location or search for weather details of any city worldwide. It uses the OpenWeatherMap API to fetch real-time weather data and presents it in a user-friendly UI.

Features
-------
 View weather details for your current location
 Search weather for any city
 Displays temperature, wind speed, humidity, and cloud coverage
 Handles API errors and user location permissions
 Responsive design for mobile and desktop

Technologies Used
------------------
HTML
CSS
JavaScript
OpenWeatherMap API

Installation & Usage:
--------------------
Clone this repository
    git clone <repo-url>
    cd weather-app
Open index.html in a browser.
Click "Grant Access" to allow location-based weather data or use the search bar to find weather details for a specific city.

API Configuration:
----------------
This project uses the OpenWeatherMap API. To use your own API key:
Sign up at OpenWeatherMap.
Replace the API_KEY variable in script.js with your key:

const API_KEY = "your_api_key_here";

Project Structure
-----------------
/weather-app
│── index.html         # Main HTML structure  
│── style.css          # Styling  
│── script.js         # JavaScript logic  
│── assets/           # Icons and images  
