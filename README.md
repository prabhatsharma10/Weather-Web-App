🌦️ Weather Web App

A simple yet functional weather web application built using HTML, CSS, and JavaScript, powered by the OpenWeatherMap API.
This app allows users to get the current weather conditions for any city around the world.

🚀 Features
- 🔍 Get real-time weather data by city name
- 🌡️ Display temperature, weather condition, and humidity
- 🌍 Supports global cities
- 📡 Uses asynchronous JavaScript with `fetch()` and `async/await`

🛠️ Technologies Used
- HTML, CSS, JavaScript (ES6+), OpenWeatherMap API

🔑 Requirements
To run this application, you’ll need the following :
1. API Key from [OpenWeatherMap] (https://openweathermap.org/)
2. *Base URL* to make requests
3. City Name input from the user

⚙️ How It Works
1. Build the API Request URL  
   You need :
   - Base URL: `https://api.openweathermap.org/data/2.5/weather`
   - Query Parameters:
     - `q`: City Name (e.g., `Lucknow`)
     - `appid`: Your API Key
     - `units`: `metric` (for temperature in Celsius)

   ```js
   const url = `https://api.openweathermap.org/data/2.5/weather?q=${cityName}&appid=${API_KEY}&units=metric`;


# Weather_Web_App
1. 3 things we need API key, URL, CityName
2. async function because await is used inside async function.
3. temp variable = url? cityname & api_key & units = metrics.  metrics --> unit of measurement
4. const "res" = await fetch(temp).    //"res" variable store response
   #fetch() -- This method starts the process of fetching a resource from a server.
5. what response you got. store in a "variable(data)" in json format.
6. res.ok --> means it is boolean property that indicated that weather an HTTP response was successfull
   if res.ok is true then call function
7. fetch all information using "variable(data)" for parameter you can check openweatherwebsite
