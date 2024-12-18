



# 🌦️ Weather App  

**This project is a simple weather application that lets users check the current weather of any city using the OpenWeather API.** It provides details such as:  
🌡️ **Temperature**  
💧 **Humidity**  
💨 **Wind Speed**  
🌤️ **Weather Conditions**  

---  

## 🌟 Features  

- 🔎 **Search for City Weather**: Enter a city name to get real-time weather data.  
- 🌈 **Dynamic Weather Icons**: Displays icons based on weather conditions (e.g., 🌧️ Rain, 🌤️ Clear Sky, ☁️ Clouds).  
- ⚠️ **Error Handling**: Shows a clear error message if an invalid city name is entered.  

---  

## 🛠️ Technologies Used  

- 🖼️ **HTML**: For the structure of the application.  
- 🎨 **CSS**: For styling the user interface (linked as `style.css`).  
- 🧑‍💻 **JavaScript**: For fetching and displaying weather data dynamically.  
- 🌐 **OpenWeather API**: For providing real-time weather information.  

---  

## ✅ Prerequisites  

1. 🌐 An active internet connection.  
2. 🔑 A valid API key from OpenWeather (replace the placeholder API key in the JavaScript code).  

---  

## 🚀 Setup Instructions  

1. 📂 Clone or download the repository.  
2. 📁 Ensure you have the following project structure:  

   ```plaintext
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

3. 🔑 Replace the placeholder API key in the `index.html` file with your own API key from OpenWeather. Update the following line:  

   ```javascript
   const apiKey = "YOUR_API_KEY";  
   ```  

4. 🌐 Open the `index.html` file in any modern web browser.  

---  

## 🎯 How to Use  

1. 🏙️ Enter the name of a city in the search input field.  
2. 🔍 Click the search button.  
3. 🌟 View the weather details, including temperature, humidity, wind speed, and a weather icon.  
4. ⚠️ If an invalid city name is entered, an error message will appear.  

---  

## 📁 File Descriptions  

- 🗂️ **index.html**: Main HTML file for the app's structure and functionality.  
- 🎨 **style.css**: CSS file for styling the user interface.  
- 🖼️ **images/**: Folder containing icons used for weather conditions and the search button.  
- 🌐 **OpenWeather API**: The source of the weather data displayed.  

---  

## 🐞 Known Issues  

1. ❌ The app does not validate user input for empty fields or special characters. This will be improved in future updates.  
2. 🗝️ The placeholder API key must be replaced with a valid one for the app to work.  

---  

## 🌈 Future Enhancements  

- 🕒 Add additional weather details like sunrise, sunset, and extended forecasts.  
- ✨ Improve UI design with animations and transitions.  
- 🌍 Add support for multiple languages to make the app more accessible.  

---  

## 📜 License  

This project is for personal or educational use only. For commercial use, ensure compliance with OpenWeather API terms.  

---
