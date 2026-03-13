# Temperature-Based-Automatic-Fan-System-NodeMCU-DHT11-
Real-time temperature and humidity monitoring using IoT. Fan control is automated based on temperature conditions.
This project is an IoT-based environmental monitoring system that measures temperature and humidity using a DHT11 sensor and automatically controls a fan using a relay module.

The system uses NodeMCU (ESP8266) to send real-time sensor data to the Blynk IoT platform, allowing users to monitor environmental conditions remotely.

When the temperature crosses a predefined threshold (26°C in this project), the system automatically turns ON the fan. When the temperature drops below the threshold, the fan turns OFF automatically.

-> Features

Real-time temperature monitoring

Real-time humidity monitoring

Automatic fan control based on temperature

IoT-based remote monitoring using Blynk

Serial monitoring for debugging

Energy-efficient automation


->Technologies Used

-> Hardware

NodeMCU (ESP8266)

DHT11 Temperature and Humidity Sensor

Relay Module

Fan

Breadboard & Jumper Wires

-> Software

Arduino IDE

Blynk IoT Platform

ESP8266 WiFi Library

DHT Sensor Library




->System Architecture

Sensor → NodeMCU → Blynk Cloud → Mobile Dashboard
↓
Relay Module → Fan Control

