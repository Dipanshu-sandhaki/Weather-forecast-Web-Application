Weather Forecast Application
A user-friendly weather forecast application built with HTML, CSS, and JavaScript. It fetches real-time weather data using the OpenWeatherMap API and displays information such as temperature, humidity, wind speed, and more.

Features
City Search: Enter a city name to get current weather details.
Dynamic Weather Icons: Displays appropriate icons based on weather conditions (e.g., clouds, rain, mist).
Error Handling: Provides an error message for invalid city names.
Responsive Design: Optimized for various screen sizes with a clean and modern UI.
Technologies Used
Frontend: HTML, CSS
Styling: Custom CSS for sleek and responsive design.
JavaScript: Handles API integration and dynamic UI updates.
API: OpenWeatherMap API for real-time weather data.
How It Works
Enter a city name in the input field.
Click the search button.
The app fetches weather data for the city and displays:
Temperature (in °C)
Humidity (in %)
Wind speed (in km/h)
Weather condition icon
If the city is not found, an error message is displayed.
Setup Instructions
Clone the Repository:
bash
Copy code
git clone <repository-url>
Open the Project:
Navigate to the project folder.
Open index.html in a browser to run the app.
Update API Key: Replace the placeholder apikey in index.html with your OpenWeatherMap API key:
javascript
Copy code
const apikey = "your-api-key-here";
File Structure
index.html – Contains the app’s structure and main functionality.
style.css – Defines the visual appearance of the application.
images/ – Stores weather-related icons for dynamic updates.
Future Enhancements
Add a feature for saving favorite cities.
Integrate a 7-day weather forecast.
Implement geolocation-based weather retrieval.
Author
Dipanshu Sandhaki
MCA Student| Aspiring Web Developer 

