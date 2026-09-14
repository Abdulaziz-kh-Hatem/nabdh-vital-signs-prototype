# Nabdh: Vital Signs Monitoring Prototype

![Nabdh Device Prototype](assets/device_close_up.jpg)

**Nabdh** (Arabic for "Pulse") is a hardware prototype I built to measure and display human vital signs. It uses biomedical sensors and a microcontroller to read the signals from the body and show the results on an LCD screen.

I developed this project to show how we can build low-cost medical devices locally in Yemen. We designed the outside case using CAD software and 3D-printed it so the device is easy to carry and protect the electronics inside.

## Awards

**First Place - Smart Manufacturing Hackathon**  
*University of Science and Technology (UST) Aden, February 2026*

Our project won first place among all engineering teams. The judges liked that we built a working prototype using 3D printing to solve local healthcare challenges.

![Hackathon Trophy](assets/hackathon_trophy.jpg)

## How It Works

Because the hackathon was only 36 hours long, we used ready-made sensor modules to build the prototype quickly. This gave us more time to focus on writing the code and designing the 3D case.

The system has three main parts:
1. **Sensors:** 
   * **ECG:** We used the AD8232 module to measure the electrical activity of the heart.
   * **PPG:** We used a MAX sensor (MAX30102) to measure the pulse.
2. **Microcontroller:** This is the brain of the device. It reads the analog voltages, cleans the signals using simple digital filters, and calculates the heart rate.
3. **Screen:** A small LCD shows the patient's heart rate in real-time.

### Breadboard Testing
During the competition, we first built the circuit on a breadboard. We tested it on ourselves and checked the signals using an oscilloscope before putting everything inside the 3D-printed box.

![Breadboard Testing](assets/nabdh_breadboard_1.jpg)

## Video Demonstration

You can watch a live video of the Nabdh device measuring my vital signs during our testing:

[![Nabdh Prototype Live Demo](https://img.youtube.com/vi/_p6Nn98H_nc/hqdefault.jpg)](https://youtu.be/_p6Nn98H_nc)

🎥 **YouTube Video:** [Watch the testing on a real person here](https://youtu.be/_p6Nn98H_nc)

![Device Usage](assets/device_usage.jpg)

## Why This Project Matters

This prototype helped me practice important Biomedical Engineering skills:
* **Connecting Sensors:** Learning how to wire analog sensors (AD8232) and digital sensors (MAX30102) to a microcontroller.
* **Writing Code:** Writing fast C/C++ code to read signals without delay.
* **Fast Building:** Using 3D printing to design and build a medical device case in just two days.

*Note: This repository is a portfolio to show pictures and videos of the hardware we built during the hackathon.*
