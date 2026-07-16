<div align="center">

# 🛰️ Secure Satellite Communication and IoT Environmental Monitoring System

### A Smart Integration of Computer Networks, IoT, and Embedded Systems

![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Cisco%20Packet%20Tracer-blue)
![ESP32](https://img.shields.io/badge/Embedded-ESP32-orange)
![IoT](https://img.shields.io/badge/Technology-IoT-green)

---

**Taif University**  
College of Computers and Information Technology  
Computer Engineering Department

Academic Project

</div>

---

# 📖 Overview

This project presents a **Secure Satellite Communication and IoT Environmental Monitoring System** that combines **Computer Networks**, **Embedded Systems**, and **Internet of Things (IoT)** technologies.

The network infrastructure was designed and simulated using **Cisco Packet Tracer**, while the embedded monitoring system was implemented using an **ESP32 microcontroller** connected to environmental sensors.

The prototype demonstrates how secure communication, environmental monitoring, and autonomous protection logic can work together in a modern satellite ground station.

---

# 🎯 Objectives

- Design a secure satellite communication network.
- Implement VLAN segmentation.
- Configure secure routing and communication.
- Integrate IoT environmental monitoring.
- Detect motion using a PIR sensor.
- Monitor temperature and humidity using a DHT11 sensor.
- Demonstrate embedded system integration using ESP32.

---

# 🛠 Technologies

- Cisco Packet Tracer
- ESP32
- Arduino IDE
- IoT
- Computer Networks
- VLAN
- Network Security
- Embedded Systems
- Simulated and tested by WOKWi

---

# 💻 Hardware Components

| Component | Description |
|------------|-------------|
| ESP32 Development Board | Main embedded controller |
| PIR Motion Sensor | Motion detection |
| DHT11 Sensor | Temperature & humidity monitoring |
| Breadboard | Prototype circuit |
| Jumper Wires | Electrical connections |
| LEDs | System status indicators |
| 220Ω Resistors | LED current protection |
| USB Cable | Programming & power |

---

# 🌐 Network Components

- Cisco 2911 Router
- Cisco 2960 Switches
- Telemetry Server
- Control PC
- Security PC
- User PC
- Home Gateway
- Motion Detector
- Humidity & Temperature Sensor

---

# 🏗 System Architecture

```
                    Satellite
                        │
                        │
               Ground Station
                        │
                 Cisco Router
                        │
              ┌─────────┴─────────┐
              │                   │
        Core Switch          IoT Switch
              │                   │
      ┌───────┼────────┐          │
      │       │        │          │
 Control   Security   User      ESP32
    PC        PC       PC         │
                                  │
                      ┌───────────┴───────────┐
                      │                       │
               PIR Motion Sensor     DHT11 Sensor
```

---

# 📂 Project Structure

```
Secure-Satellite-Communication-IoT-System
│
├── docs
│   ├── Final_Report.pdf
│   ├── Poster.pdf
│   └── Presentation.pptx
│
├── packet-tracer
│   └── Network_Topology.pkt
│
├── esp32
│   └── ESP32_Code.ino
│
├── hardware
│   └── Circuit_Diagram.png
│
├── images
│   ├── Topology.png
│   ├── Prototype.jpg
│   └── Poster.png
│
├── videos
│   └── Demonstration.mp4
│
└── README.md
```

---

# 🔒 Security Features

- VLAN Segmentation
- Router-on-a-Stick
- Access Control Lists (ACLs)
- Secure IoT Network
- Network Isolation
- Environmental Monitoring
- Motion Detection Alerts

---

# 📊 Expected Results

- ✅ Successful communication between network devices
- ✅ Secure VLAN implementation
- ✅ Real-time environmental monitoring
- ✅ Motion detection alerts
- ✅ ESP32 sensor integration
- ✅ Reliable telemetry monitoring
- ✅ Improved network security

---

# 📚 References

- Cisco Networking Academy
- Espressif Systems (ESP32 Documentation)
- IEEE Xplore Digital Library
- Computer Networks – Tanenbaum
- Network Security Essentials – Stallings

---

<div align="center">

### ⭐ Academic Project – Computer Engineering Department ⭐

</div>
