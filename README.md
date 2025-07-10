# 🌤️ React Weather App (OpenWeatherMap API)

A dynamic and minimal weather forecast application built with ReactJS and OpenWeatherMap API.

🔍 Users can enter any city name to get:
- Current temperature
- Weather condition (description)
- Wind speed

Built as part of **Day 11** of my #100DaysOfReact challenge.

---

## 📸 Screenshot

![Weather App Screenshot](./Screenshot%20(440).png) 
![Weather App Screenshot](./Screenshot%20(441).png) 



---

## 🔗 Live Demo

[Add your deployment link here if using Netlify/Vercel]

---

## ✨ Features

- Fetches real-time weather data using OpenWeatherMap API
- Validates city input and displays alerts for invalid cities
- Displays temperature, weather, and wind speed
- Stylish and responsive UI with light gradient background

---

## 🧠 What I Learned

- API integration using `fetch()`
- Managing async functions and state with `useState`
- Handling user input and API error responses
- Styling and layout design with conditional rendering

---

## 📁 Folder Structure

react-weather-app/
├── src/
│ ├── App.js
│ └── App.css
├── public/
└── .env (optional, for API key)

---

## 🚀 Getting Started

### 

1. Clone the Repo
git clone https://github.com/Gauravg2630/React-weather-api-app.git
cd React-weather-api-app

2. Install dependencies
npm install

3. Add your OpenWeatherMap API key
You can directly paste your key into App.js:
const API_KEY = 'your_actual_api_key_here';

Or use an .env file:

REACT_APP_WEATHER_API_KEY=your_actual_api_key_here
Then in App.js:
const API_KEY = process.env.REACT_APP_WEATHER_API_KEY;
✅ Don’t forget to restart the app if you use .env!

4. Run the app
npm start
🔗 GitHub Repo
https://github.com/Gauravg2630/React-weather-api-app

🙋‍♂️ Author
Created by Gaurav Gumber
Day 11 of #100DaysOfReact