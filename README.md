# Weather App

A simple React-based weather application that allows users to search for the current weather conditions of any city worldwide. The app fetches real-time weather data from the OpenWeatherMap API and displays temperature, humidity, wind speed, and weather icons.

## Features

- Search for any city to get current weather information.
- Displays temperature in Celsius.
- Shows weather condition icons dynamically based on the weather.
- Displays additional details such as humidity, wind speed, latitude, and longitude.
- Responsive and clean user interface.
- Loading and error handling states.
- City not found notification.

## Technologies Used

- React (with hooks)
- OpenWeatherMap API
- CSS for styling

## How It Works

- User enters a city name in the search input.
- On pressing Enter or clicking the search icon, the app fetches weather data from OpenWeatherMap API.
- The app updates the UI with the fetched data including temperature, location, humidity, wind speed, and weather icon.
- If the city is not found, a notification is shown.
- Loading and error states are handled gracefully.

## Usage

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the app locally using `npm run dev` (or the appropriate start command).
4. Open the app in your browser and search for any city to see the weather.

## Screenshot

![Weather App Screenshot](src/assets/screenshots/Screenshot%202025-08-12%20195222.png)