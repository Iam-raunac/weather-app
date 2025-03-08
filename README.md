# Weather App

A simple weather application built using HTML, CSS, and JavaScript. It allows users to search for a city's current weather conditions using the OpenWeather API.

## Features
- Search for the current weather of any city.
- Displays temperature, weather description, cloud percentage, humidity, and pressure.
- Shows country flag based on the searched city's location.
- User-friendly interface with smooth animations.
- Error handling for invalid city names.

## Technologies Used
- HTML
- CSS
- JavaScript (Fetch API)
- OpenWeather API
- FlagsAPI
- Font Awesome Icons

## Setup and Usage

1. Clone this repository:
   ```sh
   git clone https://github.com/your-repository/weather-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd weather-app
   ```
3. Open `index.html` in a web browser.
4. Enter a city name in the search box and click the search button to fetch the weather data.

## API Configuration
This app uses the OpenWeather API. To make it work, you need an API key from OpenWeather.

1. Get your API key from [OpenWeather](https://openweathermap.org/api).
2. Replace the existing API key in `app.js`:
   ```js
   let id = 'YOUR_API_KEY';
   ```

## File Structure
```
weather-app/
│── index.html  # Main HTML file
│── style.css   # Styling file
│── app.js      # JavaScript logic for fetching weather data
│── README.md   # Project documentation
```

## Demo
You can try the live version here: [Weather App Live](#) *(Add the link if deployed)*

## Screenshots
*(Add screenshots of the app interface here)*

## License
This project is open-source and available under the MIT License.

## Author
Developed by [Your Name] *(Replace with your name or GitHub username)*

Happy coding! 🚀


