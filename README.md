# 🌦️ **Weather App**  

An intuitive, user-friendly **weather application** that delivers real-time weather updates for any city using the **OpenWeather API**. Access details like:  
- 🌡️ **Temperature**  
- 💧 **Humidity**  
- 🌬️ **Wind Speed**  
- ☁️ **Current Weather Conditions** with dynamic icons.  

---

## ✨ **Key Features**  

### 🔍 **Search by City**  
- Enter any city to retrieve **accurate, real-time weather data**.  

### 🌤️ **Dynamic Weather Visuals**  
- Displays weather icons that reflect current conditions (e.g., 🌞 for sunny, ☔ for rain).  

### ⚠️ **Error Notifications**  
- Alerts if the input is invalid or the search field is left empty.  

### 🎨 **Responsive Design**  
- Optimized for a seamless experience on desktops 🖥️, tablets, and smartphones 📱.  

---

## 🛠️ **Built With**  

- 🖼️ **HTML**: Creates the app’s structure.  
- 🎨 **CSS**: Adds style and ensures responsive layouts.  
- 🧑‍💻 **JavaScript**: Handles API integration and user interactions.  
- 🌐 **OpenWeather API**: Provides real-time weather updates.  

---

## ✅ **Requirements**  

1. 🌐 **Internet Connection**: Needed to fetch live weather data.  
2. 🔑 **API Key**: Obtain a free API key from **OpenWeather**.  

---

## 🚀 **Getting Started**  

### Step 1️⃣: **Download the App**  
- Clone the repository or download the project files.  

### Step 2️⃣: **Organize Files**  
Ensure the following structure is maintained:  
```plaintext  
/weather-app  
├── index.html       # Main HTML file  
├── style.css        # App styling  
├── script.js        # Handles weather logic  
├── /icons           # Weather icons folder  
    ├── sunny.png  
    ├── rainy.png  
    ├── cloudy.png  
    ├── snow.png  
    ├── mist.png  
    ├── wind.png  
```  

### Step 3️⃣: **Configure API Key**  
- Open `script.js` and replace `"YOUR_API_KEY"` with your key:  
   ```javascript  
   const apiKey = "YOUR_API_KEY";  
   ```  

### Step 4️⃣: **Launch the App**  
- Open `index.html` in your browser to start exploring.  

---

## 🌍 **How It Works**  

1. 🔍 **Enter a City Name**: Type the desired city in the search bar.  
2. 🌤️ **Click Search**: Instantly fetch live weather details.  
3. 🌡️ **View Weather Stats**: Get temperature, humidity, wind speed, and more.  
4. ⚠️ **Handle Errors Gracefully**: Receive clear guidance for invalid inputs.  

---

## 📁 **File Overview**  

- **index.html**: Contains the calculator's layout and structure.  
- **style.css**: Stylesheets for responsiveness and design aesthetics.  
- **script.js**: Integrates the OpenWeather API and updates the UI dynamically.  
- **icons/**: Houses weather-related icons like sunny, rainy, cloudy, etc.  

---

## 🌟 **Planned Features**  

1. 🕒 **Extended Forecasts**  
   - Add sunrise/sunset times and 5-day weather forecasts.  

2. 🌍 **Multi-Language Support**  
   - Allow users to toggle between languages for global accessibility.  

3. ✨ **Enhanced Interactivity**  
   - Include animations for a smooth and engaging experience.  

4. 🔒 **Offline Functionality**  
   - Display cached data when the app is offline.  

---

## 🐞 **Known Limitations**  

1. **Special Characters in City Names**  
   - Certain special characters may not be properly recognized.  

2. **API Rate Limit**  
   - App performance is dependent on the OpenWeather API’s rate and availability.  

---

## 📜 **License**  

This project is free for personal and educational use. For commercial purposes, adhere to OpenWeather’s API usage guidelines.  

---
