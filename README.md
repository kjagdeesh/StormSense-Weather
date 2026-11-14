# ⚡ StormSense Weather — Live Meteorological & Indian Metros Intelligence

<p align="center">
  <img src="assets/logo.png" width="120" alt="StormSense Weather Logo" style="border-radius: 24px; box-shadow: 0 8px 24px rgba(0,0,0,0.15);" />
</p>

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-2563eb?style=flat&logo=github)](https://kjagdeesh.github.io/StormSense-Weather/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5 / Tailwind CSS](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20VanillaJS-orange.svg)](#features)
[![API: Open-Meteo](https://img.shields.io/badge/API-Open--Meteo-brightgreen.svg)](https://open-meteo.com)

**StormSense Weather** is a responsive, high-performance meteorological web application engineered with Tailwind CSS, Material Design tokens, and live Open-Meteo weather intelligence. It features a responsive Indian Metros Bento Grid, interactive intraday thermal/rain/wind curves, comprehensive Air Quality Index (AQI) tracking, real-time GPS location detection, and an extended 7-day forecast modal.

---

## ✨ Features

- 🇮🇳 **Indian Metros Weather Hub**:
  - Live grid covering 12 major Indian metropolitan regions: **Delhi NCR [DL]**, **Mumbai [MH]**, **Bengaluru [KA]**, **Kolkata [WB]**, **Chennai [TN]**, **Hyderabad [TS]**, **Ahmedabad [GJ]**, **Pune [MH]**, **Jaipur [RJ]**, **Chandigarh [CH]**, **Lucknow [UP]**, and **Kochi [KL]**.
  - **Zero Horizontal Scrolling**: Clean multi-column layout with instant regional zone filtering (`All`, `North`, `South`, `West`, `East`).
- 📈 **Interactive 3-Mode Intraday Curve**:
  - 🌡️ **Temperature**: Continuous thermal spline with 4 daylight node markers (Morning, Afternoon, Evening, Night).
  - ☂️ **Precipitation**: Spline indicating hourly rain probability percentages.
  - 💨 **Wind Speed**: Velocity curve indicating breeze and gust speeds in km/h.
- 🔮 **Adaptive Tomorrow Outlook**:
  - Real-time weather condition translation for tomorrow with dynamically themed vector artwork (Clear Sun, Scattered Clouds, Rain Showers, Thunderstorms, Morning Mist).
  - High & Low temperature bounds, rain risk percentage, and meteorological summary.
- 📅 **7-Day Extended Outlook Modal**:
  - Full weekly forecast with thermal range gradient bars, maximum UV index, and rain likelihood.
- 🔍 **Predictive Global & Indian Search**:
  - Real-time geocoding with debounce, loading indicator, quick-select metro chips, clear button, and keyboard navigation.
- 📍 **GPS Geolocation**:
  - Instant one-tap reverse geocoding to retrieve your current location's live weather.
- 🌡️ **Dynamic °C / °F Unit Toggle**:
  - Instant conversion across all hero metrics, city cards, hourly cards, and modal forecast dialogs.

---

## 📁 Project Structure

```text
weather-app-j9gm/
├── assets/
│   ├── logo.png          # High-resolution StormSense Weather logo
│   ├── favicon.ico       # Converted icon for web browsers
│   └── favicon.png       # Web icon
├── favicon.ico           # Root favicon for standard web servers
├── index.html            # Standalone single-page web application
├── README.md             # Project documentation
└── .gitignore            # Git exclusion rules
```

---

## 🚀 Getting Started

### Prerequisites
No build steps or dependencies required. **StormSense Weather** runs directly in any modern web browser.

### Quick Launch
1. Clone or download this repository:
   ```bash
   git clone <YOUR_GITHUB_REPO_URL>
   cd weather-app-j9gm
   ```
2. Open `index.html` in your browser:
   - On Windows: Double-click `index.html` or run `start index.html` in PowerShell.
   - On macOS: Run `open index.html` in Terminal.
   - On Linux: Run `xdg-open index.html`.

Or serve it with any local development server:
```bash
# Using Python
python -m http.server 3000

# Using Node.js npx
npx serve .
```

---

## 🛠️ Tech Stack

- **HTML5 & Vanilla JavaScript**: Zero runtime overhead, clean DOM manipulation, and asynchronous API calls.
- **Tailwind CSS**: Utility-first CSS framework configured with custom Material Design color tokens and typography scales.
- **Google Material Symbols & Plus Jakarta Sans**: Clean iconography and typography.
- **Open-Meteo Weather API**: Free, high-accuracy global forecast without API keys required.
- **BigDataCloud Reverse Geocoding API**: Fast, client-side GPS reverse geocoding.

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
