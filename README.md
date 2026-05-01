# Weather App

A simple weather dashboard built with HTML, CSS, and JavaScript.

## Overview

This app lets users search for a city and displays the current weather conditions using the OpenWeatherMap API.

## Features

- Search for any city name
- Display current temperature in Celsius
- Show humidity and wind speed
- Change weather icon based on weather condition
- Built with plain HTML, CSS, and JavaScript

## Files

- `index.html` – main page markup
- `style.css` – app styling
- `images/weather-app-img/images/` – icon and UI asset images

## How to Run

1. Open `index.html` in a browser.
2. Enter a city name in the search field.
3. Click the search button.
4. The app will fetch weather data and display it.

> Note: The app uses the OpenWeatherMap API key already set in `index.html`.

## API

The weather data is fetched from OpenWeatherMap:

- Endpoint: `https://api.openweathermap.org/data/2.5/weather`
- Units: metric

## Notes

- If a city is invalid or not found, an error message is shown.
- The app currently uses client-side JavaScript only.
- To customize or reuse this project, replace the API key in `index.html` with your own key.

## License

This project is provided as-is for learning and demonstration purposes.
