
## App 
# App 

This app is a desktop application that provides a set of utility features for a user, including system information, weather information, clock, calendar, games, and more.

## Features

- **System Information:** Display information about the user's system, including node, version, system type, machine, and total RAM installed.

- **Battery Status:** Real-time display of battery percentage, plug status, and estimated time remaining.

- **Weather App:** Access accurate and up-to-date weather information for a specified location.

- **Clock:** Display a digital clock with hours, minutes, seconds, and AM/PM.

- **Calendar:** View and interact with a calendar to manage dates.

- **Games:** Includes a Ludo game for entertainment.

- **File Explorer:** Open the file explorer to navigate through directories.

- **Web Browsing:** Open Chrome or visit YouTube with a click of a button.

- **Music Player:** Play, pause, stop, and resume music, with the ability to open a folder to play songs.

- **Interest Calculator:** Calculate simple interest based on principal, rate, and time.

- **Stock Prediction:** Start a Streamlit app for stock prediction.

## Usage

1. Run the `main.py` script to launch the application.

2. Navigate through the various features using the provided buttons.

3. Explore system information, battery status, weather, clock, calendar, games, and utility apps.

## Dependencies

- Python 3.x
- Tkinter
- Psutil
- Pygame
- Screen Brightness Control
- Time
- Tkcalendar
- PyAutoGUI
- Streamlit
- Yfinance
- Prophet
- Plotly

## Note

### Music Player Usage:
- The Music Player feature allows users to play MP3 files from a designated folder. Therefore, to use this feature, users need to open folders which include mp3 files. 
# About Weather App

## Overview

The Weather App is a web application that provides users with accurate and up-to-date weather information for a specified location. With a user-friendly interface, support for both text and voice input, and personalized preferences, this app aims to offer a seamless weather experience.

## Table of Contents

- [Functional Requirements](#functional-requirements)
- [User Requirements](#user-requirements)
- [Data Flow Design](#data-flow-design)
- [Limitations](#limitations)
- [Installation](#installation)
- [Usage](#usage)
- [Note](#note)

## Functional Requirements

### User Interaction

- Users can interact with the system through a user-friendly web interface, enabling easy navigation and information retrieval.

### Location Input

- Users can input a location through a search bar (city name or coordinates) to retrieve weather information.
- The system should validate and handle various input formats gracefully.

### Voice Detection

- The system incorporates voice detection technology to process voice input and convert it into location data.

### Weather Information Display

- Real-time display of weather conditions, including temperature, humidity, wind speed, and overall conditions (e.g., clear, cloudy, rainy).
- Visual representation of weather conditions through icons.

### Forecast

- Users will have access to a weather forecast for upcoming days.
- Forecast details include daily high and low temperatures, precipitation probability, and wind trends.

### Unit Preferences

- Users can set their preferred units for temperature (Celsius or Fahrenheit) and other relevant metrics.
- The system can store and apply these preferences for future use.

### Data Accuracy and Timeliness

- Ensure weather information is accurate and regularly updated from a reliable weather API.
- Implement error handling for cases where data retrieval fails.

### Historical Weather Data

- Provide access to historical weather data for specified locations.

### Error Handling

- Implement meaningful error messages to guide users in case of input errors or system issues.
- Gracefully handle scenarios where the entered location is not found or the weather API is unavailable.

### Browser Compatibility

- Verify that the web app works consistently across popular web browsers (e.g., Chrome, Firefox, Safari).

## User Requirements

### Intuitive User Interface

- The user interface should support both text and voice input seamlessly, providing an intuitive experience.

### Easy to Use

- The web app should be easy for new users to use without extensive training.

### Voice Interaction

- Users should be able to interact with the app using voice commands for tasks such as searching for weather or setting preferences.

### User Feedback

- Provide clear feedback on user actions, enhancing the user's sense of control.

### User Preferences Understanding

- Design the app to understand and adapt to user preferences seamlessly, creating a personalized experience.

### Visual Appeal

- Design the interface with a visually appealing layout and elements for an enjoyable user experience.

### User Empowerment

- Empower users to customize their experience by adjusting preferences and settings according to their needs.

### Performance Expectations

- Set clear expectations regarding app performance, such as response times for searches and data updates.

### User Engagement

- Implement features that encourage user engagement, such as notifications for severe weather conditions or interesting events.

## Data Flow Design

### Components

#### User Interface (UI)

- Represents the web interface where users interact with the weather app.

#### Search Input

- User input component where users enter the location (city or coordinates) for weather information.

#### Voice Detection

- Processes voice input using voice detection technology and converts it into location data.

#### Weather Data Processor

- Validates entered locations and formats requests for the weather API.

#### Weather API

- External service providing real-time weather

## Limitations

### Data Accuracy

The accuracy of weather information is contingent on the reliability and precision of the external weather API. Inaccuracies in the API data may result in misleading forecasts.

### Voice Input Limitations

Voice input accuracy may be affected by ambient noise, accents, and variations in speech patterns. Users might experience limitations in voice command recognition.

### Limited Feature Set

Due to project constraints or technological limitations, certain desired features may not be feasible or fully implemented.

### Continuous Data Availability

The app's real-time weather data is dependent on the availability and continuous operation of the weather API. Any interruptions in data updates may affect the timeliness of information.

### Installation

1. Clone the repository:

   ```bash
   git clone 
## Authors

- Nguyễn Hoài Thanh
- Nguyễn Bảo Chi
- Nguyễn Thanh Tùng
- Trần Thị Phước Hải

