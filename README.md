# Weather App

#### This is a simple Weather App that allows users to input a city name and receive current weather information using the OpenWeatherMap API.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User-friendly interface to enter a city name.
- Displays weather information including:
  - Weather condition
  - Temperature
  - Feels like temperature
  - Humidity
  - Atmospheric pressure
- Background image changes based on the weather condition.

## Technologies Used

- **HTML** for structuring the web page.
- **CSS** and **Bootstrap** for styling the web page.
- **JavaScript** and **jQuery** for dynamic content and API interactions.

## Setup

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/melindas2/weatherApp.git
    ```
   
2. **Navigate to the project directory**:
    ```bash
    cd weather-app
    ```

3. **Obtain an OpenWeatherMap API key**:
    - Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) to get your free API key.

4. **Replace the API key in the JavaScript**:
    - Open `index.html` in a text editor.
    - Replace the placeholder API key (`YOUR_API_KEY_HERE`) with your actual OpenWeatherMap API key:
      ```javascript
      const APIKEY = "YOUR_API_KEY_HERE";
      ```

5. **Open `index.html` in your web browser**:
    - Simply double-click on the `index.html` file or open it through your web browser's file open dialog.

## Usage

1. **Enter a city name**:
   - Type the name of the city you want to get weather information for in the input field.

2. **Click the "Search" button**:
   - The app will fetch the weather data for the entered city and display it.

3. **View the results**:
   - Weather details such as weather condition, temperature, feels like temperature, humidity, and pressure will be displayed.
   - If the city is not found, an error message will be shown.

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that contains the structure of the web page.
- `style.css`: The CSS file for custom styles.
- `assets/images/`: Directory containing background images for different weather conditions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
