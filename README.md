## Weather App

This Weather App allows users to search for the current weather and hourly forecast for any city. The app uses the OpenWeatherMap API to fetch weather data.

### Prerequisites

Before you begin, ensure you have met the following requirements:
- You have a web browser installed.
- You have an active internet connection.
- You have a text editor (like VSCode) to view and edit the code if necessary.

### Installation

1. **Clone the repository (if applicable)**:
   ```sh
   git clone <repository-url>
   ```
2. **Navigate to the project directory**:
   ```sh
   cd weather-app
   ```
3. **Ensure the following files are in the directory**:
   - `index.html`
   - `style.css`
   - `script.js`

### Usage

1. **Open the `index.html` file**:
   - You can open the file directly in your web browser by double-clicking it or by right-clicking and selecting "Open with [your browser]".

2. **Enter a city**:
   - Type the name of the city you want to get the weather information for in the input box.

3. **Click "Search"**:
   - Click the "Search" button to fetch and display the current weather and the hourly forecast for the next 24 hours (in 3-hour intervals).

### Project Structure

- `index.html`: The main HTML file that includes the structure of the web page.
- `style.css`: The CSS file for styling the app.
- `script.js`: The JavaScript file that handles the logic for fetching and displaying the weather data.

### HTML

The HTML file contains the basic structure of the app, including input fields, buttons, and containers for displaying weather information.

### CSS

The CSS file styles the web app, ensuring it looks presentable and user-friendly.

### JavaScript

The JavaScript file includes the following functions:
- `getWeather()`: Fetches the current weather and hourly forecast data from the OpenWeatherMap API.
- `displayWeather(data)`: Displays the current weather data.
- `displayHourlyForecast(hourlyData)`: Displays the hourly forecast data.
- `showImage()`: Makes the weather icon visible once it’s loaded.

### API Key

The app uses the OpenWeatherMap API. Replace with your own API key from OpenWeatherMap.

### Example

Here is how the app works:

1. Open the `index.html` file in your browser.
2. Enter "London" in the city input box.
3. Click "Search".
4. The app will display the current weather in London and the hourly forecast for the next 24 hours.

### Troubleshooting

- **Error Fetching Data**:
  - Ensure you have an active internet connection.
  - Check if the city name is spelled correctly.
  - Verify that your API key is valid and has not exceeded its usage limits.



