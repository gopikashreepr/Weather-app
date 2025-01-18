# Weather-app
This is a simple yet functional weather application built using HTML, CSS, and JavaScript. It allows users to quickly check the weather of any city in real-time, providing essential weather information such as temperature, humidity, and wind speed. The application retrieves weather data from the OpenWeather API, making it a reliable tool for getting up-to-date weather information.

#### Features
- City Search: Users can enter the name of any city to check its current weather.
- Real-Time Weather Information: The app provides temperature, humidity, and wind speed in metric units.
- Weather Icons: Depending on the current weather condition (Cloudy, Clear, Rainy, Drizzle, Mist), the app dynamically changes the weather icon to reflect the condition.
- Error Handling: If an invalid city name is entered, the app displays an error message prompting the user to try again.
- Responsive Design: The app is designed to work on mobile and desktop devices, adjusting its layout based on the screen size.
- User-Friendly Interface: The interface is minimalistic and easy to navigate, making it perfect for users looking for a quick weather check.

#### Technologies Used
- HTML5: Used for structuring the content and the layout of the app.
- CSS3: Styles the application to give it a clean, modern look. Custom styling for buttons, input fields, and weather details.
- JavaScript: Provides functionality for fetching data from the OpenWeather API, updating the UI based on user input, and handling error scenarios.
- OpenWeather API: Provides real-time weather data for the city entered by the user.

#### How It Works
- Search Functionality: The user enters the name of a city into the search box and clicks the search button.
- API Request: The app makes an API request to OpenWeather using the city name and the API key. If the city name is valid, the app retrieves the weather data.
- Display Weather: The app displays the weather information, including:
-- Temperature in Celsius
-- Humidity percentage
-- Wind speed in kilometers per hour
- Weather Icon: Based on the weather condition (e.g., Cloudy, Clear, Rainy), the app dynamically updates the weather icon to match the condition.
- Error Handling: If an invalid city is entered, the app shows an error message prompting the user to enter a valid city name.

#### Future Improvements
- Geolocation Support: Add the ability to fetch the weather data based on the user's current location using the browser's geolocation API.
- Error Handling Enhancements: Improve error handling for cases like network issues or no internet connection.
- Multiple Units: Allow users to choose between different units (Celsius, Fahrenheit, and Kelvin) for temperature.
- Hourly Forecast: Show a detailed hourly forecast along with the daily weather report.
- Weather Maps: Integrate weather maps to give users a visual representation of weather conditions.
