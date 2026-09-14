# Nabdh: Portable Vital Signs Acquisition Prototype

**1st Place, Digital Fabrication & Local Solutions Hackathon**  
*Faculty of Engineering & Computing, UST Aden (Feb 2026)*

Nabdh (Arabic for "Pulse") is a dual-channel physiological monitoring prototype designed and fabricated within a 36-hour hardware hackathon. The device acquires real-time Electrocardiogram (ECG) and Photoplethysmogram (PPG) data for immediate clinical telemetry visualization.

![Nabdh Device Prototype](assets/device_close_up.jpg)

---

## 1. System Architecture

The hardware stack integrates off-the-shelf biomedical sensor modules with embedded microcontrollers and custom 3D-printed enclosures for rapid prototyping.

### 1.1 Sensors
* **ECG Acquisition:** AD8232 single-lead analog front-end (AFE) for biopotential measurement.
* **PPG Acquisition:** MAX30102 integrated pulse oximetry and heart-rate monitor module.

### 1.2 Embedded Processing & UI
* **Microcontroller Unit (MCU):** Samples analog ECG voltages and digital I2C data from the PPG module, applying digital signal filtering to isolate heart rate metrics.
* **Display Interface:** Real-time LCD rendering of calculated pulse rate.
* **Enclosure:** Custom CAD-designed and 3D-printed chassis housing all electronics, providing a durable and portable form factor.

---

## 2. Prototyping & Validation

The system underwent incremental validation, starting from breadboard circuit analysis using digital oscilloscopes to final enclosure integration.

### 2.1 Breadboard Integration
![Breadboard Testing](assets/nabdh_breadboard_1.jpg)
*Figure 1: Initial breadboard circuit integration and signal validation.*

### 2.2 Operational Testing
The final integrated unit successfully demonstrated real-time, non-invasive physiological monitoring on human subjects.

![Device Usage](assets/device_usage.jpg)
*Figure 2: Live demonstration of the Nabdh prototype acquiring patient telemetry.*

### 2.3 Video Demonstration
* **Live Subject Testing:** [Nabdh Prototype Demonstration (YouTube)](https://youtu.be/_p6Nn98H_nc)

---

## 3. Awards & Recognition

![Hackathon Trophy](assets/hackathon_trophy.jpg)
*Figure 3: 1st Place Trophy, Digital Fabrication & Local Solutions Hackathon.*

---
*Note: This repository serves as a hardware portfolio showcasing the structural and functional outcomes of the 36-hour hackathon.*
