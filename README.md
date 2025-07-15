# 🚦 Smart Traffic Control System using ESP32

An intelligent traffic control system built using ESP32, sensors, and actuators to automate signal behavior based on real-time traffic, weather, and environmental conditions.

## 📌 Overview

This project aims to optimize traffic flow and enhance road safety using a smart traffic system. It detects real-time traffic density, weather conditions, and ambient light levels to dynamically control traffic lights and alert systems. The system also displays messages to commuters and fetches live weather updates from the internet.

## 🧠 Features

- 🚘 **Traffic Density Monitoring**: Uses ultrasonic sensors to detect the number of vehicles at an intersection.
- 🌧️ **Weather-Aware Signaling**: Detects high humidity or rain and displays a **"SLOW DOWN"** warning.
- ☀️ **Automatic Street Light Control**: Turns street lights ON/OFF using a light sensor or live weather data.
- 📡 **Live Weather Updates**: Fetches temperature and weather information from the internet every 10 seconds.
- 🖥️ **OLED Display**:
  - Shows real-time humidity and temperature.
  - Displays contextual messages like "GO NOW", "STOP NOW", or weather conditions.
- 🔴🟡🟢 **LED Traffic Lights**: Simulates traditional traffic lights using color LEDs, adapting signal duration based on traffic.
- 🚨 **Gas Detection (MQ-2)**: Detects presence of smoke or flammable gases for safety monitoring.
