# Weather App

This is a simple Weather App that allows users to check the weather for a specific city. It provides real-time weather information, including temperature, humidity, and wind speed. Inspired by @GreatStack

## Main Features

- **City Search**: Users can enter the name of a city they want to check the weather for. The app supports auto-suggestions, such as "Surrey, UK," and retrieves weather data based on the city input.

- **Real-time Weather Data**: The app fetches real-time weather data using the OpenWeatherMap API. It displays the temperature, humidity, wind speed, and weather conditions for the specified city.

- **Weather Icons**: The app displays weather icons to represent the current weather conditions, such as rain, clear skies, clouds, drizzle, and mist.

- **Error Handling**: If the entered city name is invalid or not found in the API, the app displays an error message to inform the user.

- **User-Friendly Interface**: The app has a user-friendly interface with a clean and simple design.

## How to Use

1. Enter the name of the city you want to check the weather for in the input field.

2. Click the search button or press "Enter" to initiate the search.

3. The app will display the current weather conditions for the specified city, including temperature, humidity, wind speed, and a weather icon.

4. If the city name is invalid or not found, an error message will be displayed.

## Technologies Used

- HTML: The app's front-end is built using HTML to create the user interface.

- JavaScript: JavaScript is used for interactivity and fetching weather data from the OpenWeatherMap API.

- CSS: CSS is used to style the app and make it visually appealing.

## API Integration

The app integrates with the OpenWeatherMap API to retrieve weather data. To use the app, you need to obtain an API key from OpenWeatherMap and replace the `apiKey` variable in the JavaScript code with your own API key.

```javascript
const apiKey = "YOUR_API_KEY_HERE";

