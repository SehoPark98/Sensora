# Sensora - IoT Smart Lighting System
Sensora is an ESP32-based IoT smart lighting system designed to respond to real-time environmental conditions and user input.

The system integrates ambient light, temperature/humidity, and capacitive touch sensors to automate lighting behavior while supporting remote environmental monitoring.

## Features

- Automatic lighting based on ambient light levels using an LDR sensor
- Touch-based brightness control using a CAP1188 capacitive touch sensor
- Temperature and humidity monitoring using a DHT20 sensor
- Real-time sensor processing using an ESP32 microcontroller
- Wi-Fi-based data transmission for Microsoft Azure IoT integration

## Hardware

- ESP32 microcontroller
- LDR (Light Dependent Resistor)
- DHT20 temperature and humidity sensor
- CAP1188 capacitive touch sensor
- LED
- Breadboard and jumper wires

## System Architecture

Sensora is organized into three main layers:

1. **Sensing Layer** – Collects ambient light, temperature, humidity, and touch input
2. **Processing Layer** – ESP32 processes sensor readings and controls lighting behavior
3. **Communication Layer** – Sends environmental data over Wi-Fi for cloud monitoring

## My Contributions

- Implemented LDR-based automatic lighting logic
- Implemented touch-based brightness control using the CAP1188 sensor
- Contributed to the ESP32 main processing loop
- Helped integrate sensor data with the cloud communication layer

## Technologies

`C++` `ESP32` `IoT` `Microsoft Azure` `Sensors` `Wi-Fi`

## Demo
[Watch the Sensora Demo Video](https://drive.google.com/file/d/1RKGYNkcutz6R-_y1VDcN0swi0SHR9A8F/view?usp=share_link)
