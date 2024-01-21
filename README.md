# Weather App

Welcome to the Weather App! This Python program retrieves and displays current weather information for a given city using the OpenWeatherMap API.

## How to Use

1. Run the script.
2. Enter your OpenWeatherMap API key when prompted.
3. Enter the name of the city for which you want weather information.
4. View the current temperature and weather description.

## Features

### `get_weather(api_key, city)` Function

- Makes a request to the OpenWeatherMap API to get current weather information.
- Takes your OpenWeatherMap API key and the city name as parameters.

### `display_weather(weather_data)` Function

- Displays the current weather information obtained from the API.

### `weather_app()` Function

- Main function that prompts the user for their API key and the city name.
- Calls the `get_weather` and `display_weather` functions.

## Usage

```bash
python weather_app.py
```

Follow the on-screen instructions to get weather information for a specific city.

## Author

Jeel patel 
