GITHUB LINK =     https://github.com/Ayushgreat/Weather-Forecast.git

      **GITHUB LINK = https://github.com/Ayushgreat/Weather-Forecast.git
**
# Weather-Forecast
 The project is structured into seven key sections, each contributing to the overall development process. It starts with setting up the project structure, integrating a weather API, and designing a user-friendly interface.

 project  structure 
weather-forecast-app/
├── index.html
├── styles/
│   └── output.css
├── scripts/
│   └── script.js
├── README.md
└── .gitignore

1. Set Up Project Structure 
Task: Create the basic project structure.
Steps:
Folder Structure: Create the necessary folders and files:
index.html
styles.css (although you'll primarily use Tailwind CSS)
script.js
assets/ (for storing images, icons, etc.)
Tailwind CSS Setup:
Install Tailwind CSS using npm or directly include it via a CDN in your index.html.
Version Control:
Initialize a Git repository and create a .gitignore file.
Commit the initial setup.
2. Integration with Weather API 
Task: Research and select a weather API.
Steps:
API Selection: Choose an API like OpenWeatherMap or WeatherAPI based on your needs (e.g., free tier limits, data availability).
API Key: Register and obtain an API key.
Integration:
Write a function in script.js to fetch data from the API.
Test the API call using a sample city or coordinates.
3. User Interface (UI) Design
Task: Design a responsive user interface.
Steps:
HTML Structure:
Create the basic layout in index.html.
Use semantic HTML elements.
Tailwind CSS:
Apply Tailwind classes for styling.
Responsive Design:
Test and adjust the layout for desktop, iPad Mini, and iPhone SE using media queries or Tailwind’s responsive utilities.
Icons:
Use Font Awesome for icons in the UI.
4. Location-Based Forecast (100 marks)
Task: Implement various features for location-based forecasts.
Steps:
City Search:
Add an input field and search button in index.html.
Use JavaScript to capture the search query and fetch weather data.
Current Location Search:
Use the Geolocation API to get the user's current location and fetch weather data.
User Interaction:
Add buttons, dropdowns, and input fields.
Use event listeners to handle these interactions.
Recently Searched Cities:
Implement a dropdown menu using local/session storage.
Input Validation:
Validate input fields to ensure non-empty and valid inputs.
Weather Display:
Display temperature, humidity, wind speed, and appropriate icons based on weather conditions.
5. Extended Forecast Display 
Task: Display a multi-day weather forecast.
Steps:
Display Data:
Organize the forecast into a visually appealing format (date, icon, temperature, wind, humidity).
6. Error Handling and Validation 
Task: Handle errors gracefully.
Steps:
Error Handling:
Implement try-catch blocks in your API calls.

