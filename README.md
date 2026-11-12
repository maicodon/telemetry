# telemetry 🌤️ Live Weather Telemetry Dashboard

A modern, production-ready, and secure weather tracking web application built with Vanilla JavaScript, HTML5, CSS3, and serverless architecture. Designed with a glassmorphism UI that dynamically adapts its background and theme based on real-time meteorological telemetry and local time.

App Preview: https://telemetryapp.vercel.app

## ✨ Key Features

- **Zero Client-Side Key Exposure:** All weather requests route through a secure serverless backend proxy (`/api/weather`) that injects the OpenWeatherMap API key from environment variables.
- **Real-Time Telemetry Dashboard:** View current temperature, weather conditions, humidity percentage, wind speed, atmospheric pressure, and visibility.
- **Dynamic Theme Engine:** Background gradients morph dynamically depending on weather conditions (sunny, rainy, overcast, or nighttime).
- **5-Day Forecast Grid:** Automatically parses 3-hour interval API payloads into clean daily mid-day standard cards using `Array.map()`.
- **Unit Toggle:** Seamlessly switch between Celsius (°C) and Fahrenheit (°F) on the fly.
- **Quick-Select Chips:** One-click access to global cities including Lagos, London, Tokyo, New York, and Sydney.
- **Robust Error State Management:** Graceful inline alerts for invalid city searches, network failures, or API rate limits without disruptive browser alerts.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Flexbox/Grid, CSS Variables, Glassmorphism), Vanilla ES6+ JavaScript.
- **Icons:** Lucide SVG Icons.
- **Backend / Deployment:** Vercel Serverless Functions / Node.js API Proxy.
- **API:** OpenWeatherMap Current Weather & 5-Day Forecast Endpoints.

## 🚀 Quick Setup & Deployment

1. **Clone the repository:**
   
   git clone https://github.com/maicodon/telemetry.git

   cd weather-telemetry
