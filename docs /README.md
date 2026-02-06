# Project Documentation

This folder contains the main documentation assets for the **IoT Obstacle Detection and Avoidance System**.

## System Architecture
The system is built around an ESP32 microcontroller that collects data from multiple sensors and transmits it to a cloud platform for monitoring.

![System Architecture](architecture.png)

## Simulation Environment
The project was simulated using **Wokwi** to validate circuit connections and logic before hardware implementation.

![Wokwi Simulation](wokwi-simulation.png)

## Cloud Dashboard
Sensor data is sent to **ThingSpeak** using Wi-Fi and visualized through a real-time dashboard.

![ThingSpeak Dashboard](thingspeak-dashboard.png)

## Notes
- The system focuses on obstacle detection and monitoring rather than full autonomous navigation.
- Power consumption and network reliability were considered during design.
