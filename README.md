# ⚡ StormSense Weather

<h1 align="center">⚡ StormSense Weather</h1>

<h3 align="center">Your Window to the Weather. Anywhere. Anytime.</h3>

<p align="center">
  A modern, responsive weather intelligence dashboard built for exploring live weather conditions, atmospheric trends, air quality indicators, and extended forecasts across India and the globe.
</p>

<p align="center">
  <a href="https://kjagdeesh.github.io/StormSense-Weather/">
    <img src="https://img.shields.io/badge/🌤️_Live_Demo-Visit_App-orange?style=for-the-badge" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
</p>

<p align="center">
  <b>🌍 Global Weather Search • 🇮🇳 Indian Metro Intelligence • 📊 Interactive Forecasts</b>
</p>

---

## 🌦️ About the Project

**StormSense Weather** is a modern meteorological web application designed to make weather information accessible, interactive, and visually engaging.

From checking current weather conditions in major Indian metropolitan cities to exploring hourly atmospheric trends and seven-day forecasts, StormSense brings essential weather intelligence together in one responsive dashboard.

Whether you're planning your commute, checking the rain probability, or exploring weather conditions around the world, StormSense helps you stay informed.

## ✨ Key Features

### 🇮🇳 1. Indian Metros Weather Hub
- Live weather tracking across 12 major Indian metropolitan regions.
- Dedicated city cards with temperature information.
- Regional filtering: North, South, East, and West.
- Responsive Bento Grid layout.
- Quick city selection.

### 🌡️ 2. Real-Time Weather Dashboard
- Current temperature and weather conditions.
- Feels-like temperature.
- Atmospheric pressure.
- Relative humidity.
- Wind speed.
- Dynamic weather icons and visual indicators.

### 📈 3. Interactive Intraday Weather Analytics

Explore three different atmospheric metrics through interactive charts:

| Metric | Information |
|---|---|
| 🌡️ Temperature | Hourly temperature trends |
| 🌧️ Precipitation | Hourly rain probability |
| 💨 Wind | Hourly wind speed |

### 🌍 4. Global Location Search
- Search cities across the world.
- Dynamic location suggestions.
- Debounced search functionality.
- Quick-select Indian metro locations.
- Keyboard-friendly search interactions.

### 📍 5. GPS-Based Weather Detection
- Detect your current geographical coordinates.
- Reverse geocode coordinates into a readable location.
- Automatically load weather conditions for your detected location.

### 🌤️ 6. Tomorrow's Weather Outlook
- Tomorrow's expected weather conditions.
- Maximum and minimum temperatures.
- Precipitation probability.
- Dynamic weather illustrations.

### 📅 7. Seven-Day Extended Forecast
- Extended weekly weather predictions.
- Daily maximum and minimum temperatures.
- Rain probability.
- UV index.
- Sunrise and sunset information.

### 🌫️ 8. Air Quality Indicator
- Air quality visualization.
- AQI category indicators.
- Pollutant information display.
- General air-quality guidance.

**Note:** The current AQI implementation uses predefined city-based values rather than a live air-quality data feed. It is an area for future improvement.

### 🌡️ 9. Celsius / Fahrenheit Conversion
- Switch between °C and °F.
- Updates temperature displays throughout the dashboard.
- Remembers the selected unit using browser local storage.

### 📱 10. Responsive Design
- Desktop-friendly dashboard.
- Tablet optimization.
- Mobile-friendly layouts.
- Modern Material-inspired interface.
- Clean typography and visual hierarchy.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| Vanilla JavaScript | Application logic and interactions |
| Tailwind CSS | Responsive styling |
| Open-Meteo API | Weather forecasts and meteorological data |
| Open-Meteo Geocoding API | Global location search |
| BigDataCloud API | GPS reverse geocoding |
| SVG | Interactive weather visualizations |
| Material Symbols | Icons and interface elements |
| Plus Jakarta Sans | Typography |

---

## 🌐 API Integrations

StormSense uses publicly accessible APIs to retrieve weather and location information.

| API | Usage |
|---|---|
| Open-Meteo Forecast API | Current weather, hourly data and seven-day forecasts |
| Open-Meteo Geocoding API | Global city search |
| BigDataCloud Reverse Geocoding | Convert GPS coordinates into location names |

- Weather API: https://open-meteo.com/
- Geocoding API: https://open-meteo.com/en/docs/geocoding-api
- Reverse Geocoding: https://www.bigdatacloud.com/

---

## 🚀 Getting Started

Get StormSense Weather running locally in just a few steps.

### Prerequisites

- A modern web browser.
- Internet connection for external API requests.
- Git (optional).

No package installation or build process is required.

### 1. Clone the Repository

```bash
git clone https://github.com/kjagdeesh/StormSense-Weather.git
```

### 2. Navigate to the Project

```bash
cd StormSense-Weather
```

### 3. Launch the Application

Simply open `index.html` in your browser.

Alternatively, use Python:

```bash
python -m http.server 3000
```

Open:

```text
http://localhost:3000
```

That's it! You're ready to explore StormSense Weather.

---

## 📂 Project Structure

```text
StormSense-Weather/
│
├── assets/
│   ├── logo.png
│   └── favicon.ico
│
├── .github/
│   └── workflows/
│
├── index.html
├── favicon.ico
├── .gitignore
└── README.md
```

---

## 🤝 Contributing

Contributions, ideas, and suggestions are welcome!

If you'd like to improve StormSense Weather:

1. Fork this repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

```bash
git checkout -b feature/your-feature
git commit -m "Add: your feature"
git push origin feature/your-feature
```

---

## 📜 License

This project is intended to be open source. See the repository's LICENSE file for licensing terms.

---

## 👨‍💻 Author

**K. Jagadeesh**

<p align="center">
  <a href="https://github.com/kjagdeesh">
    <img src="https://img.shields.io/badge/GitHub-Follow_Me-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

---

<p align="center">
  <b>⚡ StormSense Weather</b>
  <br>
  Making Weather Intelligence Beautiful, Accessible & Interactive.
  <br><br>
  ⭐ If you find this project useful, consider giving it a star on GitHub!
</p>
