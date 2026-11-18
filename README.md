# Weather · Week Ahead

A single-page dashboard showing the 7-day weather forecast, hosted on GitHub Pages.

**Live site:** https://hesterleyser.github.io/weather-dashboard/

## Features

- Current conditions: temperature, feels-like, humidity, wind, sunrise and sunset
- 7-day forecast with highs, lows and chance of rain
- Click any day to see an hourly temperature and rain-chance chart
- Search for any city, or use your current location
- °C / °F toggle; your location and unit choice are remembered in your browser
- Light and dark mode, following your system setting

## How it works

It's one static `index.html` file with no build step and no API key. Forecasts come from the free
[Open-Meteo](https://open-meteo.com/) API, fetched in the browser each time the page loads.
The default location is London.

To change anything, edit `index.html` and push to `main`. GitHub Pages republishes the site automatically.
