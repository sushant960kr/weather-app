
markdown
Copy
Edit
# Weather App

This is a simple weather application that allows users to check the current weather of any city by entering the city name. It uses the OpenWeatherMap API to fetch real-time weather data and displays temperature, humidity, wind speed, and a weather icon based on the current condition.

## Live Website

You can view the live version of this app here:  
👉 [https://weather-m1.netlify.app/](https://weather-m1.netlify.app/)

## About the Project

This project is built using:

- **HTML** for the structure of the webpage  
- **CSS** for styling and layout (with Flexbox and gradients)  
- **JavaScript** for logic and API integration  
- **OpenWeatherMap API** to get weather data  
- **Netlify** for deployment  

The app provides a clean and modern interface, and it works on both desktop and mobile devices.

## Features

- Search for any city to get current weather details
- Shows temperature in Celsius
- Displays humidity and wind speed
- Shows weather icons dynamically (sun, clouds, rain, etc.)
- Shows an error message if the city is not found
- Mobile responsive layout

## How It Works

1. The user types a city name into the input field and clicks the search button.
2. The app sends a request to the OpenWeatherMap API using the city name.
3. The response includes weather data like temperature, humidity, and wind speed.
4. The app updates the UI with this information and shows a relevant icon.

## How to Use Locally

If you want to run this project on your local computer:

1. **Clone the repository**

```bash
git clone https://github.com/your-username/weather-app.git
Open the project folder

bash
Copy
Edit
cd weather-app
Open the HTML file in your browser

You can simply double-click on the index.html file, or use a command like:

bash
Copy
Edit
start index.html  # For Windows
open index.html   # For macOS
Replace API Key (Optional)
The app uses a demo API key in the JavaScript file. You can get your own free API key from OpenWeatherMap:

Go to https://openweathermap.org/api

Sign up and get your API key

In the index.html file, replace this line:

js
Copy
Edit
const apiKey = "your_api_key_here";
Folder Structure
bash
Copy
Edit
weather-app/
├── images/              # Folder for icons
│   ├── cloud.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   ├── storm.png
│   ├── sun.png
│   └── weather (2).png
├── index.html           # Main HTML file
├── style.css            # Styling file
└── README.md            # This file
License
This project is open-source and available for use under the MIT License.
