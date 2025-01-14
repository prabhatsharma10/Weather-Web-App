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
 


step to call api : 
1. Go to the openweathermap.org and create an account.
2. Go "https://home.openweathermap.org/" --> copy API Keys : 95ce995b778b2aae251663c49ad6d892
3. Click on API in nav bar then Click Current Weather doc then go to API Built-in API request by city_name --> https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
4. https://api.openweathermap.org/data/2.5/weather?q={Lucknow}&appid={95ce995b778b2aae251663c49ad6d892}  if error occurs means api is not activated
