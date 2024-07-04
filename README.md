# Weather App

This is a simple weather application that allows users to search for and view the current weather conditions of a specified city. The application fetches weather data from the OpenWeatherMap API and displays it in a user-friendly interface.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [API Key](#api-key)
- [Credits](#credits)
- [File Structure](#file-structure)
  
## Features

- Search for a city's weather by entering the city name.
- Display current temperature, humidity, wind speed, and weather conditions.
- Error handling for invalid city names.
- Dynamic weather icons based on weather conditions.

## Technologies

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Setup

To set up and run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/JigarHingu/weather_app.git

2. Navigate to the project directory:

   ```sh
   cd weather_app

3. Open `index.html` in your preferred web browser.

## Usage

1. Enter the name of the city you want to check the weather for in the search box.
2. Click the search button (magnifying glass icon).
3. View the weather details displayed on the card.

## API Key

The weather app uses the OpenWeatherMap API to fetch weather data. You need an API key to access the data.

1. Sign up at OpenWeatherMap to get your API key.
2. Replace the `apikey` variable in the `index.html` file with your API key:

   ```sh
   const apikey = "your-api-key-here";
 
## Credits

- Weather data provided by [OpenWeatherMap].
- Icons from [source of your icons if applicable].
- Project inspired by various online tutorials and weather app examples.

   ```sh
   Make sure to replace placeholder text like `your-api-key-here` with actual values. This `README.md` file provides a comprehensive guide to understanding, setting up, and using the weather app.

## File Structure

 ```sh
 weather-app/
 │
 ├── weather app images/
 │   ├── search.png
 │   ├── rain.png
 │   ├── humidity.png
 │   ├── wind.png
 │   ├── clouds.png
 │   ├── clear.png
 │   ├── drizzle.png
 │   ├── mist.png
 │
 ├── index.html
 ├── style.css
 └── README.md

