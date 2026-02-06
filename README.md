
# IoT Obstacle Detection and Avoidance System

This project presents an **IoT-based obstacle detection and monitoring system** designed and simulated as part of an Internet of Things (IoT) course project.

The system focuses on collecting real-time environmental data, processing it using an ESP32 microcontroller, and transmitting the data to a cloud platform for visualization and remote monitoring.

---

## Project Overview

The system detects obstacles and motion using multiple sensors and provides visual indicators for system status. Sensor data is transmitted over Wi-Fi and displayed on a real-time cloud dashboard.

Key objectives of the project:
- Design and simulate an IoT-based sensing system
- Detect obstacles using an ultrasonic sensor
- Detect motion using a PIR sensor
- Process sensor data using ESP32 decision logic
- Transmit data to a cloud platform
- Visualize system data through a real-time dashboard

---

## System Architecture

The system is composed of the following main components:

- **Sensors**
  - Ultrasonic Sensor (HC-SR04) for distance measurement
  - PIR Motion Sensor for motion detection
- **Processing Unit**
  - ESP32 microcontroller with built-in Wi-Fi
- **Communication**
  - Wi-Fi (HTTP-based data transmission)
- **Cloud Platform**
  - ThingSpeak for data storage and visualization
- **Visual Indicators**
  - Green LED: Safe path
  - Red LED: Obstacle detected

---

## Simulation and Tools

The project was simulated and developed using the following tools:

- **Wokwi Simulator** – for circuit simulation and logic verification
- **ESP32** – main microcontroller
- **ThingSpeak** – cloud platform for real-time data visualization
- **Visual Studio Code / PlatformIO** – development environment

Simulation was used to validate system behavior before physical deployment, reducing hardware errors and debugging time.

---

## Cloud Integration

Sensor data is sent to the ThingSpeak cloud platform at regular intervals. The following data fields are monitored:

- Distance measurement (cm)
- Obstacle status (safe / obstacle)
- Motion detection status

This allows remote monitoring of the system state in real time.

---

## Security and Power Considerations

- Basic authentication is implemented using an API key for cloud communication
- Wi-Fi communication introduces potential security risks that can be mitigated using HTTPS
- Continuous Wi-Fi usage increases power consumption
- Lower transmission frequency helps reduce power usage
- USB power was used during simulation; battery power can be used for mobile deployment

---

## Limitations

- System depends on a stable internet connection
- Ultrasonic sensor accuracy decreases at longer distances
- Continuous Wi-Fi communication impacts power efficiency
- No motor control or autonomous navigation implemented

---

## Future Improvements

- Add motor drivers for autonomous robot movement
- Implement HTTPS for secure cloud communication
- Integrate battery management for improved power efficiency
- Develop a mobile or web-based dashboard for enhanced monitoring

---

## Documentation

📄 Detailed diagrams, system architecture, simulation screenshots, and dashboard visuals are available in the [`/docs`](./docs) folder.

---

## Author

**Khadiga Abdelkarim Hamid Idris**  
Computer Science (Data Science) Student  
Albukhary International University  

---
