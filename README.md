# Weather API CLI

A simple command-line Python application to fetch real-time weather data using the OpenWeatherMap API.

## Setup

1. Get a free API key from https://openweathermap.org/api
2. Create a `config.py` file in the project root
3. Add your API key to `config.py`:
   ```python
   API_KEY = "your_api_key_here"
4. Install required packages:
   pip install requests
5. Run the app:
   python Request.py

Features
- Get current weather by city name
- Displays temperature, humidity, and weather conditions
- Secure API key handling using .gitignore

Project Structure
weather-API-CLI/
├── Request.py      # Main application file
├── config.py       # API key - not tracked by git
└── .gitignore      # Ignores config.py

Security Note
The config.py file is listed in .gitignore and will not be pushed to GitHub. Never commit API keys to public repositories.
