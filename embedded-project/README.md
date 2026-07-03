# River Boat Cleaner (Embedded System Project)

An embedded and IoT-based autonomous river cleaning boat prototype developed as a university team project for the Embedded Systems course.

## Project Overview

This project focuses on developing a smart river cleaning boat prototype designed to reduce manual labor and help solve water pollution problems.

The system combines:
- Remote control via web interface
- Autonomous trash detection
- Conveyor-based garbage collection
- Real-time environmental monitoring
- Live video streaming using OpenCV

The project integrates embedded systems, IoT communication, sensor processing, and web-based control into a single platform.

---

## My Contribution

This was a 3-person team project.

My primary responsibilities included:

- UI and interaction planning
- System workflow planning
- State diagram and schematic design
- Hardware layout and prototype structure planning
- Documentation and project organization
- Prototype visualization and design support

I mainly focused on system design, planning, and integration.

---

## System Architecture

The system was divided into multiple processing nodes:

### ODROID-C4
- Flask web server
- Web control interface
- OpenCV video streaming
- API communication

### ESP32 NodeMCU
- Wi-Fi and Arduino IoT Cloud communication
- Temperature sensor processing
- Command forwarding

### Arduino UNO R3
- Ultrasonic sensor processing
- DC motor and conveyor control
- Low-level movement control

---

## Main Features

- Remote boat movement control
- Automatic trash detection
- Conveyor-based garbage collection
- Real-time telemetry monitoring
- Live camera streaming
- IoT cloud integration

---

## Technologies & Hardware

### Software
- Arduino IDE
- Flask
- OpenCV
- Arduino IoT Cloud

### Hardware
- ODROID-C4
- ESP32 NodeMCU
- Arduino UNO R3
- HC-SR04 Ultrasonic Sensor
- DS18B20 Temperature Sensor
- L298N Motor Driver
- DC Motors
- Webcam
