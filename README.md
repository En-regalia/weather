# Weather Application

Welcome to the Weather Application project! This application provides users with real-time weather information for locations worldwide.

## Overview

The Weather Application is designed to fetch weather data from a reliable API provider and present it to users in a user-friendly interface. 

## Projected Features

- **Real-Time Weather Data:** Fetches up-to-date weather information from a reliable API.
- **Search by Location:** Users can search for weather forecasts by city name or geographical coordinates.
- **Detailed Weather Information:** Displays current weather conditions, temperature, humidity, wind speed, and more.
- **Responsive Design:** The application is designed to be accessible and usable on various devices and screen sizes.

## Technologies Used

- **Frontend:** HTML, CSS, Javascript
- **Backend:** 
- **API:** OpenWeather
- **Deployment:** TBC

### OpenWeather API

- Please also note that dotenv module will need to be installed prior to use of this aplication.
- OpenWeather API key should be located in a local .env file. Defined as const ```Weather_API_Key```
- Details for the API used are [here for the 5day forcast](https://openweathermap.org/forecast5) and [here for the reverse geolocation](https://openweathermap.org/api/geocoding-api#:~:text=Reverse%20geocoding%20allows%20to%20get,see%20in%20the%20API%20response).
- individual API key can be generated [here](https://home.openweathermap.org/api_keys)

## User Stories

```
As a user
I need to be able to enter a custom location
So that I can view the weather in that location

As a user
I need to be able to use my current locaiton 
So that So that I can view the weather where I am
```

### Acceptance criteria
```
-Given- the user is viewing the website main page
-When- the user enters a location & presses the 'search' button
-Then- the weather data for the location entered sould display on the weather cards

-Give- the user is viewing the website main page
-When- the user presses the 'Use current location' button
-then- the weather data for the users current location should display on the weather card.

```
## Demo

_Not in place_

## Contributing

Contributions are welcome! If you'd like to contribute to the Weather Application project, please follow these guidelines:
- Fork the repository
- Create a new branch for your feature or bug fix
- Commit your changes
- Push your changes to your fork
- Submit a pull request


## Contact

If you have any questions or suggestions regarding the Weather Application project, please feel free to contact me.

Happy forecasting!
