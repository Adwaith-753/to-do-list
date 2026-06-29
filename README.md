## 🌐 API

This project uses the **OpenWeather Current Weather API** to fetch real-time weather information.

### Built-in API Request by City Name

The application sends a request using the city name entered by the user.

**Request URL**

```http
https://api.openweathermap.org/data/2.5/weather?q={CITY_NAME}&units=metric&appid={API_KEY}
```

**Example**

```http
https://api.openweathermap.org/data/2.5/weather?q=Kochi&units=metric&appid=YOUR_API_KEY
```

The API returns current weather information including:

* 🌡️ Temperature
* 🌤️ Weather condition
* 💧 Humidity
* 🌬️ Wind speed
* 📍 City name
* 🌍 Country
* ☁️ Weather icon information

**API Documentation**

https://openweathermap.org/current
