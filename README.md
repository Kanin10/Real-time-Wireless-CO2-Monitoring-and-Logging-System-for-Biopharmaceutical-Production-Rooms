# Real-time-Wireless-CO2-Monitoring-and-Logging-System-for-Biopharmaceutical-Production-Rooms
IoT-based CO2 monitoring system using ESP32, SCD41, Node-RED , and Telegram
> **🚧 Status: Work in Progress (Active Development)**

An advanced IoT-based environmental monitoring system designed for biopharmaceutical cleanrooms. This senior project utilizes an ESP32 microcontroller and an SCD41 sensor to continuously measure CO2 levels. It features live data visualization via **Node-RED** and **Blynk**, alongside a sophisticated multi-tier physical and digital alert system.

## 🌟 Key Features
* **Dual-Platform Dashboards:** Real-time CO2 data visualization and monitoring through Node-RED and Blynk IoT platforms.
* **Smart Multi-Tier Alert System:**
  * 🟢 **Normal Operation:** Green LED remains ON, indicating the system is active and air quality is optimal.
  * 🔴 **Warning Level (CO2 > 800 ppm):** Red LED turns solid ON, and an initial warning notification is instantly sent via Telegram.
  * 🚨 **Critical Level (CO2 > 1100 ppm):** Red LED blinks rapidly, a high-pitch Buzzer sounds, and an urgent critical alert is dispatched via Telegram.
* **Custom Enclosure:** System is safely housed in a custom 3D-printed casing designed specifically for optimal airflow and sensor accuracy.

## 🛠️ Hardware & Components
* **Microcontroller:** ESP32
* **Sensor:** SCD41 (High-accuracy CO2 sensor)
* **Indicators:** Green LED, Red LED, Active Buzzer
* **Enclosure:** Custom 3D-printed CAD design in Solidworks
* **Dashboards:** Node-RED, Blynk

## 📊 System Architecture & Logic Flow
1. The **SCD41** sensor continuously samples the ambient CO2 concentration.
2. The **ESP32** processes this data and transmits it wirelessly to the Node-RED and Blynk dashboards.
3. The system evaluates the CO2 levels against predefined thresholds (800 ppm and 1100 ppm) to trigger the appropriate hardware indicators (LEDs/Buzzer) and API requests (Telegram Bot).

## 📸 Project Showcase
**Work in Progress**

### IoT Dashboards
<img width="950" height="588" alt="image" src="https://github.com/user-attachments/assets/d4e0bfe8-75cd-4d2d-a87a-431f526c4eec" /> **Need to fix**


### Telegram Alert Demonstration
<img width="417" height="846" alt="image" src="https://github.com/user-attachments/assets/05e57dbc-6702-46c2-a2f0-edefe141f30b" />

---
## 📋 Project Roadmap (Current Progress)
- [x] System architecture and logic design
- [x] Component sourcing (ESP32, SCD41)
- [x] Node-RED and Blynk dashboard configuration
- [ ] Hardware assembly and 3D-printed casing integration
- [ ] Multi-tier alert testing (Telegram & Indicators)
- [ ] Final system calibration and stability test

## 🔒 Source Code
*Note: The full source code for this senior project is currently closed-source. However, I am fully prepared to discuss the system architecture, condition-based logic programming, and hardware integration in detail during a professional interview.*
