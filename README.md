Spotify Display (ESP32 + OLED)

## Overview
This project is a compact IoT device that displays the currently playing Spotify track in real time using an ESP32 and a 0.96" OLED display. It also allows basic playback control using physical buttons.

## Features
- Displays song title and artist
- Connects to WiFi
- Uses Spotify API for real-time data
- Physical buttons for play/pause, next, and previous

## Hardware Components
- ESP32 Development Board
- 0.96" OLED Display (SSD1306, I2C)
- 3x Tactile Push Buttons
- Jumper wires
- Breadboard

## Wiring
- OLED SDA → GPIO21
- OLED SCL → GPIO22
- Buttons → GPIO18, GPIO19, GPIO23 to GND

## How It Works
The ESP32 connects to WiFi and authenticates with Spotify. It fetches the currently playing track and displays it on the OLED screen. Buttons allow user interaction for playback control.
