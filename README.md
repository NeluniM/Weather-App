# 🌦️ **Weather App**  

Experience **real-time weather updates** in a sleek, user-friendly design! Powered by the 🌐 **OpenWeather API**, it delivers:  
- 🌡️ **Temperature**  
- 💧 **Humidity**  
- 💨 **Wind Speed**  
- 🌤️ **Current Conditions** with responsive visuals  

---

## ✨ **Core Features**  

🔍 **City Search**  
🌍 Instantly find the weather of any city by name.  

🌈 **Dynamic Weather Icons**  
☀️ Sunny, ☔ Rainy, 🌫️ Misty—icons that match live conditions!  

⚠️ **Error Handling**  
🚨 Alerts for invalid cities, empty fields, or API issues.  

📱 **Responsive Design**  
Seamlessly works on 🖥️ desktops, 📱 mobiles, and 📊 tablets.  

---

## 🛠️ **Built Using**  

- 🖼️ **HTML**: App structure.  
- 🎨 **CSS**: Styling and responsive layouts.  
- 🧑‍💻 **JavaScript**: Core logic and API connectivity.  
- 🌐 **OpenWeather API**: Real-time weather data source.  

---

## ✅ **Setup Requirements**  

1. 🌐 **Internet Access**: To fetch weather data.  
2. 🔑 **API Key**: Obtain one by registering on **OpenWeather**.  

---

## 🚀 **How to Set Up**  

### 1️⃣ **Download the Files**  
Clone or download the project repository.  

### 2️⃣ **File Structure**  
Ensure the following arrangement:  
```plaintext  
/weather-app  
├── index.html       # Main HTML file  
├── style.css        # Styling file  
├── script.js        # JavaScript logic  
├── /icons           # Weather icons directory  
    ├── sunny.png  
    ├── rainy.png  
    ├── cloudy.png  
    ├── snow.png  
    ├── mist.png  
    ├── wind.png  
```  

### 3️⃣ **API Key Configuration**  
In `script.js`, replace `"YOUR_API_KEY"` with your actual API key:  
```javascript  
const apiKey = "YOUR_API_KEY";  
```  

### 4️⃣ **Run the Application**  
Open `index.html` in your browser to launch the app!  

---

## 🌍 **App Workflow**  

1. 🔎 **Search for Weather**: Enter a city name in the input box.  
2. 🌤️ **View Results**: See live temperature, wind speed, and humidity.  
3. 🌡️ **Dynamic Display**: Icons adapt to the current weather conditions.  
4. ⚠️ **Error Handling**: User-friendly alerts for invalid inputs.  

---

## 📂 **File Details**  

- **index.html**: Defines the app's structure.  
- **style.css**: Customizes the layout and visuals.  
- **script.js**: Fetches and displays live weather using the API.  
- **icons/**: Contains visual assets for weather conditions.  

---

## 🚀 **Planned Upgrades**  

✨ **Extended Forecast**: Add a 5-day weather forecast.  
✨ **Language Options**: Support multiple languages 🌐.  
✨ **Interactive Animations**: Include smooth transitions and effects.  
✨ **Offline Mode**: Enable caching for offline access 📶.  

---

## 🐞 **Known Issues**  

1. 🆔 **City Names with Special Characters**: Errors may occur for cities with unique accents or symbols.  
2. 🚦 **API Rate Limits**: Free-tier API requests have usage caps.  

---

## 📜 **License**  

Open for personal and educational use. For commercial purposes, adhere to **OpenWeather** terms.  

