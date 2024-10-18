![Application screenshot](./public/screenshot.png)

🌦️ Weather Forecasting App
Stay updated with the latest weather forecasts for any city around the world. Our app provides detailed weather predictions, including 3-hour intervals, for the upcoming 5-6 days.

Live Demo

🚀 Quick Start Guide
Prerequisites:
Ensure Node.js and npm are installed on your system.
Obtain an API key from OpenWeatherMap. After signing up, you can find your API key in the account dashboard.
Setup Instructions:
Clone the Repository:

bash
Copy code
git clone https://github.com/Amin-Awinti/the-weather-forecasting.git
Install Dependencies: Navigate to the project folder and run:

bash
Copy code
npm install
Configure API Key:

In the src/api/OpenWeatherService.js file, replace WEATHER_API_KEY with your OpenWeatherMap API key.
Run the App:

bash
Copy code
npm start
Your local instance of the Weather Forecasting App will be live!

🌟 Features
City-based Search: Input any city name to retrieve weather information.
Detailed Forecasts: View 3-hour interval forecasts over the next 5-6 days.
Responsive UI: Built with Material-UI for sleek and accessible design.
🛠️ Technologies & Libraries
Front-end Framework: React.js
UI Library: Material-UI
For a full list of dependencies, see the package.json file.

🔮 Upcoming Features
Here’s what’s in store for future updates:

 Add Styled-components for better component-level styling.
 Migrate the codebase to TypeScript.
 Implement Unit Testing for better code reliability.
 Automatically detect user location using the Geolocation API.
 Temperature Conversion: Support for Celsius/Fahrenheit toggling.
 Dark/Light Mode for personalized UI themes.
📂 File Structure
src/api/OpenWeatherService.js: Handles all backend API calls related to weather data.
