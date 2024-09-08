
# Weather App 🌦

This is a simple weather application built using HTML, CSS, and JavaScript. The app allows users to enter a city name and receive current weather details fetched from the OpenWeatherMap API.


## Features

- Get real-time weather information.
- Displays temperature, humidity, wind speed, and weather conditions.
- Background changes based on the weather conditions (e.g., sunny, cloudy, rainy).
- Responsive design to support various devices.


## Installation

01.Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/weather-app.git
```
02.Navigate to the project directory:
```bash
 cd weather-app
```
03.Open the project in your favorite code editor.


## Usage
01.Sign up at OpenWeatherMap and get an API key.

02.Open the script.js file and replace YOUR_API_KEY with the actual API key:
```js
const apiKey = 'YOUR_API_KEY';
```
03.Open index.html in your browser, and you're good to go!
## Project Structure
```plaintext
weather-app/
│
├── index.html         # The main HTML file for the weather app
├── style.css          # The CSS file to style the app
└── script.js          # JavaScript to handle API requests and user interactions
```
## API Reference

This app uses the OpenWeatherMap API to fetch weather data.

Example API Request:
```bash
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}

```
## Built With
01.HTML5

02.CSS3

03.JavaScript (ES6+)

04.OpenWeatherMap API
## Contributing

Contributions are always welcome!

Feel free to fork this repository and contribute to improve the app! Open an issue or submit a pull request.