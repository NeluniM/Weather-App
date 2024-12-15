# Weather App



☔ ☀ This project is a simple weather application that allows users to check the current weather of any city using the OpenWeather API. It provides details such as temperature, humidity, wind speed, and weather conditions.

## Features

- **Search for city weather**: Enter a city name to get real-time weather data.
- **Dynamic weather icons**: Displays icons based on the weather condition (e.g., rain, clear sky, clouds).
- **Error handling**: Displays an error message if an invalid city name is entered.

## Technologies Used

- **HTML**: For the structure of the application.
- **CSS**: For styling the user interface (linked as `style.css`).
- **JavaScript**: For fetching and displaying weather data dynamically.
- **OpenWeather API**: For real-time weather data.

## Prerequisites

1. An active internet connection.
2. A valid API key from OpenWeather (replace the placeholder API key in the JavaScript code).

## Setup Instructions

1. Clone or download the repository.
2. Ensure you have the following project structure:

   ```
   /project-folder
   |-- index.html
   |-- style.css
   |-- /images
       |-- search.png
       |-- clouds.png
       |-- clear.png
       |-- rain.png
       |-- drizzle.png
       |-- mist.png
       |-- humidity.png
       |-- wind.png
   ```

3. Replace the placeholder API key in the `index.html` file with your own API key from OpenWeather. The API key should be updated in the following line:

   ```javascript
   const apiKey = "YOUR_API_KEY";
   ```

4. Open the `index.html` file in any modern web browser.

## How to Use

1. Enter the name of a city in the search input field.
2. Click the search button.
3. View the weather details, including temperature, humidity, wind speed, and a weather icon.
4. If an invalid city name is entered, an error message will be displayed.

## File Descriptions

- **index.html**: The main HTML file for the app structure and functionality.
- **style.css**: The CSS file for styling the user interface.
- **images/**: A folder containing icons used for weather conditions and the search button.
- **OpenWeather API**: Provides the weather data used in the app.

## Known Issues

1. The app does not validate user input for empty fields or special characters. Future versions will address this.
2. The placeholder API key may need to be replaced with a valid one.

## Future Enhancements

- Add additional weather details like sunrise, sunset, and forecasts.
- Improve UI design with animations.
- Add localization support for displaying weather in different languages.

## License

This project is for personal or educational use only. For commercial use, ensure compliance with OpenWeather API terms.

---

Feel free to modify and enhance the project to suit your needs!

