# Atmosphere Weather Dashboard

Atmosphere is a responsive weather dashboard built with HTML, CSS, and JavaScript. Search for a city to view its current temperature, weather condition, wind information, and a short forecast.

## Features

- Search weather by city name
- Display current temperature and weather condition
- Show wind information
- Display a three-day forecast
- Use weather icons from OpenWeatherMap
- Loading and city-not-found states
- Responsive glass-style interface for desktop and mobile
- Automatic redirect from `weather.html` to the main application

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- [GoWeather API](https://goweather.xyz/)
- OpenWeatherMap weather icons

## Getting Started

No build tools or installation steps are required.

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/<your-repository>.git
   ```

2. Open the project folder.

3. Open `weather.html` or `weatherProject.html` in your browser.

## Usage

1. Enter a city name in the search field.
2. Select **Search** or press Enter.
3. View the current weather and forecast.

The dashboard initially loads weather for London.

## API

Weather data is retrieved from the GoWeather API:

```text
https://goweather.xyz/v2/weather/{city}
```

No API key is required. An internet connection is required to retrieve live weather data and icons.

## Project Files

- `weatherProject.html` - Complete dashboard interface and JavaScript application
- `weather.html` - Redirect page that opens `weatherProject.html`
- `README.md` - Project documentation

## Browser Compatibility

The project works in modern browsers that support:

- Fetch API
- JavaScript ES6+
- CSS Grid
- CSS `backdrop-filter`

## Future Improvements

- Humidity and pressure measurements
- Geolocation-based weather
- Temperature unit selection
- Saved favorite cities
- Improved forecast date formatting

## License

This project is available for educational and personal use.
