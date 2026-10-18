# EcoSense 🌱

EcoSense is an Arduino-based environmental monitoring project that measures soil moisture, temperature, and humidity. It displays the sensor readings on a dot-matrix display.

## Features

- Measures soil moisture.
- Reads temperature and humidity using a DHT11 sensor.
- Displays sensor readings directly on a dot-matrix display.
- Uses Arduino to process sensor data.
- Provides live readings while the project is running.

## Components Used

- Arduino board
- Soil moisture sensor
- DHT11 temperature and humidity sensor
- MAX7219 32×8 dot-matrix display
- Breadboard
- Jumper wires
- USB cable

See [BOM.csv](BOM.csv) for the bill of materials.

## Connections

| Component | Arduino Pin |
|---|---|
| Soil moisture sensor AO | A0 |
| DHT11 DATA | D2 |
| Dot-matrix DIN | D11 |
| Dot-matrix CS | D10 |
| Dot-matrix CLK | D13 |

## Build Image

![EcoSense Build](Screenshot%202026-10-18%20214320.png)

## Working Demo

[EcoSense Working Demo](20261018_211937.mp4)

## Challenges Faced

Initially, I tried getting the ESP module to work, but it did not work as expected. I continued with the Arduino setup and worked on the sensor connections until the project was functioning correctly.

After getting the sensors working, I added a dot-matrix display to show the readings and arranged the components to give the project a cleaner, more complete appearance.

## What I Learned

- Connecting sensors to Arduino.
- Reading temperature, humidity, and soil moisture data.
- Troubleshooting circuit connections.
- Integrating a dot-matrix display.
- Improving the presentation of a hardware project.

## Future Improvements

- Add wireless monitoring.
- Improve the enclosure and wiring.
- Add data logging for tracking environmental changes.

## Project Status

Working prototype. The Arduino, sensors, and dot-matrix display are working together to show the sensor readings.
