# Weather-Check-App

 Weather App using OpenWeather API 🌦️

The Weather App is a web application that fetches real-time weather data from the OpenWeather API and presents it to the user in a user-friendly UI.

# Features ✨

- Current Weather Conditions: Display the current weather conditions including temperature, humidity, wind speed, and weather description.
- City Search: Allow users to search for weather data of different cities.
- Location Detection (Optional): Automatically detect and display the weather data of the user's current location.
- Responsive Design: Ensure a seamless experience across devices.

Live Demo: [Check Today's Weather](https://check-today-weather.netlify.app/) 🌐

 Weather App Screenshot 📷
![Weather App Screenshot](screenshot-check-today-weather-netlify-app-2023-08-02-16_40_09-dgdd)

You can see a live demo of the Weather App [here](https://check-today-weather.netlify.app/).

# Video 🎥
![Weather App Video](weather.app.mp4)

# Technologies Used 🛠️
- Frontend: HTML, CSS, and JavaScript
- API: OpenWeather API for real-time weather data
- Geolocation API (Optional): To detect the user's current location

# How to Use 📝

1. Clone the repository:
   git clone https://github.com/yourusername/weather-app.git 

2. Navigate to the project directory:
   cd weather-app 

3. Open `index.html` in your preferred web browser.

4. Enter the name of the city you want to check the weather for in the search box.

5. Press the "Search" button to fetch and display the weather data for the specified city.

6. (Optional) Allow the app to use your device's location to automatically fetch the weather data for your current location.

# API Key Setup 🔑

To use the OpenWeather API, you need to sign up on their website to obtain an API key. Once you have the API key, create a file named `config.js` in the project directory and store your API key in it as follows:
// config.js
const API_KEY = 'YOUR_API_KEY_HERE';

Replace `'YOUR_API_KEY_HERE'` with your actual API key.

Note: Do not share your API key publicly or commit it to version control. Use environment variables or other secure methods to manage the API key in production.


Feel free to contribute to this project by submitting issues or pull requests. Let's build a better weather app together! 🚀
