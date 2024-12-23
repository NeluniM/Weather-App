

# 🌦️ **Weather App**  

A simple and intuitive weather application that fetches real-time weather details for any city using the OpenWeather API. The app provides key information, including:  
- 🌡️ **Temperature**  
- 💧 **Humidity**  
- 🌬️ **Wind Speed**  
- ☁️ **Weather Description with Icons**  

---

## 🔑 **Key Features**  

### 🔍 **Search for Weather**  
- Enter any city name to instantly view the latest weather details.  

### 🌤️ **Dynamic Weather Icons**  
- Displays visual icons for current conditions (e.g., ☔ for rain, 🌞 for clear skies).  

### ⚠️ **Error Alerts**  
- Invalid city names or empty inputs prompt user-friendly error messages.  

---

## 🛠️ **Technologies Used**  

- 🖼️ **HTML**: Provides the foundational structure of the app.  
- 🎨 **CSS**: Creates a clean, responsive, and modern interface.  
- 🧑‍💻 **JavaScript**: Handles API calls and dynamically updates the UI.  
- 🌐 **OpenWeather API**: Supplies real-time weather data.  

---

## ✅ **Requirements**  

1. 🌐 **Active Internet Connection**: Required for retrieving weather data.  
2. 🔑 **API Key**: Obtain your API key from OpenWeather and configure the app.  

---

## 🚀 **Getting Started**  

1. 📥 **Download or Clone the Repository**  
   Save the project files to your local system.  

2. 📂 **Verify Project Structure**  
   Ensure your project directory looks like this:  
   ```plaintext
   /weather-app  
   ├── index.html  
   ├── style.css  
   ├── /images  
       ├── search.png  
       ├── clouds.png  
       ├── clear.png  
       ├── rain.png  
       ├── drizzle.png  
       ├── mist.png  
       ├── humidity.png  
       ├── wind.png  
   ```  

3. 🔑 **Set Your API Key**  
   Open the `index.html` file and replace `"YOUR_API_KEY"` with your actual API key:  
   ```javascript  
   const apiKey = "YOUR_API_KEY";  
   ```  

4. 🌐 **Launch the App**  
   Open `index.html` in any modern browser to start using the app.  

---

## 🎯 **How to Use**  

1. 🌍 Enter a city name in the search box.  
2. 🔍 Click the **Search** button to fetch weather data.  
3. 🌡️ View key details: temperature, humidity, wind speed, and dynamic weather icons.  
4. ⚠️ If the city is invalid or the input is empty, an error message will guide you.  

---

## 📁 **File Overview**  

- **index.html**: Defines the structure and integrates CSS and JavaScript.  
- **style.css**: Applies layout and styling to enhance the user experience.  
- **images/**: Includes icons for weather conditions and UI elements.  

---

## 🌟 **Planned Enhancements**  

1. 🕒 **Additional Weather Information**  
   - Include sunrise and sunset times, as well as extended forecasts.  

2. ✨ **Enhanced User Experience**  
   - Add animations and smooth transitions for better interactivity.  

3. 🌍 **Multi-language Support**  
   - Enable the app to support users from different regions.  

---

## 🐞 **Known Issues**  

1. **Input Validation**  
   - Special characters and empty fields are not yet fully handled.  

2. **API Key Dependency**  
   - A valid OpenWeather API key is required for the app to function.  

---

## 📜 **License**  

This project is open for personal and educational use. Commercial usage must adhere to OpenWeather API policies.  

---  

