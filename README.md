# Weather App 🌤️

A simple and interactive weather app that allows users to fetch and display real-time weather data for any city in the world. Built using **HTML**, **CSS**, and **React JS**, the app utilizes the **OpenWeatherMap API** to provide weather updates, including temperature, humidity, wind speed, and weather conditions.

## Features
- **Real-time weather data**: Displays current temperature, humidity, wind speed, and weather conditions.
- **Dynamic weather icons**: Weather icon changes based on the fetched weather conditions (e.g., sunny, cloudy, rainy).
- **Responsive design**: Works on various screen sizes and devices.
- **Error handling**: Displays an error message for invalid city names or incorrect input.
- **Interactive search**: Users can search by entering city names and get instant results.

##Project link
You can view the live demo of the project here:  
🔗 **[Live Demo](https://your-project-name.vercel.app)**


## How to Use
1. **Enter a city name** in the search bar.
2. Click the **search button** or press **Enter** to fetch the weather data.
3. The app will display the following:
   - **Temperature** (in Celsius)
   - **Humidity**
   - **Wind Speed**
   - **Weather Condition Icon** (e.g., clouds, clear sky, rain)

## Technologies Used
- **HTML5**: Structure of the web page.
- **CSS3**: Styling and layout of the app.
- **JavaScript (ES6+)**: Fetching data from the OpenWeatherMap API and dynamic content updates.
- **OpenWeatherMap API**: Source of real-time weather data.


## API Key Setup
To use the app, you'll need to set up your own OpenWeatherMap API key:

1. Go to the [OpenWeatherMap website](https://openweathermap.org/) and sign up to get a free API key.
2. Once you have the API key, navigate to the `logic.js` file in the project.
3. Replace the placeholder `apiKey` value with your actual API key:
   ```js
   const apiKey = "your-api-key-here";

