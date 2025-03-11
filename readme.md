Pepper's Ghost Weather Display (CSS Rendering is broken!)

This project creates a Pepper's Ghost holographic display for mobile devices, dynamically rendering real-time weather information from the Open-Meteo API. The text is duplicated and rotated to display correctly on a holographic pyramid placed over a smartphone screen.

Features

Real-time Weather Data: Fetches current temperature and conditions from Open-Meteo.

Four-Pane Display: Correctly positioned text for Pepper's Ghost effect on a phone pyramid.

Mobile Optimized: Designed to work properly on smartphone screens.

Setup

Clone this repository or copy the HTML file.

Open the index.html file in a mobile web browser.

Place a holographic pyramid on top of your phone screen.

View the Pepper's Ghost effect in action!

How It Works

The Open-Meteo API fetches the weather for San Francisco (default).

The weather text is rendered four times: top, bottom (mirrored), left (rotated 90°), and right (rotated -90°).

The text overlays are positioned to align with the holographic reflection, creating the illusion of floating text.

Customization

Change the latitude and longitude in the API call inside fetchWeather() to get weather for a different location.

Adjust font size and positioning in the CSS for different phone screens.

Dependencies

This project is pure HTML, CSS, and JavaScript, so no external libraries are required.

Credits

Uses the Open-Meteo API for weather data.

Inspired by Pepper's Ghost effect for holographic displays.