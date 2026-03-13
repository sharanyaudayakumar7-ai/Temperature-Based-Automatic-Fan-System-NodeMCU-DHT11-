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



* How It Works

1.The DHT11 sensor measures temperature and humidity.

2.NodeMCU reads the sensor data every 2 seconds.

3.The values are sent to the Blynk cloud platform.

4.If the temperature exceeds 26°C, the system:

5.Activates the relay

6.Turns ON the fan

7.If the temperature is below 26°C, the fan turns OFF.

8.Users can monitor temperature and humidity in the Blynk mobile app.

📱Blynk Dashboard Output
 
 This dashboard shows the real-time temperature and humidity values received from the DHT11 sensor through NodeMCU.
 
<img width="1912" height="915" alt="Blynk console" src="https://github.com/user-attachments/assets/23963bb9-a111-4713-a3e1-97380b98372a" />
