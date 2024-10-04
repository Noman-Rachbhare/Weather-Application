# Weather-Application

This project is a Weather  application that allows users to search for current weather of any city. Users can also get weather information for their current location using the Geolocation API.

## Features

- Search weather by city name.
- Get weather details for the current city.
- Display current weather information including temperature, wind speed, and humidity.
  

## Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Setup and Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Weather-Application
    ```

2. Navigate to the project directory:
    ```sh
    cd weather-Application
    ```

3. Open `index.html` in your browser to view the application.

## Usage

1. Enter a city name in the input field and click the "Search" button to get weather details for that city.
2. Click the "search your city name" button to get weather details for your city location.

## API Key

This project uses the OpenWeatherMap API. You need to have an API key to fetch the weather data.

1. Sign up on [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) to get your API key.
2. Replace the placeholder API key in the `script.js` file with your own API key:
    ```javascript
    const API_KEY = "YOUR_API_KEY"; // Replace with your OpenWeatherMap API key
    ```

## Project Structure
```
weather-dashboard/
│
├── index.html # Main HTML file
├── style.css # CSS file for styling
├── script.js # JavaScript file with functionality
├── README.md # Readme file

```

## Acknowledgements

- [OpenWeatherMap API](https://openweathermap.org/api) for providing the weather data.
  
