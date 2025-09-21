# weather-analysis
Command-Line Weather App 🌦️
A simple Python script that fetches and displays the current weather for a specified city using the OpenWeatherMap API.

Features
Fetches real-time weather data for any city.

Displays key information: temperature, humidity, pressure, and a general description.

Handles common errors like invalid city names or network issues.

Prerequisites
Before you begin, ensure you have the following installed:

Python 3.x

The requests library

Setup & Installation
Follow these steps to get the application running.

Clone the repository or download the weather.py script.

Install the required Python library:
Open your terminal or command prompt and run the following command:

Bash

pip install requests
Get an API Key:
This project requires a free API key from OpenWeatherMap.

Sign up for a free account at openweathermap.org.

Navigate to the "API keys" section in your user profile.

Copy the generated API key.

Add your API key to the script:
Open the weather.py file and replace the placeholder YOUR_API_KEY with the key you just copied.

Python

# Find this line in the script
API_KEY = "YOUR_API_KEY"
Usage
To run the application, navigate to the project directory in your terminal and execute the script:

Bash

python weather.py
The program will then prompt you to enter a city name.

Example
$ python weather.py
Enter city name: Coimbatore

--- Weather in Coimbatore ---
Temperature: 26.1°C
Humidity: 88%
Pressure: 1011 hPa
Description: Light Rain
--------------------------
