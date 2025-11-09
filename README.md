# 🌤️ Weather Web Application  

A sleek, responsive weather application built using **HTML**, **CSS**, and **JavaScript**, powered by the **OpenWeatherMap API**.  
Get real-time weather updates for any city or your current location — with a stunning day and night theme that adapts beautifully to the time of day.  

---

## 💻 Technologies Used  

- **HTML5** – for a clean and semantic structure  
- **CSS3** – for modern, responsive, and dynamic UI design  
- **JavaScript (ES6)** – for API handling, interactivity, and dynamic updates  

---

## 🎨 App Design  

**🌞 Day Mode:** Bright, fresh visuals that capture the warmth of daylight.  
**🌙 Night Mode:** Cool, dark aesthetics for a smooth nighttime experience.  

The app automatically adjusts its theme based on real-time weather conditions and time of day — ensuring an immersive and elegant experience every time.  

---

## 🔗 API Integration  

This app uses the **OpenWeatherMap API** to fetch accurate and up-to-date weather data.  

**API Base URL:**  
https://api.openweathermap.org/data/2.5/weather?units=metric

**Example Endpoint:**  
https://api.openweathermap.org/data/2.5/weather?q=mumbai&appid=YOUR_API_KEY&units=metric
Simply replace `YOUR_API_KEY` with your own key from [OpenWeatherMap](https://openweathermap.org/api).  

---

## ⚙️ Features  

✅ **Live Weather Data** — Instantly get temperature, humidity, and condition updates for any city.  
✅ **Location-Based Access** — Automatically detect and display weather data for your current location (with permission).  
✅ **Manual Search** — Search for weather in any city across the world.  
✅ **Day/Night Mode** — Visually dynamic design that changes based on time of day.  
✅ **Error Handling** — Clear alerts for invalid city names or denied location access.  
✅ **Fully Responsive** — Works seamlessly across desktop, tablet, and mobile screens.  

---

## 🚨 Error Handling  

- If **location access** is **granted**, the app automatically displays weather for the user’s current city.  
- If **access is denied**, users can manually enter a city name to get weather details.  
- Displays user-friendly messages for invalid input or connection issues.  

---

## 📁 Project Setup  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/Weather-App-Project.git
   ```
2. **Navigate to the project folder**
```bash
cd Weather-App-Project
```
3. **Open index.html in your browser and explore the app!**
