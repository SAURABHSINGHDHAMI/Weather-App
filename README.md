# Weather App :partly_sunny:

A simple and elegant Python Weather Application that displays the current weather data of a specified city.

<p align="center">
  <img src="https://github.com/SAURABHSINGHDHAMI/Weather-App/blob/main/sample/delhi_weather_screenshot.jpg" />
</p>

## About

The Weather App is a Python-based application that utilizes the OpenWeatherMap API to fetch and display real-time weather information for a given city. It provides essential weather details such as temperature, weather condition, wind speed, sunrise, sunset, and more.

## Features

- Retrieve and display current weather data.
- Simple and intuitive user interface.
- Real-time updates from OpenWeatherMap API.

## Sample

```python
# weather.py

import tkinter as tk
import requests
import time

def getWeather(canvas):
    # ... (existing code)

canvas = tk.Tk()
canvas.geometry("600x500")
canvas.title("Weather App")

# ... (existing code)

canvas.mainloop()
```
## Open Weather API

This application uses the [OpenWeatherMap API](https://openweathermap.org/) to fetch weather data.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Weather-App.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/) and replace `'YOUR_API_KEY'` in the `weather.py` file with your actual API key.

## Usage

1. Run the application:
    ```bash
    python weather.py
    ```

2. Enter the desired city in the text field and press Enter to fetch the weather information.
