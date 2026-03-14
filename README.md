**🌡️ Temperature-Based Automatic Fan System using NodeMCU and DHT11**

An IoT-based environmental monitoring system that measures temperature and humidity using a DHT11 sensor and automatically controls a fan using a relay module.

The system uses NodeMCU (ESP8266) to send real-time sensor data to the Blynk IoT platform, allowing users to monitor environmental conditions remotely.

When the temperature crosses a predefined threshold (30°C in this project), the system automatically turns ON the fan. When the temperature drops below the threshold, the fan turns OFF automatically.

**✨Features**

Real-time temperature monitoring

Real-time humidity monitoring

Automatic fan control based on temperature

IoT-based remote monitoring using Blynk

Serial monitoring for debugging

Energy-efficient automation

**🛠 Technologies Used**

🔌 Hardware

NodeMCU (ESP8266)

DHT11 Temperature and Humidity Sensor

Relay Module

Fan

Breadboard

Jumper Wires

💻 SoftwareSoftware

Arduino IDE

Blynk IoT Platform

ESP8266 WiFi Library

DHT Sensor Library




**🧠 System Architecture**

Sensor → NodeMCU → Blynk Cloud → Mobile Dashboard
↓
Relay Module → Fan Control


**⚙️ How It Works**

1) The DHT11 sensor measures temperature and humidity.

2) NodeMCU reads the sensor data and sends it to the Blynk cloud.

3) If the temperature exceeds 30°C, the relay is activated and the fan turns ON.

4) If the temperature drops below 30°C, the fan turns OFF.

5) Users can monitor temperature and humidity in the Blynk mobile app.
   

**☁️ Blynk Setup and Configuration**

1) Create a template in the Blynk Console with hardware set as ESP8266 and connection type WiFi.

2) Add Datastream V0 (Virtual Pin) to send temperature data from the sensor.

3) Add Datastream V1 (Virtual Pin) to control the fan through the relay.

4) Create a device from the template, which generates the Blynk Authentication Token.

5) Add the Template ID, Template Name, and Auth Token in the Arduino code.

6) Connect the ESP8266 to WiFi and the Blynk cloud using the Blynk library.

7)  the Blynk mobile app, create a dashboard for the project.

8) Add a Gauge widget connected to V0 to display temperature readings.

9) Add a Button widget connected to V1 to control the fan (relay ON/OFF).

10) The ESP8266 sends temperature data to Blynk and receives commands to switch the fan through the relay.

**>📱Blynk Dashboard Output**
 
 This dashboard shows the real-time temperature and humidity values received from the DHT11 sensor through NodeMCU.
 <img width="1918" height="967" alt="Image" src="https://github.com/user-attachments/assets/eb8a701b-2694-408d-85a7-cf6373a375db" />

**💻 Software Implementation**
Arduino Code

This section contains the embedded C code used to program the NodeMCU using Arduino IDE.

The code reads sensor data from the DHT11 sensor, sends the values to the Blynk cloud, and controls the relay module based on the temperature threshold.

 ![Image](https://github.com/user-attachments/assets/18e9e90a-21e2-4907-923f-cf478ea8660b)

![Image](https://github.com/user-attachments/assets/26ab544b-c4c0-49ca-89b8-3a43889199e9)

![Image](https://github.com/user-attachments/assets/f05a6c03-2eae-44e4-89f5-749dccc45bc3)

**📊 System Output**
The following images show the working output of the system, including the Blynk dashboard readings and real-time sensor monitoring.

 ![Image](https://github.com/user-attachments/assets/5c82ccec-d678-4b7d-86d0-985301a29c1a)

![Image](https://github.com/user-attachments/assets/a744f1ed-2973-45f3-a472-83754fdf1a1f)


**🚀 Future Improvements**

• 📡 Integration with more IoT sensors
• 🤖 Smart automation using AI/ML
• 📊 Cloud data analytics
• 🔔 Mobile notifications for temperature alerts

 
