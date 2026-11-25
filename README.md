# Realistic Space Sensor Lab 🚀

A real-time IoT monitoring dashboard that fetches temperature and humidity data from an ESP32/ESP8266 through Firebase Realtime Database and displays it on a web frontend.

## Working Flow

```text
DHT Sensor
    ↓
ESP32 / ESP8266
    ↓
Firebase Realtime Database
    ↓
HTML, CSS & JavaScript Frontend
    ↓
Live Temperature & Humidity Display
```

## Features
- ESP32/ESP8266 sensor data integration.
- Firebase Realtime Database connectivity.
- Live temperature and humidity monitoring.
- Real-time graph using Chart.js.
- Animated space-themed background.
- CSV export (planned).
- Clear chart functionality.

## Firebase Database Structure

```json
{
  "sensor": {
    "temperature": 28.5,
    "humidity": 65
  }
}
```

## Technologies Used
- ESP32 / ESP8266
- DHT11 / DHT22 Sensor
- Firebase Realtime Database
- HTML, CSS, JavaScript
- Chart.js
- HTML5 Canvas

## Setup
1. Connect the DHT sensor to the ESP32/ESP8266.
2. Configure the Firebase project and Realtime Database.
3. Program the ESP to upload temperature and humidity readings to Firebase.
4. Add Firebase configuration to the frontend.
5. Open `index.html` using a browser or VS Code Live Server.

## Author
**Sahil Chavan**
