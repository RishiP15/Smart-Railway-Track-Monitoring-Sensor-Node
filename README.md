# 🚆 Smart Railway Sensor Node

## Overview

The Smart Railway Sensor Node is an embedded systems and VLSI-oriented project designed to monitor railway track health using intelligent sensing, data processing, and digital hardware concepts.

This project focuses on designing a prototype electronic monitoring node that can be deployed alongside railway tracks to continuously acquire sensor data, analyze track conditions, and assist railway authorities through intelligent maintenance alerts.

Rather than constructing a railway track model, the project demonstrates the design and implementation of the electronic monitoring system that forms the foundation of a real railway monitoring network.

---

# Problem Statement

Railway tracks require continuous monitoring to detect abnormal conditions that may affect operational safety and maintenance planning. Manual inspection is time-consuming and cannot provide real-time monitoring over large railway networks.

This project proposes a low-cost intelligent monitoring node capable of collecting vibration and environmental data, processing it using embedded systems and Python, and generating condition-based maintenance alerts.

---

# Objectives

- Monitor vibration using an MPU6050 accelerometer.
- Monitor environmental temperature.
- Acquire sensor data using Arduino Uno.
- Process sensor data using Python.
- Classify railway track condition into:
  - Normal
  - Warning
  - Critical
- Display monitoring information through a dashboard.
- Develop Verilog RTL modules for future FPGA/ASIC implementation.

---

# Technologies Used

## Hardware

- Arduino Uno
- MPU6050 Accelerometer
- LM35 / DHT22 Temperature Sensor
- Breadboard
- Jumper Wires

## Software

- Arduino IDE
- Embedded C
- Python
- VS Code
- Git & GitHub
- Icarus Verilog
- GTKWave

---

# Project Architecture

Railway Environment

↓

Sensors (MPU6050 + Temperature)

↓

Arduino Uno

↓

Python Data Processing

↓

Dashboard

↓

Condition Classification

↓

Maintenance Alert

---

# Repository Structure

```
Smart-Railway-Sensor-Node/

├── Arduino/
├── Python/
├── Verilog/
├── Docs/
├── Dataset/
├── Images/
├── Presentation/
├── Research/
└── README.md
```

---

# Features

- Real-time vibration monitoring
- Temperature monitoring
- Data logging
- Python-based analysis
- Dashboard visualization
- Intelligent alert generation
- Verilog RTL design
- VLSI-oriented architecture

---

# Development Roadmap

| Phase | Description | Status |
|--------|-------------|--------|
| Phase 1 | Project Planning & GitHub Setup | 🚧 In Progress |
| Phase 2 | Hardware Integration | ⏳ Pending |
| Phase 3 | Python Data Processing | ⏳ Pending |
| Phase 4 | Dashboard & Alert System | ⏳ Pending |
| Phase 5 | Verilog RTL Design | ⏳ Pending |
| Phase 6 | Testing & Documentation | ⏳ Pending |

---

# Future Scope

- IoT-based remote monitoring
- Cloud database integration
- AI-assisted predictive maintenance
- FPGA implementation
- ASIC implementation
- Multi-node railway monitoring system

---

# Current Progress

Repository Created ✅

Project Planning 🚧

Hardware Procurement ⏳

Software Development ⏳

---

# Author

**Sujal Panda**

B.Tech Electronics Engineering (VLSI)

Jaypee Institute of Information Technology (JIIT)

---

# License

This project is licensed under the MIT License.
