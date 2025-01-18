# Weather Dashboard Project using S3, Python and OpenWeather API

## Overview

The **Weather Dashboard** is a Python-based application that provides real-time weather updates and displays weather information in a user-friendly dashboard format. It leverages external weather APIs to fetch data and present it efficiently.

## Features

- Fetches current weather data for specified locations.
- Displays temperature, humidity, wind speed, and weather conditions.
- Simple and customizable dashboard interface.

## Project Structure


```plaintext
src/
├── __init__.py            # Marks the directory as a Python package
├── weather_dashboard.py   # Main script for the weather dashboard
.gitignore                 # Specifies files and directories to be ignored by Git
README.md                  # Project documentation
requirements.txt           # List of dependencies for the project
```

## Requirements
Ensure you have Python installed on your machine. Install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage
1. **Clone the repository:**

```bash
git clone [<repository-url>](https://github.com/ameh0429/Open-Weather-API-Project.git)
cd Open-Weather-API-Project
```

## Install dependencies:

```bash
pip install -r requirements.txt
```
## Run the application:

```bash
python src/weather_dashboard.py
```
Follow the prompts to get weather data for your desired location.

## Configuration
- Obtain an API key from a weather data provider (e.g., OpenWeatherMap).
- Update the API key in the `weather_dashboard.py` script.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements or fixes.
