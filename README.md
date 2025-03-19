# Weather App

This is a simple weather application that allows users to check the current weather of any city using the OpenWeather API.

## Features
- Fetches real-time weather data from OpenWeather API
- Displays temperature, humidity, and wind speed
- Responsive and user-friendly UI
- Shows an error message for invalid city names

## Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeather API

## Usage
1. Enter a city name in the search box.
2. Click the search button to fetch weather details.
3. View the temperature, humidity, and wind speed.
4. If the city name is invalid, an error message will be displayed.

## File Structure
```
weather-app/
├── style.css
├── script.js
├── Weather App.html
├── images/ (contains weather icons like rain.png, clear.png, etc.)
```

## API Key Configuration
- The application uses an API key from OpenWeather API.
- To use your own API key, replace the existing key in `script.js`:
  ```js
  const apiKey = "YOUR_API_KEY";
  ```

## Contributing
If you'd like to contribute, feel free to fork the repository and submit pull requests.
