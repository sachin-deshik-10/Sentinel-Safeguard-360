# Sentinel Safeguard 360: Smart Protection with AI

## Introduction
**Sentinel Safeguard 360** is an innovative solution aimed at revolutionizing security protocols by leveraging advanced AI algorithms, robust hardware components, and efficient communication systems. This autonomous security patrol robot is designed to enhance security measures across various environments, ensuring proactive and effective threat detection and response.

## Problem Statement
Current security measures often fall short in addressing vulnerabilities and potential threats. Our goal is to develop an autonomous security patrol robot that significantly enhances security effectiveness through advanced technologies.

## Proposed Solution
The Sentinel Safeguard 360 robot employs sophisticated SLAM algorithms for accurate mapping and navigation, allowing it to autonomously patrol pre-designated regions. Integrated sensors, including motion sensors and cameras, provide environmental awareness for intrusion detection and visual monitoring. The robot communicates wirelessly with a central control system using WiFi, ensuring reliable data transmission.

### Key Features
- **SLAM Algorithms**: Real-time mapping and localization for autonomous navigation.
- **Intrusion Detection**: Integrated cameras and motion sensors detect unauthorized entries and security breaches in real-time.
- **Reliable Communication**: WiFi modules ensure instant reporting of incidents and robot status.
- **User Interface**: Web-based dashboard for monitoring, alerts, and remote control.
- **Proactive Surveillance**: Continuous learning and anomaly detection via AI algorithms integrated with an MQTT server.

## Technical Approach

### Hardware Components
- **ESP32 CAM Module**: Captures and monitors the surveillance area, equipped with WiFi for real-time streaming and alerts.
- **PIR Motion Sensor**: Triggers camera movement and alert system upon detecting motion.
- **LDR Sensor**: Adjusts RGB LED illumination based on ambient light levels.
- **Gear Motor**: Moves the camera for continuous area coverage.
- **RGB LED**: Provides optimal lighting based on sensor input.

### Software Components
- **OpenCV**: Real-time image processing for intrusion detection.
- **Arduino IDE**: Development environment for coding and uploading to the ESP32 CAM.
- **TensorFlow Lite**: Deploys pre-trained AI models for intruder detection.
- **SLAM Algorithms**: For environment mapping and localization.
- **Python Programming**: System integration and algorithm development.
- **MQTT Protocol**: Sends real-time notifications to user devices.
  
### Connection Diagram
![Connection Diagram](https://drive.google.com/uc?export=view&id=1cwItm6PWIRVNIh_fk9lSIsK9oXjjuMGn)

### Pin Connections

| Component          | ESP32 CAM Pin | Description                 |
|--------------------|---------------|-----------------------------|
| PIR Motion Sensor  | GPIO 12       | Detects motion              |
| LDR Sensor         | GPIO 34       | Measures ambient light      |
| Gear Motor 1       | GPIO 14       | Controls motor 1 movement   |
| Gear Motor 2       | GPIO 15       | Controls motor 2 movement   |
| RGB LED            | GPIO 2        | Adjusts lighting            |

## Goals and Objectives
- Enable autonomous navigation using SLAM algorithms.
- Detect security breaches in real-time with integrated sensors.
- Develop a reliable communication system using WiFi.
- Create an intuitive web-based dashboard for monitoring and control.
- Ensure robust performance through rigorous testing and maintenance.

## Target Audience
This solution targets homeowners, businesses, government agencies, educational institutions, and public buildings. It aims to enhance security protocols, safeguard resources, personnel, and private data, and provide a safer environment for employees and households.

## Expected Outcomes
The AI-powered security system is expected to significantly enhance security in homes, offices, and public spaces, leading to reduced theft, illegal entry, and safety violations. Users will benefit from real-time monitoring and timely alerts, gaining greater control and understanding of their security.

## Budget and Resources

| Item                        | Cost (₹) |
|-----------------------------|----------|
| PIR Motion Sensor           | 800      |
| LDR Sensor                  | 150      |
| ESP32 CAM Module            | 850      |
| Gear Motor                  | 100      |
| Resistors, MOSFET, Jumper Wires | 200  |
| **Total**                   | 2000     |

### WEBPAGE INTERFACE
![WhatsApp Image 2024-07-04 at 13 09 28_6c5aeb00](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/12d56152-eeb1-4e38-a562-7dd12086b5ea)

### RESULTS

![1](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/047c6222-0c41-4805-949b-83f7289602bd)

![2](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/aefa99a8-a6b8-4615-8577-a81739eb696b)

![3](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/d1ecd36e-9d03-469a-a7a7-77fda855d49e)

## Conclusion
The Sentinel Safeguard 360 system combines intelligent hardware, AI algorithms, and efficient communication channels to enhance security. By detecting threats in real-time and providing proactive alerts, this solution aims to improve safety for various stakeholders. The user-friendly interface and MQTT server integration ensure seamless interaction and peace of mind.

## Documentation
For detailed documentation, please refer to the [Sentinel Safeguard 360 Report](https://drive.google.com/file/d/13sIAQ4KSWMCDfzRS-VC6yvgaMrkVyByW/view).

