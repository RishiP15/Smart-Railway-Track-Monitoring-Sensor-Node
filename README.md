# 🚆 Smart Railway Sensor Node

## Overview

The Smart Railway Sensor Node is an embedded systems and VLSI-oriented project designed to monitor railway track health using intelligent sensing, data processing, and digital hardware concepts. The system acquires vibration and environmental data, analyzes the information, classifies the track condition, and generates maintenance alerts to support predictive maintenance.

Instead of constructing a railway track model, this project focuses on designing a **prototype monitoring node** that represents an electronic unit intended to be deployed alongside railway tracks.

---

## Problem Statement

Railway tracks require continuous monitoring to detect abnormal conditions that may affect operational safety and maintenance planning. Manual inspection is time-consuming and cannot provide real-time monitoring. This project proposes a low-cost intelligent monitoring node capable of collecting sensor data and assisting railway authorities through condition-based alerts.

---

## Objectives

- Monitor vibration using an MPU6050 sensor.
- Monitor environmental temperature.
- Acquire and process sensor data using Arduino Uno.
- Analyze collected data using Python.
- Classify track condition as **Normal**, **Warning**, or **Critical**.
- Display monitoring information through a dashboard.
- Develop Verilog RTL modules for future ASIC/FPGA implementation.

---

## Technologies

### Hardware
- Arduino Uno
- MPU6050 Accelerometer
- Temperature Sensor (LM35/DHT22)
- Breadboard
- Jumper Wires

### Software
- Arduino IDE
- Python
- VS Code
- Git & GitHub
- Icarus Verilog
- GTKWave

---

## Project Structure

```text
Arduino/
Python/
Verilog/
Docs/
Dataset/
Images/
Presentation/
Research/
```

---

## Project Status

🚧 Phase 1 – Project Planning & Repository Setup

Current Progress:
- ✅ GitHub repository created
- ✅ Project documentation started
- ⏳ Hardware procurement
- ⏳ Software development

---

## Future Scope

- IoT-based remote monitoring
- Cloud database integration
- AI-based predictive maintenance
- FPGA/ASIC implementation of digital modules
- Multi-node railway monitoring network
