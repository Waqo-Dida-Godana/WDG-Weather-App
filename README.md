# WDG Weather App

A simple, user-friendly weather application that lets you check the current weather by city or your current location using the OpenWeatherMap API.

---

## Features

- Search weather by city name (with country code fixed to Kenya).
- Get weather information based on your current geolocation.
- Displays weather conditions including temperature, wind speed, humidity, and a brief description.
- Responsive and clean UI built with Bootstrap 5.

---

## Demo

![WDG Weather App Screenshot](path_to_screenshot_if_any.png)

---

## How to Use

1. Enter the name of a city (e.g., Marsabit) in the input box and click **Get Weather**.
2. Alternatively, click **Use My Location** to allow the app to fetch weather data for your current location.
3. The weather details will be displayed below the buttons.

---

## Technologies Used

- HTML5
- CSS3 (with Bootstrap 5)
- JavaScript (Fetch API)
- OpenWeatherMap API for weather data

---

## Setup & Installation

1. Clone this repository or download the `index.html` file.
2. Open the file in any modern web browser.
3. Make sure you have an active internet connection for Bootstrap CDN and API requests.
4. **Note:** The API key is currently embedded in the script for demo purposes. For production, consider securing your API key.

---

## API Key

This project uses OpenWeatherMap API. The key is currently hardcoded in the script:

```js
const apiKey = "69f8b59f607d6d0b0b815561301cf8f0";
