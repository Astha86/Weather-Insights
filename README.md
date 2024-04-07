# Weather Insights

It is a web application that fetches real-time weather data from the OpenWeather API and presents it to the user in a user-friendly UI.

# Features

    - Display the current weather conditions including temperature, humidity, wind speed, and weather description.
    - Allow users to search for weather data of different locations.
    - Automatically detect and display the weather data of the user's current location (optional).
    - Responsive design to ensure a seamless experience across devices.

# Technologies Used

    - HTML, CSS, and JavaScript for the frontend user interface.
    - OpenWeather API to fetch real-time weather data.
    - (Optional) Geolocation API to detect the user's current location.

## How to Use

    - Clone the repository:

## cd weather-app

    - Open index.html in your preferred web browser.

    - Enter the name of the city you want to check the weather for in the search box.

    - Press the "Search" button to fetch and display the weather data for the specified city.

    - (Optional) Allow the app to use your device's location to automatically fetch the weather data for your current location.

## API Key Setup

To use the OpenWeather API, you need to sign up on their website to obtain an API key. Once you have the API key, create a file named config.js in the project directory and store your API key in it as follows:

#E javascript

// config.js
const API_KEY = 'YOUR_API_KEY_HERE';

Replace 'YOUR_API_KEY_HERE' with your actual API key.

### Note: Do not share your API key publicly or commit it to version control. Use environment variables or other secure methods to manage the API key in production.
