

# Sentinel Safeguard 360: Smart Protection with AI

## Introduction
**Sentinel Safeguard 360** revolutionizes modern security by integrating advanced AI, robust hardware, and efficient communication systems. This autonomous patrol robot proactively safeguards environments, offering intelligent surveillance and instant incident response.

---

## Problem Statement
Traditional security solutions often fail to address critical vulnerabilities and evolving threats. Sentinel Safeguard 360 aims to deliver an autonomous security patrol robot that dramatically improves security effectiveness and reliability.

---

## Proposed Solution
The Sentinel Safeguard 360 robot uses sophisticated SLAM (Simultaneous Localization and Mapping) algorithms for accurate mapping and navigation, enabling autonomous patrols in designated areas. Integrated sensors (cameras, PIR, LDR) and AI models detect, analyze, and report security breaches in real time, ensuring proactive and responsive surveillance.

---

## Key Features
- **SLAM Algorithms:** Real-time mapping and localization for autonomous navigation.
- **Intrusion Detection:** AI-powered cameras and motion sensors detect unauthorized entries and security breaches instantly.
- **Reliable Communication:** WiFi modules provide prompt reporting of incidents and system status.
- **Web Dashboard:** Intuitive interface for monitoring, alerts, and remote control.
- **Proactive Surveillance:** Continuous learning and anomaly detection using AI, integrated with MQTT for real-time notifications.

---

## Technical Approach

### Hardware Components
- **ESP32 CAM Module:** Captures and streams surveillance footage; WiFi-enabled for alerts.
- **PIR Motion Sensor:** Activates camera and alert system upon motion detection.
- **LDR Sensor:** Automatically adjusts lighting based on ambient conditions.
- **Gear Motor:** Enables dynamic camera movement for complete area coverage.
- **RGB LED:** Provides optimal illumination based on sensor feedback.

### Software Components
- **OpenCV:** Real-time image processing for intrusion analysis.
- **Arduino IDE:** Firmware development and deployment for ESP32 CAM.
- **TensorFlow Lite:** Deploys efficient AI models for intruder detection.
- **SLAM Algorithms:** Environmental mapping and localization.
- **Python Programming:** Integrates system components and algorithms.
- **MQTT Protocol:** Delivers real-time notifications to user devices.

---

### System Connection Diagram
![Connection Diagram](https://drive.google.com/uc?export=view&id=1cwItm6PWIRVNIh_fk9lSIsK9oXjjuMGn)
_See above for hardware connectivity and system architecture._

---

### Pin Connections

| Component          | ESP32 CAM Pin | Description                 |
|--------------------|---------------|-----------------------------|
| PIR Motion Sensor  | GPIO 12       | Detects motion              |
| LDR Sensor         | GPIO 34       | Measures ambient light      |
| Gear Motor 1       | GPIO 14       | Controls motor 1 movement   |
| Gear Motor 2       | GPIO 15       | Controls motor 2 movement   |
| RGB LED            | GPIO 2        | Adjusts lighting            |

_Note: Pin selection ensures optimal performance and minimal interference with other components._

---

## Goals and Objectives
- Achieve autonomous navigation using SLAM algorithms.
- Detect and respond to security breaches in real time.
- Establish robust, reliable WiFi-based communication.
- Deliver a user-friendly dashboard for monitoring and control.
- Maintain system reliability through thorough testing.

---

## Target Audience
Sentinel Safeguard 360 is designed for homeowners, businesses, government agencies, educational institutions, and public buildings—anywhere enhanced security and resource protection are needed.

---

## Expected Outcomes
- Increased security and reduced incidents of theft and unauthorized entry.
- Real-time alerts and actionable insights for users.
- Scalable, AI-powered solution suitable for diverse environments.

---

## Budget and Resources

| Item                        | Cost (₹) |
|-----------------------------|----------|
| PIR Motion Sensor           | 800      |
| LDR Sensor                  | 150      |
| ESP32 CAM Module            | 850      |
| Gear Motor                  | 100      |
| Resistors, MOSFET, Jumper Wires | 200  |
| **Total**                   | 2000     |

---

## Webpage Interface
![Web Dashboard](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/12d56152-eeb1-4e38-a562-7dd12086b5ea)
_Example of the intuitive, real-time dashboard._

---

## Results
1. ![Intrusion Detection Example 1](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/047c6222-0c41-4805-949b-83f7289602bd)
2. ![Intrusion Detection Example 2](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/aefa99a8-a6b8-4615-8577-a81739eb696b)
3. ![Intrusion Detection Example 3](https://github.com/GOUTHAMBB/Sentinel-Safeguard-360/assets/110834190/d1ecd36e-9d03-469a-a7a7-77fda855d49e)

---

## Practical Demonstration Videos
- [GitHub Attachment](https://github.com/user-attachments/assets/217bbdf6-9a3e-47af-88f0-6b3923dbd5c4)
- [Drive Folder](https://drive.google.com/drive/folders/1gOXyFcAaVc6k9J3CBRlYI1KvL1vN36tD)

---

## Installation & Usage

### Prerequisites
- ESP32 CAM and compatible sensors (refer to Hardware Components above)
- Arduino IDE and Python (latest versions recommended)
- MQTT server setup

### Setup Steps
1. Assemble hardware following the connection diagram and pin table.
2. Install required software libraries (OpenCV, TensorFlow Lite, MQTT).
3. Upload firmware to ESP32 CAM via Arduino IDE.
4. Run Python integration scripts for SLAM and AI detection.
5. Access the web dashboard via provided IP address.

### Troubleshooting
- Verify WiFi connectivity and MQTT broker settings.
- Double-check pin connections and sensor orientations.
- For image processing errors, ensure OpenCV and TensorFlow libraries are updated.

---

## Contributing
We welcome contributions! Please submit issues or pull requests for feature suggestions, bug fixes, or documentation improvements.

---

## Licensing
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Documentation
For detailed technical documentation, see the [Sentinel Safeguard 360 Report](https://drive.google.com/file/d/13sIAQ4KSWMCDfzRS-VC6yvgaMrkVyByW/view).

---

## Conclusion
Sentinel Safeguard 360 seamlessly integrates intelligent hardware, AI algorithms, and reliable communication to deliver next-generation security. Its autonomous, AI-driven patrols and instant alerts set a new standard for safety and peace of mind.

