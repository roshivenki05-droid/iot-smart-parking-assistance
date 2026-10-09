# Project Details

## Project Title
IoT-Based Car Detection and Parking Assistance System

## Problem Statement
Parking in confined spaces can make it difficult to judge the distance between a vehicle and nearby obstacles. This project aims to provide distance-based assistance through ultrasonic sensing and an audible alert.

## Proposed Solution
Two HC-SR04 ultrasonic sensors measure distances to nearby objects. An ESP8266 NodeMCU processes the readings and controls a buzzer according to programmed conditions. Blynk IoT is planned for remote monitoring.

## Hardware Components
- ESP8266 NodeMCU
- Two HC-SR04 ultrasonic sensors
- Buzzer
- Connecting wires and suitable power supply

## Software and Cloud Tools
- Arduino IDE
- Blynk IoT
- GitHub

## System Workflow
1. Ultrasonic sensors measure distances to nearby objects.
2. The ESP8266 processes the readings.
3. The programmed logic determines the required alert.
4. The buzzer responds according to the configured conditions.
5. Sensor data can be sent to Blynk when cloud connectivity is implemented.

## Planned Blynk Datastreams
- V0: Sensor 1 Distance (cm)
- V1: Sensor 2 Distance (cm)
- V2: Parking Status
- V3: Buzzer Status

## Project Status
The project documentation and cloud dashboard configuration are in progress. Hardware operation, firmware integration, and live telemetry must be verified before being reported as functional.

## Future Improvements
- Live cloud monitoring
- Distance history and visualisation
- Testing under different parking conditions
