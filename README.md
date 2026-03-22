# RTOS-Based Smart Storage Monitoring System

## 📌 Overview
This project is developed using ESP32 and FreeRTOS to monitor storage conditions such as door status, temperature, and humidity in real-time.

## ⚙️ Features
- Door status detection using Ultrasonic Sensor (HC-SR04)
- Temperature & humidity monitoring using DHT22
- LED indicators:
  - Blue → Door Open
  - Red → High Temperature/Humidity
  - Green → Normal Condition
- LCD display for real-time status
- RTOS task scheduling for efficient performance

## 🛠️ Hardware Used
- ESP32 NodeMCU
- DHT22 Sensor
- HC-SR04 Ultrasonic Sensor
- LCD Display
- LEDs (Red, Green, Blue)
- Resistors & Jumper wires

## 🧠 RTOS Concept Used
- Task Scheduling
- Multi-tasking (Sensor + Display + Alerts)
- Delay handling using RTOS

## 📷 Project Output

### Door Open Detection
![Door Open](images/door_open.jpg)

### High Temperature Alert
![Temp Alert](images/temp_alert.jpg)

### Normal Condition
![Normal](images/normal_condition.jpg)

## 📄 Documentation
Full report available here:
[Download Report](docs/report.pdf)

## 👨‍💻 Author
Naveen karan R S
