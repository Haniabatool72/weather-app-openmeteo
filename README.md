# 🌤️ Weather App

A clean and simple Weather App built using **HTML, CSS, and JavaScript**. It fetches real-time weather data for any city in the world using the free **Open-Meteo API** — no API key required.

## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Displays current temperature, "feels like" temperature, humidity, and wind speed
- 🔄 Toggle between Celsius (°C) and Fahrenheit (°F)
- ☀️🌧️⛈️ Dynamic weather icons based on real conditions
- ❌ Error handling for invalid city names
- 📱 Fully responsive design

## 🛠️ Built With

- **HTML5** – structure
- **CSS3** – styling and animations
- **JavaScript (Vanilla)** – functionality and API calls
- **[Open-Meteo API](https://open-meteo.com/)** – free weather + geocoding data (no API key needed)

## 🚀 Getting Started

### Prerequisites

Just a web browser with an internet connection. No installations, API keys, or dependencies required.

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Haniabatool72/weather-app-openmeteo.git
   ```
2. Navigate to the project folder
   ```bash
   cd weather-app-openmeteo
   ```
3. Open `index.html` in your browser

That's it — no build tools or servers needed!

## 📂 Project Structure

```
weather-app-openmeteo/
│
├── index.html      # Main HTML, CSS, and JS file
└── README.md        # Project documentation
```

## 🎯 How It Works

1. User enters a city name and hits search
2. The app calls Open-Meteo's **geocoding API** to convert the city name into latitude/longitude coordinates
3. Those coordinates are used to call the **forecast API**, which returns current weather data
4. Weather codes returned by the API are mapped to matching icons and descriptions
5. Temperature can be toggled between Celsius and Fahrenheit instantly (converted client-side)

## 🔮 Future Improvements

- [ ] Add 5-day forecast
- [ ] Add "Use my location" (geolocation) button
- [ ] Add search history / recent cities
- [ ] Add background changes based on weather condition (rainy, sunny, etc.)
- [ ] Dark mode toggle

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Haniabatool72/weather-app-openmeteo/issues).

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Hania Batool**
- GitHub: [@Haniabatool72](https://github.com/Haniabatool72)

---

⭐ If you like this project, give it a star on GitHub!
