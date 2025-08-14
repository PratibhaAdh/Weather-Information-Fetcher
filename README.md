# Weather-Information-Fetcher


A sleek and intuitive desktop application built with **Python** and **Tkinter**, fetching real-time weather data using the **OpenWeatherMap API**.

---

## Features

- **Worldwide City Support** – Fetches weather by city name from around the globe.
- **Detailed Weather Data** – Displays temperature, humidity, wind speed, weather description.
- **Error Handling** – Robust handling of invalid city inputs and network issues.
- **Clean GUI** – Simple, user-friendly interface using Tkinter.
- **Customizable & Extensible** – Easy for beginners to adapt or extend.

---

## Screenshot



---

## Getting Started

### Prerequisites

Ensure you have **Python 3** installed. Then install dependencies:

```bash
pip install -r requirements.txt
```

Configuration: API Key

Sign up at OpenWeatherMap and get an API key.

Open weather_app.py and find the line:

API_KEY = "YOUR_API_KEY"


Replace "YOUR_API_KEY" with your actual key, or store it securely in an environment variable and modify the script accordingly.



---

Running the App
python weather_app.py

The GUI window will launch. Enter a city and click “Get Weather” to see live data.
