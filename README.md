# IoT-Based Car Detection and Parking Assistance System

## Overview
This project aims to develop an IoT-based parking assistance system using an ESP8266 NodeMCU, two HC-SR04 ultrasonic sensors, and a buzzer. The system is designed to measure distances to nearby objects and provide an audible alert to assist with parking manoeuvres.

## Objectives
- Detect nearby objects using ultrasonic sensors.
- Process distance measurements using the ESP8266.
- Activate a buzzer according to programmed distance conditions.
- Prepare a cloud dashboard using Blynk IoT for remote monitoring.

## Hardware Components
- ESP8266 NodeMCU
- 2 × HC-SR04 ultrasonic sensors
- Buzzer
- Connecting wires and suitable power supply

## Software and Cloud Tools
- Arduino IDE for firmware development
- Blynk IoT for the cloud dashboard
- GitHub for source code and documentation

## System Workflow
1. The ultrasonic sensors measure distances to nearby objects.
2. The ESP8266 processes the measurements.
3. The firmware applies the programmed detection and alert logic.
4. The buzzer provides an audible alert when the configured conditions are met.
5. When cloud connectivity is implemented, sensor data can be sent to Blynk for dashboard monitoring.

## Cloud Dashboard
The planned Blynk dashboard includes:
- Sensor 1 distance (V0)
- Sensor 2 distance (V1)
- Parking status (V2)
- Buzzer status (V3)

## Project Status
The cloud dashboard structure has been configured. Hardware integration, firmware connectivity, and live telemetry must be verified before they can be reported as operational.

## Contributors
Add the names and contributions of the project team members here.

## Future Improvements
- Live cloud telemetry and historical sensor charts.
- Improved parking-status logic and alert handling.
- Testing under different distances and parking conditions.
-
